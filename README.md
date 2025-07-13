# 🏁 Tugas Akhir (TA) - Final Project

**Nama Mahasiswa**: Richard Ryan  
**NRP**: 5025211141  
**Judul TA**: Pengaruh Reorientasi Anterior Commisure – Posterior Commisure dan Tuning Hyperparameter untuk Kasus Segmentasi 3D Aneurisma di Otak  
**Dosen Pembimbing**: Prof. Drs. Ec. Ir. Riyanarto Sarno, M.Sc., Ph.D.  
**Dosen Ko-pembimbing**: Dr. Kelly Rossa Sungkono, S.Kom., M.Kom.


---

## 📺 Demo Aplikasi  

[![Demo Aplikasi](img/pic_vid.jpg)](https://youtu.be/ZpgLPlfG3Do)  
*Klik gambar di atas untuk menonton demo*

## 🛠 Panduan Instalasi & Menjalankan Software  

### Prasyarat  
- Python 3.9.13

### Langkah-langkah  
1. **Clone Repository**  
   ```bash
   git clone https://github.com/Informatics-ITS/ta-RichardRyan141.git
   ```
2. **Instalasi Dependensi**
   ```bash
   cd [folder-proyek]
   pip install -r requirements.txt
   ```
3. **Download dataset**
- Registrasi dan download data dari ADAM Challenge (https://www.adam.isi.uu.nl)  
### Format data awal:
resized_data/  
|-- 10001/  
|&nbsp;&nbsp;&nbsp;&nbsp;|-- orig/  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- reg_struct_to_TOF.txt  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- ScanParams_struct.json  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- ScanParams_TOF.json  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- struct.nii.gz  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- struct_aligned.nii.gz  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- TOF.nii.gz  
|&nbsp;&nbsp;&nbsp;&nbsp;|-- pre/  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- struct.nii.gz  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- struct_aligned.nii.gz  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- TOF.nii.gz  
|&nbsp;&nbsp;&nbsp;&nbsp;|-- aneurysms.nii.gz  
|&nbsp;&nbsp;&nbsp;&nbsp;|-- location.txt  
|-- 10002/  
|&nbsp;&nbsp;&nbsp;&nbsp;|-- orig/  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- reg_struct_to_TOF.txt  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- ScanParams_struct.json  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- ScanParams_TOF.json  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- struct.nii.gz  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- struct_aligned.nii.gz  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- TOF.nii.gz  
|&nbsp;&nbsp;&nbsp;&nbsp;|-- pre/  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- struct.nii.gz  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- struct_aligned.nii.gz  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- TOF.nii.gz  
|&nbsp;&nbsp;&nbsp;&nbsp;|-- aneurysms.nii.gz  
|&nbsp;&nbsp;&nbsp;&nbsp;|-- location.txt  
|-- 10003/
...  
4. **Jalankan Kode**
- Buka resizer.ipynb, ubah variabel yang ditunjukkan (jika perlu) dan jalankan code
- Download acpcdetect dari NITRC (https://www.nitrc.org/projects/art) kemudian jalankan untuk setiap directory kasus data (Note: Diperlukan WSL)
- Buka reorient.ipynb, ubah variabel yang ditunjukkan (jika perlu) dan jalankan code
- Buka generate-csv.ipynb, ubah variabel yang ditunjukkan (jika perlu) dan jalankan code
- Buka train.ipynb, ubah variabel yang ditunjukkan (jika perlu) dan jalankan code
- Buka validate.ipynb, ubah variabel yang ditunjukkan (jika perlu) dan jalankan code

---

## ⁉️ Pertanyaan?

Hubungi:
- Penulis: richard.ryan.rr0@gmail.com
- Pembimbing Utama: riyanarto@if.its.ac.id
