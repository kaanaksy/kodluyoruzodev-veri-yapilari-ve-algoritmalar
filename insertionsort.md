[22,27,16,2,18,6] -> Insertion Sort

1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2) Big-O gösterimini yazınız.
3) Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

1)  [22,27,16,2,18,6] -> n
    [2,27,16,22,18,6] -> (n-1)
    [2,6,16,22,18,27] -> (n-2)
    [2,6,16,18,22,27] -> 1

2)  O(n^2)

3)  Average Case: [6,2,16,18,22,27]
    Worst Case: [27,22,18,16,6,2]
    Best Case: [2,6,16,18,22,27]

4) Average Case. Çünkü 18 ortada bulunuyor

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1.[2,3,5,8,7,9,4,15,6]
2.[2,3,4,8,7,9,5,15,6]
3.[2,3,4,5,7,9,8,15,6]
4.[2,3,4,5,6,9,8,15,7]