# Binary Search Tree Projesi
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

# Binary Search Tree Projesi Cevap

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
    
Cevap: 
![](binarysearchtree.png)


1.Aşama: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] sıralanmamış dizisinin ilk eleman 7, root(kök) olarak belirlenir.

2.Aşama: Dizinin ikinci elemanı olan 5, 7'den küçük olduğu için 7'nin sol tarafına eklenir. 

3.Aşama: Dizinin üçüncü elamanı 1, 7'den küçüktür. Bu yüzden sol tarafa yazılmalıdır. 2.Aşama'da eklediğimiz 5'ten de küçük olduğu için 5'in de sol tarafına eklenir.   

4.Aşama: Dizinin dördüncü elemanı 8, 7'den büyük olduğu için 7'nin sağ tarafına eklenir. 

5.Aşama: Dizinin beşinci elemanı 3, 7'den küçüktür. Bu yüzden sol tarafa yazılmalıdır. 2.Aşamada eklediğimiz 5'ten de küçük olduğu için 5'in de sol tarafına yazılmalıdır. Ancak 3.Aşama'da 5'in sol tarafına eklediğimiz 1'den büyüktür. Bu yüzden 1'in sağ tarafına eklenir. 

6.Aşama: Dizinin altıncı elemanı 6, 7'den küçüktür. Bu yüzden sol tarafa yazılmalıdır. 2.Aşama'da eklediğimiz 5'ten büyük olduğu için 5'in sağ tarafına eklenir.

7.Aşama: Dizinin yedinci elemanı 0, 7'den küçüktür. Bu yüzden sol tarafa yazılmalıdır. 2.Aşama'da eklediğimiz 5'ten de küçük olduğu için 5'in de sol tarafına yazılmalıdır. 3.Aşama'da 5'in sol tarafına eklediğimiz 1'den de küçük olduğu için 1'in sol tarafına eklenir.   

8.Aşama: Dizinin sekizinci elemanı 9, 7'den büyüktür.  Bu yüzden sağ tarafa yazılmalıdır. 4.Aşama'da eklediğimiz 8'den de büyük olduğu için 8'in sağ tarafına eklenir.

9.Aşama: Dizinin dokuzuncu elemanı 4, 7'den küçüktür. Bu yüzden sol tarafa yazılmalıdır. 2.Aşama'da eklediğimiz 5'ten de küçük olduğu için 5'in de sol tarafına yazılmalıdır. 3.Aşama'da eklediğimiz 1'den büyük olduğu için 1'in sağına yazılmalıdır. 5.Aşamada 1'in sağına eklediğimiz 3'ten de büyük olduğu için 3'ün sağına eklenir.

10.Aşama: Dizinin onuncu elemanı 2, 7'den küçüktür. Bu yüzden sol tarafa yazılmalıdır. 2.Aşama'da eklediğimiz 5'ten de küçük olduğu için 5'in de sol tarafına yazılmalıdır. 3.Aşama'da eklediğimiz 1'den büyük olduğu için 1'in sağına yazılmalıdır. 5.Aşamada 1'in sağına eklediğimiz 3'ten küçük olduğu için 3'ün soluna eklenir.

## Patika Profilim
[Patika linki](https://app.patika.dev/melisaesenn)