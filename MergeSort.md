# Merge Sort

## [16,21,11,8,12,22]
- ### Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
*** [16,21,11,8,12,22] ilk asama olarak parcalama yapmaliyiz

1- [16,21,11] [8,12,22] => 3 erli 2 gruba ayirdik

2- [16] [21,11] [8,12] [22] => 3 lu gruplari 2 serli gruplara ayirdik(esi olmayan tek kalabilir,tek kalan rastgele secilir)

3- [16] [21] [11] [8] [12] [22] => 2 li gruplar tekli gruplara dagilir

4- [16] [11,21] [8,12] [22] => gruplar tekrar 2'li gruplara donusturulur tek fark grup yapilirken kucuk basa gecer

5- [11,16,21] [8,12,22] => 3'lu sirali gruplara gecilir

6- [8,11,12,16,21,22] => tum grup birlesir ve kendi icinde siralanir


- ### Big-O Notation -> O(n.logn)