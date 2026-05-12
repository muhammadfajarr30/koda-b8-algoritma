# Algoritma

# Luas dan Keliling Lingkaran

Algoritma menghitung luas dan keliling lingkaran

1. Mulai
2. masukan nilai ke dalam r untuk menampung nilai jari-jari
3. jika nilai r dimodulkan dengan 7 sama dengan nol maka gunakan nilai 22/7 untuk pi
4. jika tidak maka gunakan nilai 3.14 untuk pi
5. hitung luas dengan pi dikalikan r kuadrat
6. outputkan nilai dari luas lingkaran
7. hitung keliling dengan dua dikalikan dengan pi dikalikan dengan r
8. outputkan nilai dari keliling lingkaran
9. selesai

## flowchart

membuat flowchart untuk program menghitung luas dan keliling lingkaran

```mermaid
flowchart TD

a@{ shape: circle, label: "start" }
b@{ shape: lean-r, label: "r" }
c@{ shape: diamond, label: " r % 7 == 0" }
d@{ shape: rect, label: "pi = 22/7" }
e@{ shape: rect, label: "pi = 3.14" }
f@{ shape: rect, label: "luas = pi x r x r " }
g@{ shape: rect, label: "keliling = 2 x pi x r " }
h@{ shape: lean-r, label: "#quot;luas lingkaran {luas}#quot;" }
i@{ shape: lean-r, label: "#quot;Keliling lingkaran {keliling}#quot;" }
j@{ shape: dbl-circ, label: "Stop" }

a --> b
b--> c
c-- yes --> d
c-- no --> e
d--> f
e--> f
f--> h
h--> g
g--> i
i--> j


```

## PSEUDO-CODE

```pseudo code

DECLARE r: INTEGER
DECLARE pi: REAL
DECLARE luas: REAL
DECLARE keliling: REAL

INPUT r

IF r % 7 == 0 THEN
    pi = 22/7
ELSE
    pi = 3.14
ENDIF

luas <-- pi * r * r
OUTPUT "luas lingkaran", luas
keliling <-- 2 * pi * r
OUTPUT "keliling lingkaran", keliling


```
