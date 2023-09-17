# Patika-Veri-Yapilari
## This is a basic data structures example taken from patika.dev

### [22,27,16,2,18,6] -> Insertion Sort
### Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Adım 1: [22], [27, 16, 2, 18, 6]
Adım 2: [22, 27], [16, 2, 18, 6]
Adım 3: [16, 22, 27], [2, 18, 6]
Adım 4: [2, 16, 22, 27], [18, 6]
Adım 5: [2, 16, 18, 22, 27], [6]
Adım 6: [2, 6, 16, 18, 22, 27], []


### Big-O gösterimini yazınız.
1+(n-5)+(n-4)+(n-3)+(n-2)+(n-1)+n=[n(n+1)]/2=(n^2+n)/2 → O(n^2)

### Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
Average case


### [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
Adım 1 : [2, 3, 5, 8, 7, 9, 4, 15, 6]
Adım 2: [2, 3, 5, 4, 7, 9, 8, 15, 6]
Adım 3: [2, 3, 4, 5, 7, 6, 8, 15, 9]
Adım 4: [2, 3, 4, 5, 6, 7, 8, 15, 9]

### 
### [16,21,11,8,12,22] -> Merge Sort
Adım 1 : [16, 21, 11], [8, 12, 22]
Adım 2: [16], [21, 11], [8], [12, 22]
Adım 3: [16], [11, 21], [8], [12, 22]
Adım 4: [11, 16, 21], [8], [12, 22]
Adım 5: [11, 16, 21], [8, 12, 22]
Adım 6: [8, 11, 12, 16, 21, 22]

### Big-O gösterimini yazınız.
O(nlogn)
### 

### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Kök düğüm 3 olarak alınırsa sol kısımda 3 den küçük ,sağda 3’den büyük değerler sıralanacaktır.

    3
/       \
1         7
/ \       /   \
0  2   5     8
        /  \       \
       4    6      9
