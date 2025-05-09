## 🔍 Marker-based AR Testing with MindAR + A-Frame + Bootstrap

Proyek ini adalah contoh sederhana **Augmented Reality (AR)** menggunakan **MindAR.js**, **A-Frame**, dan **Bootstrap** untuk keperluan **testing awal** tanpa model 3D (seperti origami). Ketika marker dikenali, sebuah gambar akan ditampilkan di AR.

---

### ✅ Fitur

* Deteksi marker berbasis gambar (`.mind`)
* Menampilkan gambar 2D (plane)
* Tombol untuk tampil/sembunyikan gambar
* Siap dikembangkan lebih lanjut (misal: menambahkan model 3D `.glb`/`.gltf`)

---

### 🧱 Teknologi

* [MindAR.js](https://hiukim.github.io/mind-ar-js-doc/quick-start/overview)
* [A-Frame](https://aframe.io/)
* [Bootstrap 5](https://getbootstrap.com/)
* HTML5, JavaScript

---

### 📁 Struktur Folder

```
project-folder/
├── index.html
└── assets/
    ├── nocturnailed.png       # Gambar marker
    └── nocturnailed.mind      # File marker hasil kompilasi
```

---

### 🚀 Cara Menggunakan

1. **Buka `index.html`** di browser modern yang mendukung WebXR (Chrome, Edge, Firefox terbaru).
2. Izinkan akses kamera jika diminta.
3. Arahkan kamera ke gambar marker (`nocturnailed.png`).
4. Gambar akan muncul secara otomatis.
5. Gunakan tombol UI:

   * **Tampilkan** → Menampilkan objek AR
   * **Sembunyikan** → Menyembunyikan objek AR

---

### 🛠️ Cara Membuat File `.mind`

1. Buka: [MindAR Compile Tool](https://hiukim.github.io/mind-ar-js-doc/tools/compile/)
2. Upload gambar `.png`/`.jpg` sebagai marker
3. Klik `Compile`
4. Simpan file `.mind` dan file gambar ke dalam folder `/assets/`

---

### 🌐 Catatan

* Direkomendasikan untuk menjalankan via server (localhost, GitHub Pages, atau Vercel) karena akses kamera bisa dibatasi di `file://` protocol.
* Tes langsung di **mobile browser** untuk pengalaman terbaik.

---

### 🧠 Credits

Dibuat oleh Muhammad Ikhwan Fathulloh
Berbasis proyek [MindAR.js Quick Start](https://hiukim.github.io/mind-ar-js-doc/quick-start/overview)