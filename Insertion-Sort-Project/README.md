# Insertion Sort

[ 22, 27, 16, 2, 18, 6 ]

## Steps:
Başlangıç: [ 22, 27, 16, 2, 18, 6 ] 
1. [ 2, 27, 16, 22, 18, 6 ]
2. [ 2, 6, 16, 22, 18, 27 ]
3. [ 2, 6, 16, 18, 22, 27 ]

Sayıları sırasıyla soldan sağa küçükten büyüğe gelecek şekilde dizme amacıyla, sırasında olmayan en küçük sayıyı bulup ve bunu yaparken yerine geçecek olduğumuz elemanla yer değiştirerek sıralamamızı yaptık.
  
## Big O Notation:
 
Big O(n²)

## Time Complexity:

**Worst Case:** O(n²)  
**Average Case:** O(n²)  
**Best Case:** O(n)

## Case of Number 18:
Yer değiştirme sırasında ortada olduğu için Average Case kapsamına girer.

## Bonus:

[ 7, 3, 5, 8, 2, 9, 4, 15, 6 ] dizisinin Insertion Sort'a göre ilk 4 adımı:

**Steps**  

Başlangıç: [ 7, 3, 5, 8, 2, 9, 4, 15, 6 ]
  
1. [ 2, 3, 5, 8, 7, 9, 4, 15, 6 ]
2. [ 2, 3, 4, 8, 7, 9, 5, 15, 6 ]
3. [ 2, 3, 4, 5, 7, 9, 8, 15, 6 ]
4. [ 2, 3, 4, 5, 6, 9, 8, 15, 7 ]







