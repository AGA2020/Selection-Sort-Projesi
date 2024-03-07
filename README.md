# SORU

[22,27,16,2,18,6] -> Insertion Sort

a) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

b) Big-O gösterimini yazınız.

c) Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

d) [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

------------

# CEVAP

a;

1. [22,27,16,2,18,6]  Başlangıç n
2. [2,27,16,22,18,6]  2 ile 6 yer değiştirdi. n-1
3. [2,6,16,22,18,27]  6 ile 27 yer değiştirdi. n-2
4. [2,6,16,22,18,27]  16 üçüncü en küçük doğru konumda. n-3
5. [2,6,16,18,22,27]  18 ile 22 yer değiştirdi. n-4
6. [2,6,16,18,22,27]  22 beşinci en küçük doğru konumda. 1

b;

Big-O: 1+(n-4)+(n-3)+...+(n)=((n+1).n)/2=(n^2+n)/2=O(n^2)

c;

[2,6,16,18,22,27]  Dizi sıralı haldeyken 18 sayısı ortada bulunmaktadır. Yani average case.

d;

[7,3,5,8,2,9,4,15,6]  Başlangıç n
[2,3,5,8,7,9,4,15,6]  2 ve 7 yer değiştirdi.
[2,3,5,8,7,9,4,15,6]  3 sabit.
[2,3,4,8,7,9,5,15,6]  5 ve 4 yer değiştirdi.
[2,3,4,5,7,9,8,15,6]  8 ve 5 yer değiştirdi.

--------------------------------------------------------------

