# Algoritma

# Luas dan Keliling Lingkaran

Algoritma menghitung luas dan keliling lingkaran

1. Mulai
2. tentukan nilai jari jari
3. untuk mengetahui nilai pi tentukan apakah jari-jari dapat habis dibagi dengan 7 jika dapat habis dibagi dengan 7 maka pi bernilai 22/7 jika tidak maka pi bernilai 3.14
4. selanjutnya untuk mengetahui luas lingkaran didapat dengan rumus pi dikalikan dengan jari-jari lingkaran kuadrat
5. selanjutnya untuk mengetahui keliling lingkaran didapat dengan rumus dua dikalikan dengan pi dikalikan dengan pi dikalikan dengan jari-jari
6. selesai

## flowchart

membuat flowchart untuk program menghitung luas dan keliling lingkaran

```mermaid
flowchart TD

a@{ shape: circle, label: "start" }
b@{ shape: lean-r, label: "r" }
c@{ shape: diamond, label: " r % 7 == 0" }
d@{ shape: rect, label: "pi = 22/7" }
e@{ shape: rect, label: "pi = 3.14" }
f@{ shape: rect, label: "luas: pi x r x r " }
g@{ shape: rect, label: "keliling: 2 x pi x r " }
h@{ shape: lean-r, label: "luas lingkaran: #quot;{luas}#quot;" }
i@{ shape: lean-r, label: "Keliling: #quot;{keliling}#quot;" }
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
