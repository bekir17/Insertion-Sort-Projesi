# Insertion-Sort-Projesi
## [22,27,16,2,18,6] -> Insertion Sort

Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
  
 # Insertion-sort Türüne göre aşamaları                      
 [22,27,16,2,18,6]                        =n                
 [2,27,16,22,18,6]                        =n-1                                                  
 [2,6,16,22,18,27]                        =n-2
 [2,6,16,18,22,27]                        =1

  # Big O Gösterimi
  #  1 den n kadar olan sayıların toplamı : n.(n+1)/2=n^2+n/2 büyük ifade alınır 
  #                                          sonuç : O( n^2)
  # Time Complextiy ( 2 için inceleyelim )
   Best Case :   [2,6,16,18,22,27]
   Avarage Case: [22,27,16,2,18,6]
   Worst Case :  [22,27,16,6,18,2]
  
  # [2,6,16,18,22,27] Dizi sıralandıktan sonra 18 sayısı ortada bir yerde yer aldığı için Avarage case kapsamına girer.
  
  # [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
     [7,3,5,8,2,9,4,15,6]
     [2,3,5,8,7,9,4,15,6]
     [2,3,4,8,7,9,5,15,6]
     [2,3,4,5,7,9,8,15,6]
     [2,3,4,5,6,9,8,15,7]
     [2,3,4,5,6,7,8,15,9]
     [2,3,4,5,6,7,8,9,15]
