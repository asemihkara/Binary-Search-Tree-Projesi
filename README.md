# Binary-Search-Tree-Projesi
Patika.dev projesi; https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/binary-search-tree-proje

Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree asamalarini yaziniz.

root 5 olsun. 

1. step		5

2. step: 7, 5'in saginda bulunur.

            5
             \
              7

3. step: 1, 5'in solunda bulunur.

            5
           / \
          1   7

4. step: 8, 5'in ve 7'nin saginda bulunur.

             5
            / \
           1   7
                \
                 8

5. step: 3, 5'in solunda, 1'in saginda bulunur.

             5
            / \
           1   7
            \   \
             3   8

6. step: 6, 5'in saginda, 7'nin solunda bulunur.

               5
              / \
             /   \
            /     \
           1       7
            \     / \
             3   6   8

7. step: 0, 5'in ve 1'in solunda bulunur.

               5
              / \
             /   \
            /     \
           1       7
          / \     / \
         0   3   6   8

 8. step: 9; 5, 7 ve 8'in saginda bulunur.

               5
              / \
             /   \
            /     \
           1       7
          / \     / \
         0   3   6   8
                      \
                       9

9. step: 4, 5'in solunda, 1'in ve 3'un saginda bulunur.

               5
              / \
             /   \
            /     \
           1       7
          / \     / \
         0   3   6   8
              \       \
               4       9

10. step: 2; 5'in solunda, 1'in saginda, 3'un solunda bulunur.

                5
               / \
              /   \ 
             /     \
            1       7
           / \     / \
          0   3   6   8
             / \       \
            2   4       9