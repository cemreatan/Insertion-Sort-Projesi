# Insertion-Sort-Projesi
Patika - Veri yapıları ve algoritmalar dersi

[Patika.dev](Patika.dev)

## [22,27,16,2,18,6] -> Insertion Sort
- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

 [22,27,16,2,18,6] ->   n
 [2,27,16,22,18,6] ->   n-1
 [2,6,16,22,18,27] ->   n-2
 [2,6,16,18,22,27] ->   1 
 
 - *Big-O gösterimini yazınız.*
 
  (n.(n+1))/2
 
  (n^2+n)/2
 
   O(n^2)
   
   
 - *Time Complexity*
 
 Average case: Aradığımız sayının(18) ortada olması -->[2,6,16,18,22,27]
 
 Worst case: Aradığımız sayının(2) sonda olması,   -->[27,22,18,16,6,2]
 
 Best case: Aradığımız sayının(2) dizinin en başında olması. -->[2,6,16,18,22,27]
 
 - *Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.*
 
 Sıralı dizi : [2,6,16,18,22,27]
 
 Average Case'dir.
 
 - *[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.*
 
 [7,3,5,8,2,9,4,15,6]  -> n
 
 [2,7,5,8,3,9,4,15,6]  ->  n-1
 
 [2,3,5,8,7,9,4,15,6]  ->  n-2
 
 [2,3,4,8,7,9,5,15,6]  ->  n-3
 
 
