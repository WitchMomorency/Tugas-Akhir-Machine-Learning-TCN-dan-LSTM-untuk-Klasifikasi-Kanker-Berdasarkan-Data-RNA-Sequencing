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
### Perihal Kode Variant
- **D1 dan D2**  
  Merupakan kode bagian pencarian parameter search nya  

- **V1 dan V2**  
  Merupakan running berdasarkan hasil pencarian dan seleksi dari D1 dan D2 nya  

- **V1 SMOTE dan V2 SMOTE**  
  Versi run dengan penetapan dengan semuanya menggunakan augmentasi smote di data latihnya  
