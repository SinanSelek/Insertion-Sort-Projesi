
# Selection Sort Projesi 
## [22,27,16,2,18,6]  -> Selection Sort 

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
	- En düşük sayı olan 2 ile 22 yer değiştirir. [2,27,16,22,18,6]
	- İkinci en düşük sayı 6 ile 27 yer değiştirir. [2,6,16,22,18,27]
	- Dördüncü en düşük sayı 18 ile 22 yer değiştirir. [2,6,16,18,22,27]

2. Big-O gösterimini yazınız.
	* n + (n-1) + (n-2) + ... + 1 = n*(n+1)/2 = (n²+n)/2
	* Sonuca göre Big-o -> O(n²)'dir.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
	* Average case : O(n²)
	* Worst case : O(n²)
	* Best case : O(n²)
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
	* Aranan sayi dizinin ortasinda olduğu için Average Case olur. 

## ## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız
	1. 2 ile 7 yer değiştirir -> [2,3,5,8,7,9,4,15,6]
	2. 3 sabit kalır -> [2,3,5,8,7,9,4,15,6]
	3. 4 ile 5 yer değiştirir -> [2,3,4,8,7,9,5,15,6]
	4. 5 ile 8 yer değiştirir -> [2,3,4,5,7,9,8,15,6]
	
 
