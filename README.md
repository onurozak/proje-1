[Patika.dev](https://www.patika.dev/tr)

Insertion Sort Projesi

Proje 1
[22,27,16,2,18,6] -> Insertion Sort
  
1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
    
    1.	Aşama   [2,27,16,22,18,6]
    2.	Aşama   [2,6,16,22,18,27]
    3.	Aşama   [2,6,16,18,22,27]
    
2. Big-O gösterimini yazınız.
    
    n+(n-1)+(n-2) . . . +1 = n . (n+1)/2 = (n2+n)/2 
    Big-O = O(n2)
    
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
    
    Average Case : O(n2)
    Worst Case : O(n2)
    Best Case : O(n)

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
    
    Dizi sıralandıktan sonra 18 sayısı orta noktada yer aldığı için average case kapsamına girer.

5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

    1.	Aşama    [2,3,5,8,7,9,4,16,6]
    2.	Aşama    [2,3,4,8,7,9,5,16,6]
    3.	Aşama    [2,3,4,5,7,9,8,16,6]
    4.	Aşama    [2,3,4,5,6,9,8,16,7]
