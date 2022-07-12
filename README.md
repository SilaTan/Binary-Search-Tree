# Binary-Search-Tree

Patika Profili = https://app.patika.dev/SilaTan

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları

İlk değer olan 7 root seçilir. 5 değeri root değerinden küçük olduğu için sol tarafa yazılır.

1. ----------------------------------------------------

7

2. ----------------------------------------------------


   7
  /
 5
 
 1 değeri 7'den küçüktür, sola tarafa gider, 5'ten de küçüktür o yüzden 5'in sol altına yazılır.
 
 3. ----------------------------------------------------


	  7
	 /
	5
 /
1

8 değeri 7'den büyüktür, root'un sağ tarafına yazılır.

4. ----------------------------------------------------

     7
	  / \
   5   8
  /   
 1    
 
 
 3 değeri 7'den küçüktür, 5'ten küçüktür ama 1'den büyüktür, bu yüzden 1'in sağ tarafına yazılır.
 
 5. ----------------------------------------------------

     7
	  / \
   5   8
  /   
 1  
	\
	 3
   
6 değeri 7'den küçüktür, 5'ten büyüktür, bu yüzden 5'in sağına yazılır.

6. ----------------------------------------------------


     7
	  / \
   5   8
  / \   
 1   6
	\
	 3
   
0 değeri 7'den, 5'ten ve 1'den küçüktür, bu yüzden 0'ın soluna yazılır.   

7. ----------------------------------------------------


      7
	   / \
    5   8
   / \   
  1   6
 / \
0	  3



9 değeri 7'den ve 8'den büyüktür, bu yüzden 8'in sağına yazılır

8. ----------------------------------------------------


      7
	   / \
    5   8
   / \   \
  1   6   9
 / \
0	  3
	  
4 değeri 7'den ve 5'den küçüktür, 1'den ve 3'ten büyüktür, bu yüzden 3'ün sağına yazılır.

9. ----------------------------------------------------


      7
	   / \
    5   8
   / \   \
  1   6   9
 / \
0	  3
	   \
      4
      
   
2 değeri 7'den ve 5'den küçüktür, 1'den büyük ama 3'den küçüktür, bu yüzden 3'ün soluna yazılır.   
   
   10. ----------------------------------------------------


      7
	   / \
    5   8
   / \   \
  1   6   9
 / \
0	  3
	 / \
  2   4

   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
 
 
 
 
 
 
 
 
 
 
 
 
