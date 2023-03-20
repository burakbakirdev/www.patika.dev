# Merge Sort

- [16,21,11,8,12,22] 
- [16,21,11]  [8,12,22] Tek bir eleman kalana kadar bölüm yapılır.
- [16,21] [11]    [8,12] [22] Elemanlar kıyaslanarak merge yapılır. Burada önemli nokta en soldaki elemandan başlanarak kıyas yapılması. Böylelikle az işlem yapılır.
- [11,16,21]     [8,12,22]
- [8,11,12,16,21,22] 

Big-O(nlogn)
