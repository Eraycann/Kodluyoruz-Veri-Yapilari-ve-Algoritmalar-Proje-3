# MERGE Sort

### Proje 3

> Q: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

**Binary Search Tree Oluşturma Adımları**

1. Kök düğüm seçimi:
   - İlk eleman kök düğüm olarak seçilir: 7

2. Diğer elemanları ekleme:
   - Her bir elemanı kökle karşılaştırarak, küçükse sol alt ağaca, büyükse sağ alt ağaca yerleştiririz.

**Adım Adım Ekleme Süreci**

1. 7 Kök Düğüm

    ```
    7
    ```

2. 5'i ekle

    ```
       7
      /
     5
    ```

3. 1'i ekle

    ```
       7
      / \
     5   1
    ```

4. 8'i ekle

    ```
       7
      / \
     5   8
      \
       1
    ```

5. 3'ü ekle

    ```
       7
      / \
     5   8
    / \
   1   3
    ```

6. 6'yı ekle

    ```
       7
      / \
     5   8
    / \
   1   6
      /
     3
    ```

7. 0'ı ekle

    ```
         7
        / \
       5   8
      / \
     1   6
    / \
   0  3
 
    ```

8. 9'u ekle

    ```
          7
         / \
        5   8
       / \   \
      1   6   9
     / \
    0   3
    ```

9. 4'ü ekle

    ```
          7
         / \
        5   8
       / \   \
      1   6   9
     / \   
    0   3   
         \
          4
    ```

10. 2'yi ekle

    ```
           7
          / \
         5   8
        / \   \
       1   6   9
      / \   \
     0   3   
        / \
       2   4
    ```

> Sonuç Olarak Oluşan Binary Search Tree

```
           7
          / \
         5   8
        / \   \
       1   6   9
      / \   \
     0   3   
        / \
       2   4
```

# Açıklama

- Kök düğüm 7 olarak seçildi.
    - Her ekleme işleminde, eklenecek eleman mevcut düğümle karşılaştırılarak daha küçükse sol alt ağaca, daha büyükse sağ alt ağaca yerleştirildi.
    - Bu işlem her düğüm için tekrar edilerek BST oluşturuldu.
    - Bu adımlarla verilen diziden oluşturulan Binary Search Tree (BST) yukarıdaki gibi olacaktır.

    ### Hakkımda

    - 💻 Yazılım Geliştirici
    - 🌱 Şu anda yeni teknolojiler öğreniyorum
    - 🤝 Açık kaynak projelere katkıda bulunmayı seviyorum

    ## İletişim

    - [LinkedIn](https://www.linkedin.com/in/eraycan-sivri-827997226/)
    - [E-posta](mailto:eraycansivri@hotmail.com)