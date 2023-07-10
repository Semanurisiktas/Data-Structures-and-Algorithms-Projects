# Data-Structures-and-Algorithms-Projects

## Project 1

[22,27,16,2,18,6] -> Insertion Sort

A) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

- Adım 1: İlk olarak dizinin en küçük elemanı bulunur ve en baştaki eleman ile yer değiştirilir. 

  > [2,27,16,22,18,6]

- Adım 2: Dizinin ikinci en küçük elemanı bulunur ve ikinci sıradaki eleman ile yer değiştirilir.

  >[2,6,16,22,18,27]

- Adım 3: Dizinin üçüncü en küçük elemanı bulunur ve üçüncü sıradaki eleman ile yer değiştirilir. (Burada 16 sayısı doğru sırada olduğu için yer değiştirmedi)

  > [2,6,16,22,18,27]

- Adım 4: Dizinin dördüncü en küçük elemanı bulunur ve dördüncü sıradaki eleman ile yer değiştirilir.

  > [2,6,16,18,22,27]

- Adım 5: Dizinin en küçük beşinci elemanı bulunur ve altıncı sıradaki eleman ile yer değişitirllir. (Burada 22 ve 27 doğru sırada olduğu için yer değiştirmedi)


- Dizinin sıralanmış son hali : 
  > [2,6,16,18,22,27]

B) Big-O gösterimini yazınız.
  > Big-O(n<sup>2</sup>)

C) Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?

  > Aradığımız sayı (18) ortada olduğu için average case kapsamına girer. 

Average case: Aradığımız sayının ortada olması

Worst case: Aradığımız sayının sonda olması

Best case: Aradığımız sayının dizinin en başında olması.

D) [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
- Adım 1: [2,3,5,8,7,9,4,15,6]

- Adım 2: [2,3,5,8,7,9,4,15,6]

- Adım 3: [2,3,4,8,7,9,5,15,6]

- Adım 4: [2,3,4,5,7,9,8,15,6]

--- 
## Project 2

[16,21,11,8,12,22] -> Merge Sort

A) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
  - Adım 1: [16,21,11] -- [8,12,22]
  - Adım 2: [16] [21,11] --  [8] [12,22]
  - Adım 3: [16] [21] [11] --  [8] [12] [22]
  - Adım 4: [16] [11, 21] -- [8] [12,22]
  - Adım 5: [11,16,21] -- [8,12,22]
  - Adım 6: [8,11,12,16,21,22]
  
B) Big-O gösterimini yazınız.
  
  > Big-O(nlogn)

--- 
## Project 3

- [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

    Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

> Root 7'dir. 7 sayısı her iki tarafa (sağ-sol) referans verir. Sağ tarafta kendinden büyük sayıları, sol tarafta ise kendinden küçük sayıları barındırır. 8 sayısı 7'den büyük olduğu için root'un sağında, 5 sayısı 7'den küçük olduğu için solunda bulunur.  



                          7     --->Root
                        /   \
                       5      8
                      / \      \
                     1   6      9
                    / \
                    0  3
                      /  \
                     2    4

