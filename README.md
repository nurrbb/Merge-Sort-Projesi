# Merge Sort Projesi

 [Patika.dev](https://www.patika.dev/tr) - Veri Yapıları ve Algoritmalar Dersi
 
 Soru 1: [16,21,11,8,12,22] dizisini Merge Sort türüne göre aşamalarını yazınız.
 
 
                          [16,21,11,8,12,22]
                          /                \
                      [16,21,11]         [8,12,22]
                       /    \             /     \ 
                   [16,21]   [11]      [8,12]    [22]
                   /    \      \       /    \      \
                 [16]   [21]   [11]  [8]    [12]   [22]
                   \     /      /     \      /      /
                   [16,21]    [11]     [8,12]     [22]
                      \        /          \       /  
                      [11,16,21]          [8,12,22]
                           \                 /
                           [8,11,12,16,21,22]
                      
                
Soru 2:Big-O gösterimini yazınız. 
>O(6*(log6))
