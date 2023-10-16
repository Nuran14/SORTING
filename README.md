# Selection-Sort
         S1:                   [22,27,16,2,18,6]
a) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[2,27,16,22,18,6]

[2,6,16,22,18,27]

[2,6,16,22,18,27]

[2,6,16,18,22,27]


```
b) Big-O gösterimini yazınız.
```
cevap: Big O : O(n^2) 

```
c) Time Comlexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

1. Average Case: Aranan sayının ortada olması
2. Worst Case: Aranan sayının sonda olması
3. Best Case: Aranan sayının dizinin en başında olması
```
cevap: Average Case

```
S2: [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
```
[2,3,5,8,7,9,4,15,6]

[2,3,4,8,7,9,5,15,6]

[2,3,4,5,7,9,8,15,6]

[2,3,4,5,6,9,8,15,7]

# Merge Sort
```
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

CEVAP: 
            [16,21,11]                             [8,12,22]
           /           \                         /           \
         [16,21]    -    [11]                  [8,12]    -    [22] 
         /        \             \               /      \            \
   [16]    -    [21]    -    [11]        [8]     -    [12]    -    [22]   
   \       /              /             \         /            /
        [16,21]    -    [11]                  [8,12]    -    [22]
        \            /                        \           /
                [11,16,21]                            [8,12,22]
                                  
                     =>        [8,11,12,16,21,22]

Big O : O(nlog)
```
# Binary Search Trea
```
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
```
CEVAP:

```
Root x = 6
                             6
                           /   \ 
                          5     7
                        /         \
                       1           8
                     /   \           \
                    0     3           9
                        /   \      
                       2     4    

```


