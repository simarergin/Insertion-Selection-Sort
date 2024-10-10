# Insertion Sort
[22,27,16,2,18,6] 

İlk başta 22 27’den küçük olduğu için sabit kalır.

2. [22,16,27,2,18,6]
3. [16,22,27,2,18,6]
4. [2,16,22,27,18,6]
5. [2,16,18,22,27,6]
6. [2,6,16,18,22,27]

**_NOT_**: Derste anlatılan gibi yapılırsa Selection sort ile aynı yani 

1. [22,27,16,2,18,6]  
2. [2,27,16,22,18,6]
3. [2,6,16,22,18,27]
4. [2,6,16,22,18,27]
5. [2,6,16,18,22,27]

__Big O gösterimi__ 

n + (n-1) + ... + 1 
= (n * (n - 1)) / 2
= (n^2 - n) => Big-O 
= O(n^2)


Time Complexity: Dizi sıralandıktan sonra 18 sayısı Avarage Case kapsamına girer
1. Average case: 16, 18
2. Worst case: 27
3. Best case: 2


[7,3,5,8,2,9,4,15,6] dizisinin **_Selection Sort_**'a göre ilk 4 adımı 

1. [2,3,5,8,7,9,4,15,6]
2. [2,3,4,8,7,9,5,15,6]
3. [2,3,4,5,7,9,8,15,6]
4. [2,3,4,5,6,9,8,15,7]
