# Binary-Search-Tree-Projesi
 - [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız. 
 - Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

## 1.
	Root:7
## 2.
5, 7'den küçük bu yüzden sol tarafa yazılır.

        7
       /   
      5
## 3.
1, 5'ten küçük bu yüzden sol tarafa yazılır.
			
			
        7
       /   
      5 
     /
    1 
## 4.
8, 7'den büyük bu yüzden sağ tarafa yazılır.

        7
       / \  
      5   8
     /
    1 
## 5.
3, 1'den büyük bu yüzden 1'in sağına yazılır.

        7
       / \  
      5   8
     / 
    1   
     \
      3
## 6.
6, 5'ten büyük bu yüzden 5'in sağına yazılır.

        7
       / \  
      5   8
     / \
    1   6
     \
      3
## 7.
0, 1'den küçük bu yüzden 1'in soluna yazılır.

          7
         / \  
        5   8
       / \     
      1   6   
     / \
    0   3
## 8.
9, 8'den büyük bu yüzden 8'in sağına yazılır.

           7
          / \  
         5   8
        / \   \  
       1   6   9
      / \
     0   3 
## 9.
4, 3'ten büyük bu yüzden 3'ün sağına yazılır.

          7
         / \  
        5   8
       / \   \  
      1   6   9
     / \
    0   3
         \
          4
## 10.
2, 3'ten küçük bu yüzden 3'ün soluna yazılır.

          7
         / \  
        5   8
       / \   \  
      1   6   9
     / \
    0   3
       / \
      2   4
