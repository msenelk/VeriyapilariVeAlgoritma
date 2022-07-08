# Patika.dev
## Veri Yapıları ve Algoritma Ödevi

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

### Soru - 2 Cevap

```
O(7*(log7))
```




[Patika.dev](http://www.patika.dev)
