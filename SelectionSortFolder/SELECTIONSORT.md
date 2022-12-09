# Veri Yapıları Projeler
## Selection Sort çözümü

```
[22,27,16,2,18,6] -> Insertion Sort
```
### aşamalar
* [2,27,16,6,18,22] en küçük 2 olduğundan 6 ile yer değiştiriliyor.
* [2,6,16,27,18,22] ikinci küçük 6 olduğunda 27 ile yer değiştiriliyor.
* [2,6,16,27,18,22] zaten 16 üçüncü sırada. 
* [2,6,16,18,27,22] 18 ile 27 yer değiştiriyor
* [2,6,16,18,22,27] 27 ile 22 yer değiştiriliyor
* [2,6,16,18,22,27] sonuç

### big-O gösterimi
6 5 4 .. 1 şeklinde bakılıyor. Bu durum 
`n+(n-1)+(n-2)+…+1` ve dolayısıyla da `n(n+1)/2` ile ifade edilebilir ve ifade açılırsa içinde `n^2` ifadesi bulunmaktadır. Big-O ifade O(n^2)'dir.

### zaman karmaşıklığı
18 sayısı hem başta hem de sonda olmadığı için `Average Case` kapsamına girer.

### [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı
* [2,3,5,8,7,9,4,15,6]
* [2,3,5,8,7,9,4,15,6]
* [2,3,4,8,7,9,5,15,6]
* [2,3,4,5,7,9,8,15,6]



