## Insertion Sort Project

## Project- 1

[22,27,16,2,18,6] -> Insertion Sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2.Big-O gösterimini yazınız.
3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## Solution

### 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

 En basit sorting algoritmalarından biridir. 
İlk olarak verilen dizideki en küçük elemanı buluyor. Ve en baştaki sayı ile yer değiştiriyor. Sonrasında ikinci en küçük elemanı buluyor ve ikinci sıra ile yer değiştiriyor. Ardından üçüncü, dördüncü ve bu şekilde işlemine devam ediyor. Eğitim videosunda kitap sayfalarını tek tek kontrol etme örneğindeki gibi dizideki elemanlara tek tek bakıyoruz. Bu da O(n) zamanda işlem yapmaya neden oluyor.

İlk hali : [22,27,16,2,18,6]
```
 [22|,27,16,2,18,6]
 [22,27|,16,2,18,6]
 [16,22,27|,2,18,6]
 [2,16,22,27|,18,6]
 [2,16,18,22,27|,6]
 [2,6,16,18,22,27]

```

## 2- Big-O gösterimini yazınız.

 Worst Case : O(n^2)
 Avarage Case : O(n^2)
 Best Case : O(n)

## 3 - Time Complexity

```
 Best Case : [2,6,16,18,22,27]
 Worst Case : [27,22,18,16,6,2]

 ```

## 4 - Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


Dizi sıralandıktan sonra [2,6,16,18,22,27] halini alır.Bu durumda 18 sayısı ortada olarak sayılabilir.

Average case -> [2, 6, 16, 18, 22, 27] 


## Ek Soru

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


```
 [7|,3,5,8,2,9,4,15,6]

 [3,7|,5,8,2,9,4,15,6]

 [3,5,7|,8,2,9,4,15,6]

 [3,5,7,8|,2,9,4,15,6]

```


#### You can reach Patika Dev Profile : https://app.patika.dev/liri