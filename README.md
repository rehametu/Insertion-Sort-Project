# Insertion-Sort-Project
Patika.dev Bootcamp Insertion Sort Project
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

____Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

1. Adım --> Listedeki en küçük sayımız olan 2, 22 sayısıs iler yer değiştirir. --> [2,27,16,22,18,6]
2. Adım --> Listede en küçük sayı bulunduğu için ikinci sıraya atlanır ve 6 sayısı, 27 sayısı ıle yer değştirir. --> [2,6,16,22,18,27]
3. Adım --> Üçüncü sıra için yapılan kontrolde 16 sayısı hali hazırda bulunması gereken sırada olduğu için değişiklik olmaz.
4. Adım --> Dördüncü sıra için kontrolde 18 sayısı ile 22 sayısı yer değiştirir. --> [2,6,16,18,22,27]
5. Adım --> Değişikliğe gerek yok.

____Big-O gösterimini yazınız.

==> Insertion sort sıralamasının ilk adımında listedeki tüm değerler kontrol edildiği için n adet işlem yapılır. Bir sonraki adımda ilk sıra harici kontrol edilir ve işlem sayısı bu sefer n-1 olur. Bu dizi devam ettirildiğinde n adetten geri sayılarak 1 e kadar devam edilir. Toplam işlem sayısı n'den 1 e kadar satıların toplamı yani (n)(n-1)/2 dir. Big-O gösterimi n^2 baskınlığından kaynaklı olarak O(n^2) 'dir.



___Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

*Average Case: 16,18
*Worst Case: 27
*Best Case: 2

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

==> 18 sayısı ortada bulunduğu için average case kapsamındadır.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1. Adım --> [2,3,5,8,7,9,4,15,6]
2. Adım --> [2,3,5,8,7,9,4,15,6]
3. Adım --> [2,3,4,8,7,9,5,15,6]
4. Adım --> [2,3,4,5,7,9,8,15,6]




