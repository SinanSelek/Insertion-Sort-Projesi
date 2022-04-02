# Merge Sort Projesi 
## [16,21,11,8,12,22] -> Merge Sort 
### [Patika.dev Kurs Linki](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/merge-sort-proje)

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

                                [16,21,11,8,12,22]

                        [16,21,11]     ----     [8,12,22]  

                    [16,21]  -   [11]  ----   [8,12]  - [22]  

                  [16] - [21]   - [11] ----  [8]-  [12]- [22] 

                    [16,21]   -  [11]  ----   [8,12]  - [22] 

                         [11,16,21]    ----    [8,12,22] 

                                [8,11,12,16,21,22]

2. Big-O gösterimini yazınız.
	- $2^{x}$ = n
	- x = $log{n}$ buradan big-o -> o(logn) gelir. 
	- İşlem aşamalarından big-o o(n) gelir. 
	- Sonuç olarak big-o o(nlogn) olur.
