# Merge_Sort_Projesi

[16,21,11,8,12,22] -> Merge Sort

- [16,21,11]  |  [8,12,22]
- [16] [21,11]  |  [8,12] [22]
- [16] [21] [11]  |  [8] [12] [22]
- [11,16,21]  |  [8,12,22]
- [8,11,12,16,21,22]

#### 2. Big-O gösterimini yazınız.
Recursive bir fonksiyon olduğu için sürekli kendini çağırarak diziyi hep ikiye bölmektedir. Her bölünmüş dizinin Merge işlemi için de dizinin uzunluğu olan n işlem yapıldığından O(n*(logn)) --> O(6*(log6)) olacaktır.

[Patika.dev](www.patika.dev)
