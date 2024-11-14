# AYT Interlinear

## Apa itu AYT?
Alkitab Yang Terbuka (AYT) adalah Alkitab berbahasa Indonesia yang dibuat dan diterbitkan oleh Yayasan Lembaga SABDA (YLSA) dengan dukungan para mitra untuk mempersembahkan sebuah versi Alkitab bahasa Indonesia yang tepat dan bertanggung jawab. AYT bukan Alkitab terjemahan baru, tetapi terjemahan ulang yang berdasar pada bahasa asli (Ibrani dan Yunani), Inggris, Indonesia, dan seluruh peralatan biblika modern.

## Definisi Interlinear
Baris-baris paralel yang unsur-unsur kalimatnya saling berkorelasi dan memberi suatu informasi, sebagai �alat studi kata� bahasa tertentu.

## Kegunaan Interlinear
Alkitab sebagai buku yang paling populer dan berpengaruh, paling banyak dicetak dan diterjemahkan dalam berbagai bahasa. (Namun) ada kemungkinan gap (kesenjangan) antar terjemahan, khususnya bahasa asli alkitab dan bahasa terjemahan.
Interlinear sebagai sarana untuk melihat makna kata atau frasa pada teks asli.

## Jenis-jenis Interlinear
a. Classic Interlinear
    ![Classic Interlinear](./assets/AYT_Classic_Interlinear__John_3_16.png)
b. Reverse Interlinear
    ![Classic Interlinear](./assets/AYT_Reverse_Interlinear__John_3_16.png)
c. Bi-linear
    ![Classic Interlinear](./assets/AYT_Bilinear__John_3_16.png)

## Datasets
Kami menyediakan data dalam format SQL, semua file berada dalam directory [data](./data). 
Berikut ini adalah informasi tentang file-file tersebut:
```
* bib_id_ayt_texts.sql      : Teks AYT Kejadian-Wahyu
* bib_id_aytst_texts.sql    : Teks AYT dengan nomor strong (embedded) Kejadian-Wahyu
* bib_id_ayt_pl_words.sql   : Teks AYT Perjanjian Lama per kata
* hebrew.sql                : Daftar kata dalam Ibrani
* bhsstr_word.sql           : Teks Alkitab Biblia Hebraica Stuttgartensia (BHS) with Strong PL Ibrani Per Kata
* itl_linkage_heb2ayt.sql   : Table korelasi Hebrew/Ibrani-AYT
* bib_id_ayt_pb_words.sql   : Teks AYT Perjanjian Baru per kata
* greek.sql                 : Daftar kata dalam Yunani
* wh_word.sql               : Teks Alkitab Westcott-Hort PB Yunani per kata
* itl_linkage_grk2ayt.sql   : Table korelasi per kata Alkitab Greek/Yunani-AYT
* vrefs.sql                 : Table referensi ayat dari nomor 1-31102 ((Kejadian 1:1 s.d. Wahyu 22:21)
```

## Referensi
+ [Teks Alkitab AYT GitHub](https://github.com/sabdacode/ayt/)
+ Interlinear AYT Perjanjian Lama: 
  - [Indeks Kata](https://ayt.co/interlinear/heb2ayt/), 
  - [Classic Interlinear](https://ayt.co/interlinear/view/?book=1&chapter=1&version=ayt&dir=classic&show=all), 
  - [Reverse Interlinear](https://ayt.co/interlinear/view/?book=1&chapter=1&version=ayt&dir=reverse&show=all), 
  - [Bi-linear](https://ayt.co/interlinear/heb2ayt/detail.php?id=1)
+ Interlinear AYT Perjanjian Baru: 
  - [Indeks Kata](https://ayt.co/interlinear/grk2ayt/), 
  - [Classic Interlinear](https://ayt.co/interlinear/view/?book=40&chapter=1&version=ayt&dir=classic&show=all), 
  - [Reverse Interlinear](https://ayt.co/interlinear/view/?book=40&chapter=1&version=ayt&dir=reverse&show=all), 
  - [Bi-linear](https://ayt.co/interlinear/grk2ayt/detail.php?id=23146)
+ Contoh multilinear dalam situs Alkitab.SABDA.org: [Yoh 3:16](https://alkitab.sabda.org/verse.php?book=Yoh&chapter=3&verse=16#str)
+ [File PDF Bible Interlinear](./Bible_Interlinear.pdf)
+ Situs AYT: https://ayt.co, situs YLSA: https://ylsa.org
