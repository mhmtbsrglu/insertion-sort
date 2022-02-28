# [22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.
 
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Patika insertion sort ödevi.</br>
Not:birbirleri ile yer değiştirirler

# [22,27,16,2,18,6] -> Insertion Sort (N + (N-1) + ( N-2 ) ... + 1)
- [22,27,16,2,18,6]
- [2,27,16,22,18,6]
- [2,6,16,22,18,27]
- [2,6,16,18,22,27] 2 low 18 mid 27 high

# Big O Notation
- O(n^2)

# Time Complexity
- Average case: Aradığımız sayının ortada olması,
- Worst case: Aradığımız sayının sonda olması,
- Best case: Aradığımız sayının dizinin en başında olması.

# Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
- Middle yani Ortalama(Avarage) Case'dir.


# [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

- [7,3,5,8,2,9,4,15,6]
- [2,3,5,8,7,9,4,15,6]
- [2,3,4,8,7,9,5,15,6]
- [2,3,4,5,7,9,8,15,6]
- [2,3,4,5,6,9,8,15,7]
- [2,3,4,5,6,7,8,15,9]
- [2,3,4,5,6,7,8,9,15]
