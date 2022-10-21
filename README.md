# Insertion-Sort-Project


1)
[22,27,16,2,18,6] -> Insertion Sort

[2,27,16,22,18,6] -- Listeden en küçük değeri bulup baştaki değerle yerini değiştirdik.

[2,6,16,22,18,27] -- 2. en küçük değeri bulup 2. sıradaki değerle yerini değiştirdik.

[2,6,16,22,18,27] -- 16 zaten 3. küçük değer olduğu için yerinde kaldı.

[2,6,16,18,22,27] -- 4. en küçük değerle 4. sıradaki değerin yerini değiştirdik ve böylece listeyi de sıralamış olduk.

2) 
O(n^2)

3) 
Worst Case: aradığımız elemanın sonda olması, son sorguda bulunması [27]

Avarage Case: aradağımız elemanın ortada olması, ortalama sorgu sayısında bulunması [18]

Best Case: aradağımız elemanın başta olması, ilk sorguda bulunması [2]

4) 
18 sayısı Avarage Case kapsamına girer çünkü 18 başta ve sonda değildir, dolayısıyla best veya worst olamayacağı için avarage olmalıdır.

5) 
[7,3,5,8,2,9,4,15,6] 

Soruda istenen aşamalar:

I.[2,3,5,8,7,9,4,15,6]

II.[2,3,4,8,7,9,5,15,6]


III.[2,3,4,5,7,9,8,15,6]

IV.[2,3,4,5,6,9,8,15,7]

Son iki aşama:

V.[2,3,4,5,6,7,8,15,9]

VI.[2,3,4,5,6,7,8,9,15]
