# do-while Loop

## Definisi do-while Loop
do-while loop sama seperti while loop yaitu struktur kontrol program untuk mengulang blok kode berkali kali selama kondisi bernilai True tapi akan menjalankan blok kode sekali sebelum masuk ke iterasi dan penulisan nya diatas while

do-while loop ditulis dengan dengan ekspresi didalam parameternya

Satu kali ter eksekusi disebut dengan satu iterasi

example code : 
let i = 0
do{
    console.log(i)
    i++
}
while(i <= 10)

## Flowchart do-while Loop

```mermaid
flowchart TD

start@{"shape": circle, "label": "Mulai"}
initialI@{"shape": lean-l, "label":"Input: i = 0"}
isIlessthanTen@{"shape": diamond, "label": i <= 10}
isIlessthanTenTrue@{"shape": lean-l, "label": "Output: i"}
iIncrement@{"shape": rectangle, "label": i++}
stop@{"shape": dbl-circ, "label": "Selesai"}

start-->initialI-->isIlessthanTenTrue-->iIncrement-->isIlessthanTen--True-->isIlessthanTenTrue
isIlessthanTen--False-->stop

```