# **Merge Sort Projesi**

## ***Soru***
___

[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.


## ***Cevap***
---
Sıralanacak diziyi ikiye bölüp kendi içinde sıralı küçük parçaları birleştirme mantığına dayanır.

1. [16,21,11,8,12,22] dizisi örneği için;

Dizinin sort türüne göre aşamaları: [16,21,11,8,12,22] [16,21,11] [8,12,22] [16] [21,11] [8] [12,22] [16] [21,11] [8] [12,22] [16,21,11] [8,12,22] [8,12,16,21,11,22]

2. Big-O gösterimi: On(logn)