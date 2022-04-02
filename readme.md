
# Binary Search Tree Projesi 

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız. 

- Root olarak dizinin sıralanmış halinin ortalarından bir sayı seçersek daha dengeli bir dağılım olur
- Root olarak 5 seçelim
- 7>5 olduğu için 7 5'in sağına eklenir
- 1>5 olduğu için 1 5'in soluna eklenir 
- 8>5, 8>7 olduğu için 8 7'nin sağına eklenir
- 3<5, 3>1 olduğu için 3 1'in sağına eklenir
- 6>5, 6<7 olduğu için 6 7'nin soluna eklenir
- 0<5, 0<1 olduğu için 0 1'in soluna eklenir
- 9>5, 9>7, 9>8 olduğu için 9 8'in sağına eklenir
- 4<5, 4>1, 4>3 olduğu için 4 3'ün sağına eklenir
- 2<5, 2>1, 2<3 olduğu için 2 3'ün soluna eklenir

                5
			 /     \
		   1         7 
		 /   \     /   \
		0    3    6     8
		   /   \         \
		  2     4         9