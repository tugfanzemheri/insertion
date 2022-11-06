# Insertion Sort Projesi

## proje 1

[22,27,16,2,18,6] Insertion Sort

1.  Yukarıda verilen dizinin sort türüne göre aşamlarını yazın

2. Big-O gösterimi yapın
3. Time Complexity : Avarage Case : Aradığımız sayının ortada olması, Worst Case : Aradığımız sayının sonda olması, Best Case : Aradığımız sayının dizinin en başında olması.
4. Dizi Sıralandıktan sonra 18 sayısı hangi case kapsamına girer? yazınız.  


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

---
# İSTENEN PROJENİN YAPILMIŞ HALİ
---
## Dizinin sort türüne göre aşamaların yazılması.
---
1. [2,27,16,22,18,6] 2 Diznin en küçük sayısı olduğundan en başa alabilmek için 22 ile yer değiştiriyoruz.
2. [2,6,16,22,18,27] dizinin 2 den sonra en küçük rakamı 6 olduğundan 6 ile 27 rakamlarını yer değiştiriyoruz.
3. [2,6,16,18,22,27] dizide 6 dan sonra en küçük rakam 16 olduğunda üçüncü sıra için işlem yapmamıza gerek kalmadan 16 dan sonraki en küçük rakam olan 18 i dördüncü sıraya alabilmek için 22 ile yer değiştiriyoruz.beşinci ve altıncı sıradaki rakamlar zaten sıralı olduğundan dizimiz sıraya alınmış oluyor.
---
## Big-O gösteriminin yapılması
---
* bir dizinin eleman sayısına n dersek bu diziyi sıralayabilmek için ilk adımda büyükmüdür küçükmüdür diye hepsine baktığımda n tane işlem yapıyorum yani 6 tane işlem yapıyorum n=6 en küçük elemanı bulmuş oluyorum.
* ikinci adımda en küçük elemandan sonraki en küçük elamanı bulmak için n-1 tane işlem yapıyorum yani 6-1=5 işlem
* üçüncü adımda iki en küçük elemandan sonraki en küçük elemanı bulmak için n-2 tane işlem yapıyorum yani 6-2=4 işlem
* dördüncü adımda üç en küçük elemandan sonraki en küçük elemanı bulmak için n-3 tane işlem yapıyorum yani 6-3=3 işlem
* beşinci adımdan dört küçük elemandan sonraki en küçük elemanı bulmak için n-4 tane işlem yapıyorum yani 6-4=2 işlem 6 elemanlı bir dizi olduğu için altıncı adıma gerek kalmadan son elaman altıncı elaman olmuş oluyor.
benim algoritmam n+(n-1)+(n-2)+(n-3)+(n-4)+1 kadar işlem yapmış oluyor 6+5+4+3+2+1 den 21 işlemde diziyi sıralamış oluyorum.
Big-O cinsinden açıklarsak olayı
bu bana birden n'e kadar olan sayıların toplamını veriyor. 
birden n'e kadar sayıların toplama formülü ne idi [n(n+1)]/2 bunuda açarsak (n²+n)/2 çıkar. Big-o Notationda ne yapıyorduk bunu domine eden fonksiyonu aldığımız için n² değerini alıyoruz.

**Big-O değeri = O(n²)**
___

## Time Complexity
___
 18 sayısı için sıralarsak

  Best Case:     [18,.,.,.,.,.]

 Worst Case:    [.,.,.,.,.,18]

 Avarage Case:  [.,.,.,18,.,.]
 ___
## Dizi Sıralandıktan sonra 18 sayısı hangi case kapsamına girer?

___


Avarage Case : Aradığımız sayının ortada olması

 Worst Case : Aradığımız sayının sonda olması

  Best Case : Aradığımız sayının dizinin en başında olması.
  Dizinin sıralanmış hali

  [2,6,16,18,22,27] olduğuna göre ve 18 sayısı ortada kaldığı için Avarage Case kapsamına girer.

  ___

 ## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

___

[2,|3,5,8,7,9,4,15,6] Birinci adım

[2,3,|5,8,7,9,4,15,6] İkinci adım

[2,3,4,|8,7,9,5,15,6] Üçüncü adım

[2,3,4,5,|7,9,8,15,6] Dördüncü adım
___

[www.patika.dev](https://www.patika.dev/tr)











