# Binary-Search-Tree
Verilen dizi: \([7, 5, 1, 8, 3, 6, 0, 9, 4, 2]\)

Bu diziyi bir Binary Search Tree (BST) oluşturmak için sırayla elemanları ekleyerek adımları yazalım:

1. **Root oluşturma:**
   - İlk eleman root olur.
   - Root: 7

2. **5 ekleme:**
   - 5, 7'den küçüktür, bu yüzden sol tarafa eklenir.
   - Sol: 5

3. **1 ekleme:**
   - 1, 7'den küçüktür, sola git.
   - 1, 5'ten küçüktür, sola git.
   - Sol: 1 (5'in soluna)

4. **8 ekleme:**
   - 8, 7'den büyüktür, bu yüzden sağ tarafa eklenir.
   - Sağ: 8

5. **3 ekleme:**
   - 3, 7'den küçüktür, sola git.
   - 3, 5'ten küçüktür, sola git.
   - 3, 1'den büyüktür, sağ tarafa eklenir.
   - Sağ: 3 (1'in sağına)

6. **6 ekleme:**
   - 6, 7'den küçüktür, sola git.
   - 6, 5'ten büyüktür, sağ tarafa eklenir.
   - Sağ: 6 (5'in sağına)

7. **0 ekleme:**
   - 0, 7'den küçüktür, sola git.
   - 0, 5'ten küçüktür, sola git.
   - 0, 1'den küçüktür, sola git.
   - Sol: 0 (1'in soluna)

8. **9 ekleme:**
   - 9, 7'den büyüktür, sağa git.
   - 9, 8'den büyüktür, sağa git.
   - Sağ: 9 (8'in sağına)

9. **4 ekleme:**
   - 4, 7'den küçüktür, sola git.
   - 4, 5'ten küçüktür, sola git.
   - 4, 1'den büyüktür, sağa git.
   - 4, 3'ten büyüktür, sağa git.
   - Sağ: 4 (3'ün sağına)

10. **2 ekleme:**
    - 2, 7'den küçüktür, sola git.
    - 2, 5'ten küçüktür, sola git.
    - 2, 1'den büyüktür, sağa git.
    - 2, 3'ten küçüktür, sola git.
    - Sol: 2 (3'ün soluna)

Sonuç olarak, BST yapısı şu şekilde oluşur:

```
       7
      / \
     5   8
    / \   \
   1   6   9
  / \
 0   3
    / \
   2   4
```

### Aşamalar:
- **Root:** 7'dir.
- **5:** 7'nin solunda bulunur.
- **1:** 5'in solunda bulunur.
- **8:** 7'nin sağında bulunur.
- **3:** 1'in sağında bulunur.
- **6:** 5'in sağında bulunur.
- **0:** 1'in solunda bulunur.
- **9:** 8'in sağında bulunur.
- **4:** 3'ün sağında bulunur.
- **2:** 3'ün solunda bulunur.
