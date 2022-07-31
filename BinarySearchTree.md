[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız

bu ağaçta root 6'dır.

7, 6 dan büyük olduğu için sağdadır.

                6
                    7

5, 6 küçük olduğu için soldadır.

                6
            5       7

1, 6 ve 5 ten küçük olduğu için soldadır

                6
           5       7
        1

8, 6 ve 7 den büyük olduğu için en sağdadır.

                6
           5       7
        1               8

3, 6 dan küçük, 1 den büyük olduğu için sağdadır.

                6
           5       7
        1               8
            3


0, en küçük rakam olduğu için en soldadır.

                6
           5       7
        1               8
            3
    0


9, en büyük rakam olduğu içn en sağdadır.

                6
           5       7
        1               8
    0        3              9
    

4, 6 dan küçük, 3 ila 5 arasındadır.

                 6
           5          7
        1                   8
    0        3                   9
                4


2, altıdan küçük olduğu için sol tarafta olacak

                 6
           5          7
        1                   8
    0        3                   9
                4
            2


[Patika.dev](http://www.patika.dev)