# INSERTION SORT
www.patikadev.com
Sorting-Insertion method

[22,27,16,2,18,6] -> Insertion Sort

1. Dizinin sort türüne göre aşamaları : 
   [22]
   [22 , 27]
   [16, 22 , 27]
   [2, 16, 22, 27]
   [2, 16, 18 , 22, 27 ]
   [2, 6 , 16, 18, 22 , 27]   
   
2. Big-O notation :
Her değer diğer değerler ile kıyaslanarak sıralama yapılır. Örneğin birinci sırada yer alan 22 sayısı, en küçük değeri bulup yer değiştirir ve bunun için n tane kontrol yapar. İkinci sıra için artık birincinin yeri kesindir ve (n-1) tane arama yapılır. (n-3),(n-4) ... (1) şeklinde azalarak kontrol sayısı devam eder. Bunun formule edilmiş hali :(n.(n+1))/2 'dir. 
Dominant n^2 katsayıyı notasyondur. O(n^2)
3.Time Complexity 
- Avarage case : n^2 
- Worst case : (n^2)
- Best case : n (en iyi ihtimalle sıralıdır ve her sayı sadece bir kontrol yapar.)
4. 18 sayısı avarage case kapsamındadır.
5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
  [7]
  [3,7]
  [3,5,7]
  [3,5,7,8]
  [2,3,5,7,8]
