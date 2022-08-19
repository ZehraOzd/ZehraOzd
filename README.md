Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


1)
 n elamanın hepsine bakılır

[22,27,16,2,18,6]               [2] başa sabitlenir, sonraki n-1 elemana bakılır     
                                                
[2,27,16,22,18,6]               [2,6] sabitlenir , sonraki n-2 elemana bakılır

[2,6,16,22,18,27]               [2,6,16] sabitlenir  sonraki n-3 elemana bakılır

[2,6,16,18,22,27]               [2,6,16,18] sabitlenir  sonraki n-4 elemana bakılır

[2,6,16,18,22,27]               [2,6,16,18,22] sabitlenir sonraki n-5 elamana bakılır

                                 Dizi son olarak [2,3,16,18,22,27] olarak sıralanır  

          n*(n+1)/2 => Bıg O(n^2)
2)
Average case : O(n^2)
Worst case     : O(n^2)
Best case       :O(n)
3)
Average kapsamına girer çünkü aradaığız sayı dizini ortasıda .


- [7,3,5,8,2,9,4,15,6] ınsertion sorta göre sıralama .

[2,3,5,8,7,9,4,15,16]
[2,3,4,8,7,6,5,15,16]
[2,3,4,5,7,6,8,15,16]
[2,3,4,5,6,7,8,15,16]
