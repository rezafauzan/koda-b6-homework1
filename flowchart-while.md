# while Loop

## Definisi while Loop
while loop mirip seperti for yaitu struktur kontrol program untuk mengulang blok kode berkali kali tapi selama kondisi bernilai True

while loop ditulis dengan dengan ekspresi didalam parameternya

Satu kali ter eksekusi disebut dengan satu iterasi

example code : 
let i = 0
while(i <= 10){
    console.log(i)
    i++
}

## Flowchart while Loop

```mermaid
flowchart TD

start@{"shape": circle, "label": "Mulai"}
initialI@{"shape": lean-l, "label":"Input: i = 0"}
isIlessthanTen@{"shape": diamond, "label": i <= 10}
isIlessthanTenTrue@{"shape": lean-l, "label": "Output: i"}
iIncrement@{"shape": rectangle, "label": i++}
stop@{"shape": dbl-circ, "label": "Selesai"}

start-->initialI-->isIlessthanTen--True-->isIlessthanTenTrue-->iIncrement-->isIlessthanTen
isIlessthanTen--False-->stop

```