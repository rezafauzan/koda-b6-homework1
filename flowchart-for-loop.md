# For Loop

## Definisi For Loop
For loop adalah struktur kontrol program untuk mengulang blok kode berkali kali hingga kondisi pengecekan terpenuhi

For loop terdiri dari inisialisasi; kondisi;increment/decrement

Satu kali ter eksekusi disebut dengan satu iterasi

example code : 
for(let i = 0; i < 10; i++){
    console.log(i)
}

## Flowchart For Loop

```mermaid
flowchart TD

start@{"shape": circle, "label": "Mulai"}
initialI@{"shape": lean-l, "label": "Input: i = 0"}
isIlessthanTen@{"shape": diamond, "label": i <= 10}
isIlessthanTenTrue@{"shape": lean-l, "label": "Output: i"}
iIncrement@{"shape": rectangle, "label": i++}
stop@{"shape": dbl-circ, "label": "Selesai"}

start-->initialI-->isIlessthanTen--True-->isIlessthanTenTrue-->iIncrement-->isIlessthanTen
isIlessthanTen--False-->stop

```