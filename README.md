### Dataset
Dataset: [TCGA RNA Datasets](https://www.kaggle.com/datasets/tianjiechen/tcga-rna-datasets)

> Notebook tidak menyertakan dataset maupun folder output. Untuk menjalankan ulang, dataset harus diunduh dari Kaggle dan folder output dibuat manual.
### Struktur Folder
```
project-root/
├── data/          # dataset TCGA RNA
├── output/        # hasil eksekusi
└── notebook.ipynb # Notebook utama
```
### Perihal Kode variant
D1 dan D2 merupakan kode bagian pencarian parameter search nya
Sedangkan V1 dan V2 merupakan running berdasarkan hasil pencarian dan seleksi dari D1 dan D2 nya
Sedangan V1 SMOTE dan V2 SMOTE versi run dengan penetapan dengan semuanya menggunakan augmentasi smote di data latihnya
