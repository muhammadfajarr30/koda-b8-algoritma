# Program Algoritma

## menghitung BMI (BODY MASS INDEX)

## Deskriptif Algoritma

1. Mulai
2. buat nilai a yang berisi nilai berat badan
3. buat nilai b yang berisi tinggi badan
4. Buat nilai BMI dengan cara berat badan dibagi (tinggi badan dikali tinggi badan)
5. jika BMI kurang dari 18.5 maka kurus
6. jika BMI kurang dari 25 maka normal
7. jika BMi kurang dari 30 maka gemuk
8. jika tidak semua maka obesitas
9. selesai

## Flowchart

```mermaid

flowchart TD
    start@{shape: circle, label:"start"}
  a@{ shape: lean-r, label: "a" }
  b@{ shape: lean-r, label: "b" }
  c@{ shape: lean-r, label: "BMI = a/(bxb)" }
  d@{ shape: diamond, label: "BMI < 18.5" }
  e@{ shape: diamond, label: "BMI < 25" }
  f@{ shape: diamond, label: "BMI < 30" }
  g@{ shape: lean-r, label: "#quot;kurus#quot;"}
  h@{ shape: lean-r, label: "#quot;normal#quot;"}
  i@{ shape: lean-r, label: "#quot;gemuk#quot;"}
  j@{ shape: lean-r, label: "#quot;obesitas#quot;"}
  k@{ shape: dbl-circ, label: "stop" }

start-->a
  a-->b
  b-->c
  c-->d
  d-- yes -->g-->k
  d-- no -->e
  e-- yes-->h-->k
  e-- no -->f
  f-- yes -->i-->k
  f-- no -->j-->k



```

## Pseudo-Code

```Pseudo-code
DECLARE a = REAL
DECLARE b = REAL
DECLARE BMI = REAL

INPUT a
INPUT b
BMI <- a / (b * b)

    IF bmi < 18.5 THEN
OUTPUT "KURUS"
    ELSE IF BMI <25 THEN
OUTPUT "NORMAL"
    ELSE IF BMI <30 THEN
OUTPUT "GEMUK"
    ELSE
OUTPUT "OBESITAS"
    ENDIF

```
