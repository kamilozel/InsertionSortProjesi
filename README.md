# InsertionSortProjesi
Patika.dev Veri Yapıları ve Algoritmaları - Insertion Sort Projesi


## [22,27,16,2,18,6] -> Insertion Sort
**##Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.**

1. [22,27,16,2,18,6]
2. [16,22,27,2,18,6]
3. [2,16,22,27,18,6]
4. [2,16,18,22,27,6]
5. [2,6,16,18,22,27]


**Big-O gösterimini yazınız.**
<br>n+(n-1)+(n-2)+...+1 = n.(n+1)/2 = n^2+n/2 
<br>[Dominant Fonksiyon n^2] olduğu için --> O(n2)

**Time Complexity:** <br>
Average case: Aradığımız sayının ortada olması, O(n^2)<br>
Worst case: Aradığımız sayının sonda olması, --> O(n^2)<br>
Best case: Aradığımız sayının dizinin en başında olması. --> O(n)

**Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.**
<br>Avarage Case


**[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**
<br>
1. 3,7,5,8,2,9,4,15,6
2. 3,5,7,8,2,9,4,15,6
3. 3,5,7,8,2,9,4,15,6
4. 2,3,5,7,8,9,4,15,6