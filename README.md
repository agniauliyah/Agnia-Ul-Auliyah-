# Agnia Ul Auliyah_Algoritma_Pemograman
Tugas Algortma Pemograman 
## MENENTUKAN LUAS DAN KELILING PERSEGI PANJANG

## A. Deskripsi Masalah

Program ini dibuat untuk menghitung luas dan keliling persegi panjang menggunakan bahasa pemrograman Python.

Pengguna memasukkan nilai panjang dan lebar persegi panjang sebagai input. Selanjutnya, program menghitung luas menggunakan rumus:

L = p × l

dan keliling menggunakan rumus:

K = 2 × (p + l)

Hasil yang ditampilkan berupa nilai luas dan keliling persegi panjang.

# A. Identifikasi Input-Proses-Output

| Komponen | Keterangan |
|---|---|
| **Input** | Panjang dan lebar persegi panjang |
| **Proses** | Menghitung luas dengan rumus `L = p × l` dan keliling dengan rumus `K = 2 × (p + l)` |
| **Output** | Nilai luas dan keliling persegi panjang |

# B. Pseudocode

```text
ALGORITMA Menghitung Luas dan Keliling Persegi Panjang

MULAI

INPUT panjang
INPUT lebar

luas ← panjang × lebar
keliling ← 2 × (panjang + lebar)

OUTPUT luas
OUTPUT keliling

SELESAI


**Tapi ada sedikit perbaikan rumus** supaya tidak salah di flowchart. Yang benar:

```markdown

## D. Flowchart

```mermaid
flowchart TD
    A([MULAI]) --> B[/Input panjang dan lebar/]
    B --> C[Hitung luas = panjang × lebar]
    C --> D[Hitung keliling = 2 × (panjang + lebar)]
    D --> E[/Output luas dan keliling/]
    E --> F([SELESAI])
