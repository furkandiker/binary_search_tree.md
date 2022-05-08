# binary_search_tree.md
Patika.dev egitimlerinden Veri Yapilari ve Algoritma egitiminin son projesi

Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb. 

Cozum

    root= 7
```
5, 7'den kucuktur soluna yazilir                                     7
                                                                   5
```																							 
```		
1, 7'den ve 5'ten kucuktur soluna yazilir                           7
                                                                  5					
                                                                1
```		
```    
8, 7'den buyuktur sagina yazilir                                     7
                                                                5         8	
                                                             1						 		
```		
```       
3, 7'den ve 5'ten kucuktur 1'den buyuk                           7
1'in sagina yazilir                                         5        8
                                                       1		
                                                          3	
```
```
6, 7'den kucuktur 5'ten buyuktur 5'in sagina yazilir             7
                                                          5          8
                                                       1      6		
                                                          3
```		
```		
0, 7 5 ve 1'den kucuktur en sola yazilir                         7
                                                          5          8
                                                       1      6		
                                                    0     3                            
```																														
```																														
9, 7 ve 8'den buyuktur en saga yazilir                         7
                                                          5          8
                                                       1      6		      9
                                                    0     3
```
```
4, 7'den ve 5'ten kucuk 1 ve 3'ten buyuktur 3'un sagina yazilir                        7
                                                                                  5          8
                                                                               1     6          9
                                                                             0    3
                                                                                    4
```
```
2, 7 ve 5'ten kucuk 1'den buyuk ve 3'ten kucuk oldugu icin                              7
                                                                                  5          8
                                                                               1     6          9
                                                                             0    3
                                                                               2    4
```                                                                            
