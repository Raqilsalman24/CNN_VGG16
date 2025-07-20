# VGG16_Klasifikasi_Tumor_Otak

Proyek ini merupakan implementasi model klasifikasi citra berbasis **CNN VGG16** untuk mendeteksi dan mengklasifikasikan **jenis tumor otak** dari hasil pemindaian MRI. Tiga jenis tumor yang diklasifikasikan adalah:

- **Glioma**
- **Meningioma**
- **Pituitary Tumor**

Model ini bertujuan membantu proses diagnosis awal tumor otak secara otomatis menggunakan citra medis, dengan memanfaatkan kekuatan transfer learning dari arsitektur VGG16 yang telah terbukti efektif untuk pengenalan pola visual.

---

## 🛠️ Libraries yang Digunakan

- `torch` – untuk pembangunan dan pelatihan model deep learning
- `torchvision` – modul pre-trained VGG16 dan transformasi gambar
- `numpy` – manipulasi data numerik
- `matplotlib` – untuk visualisasi hasil dan metrik evaluasi
- `PIL` – untuk pemrosesan gambar MRI
