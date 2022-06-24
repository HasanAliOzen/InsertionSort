# Insertion Sort Project

[22,27,16,2,18,6] -> Insertion Sort 


## Q1

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

### A1

- [2,27,16,22,18,6]
- [2,6,16,22,18,27]
- [2,6,16,18,22,27]

## Q2

Big-O gösterimini yazınız.


### A2

- n + (n-1) + (n-2) + (n-3) + (n-4) 
- O(n^2)

## Q3

Time Complexity: 
* Best case: Aradığımız sayının dizinin en başında olması.
* Average case: Aradığımız sayının ortada olması,
* Worst case: Aradığımız sayının sonda olması, 

### A3 

* Best case: O(1) -> Aradığımız sayının dizinin en başında olması.

* Average case: O(n/2) -> Aradığımız sayının ortada olması.

* Worst case: O(n) -> Aradığımız sayının sonda olması.

## Q4

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?

### A4 

18'in indexi 3. Dizinin ortasında bulunduğu için average casedir.

## Q5

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

### A5

- [2,3,5,8,7,9,4,15,6]
- [2,3,4,8,7,9,5,15,6]
- [2,3,4,5,7,9,8,15,6]
- [2,3,4,5,6,9,8,15,7]


