# Binary Search Tree Projesi
[7,5,1,8,3,6,0,9,4,2]
* Root 7 seçersem;
-                7
-              /   \
-             5     8
-           /   \    \
-          1     6    9
-        /  \
-      0     3   
-             \           
-              4
## Açıklama 
Root 7 seçildiği zaman;
* 5, 7'den küçük olduğu için root'un solunda bulunur.
* 1, 7'den ve 5'ten küçük olduğu için 5'in solunda bulunur.
* 8, 7'den büyük olduğu için 7'nin sağında bulunur.
* 3, 7'den ve 5'ten küçük; 1'den büyük olduğu için 1'in sağında bulunur.
* 6, 7'den küçük 5'den büyük olduğu için 5'in sağında bulunur.
* 0, hepsinden küçük olduğu için kendinden önceki en küçük sayı olan 1'in solunda bulunur.
* 9, hepsinden büyük olduğu için kendinden önceki en büyük sayı olan 8'in sağında bulunur.
* 4, 7 ve 5'ten küçük; 1 ve 3'ten büyük olduğu için 3'ün sağında bulunur.
* 2, 7 ve 5'ten küçük; 1'den büyük ve 3'ten küçük olduğu için 3'ün solunda bulunur.
