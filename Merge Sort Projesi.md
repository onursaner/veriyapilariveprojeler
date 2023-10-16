# Merge Sort Projesi

1) [16,21,11,8,12,22] serisinin merge sort'a göre aşamaları yukarıdan aşağıya olacak

```
[16,21,11,8,12,22]
[16,21,11] [8,12,22]
[16] [21,11] [8,12] [22]
[16] [21] [11] [8] [12] [22]
[16,21] [8,11] [12,22]
[8,11,16,21] [12,22]
[8,11,12,16,21,22]
```

şekildedir.


2) Big-O Notation 

```
Divide sürecinde eleman sayıları her seferinde ikiye ayrılmaktadır. 
Input=2^x=n ise x=log(n) olur. O(logn) olarak analiz edilir.

Merge sürecinde iki serinin ilk elemanları arasında küçük olana bakılıyor. küçük mü değil mi iki ihtimalli bu durum n/2 input'u ortaya çıkarmaktadır. dominant char n ise O(n) olarak analiz edilir.

Merge sort'un toplam big-o notation ise O(logn).O(n)=O(nlogn) olacaktır.

```

şeklindedir.
