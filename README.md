# Project 1
# Project 1.1
[22,27,16,2,18,6] -> Insertion Sort Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

```
İlk elemanla sağındaki eleman karşılaştırılır. Daha küçük olan sola alınır.
[22,27,16,2,18,6] 22 ve 27 doğru sırada. Bu şekilde bırakılır.
[16,22,27,2,18,6] 27 ve 16 karşılaştırılır. 16 daha küçük olduğu için yer değiştirirler. 16, 22'den de küçük olduğu için onunla da yer değiştirir.
[2,16,22,27,18,6] 2, 27'den, 22'den ve 16'dan küçük olduğu için en başa gelir. Geri kalan elemanlar da aynı mantıkla sıralanır.
[2,6,16,18,22,27] 
```
Big-O gösterimini yazınız.
```
n ile başlar, n-1,n-2,n-3 ve 1 ile son bulur. 
Bu sayıların toplamı (n*(n+1))/2 olduğundan O(n²) ile ifade edilir.
```

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
```
18 sayısı sıralamada ortada yer aldığından Average case kapsamına girer.
```
Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
## Project 1.2
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
```
Step 1: [2,3,5,8,7,9,4,15,6] 
Step 2: [2,3,4,8,7,9,5,15,6] 3 sayısı 2. küçük değer olduğu için dokunmuyoruz.
Step 3: [2,3,4,5,7,9,8,15,6] 
Step 4: [2,3,4,5,6,9,8,15,7]
```

