# ProjectInsertionSort-WorkShop

Insertion Sort

## Proje-1

## [22,27,16,2,18,6] -> Insertion Sort

### Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

İlk elemanla sağındaki eleman karşılaştırılır. Daha küçük olan sola alınır.

1. [22,27,16,2,18,6] 22 ve 27 doğru sırada. Bu şekilde bırakılır.
2. [16,22,27,2,18,6] 27 ve 16 karşılaştırılır. 16 daha küçük olduğu için yer değiştirirler. 16, 22'den de küçük olduğu için onunla da yer değiştirir.
3. [2,16,22,27,18,6] 2, 27'den, 22'den ve 16'dan küçük olduğu için en başa gelir. Geri kalan elemanlar da aynı mantıkla sıralanır.
4. [2,16,18,22,27,6] 18 elemanı 2'den büyüktür ve sağına kayar, 16'dan da büyüktür ve sağına kayar 22'den küçüktür burada kalır.
5. [2,6,16,18,22,27] 6 elemanı 2'den büyüktür ve sağına kayar, 16'dan küçüktür burada kalır. Böylelikle Dizimiş oluşmuş olur.

### Big-O gösterimini yazınız.

Insertion Sort algoritmasının en kötü durumda çalışması (O(n^2)) olarak ifade edilir. Çünkü her eleman, neredeyse tüm diğer elemanlarla karşılaştırılmak zorundadır. Ortalama durumda da yine (O(n^2)) olarak ifade edilir. En iyi durumda, yani dizi zaten sıralıysa, (O(n)) olur.

### Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

Time Complexity
18 sayısı, sıralandıktan sonra dizinin ortasında yer alır. Bu nedenle, Average Case kapsamına girer.

### [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Selection Sort Aşamaları
Verilen dizi: [7, 3, 5, 8, 2, 9, 4, 15, 6]

1. İlk adımda en küçük eleman (2) bulunur ve ilk elemanla yer değiştirilir:
   [2, 3, 5, 8, 7, 9, 4, 15, 6]
2. İkinci en küçük eleman (3) zaten ikinci sıradadır, yer değiştirme yapılmaz:
   [2, 3, 5, 8, 7, 9, 4, 15, 6]
3. Üçüncü en küçük eleman (4) bulunur ve üçüncü elemanla yer değiştirilir:
   [2, 3, 4, 8, 7, 9, 5, 15, 6]
4. Dördüncü en küçük eleman (5) bulunur ve dördüncü elemanla yer değiştirilir:
   [2, 3, 4, 5, 7, 9, 8, 15, 6]
