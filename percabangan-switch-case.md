# Percabangan Switch Case Dan Penggunaannya

## Definisi
Switch-Case merupakan salah satu struktur kontrol percabangan atau mekanisme alur kendali program yang mengevaluasi suatu variable atau ekspresi terhadap beberapa nilai yang disebut case kemudian menjalankan blok code yang sesuai jika ada kecocokan 

## Penggunaan
switch case digunakan ketika perlu untuk membuat alur program dengan percabangan banyak berdasarkan satu nilai variable tunggal yang sudah ditentukan untuk membuat struktur kode yang lebih bersih dan mudah dibaca

## Syntax
Switch-Case pada javascript ditulis dengan format sebagai berikut:
switch(ekspresi/variable){
    case n:
        //statement yang dijalankan jika ekspresi atau variable bernilai n
        break //satu case diakhiri dengan break
    case r:
        //statement yang dijalankan jika ekspresi atau variable bernilai r
        break
    default:
        //statement yang dijalankan jika ekspresi atau variable tidak memenuhi atau tidak sesuai dengan case manapun dalam blok switch-case ini
}

## Kekurangan Menggunakan Switch Case 
1. Switch Case hanya mendukung perbandingan strict equal atau (===) dan tidak bisa untuk rentang seperti pada percabangan if else
2. rawan kesalahan jika lupa memberikan keyword break pada blok case akan membuat alur percabangannya fall through sehingga case berikutnya berkemungkinan ikut terjalankan
