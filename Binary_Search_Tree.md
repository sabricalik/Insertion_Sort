# Binary Search Tree

## Adım-1
### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

- Dizinin Root Elemanını 7 olarak kabul edersek;
- 5, 7 sayısından kücük olduğu için soluna eklenir.
```
    7
   /
  5
  ```
- 1, 5 sayısından küçük olduğu için soluna eklenir.
```
    7
   /
  5
 / 
1  
```
- 8, 7 sayısından büyük olduğu için sağına eklenir.
```
    7
   / \
  5   8
 / 
1  
```
- 3, 1 sayısından büyük olduğu için sağına eklenir.
```
    7
   / \
  5   8
 / 
1  
 \
  3
```
- 6, 5 sayısından büyük olduğu için sağına eklenir.
```
    7
   / \
  5   8
 / \
1   6
 \
  3
```
- 0, 1 sayısından küçük olduğu için soluna eklenir.
```
      7
     / \
    5   8
   / \
  1   6
 / \
0  3
```
- 9, 8 sayısından büyük olduğu için sağına eklenir.
 ```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0  3
```
- 4, 3 sayısından büyük olduğu için sağına eklenir.
```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0  3
    \
     4
```
- 2, 3 sayısından küçük olduğu için soluna eklenir.
```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0  3
  / \
 2   4
```
