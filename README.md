# Patika.dev_Merge_Sort_Projesi

https://www.patika.dev/tr

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

                       [16,21,11,8,12,22]
                          
        [6,21,11]                                 [8,12,22]                 Dizimizi tek birim kalıncaya kadar ikiye bölerek devam ediyoruz.
    
    [6,21]    [11]                         [8,12]            [22]
    
        [6] [21] [11]                      [8]  [12]  [22]
    
          [6,21] [11]                      [8,12] [22]                      Tek birim kaldıktan sonra gurupları tekrar sıralayarak birleştiriyoruz.
    
              [6,11,21]                 [8,12,22]
    
                      [6,8,11,12,21,22]
                      
                   
 Big-O gösterimi Q(nlogn)
