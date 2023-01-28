# Insertion Sort
Bu README.md dosyası [Patika.dev-Binary_Search](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/binary-search-tree-proje) alıştırmaları kapsamında hazırlanmıştır.

### Alıştırma Sorusu :

    [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] 
    dizisinin Binary-Search-Tree aşamalarını yazınız.

    Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

### Cevap :

Binary Search Tree (BST) oluşturmak için verilen dizi için aşağıdaki adımlar takip edilir:

    1. 7, dizinin ilk elemanı olarak, root olarak seçilir.
    2. 5, root'un soluna eklenir.
    3. 1, 5'in soluna eklenir.
    4. 8, root'un sağına eklenir.
    5. 3, 1'in sağına eklenir.
    6. 6, 8'in soluna eklenir.
    7. 0, 1'in soluna eklenir.
    8. 9, 8'in sağına eklenir.
    9. 4, 3'ün sağına eklenir.
    10. 2, 3'ün soluna eklenir.
    Sonuç:
              7
            /   \ 
           5     8
          /     / \
         1     6   9
        / \
       0   3
          / \
         2   4
  

Insertion sort'un Big-O değeri, O(n^2) 'dir. Çünkü her döngüde, karşılaştırma ve yer değiştirme işlemleri n defa yapılır.
