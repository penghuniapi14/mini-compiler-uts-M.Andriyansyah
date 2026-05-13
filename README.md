# Mini Compiler UTS

Program Mini Compiler sederhana menggunakan Python.

## Fitur
- Mendukung operator:
  - Penjumlahan (+)
  - Pengurangan (-)
  - Perkalian (*)
  - Pembagian (/)
  - Pangkat (^)

## Struktur AST
- BinOp
- Num
- Var

## Contoh Input

```python
a ^ 2 + b * c
```

## Contoh Output TAC

```text
t1 = a ^ 2
t2 = b * c
t3 = t1 + t2
```

## Cara Menjalankan

```bash
python mini_compiler.py
```

## Author
Nama: Andri