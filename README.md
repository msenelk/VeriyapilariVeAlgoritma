# Patika.dev
## Veri Yapıları ve Algoritma Ödevi

### Insertion Sort Projesi

**[22,27,16,2,18,6]** -> Insertion Sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2.Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

3.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

4.**[7,3,5,8,2,9,4,15,6]** dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


### Soru - 1 Cevap
```
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]
```


### Soru - 2 Cevap
```
o(3^2)
```

### Soru - 3 Cevap

```
Avarage Case: (16,18)
Word Case: (27)
Best Case: (2)
```
### Soru - 4 Cevap

```
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]
```
--------------

### Merge Sort Projesi

**[16,21,11,8,12,22]** -> Merge Sort

1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

2.Big-O gösterimini yazınız.

### Soru - 1 Cevap

|||||||||||||
|-----|-----| ----|----|----|----|----|----|----|----|----|----|
|Satır Sıralaması  |1|2|3|4|5|6|7|8|9|10|11|12|
|Diziyi ikiye bölerek yeniden yazıyoruz  ||||16|21|11|8|12|22|||
|Sol ve sağdaki dizileri tekrar ikiye böluyoruz.  |||16|21|11|||8|12|22||
|Tek eleman kalana kadar bir kez daha bölüyoruz.  ||16|21||11|||8||12|22||
|  |16||21||11||8||12||22||


### Bölme işlemi bitikten sonra, tek elemanlı dizilerimizi ikili ikili birleştiriyoruz. Sıralı dizi elde edinceye kadar bu işleme devam ediyoruz.

|||||||||||||
|-----|-----| ----|----|----|----|----|----|----|----|----|----|
|Satır Sıralaması  |1|2|3|4|5|6|7|8|9|10|11|12|
|ikili ikili ikili sıralayarak birleştiriyoruz.  |16||21||11||8||12||22||
|Tekrar ikili ikili sıralayarak birleştiriyoruz.  ||16|21||11||8||12|22|||
|Tekrar ikili ikili sıralayarak birleştiriyoruz.  ||16|21||11||8|||12|22||
|Tekrar ikili ikili sıralayarak birleştiriyoruz.  |||11|16|21||||8|12|22||
|Son birleştirmede küçükten büyüğe sıralıyoruz.  ||||8|11|12|16|21|22||||

### Soru - 2 O(7*(log7)) Cevap




[Patika.dev](http://www.patika.dev)
