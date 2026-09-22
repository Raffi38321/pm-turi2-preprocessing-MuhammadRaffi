# Praktikum 2 - Preprocessing
Mata Kuliah: Pembelajaran Mesin (INF62325)
Nama : Muhammad Raffi
NIM : 2488010046
## Ringkasan
Praktikum preprocessing data:
data splitting,label encoding dan one hot encoding
## Isi Repositori
- PM_P4_EDA_MuhammadRaffi_2488010046.ipynb : notebook praktikum
## Temuan Utama
preproscessing = perbaikan ke data(misal data hilang dihapus atau lainnya)/pembersihan dan menstandarkan data.
fitur enginering = membuat/ menciptakan fitur baru(pake intuisi) dan memilih fitur informatif / yang akan digunakan di pemodelan. nambah kalo sebuah fitur penting diciptakan dikurangi kalo sebuah fitur tidak berkorelasi dengan label
encoding = pengubahan nilai menjadi sebuah angka 
penskalaan = cara menyederhanakan sebuah data
split = pembagian data antara training dan testing, kita juga akan memilih mana penjelas dan label
strategi penanganan nan: menghapus baris/ kolom yang bermasalah. imputasi pengisian nilai hilang dengan nilai sebuah nilai estimasi(median(tahan outlier),modus(kalo fiturnya kelas),mean)
cara menangani data tidak seimbang: oversampling(perbanyak kelas minoritas(smote)), undersampling(kurangi data mayoritas), classweight(beri bobot lebih ke minoritas).

