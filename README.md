### Kodluyoruz Veri Yapıları ve Algoritmalar Ödevi 1 Sort Projesi

##  [22,27,16,2,18,6] -> Insertion Sort'a göre aşamalarını yazınız.

Aşamalar

1. [2,27,16,22,18,6]
2. [2,6,16,22,18,27]
3. [2,6,16,22,18,27] (olduğu gibi kalır çünkü kendisi en küçük rakam)
3. [2,6,16,18,22,27]

## Big O Gösterimi

n + (n-1) + (n-2) ... + 1 = n*(n+1)/2 = (n^2+n)/2 Big O(n^2)

## Time Complexity

1. Worst Case: Aradığımız sayının en sonda olması

2. Average Case: Aradığımız sayının ortada olması

3. Best Case: Aradığımız sayının başta olması.

## Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Average case kapsamına girer.

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1. [2,3,5,8,7,9,4,15,6]
2. [2,3,5,8,7,9,4,15,6]
3. [2,3,4,8,7,9,5,15,6]
4. [2,3,4,5,7,9,8,15,6]