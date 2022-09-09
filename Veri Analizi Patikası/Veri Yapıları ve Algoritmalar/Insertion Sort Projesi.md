# Insertion Sort Projesi

* [22,27,16,2,18,6]

    1. Yukarı verilen dizinin insertion sort türüne göre aşamalarını yazınız.
    2. Big-O gösterimini yazınız.
    3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
    4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


* [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

# Insertion Sort Projesi Cevap

* [22,27,16,2,18,6]

1. Yukarı verilen dizinin insertion sort türüne göre aşamalarını yazınız.

    Cevap:  
    1. [**22**,**27**,16,2,18,6] -> [22,27,16,2,18,6]
    2. [22,**27**,**16**,2,18,6] -> [22,16,27,2,18,6]
    3. [**22**,**16**,27,2,18,6] -> [16,22,27,2,18,6] 
    4. [16,22,**27**,**2**,18,6] -> [16,22,2,27,18,6]
    5. [16,**22**,**2**,27,18,6] -> [16,2,22,27,18,6]
    6. [**16**,**2**,22,27,18,6] -> [2,16,22,27,18,6]
    7. [2,16,22,**27**,**18**,6] -> [2,16,22,18,27,6]
    8. [2,16,**22**,**18**,27,6] -> [2,16,18,22,27,6]
    9. [2,16,18,22,**27**,**6**] -> [2,16,18,22,6,27]
    10. [2,16,18,**22**,**6**,27] -> [2,16,18,6,22,27]
    11. [2,16,**18**,**6**,22,27] -> [2,16,6,18,22,27]
    12. [2,**16**,**6**,18,22,27] -> [2,6,16,18,22,27]


2. Big-O gösterimini yazınız.
 
    Cevap: n tane sayı içeren bir sayı dizisi olduğunu kabul edelim.
    1. Best Case: Bu n sayı içeren dizinin best case durumu küçükten büyüğe sıralı olmasıdır. Bu durumda sayılar yer değiştirmez sadece karşılaştırılır. n tane sayı içeren dizide n-1 karşılaştırma yapılır, insertion sort için best case time comlexity O($n$)'dir. 

    2. Worst Case: Bu n sayı içeren dizinin worst case durumu büyükten küçüğe sıralı olmasıdır. İlk olarak n-1 karşılaştırma yapılır, yer değiştirmeler yapıldıktan sonra karşılatırmak için n-2 sayı kalır. Bu şekilde 1 karşılaştırma kalana kadar sayı dizisi küçükten büyüğe sıralanır. Yani $(n-1)+(n-2)+(n-3)+...+1= {n.(n-1)\over 2}$ eşitliğinden insertion sort için worst case time comlexity O($n^2$)'dir. 

    3. Average Case: Bu n sayı içeren dizinin average case durumu dizinin yarısının sıralı olmasıdır. Worst case durumunda hesapladığımız işlemlerin yarısı olacağını düşünürsek ${n.(n-1)\over 4}$ eşitliğinden insertion sort için average case time comlexity O($n^2$)'dir. 
    
    [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort Big-O gösterimi O($n^2$)'dir.

3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
    
    

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
    
    Cevap: [22,27,16,2,18,6] dizisi [2,6,16,18,22,27] olarak sıralanır. 18 sayısı dizi sıralandıktan sonra  average case kapsamına girer.

* [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.    
    Cevap: 
    1. [**7**,**3**,5,8,2,9,4,15,6] -> [3,7,5,8,2,9,4,15,6]
    2. [3,**7**,**5**,8,2,9,4,15,6] -> [3,5,7,8,2,9,4,15,6]
    3. [3,5,**7**,**8**,2,9,4,15,6] -> [3,5,7,8,2,9,4,15,6]
    4. [3,5,7,**8**,**2**,9,4,15,6] -> [3,5,7,2,8,9,4,15,6]