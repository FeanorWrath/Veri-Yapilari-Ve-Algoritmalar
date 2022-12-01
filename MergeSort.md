# PROJE 2

>[16,21,11,8,12,22]--> Merge Sort
- Yukarıdaki dizinin sort türüne göre aşamlarını yazınız.
- Big-O gösterimini yazınız.
    
       
 >                                          [16,21,11,8,12,22]    
 >                                          /                \  
 >                                         /                  \
 >                                    [16,21,11]            [8,12,22]
 >                                       /                      \
 >                                      /                        \
 >                                 [16,21] [11]               [8,12] [22]
 >                                    /                            \
 >                                   /                              \
 >                              [16] [21] [11]                      [8] [12] [22]
 >                                  \                                 /
 >                                   \                               /
 >                                [16,21] [11]                    [8,12] [22]
 >                                     \                           /
 >                                      \                         /
 >                                  [11,16,21]                [8,12,22]
 >                                        \                    /
 >                                         \                  /
 >                                          [8,11,12,16,21,22]


Big-O gösterimi Her aşamada diziyi yarısına bölerek işlem yapıyoruz.   
2^n=x     O(nlogn)

