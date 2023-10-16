# Selection Sort Projesi

1) [22,27,16,2,18,6] serisinin, insertion sort ile aşamaları yukarıdan aşağı olacak

```
[22,27,16,(2),18,6]
[(2),22,27,16,18,6]
[(2,6),22,27,16,18]
[(2,6,16),22,27,18]
[(2,6,16,18),22,27]
```

şekildedir.

Big-O Notation gösterimi ise;

``
Inputs=n+(n-1)+(n-2)+(n-3)+...+1
I=n.(n+1)/2=(n^2+n)/2
Dominant Char=n^2
Time Complexity Worst Case O(n^2)
``

Time Complexity: Dizi sıralandıktan sonra 18 sayısı Average Case'e girmektedir.

2) [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yukarıdan aşağıya olacak şekildeki gösterimi:

```
[7,3,5,8,(2),9,4,15,6]
[(2),7,3,5,8,9,4,15,6]
[(2,3),7,5,8,9,4,15,6]
[(2,3,4),7,5,8,9,15,6]