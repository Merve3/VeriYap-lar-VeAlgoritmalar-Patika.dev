# VeriYapilariVeAlgoritmalari-Patika.dev
<summary>Merge Sort Projesi</summary>
   [16,21,11,8,12,22] 
<ol> <li>Yukarı dizinin sort türüne göre aşamalarını yazınız. </li>
 
                    [16,21,11,8,12,22] 
                  [16,21,11]   [8,12,22] 
              [16] - [21,11]   [8] - [12,22] 
        ------------------------------------------ 
          [16] - [21] - [11]     [8] - [12] - [22] 
       ------------------------------------------ 
              [16] - [11,21]   [8] - [12,22] 
                  [11,16,21]   [8,12,22] 
                    [8,11,12,16,21,21]
 
 <li>Big-O gösterimini yazınız. </li></ol>
 
  n = 2^x
  
  logn = x

  O(nlogn)     
    
