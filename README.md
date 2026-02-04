# Portfolio Website - Bima Pratama

Portfolio website profesional untuk Mobile Developer (Flutter & Android). Website ini dirancang dengan desain modern, responsive, dan siap di-deploy ke GitHub Pages.

## 🚀 Fitur

- ✨ Desain modern dan profesional
- 📱 Fully responsive (mobile, tablet, desktop)
- 🎨 Animasi smooth dan interaktif
- 📧 Contact form terintegrasi
- 🌐 SEO friendly
- ⚡ Fast loading
- 🎯 Sections lengkap: About, Skills, Experience, Education, Contact

## 📋 Struktur File

```
portfolio-website/
│
├── index.html          # Halaman utama portfolio
├── style.css           # Stylesheet untuk desain
├── script.js           # JavaScript untuk interaktivitas
└── README.md           # Dokumentasi
```

## 🛠️ Teknologi yang Digunakan

- HTML5
- CSS3 (dengan CSS Variables & Flexbox/Grid)
- JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts

## 📦 Cara Deploy ke GitHub Pages

### Langkah 1: Buat Repository GitHub

1. Buka [GitHub](https://github.com) dan login
2. Klik tombol **"New"** atau **"+"** untuk membuat repository baru
3. Beri nama repository: `username.github.io` (ganti `username` dengan username GitHub Anda)
   - Contoh: `mbimbim.github.io`
4. Pilih **Public**
5. Klik **"Create repository"**

### Langkah 2: Upload File ke Repository

#### Metode 1: Upload via Web (Mudah)

1. Di halaman repository, klik **"uploading an existing file"**
2. Drag & drop semua file (`index.html`, `style.css`, `script.js`) ke browser
3. Scroll ke bawah, tambahkan commit message: "Initial commit"
4. Klik **"Commit changes"**

#### Metode 2: Via Git Command Line (Rekomendasi)

```bash
# 1. Buka terminal/command prompt di folder portfolio-website

# 2. Initialize git repository
git init

# 3. Add semua file
git add .

# 4. Commit
git commit -m "Initial commit: Portfolio website"

# 5. Connect ke GitHub repository
git remote add origin https://github.com/mbimbim/mbimbim.github.io.git

# 6. Push ke GitHub
git branch -M main
git push -u origin main
```

### Langkah 3: Aktifkan GitHub Pages

1. Di repository GitHub, klik tab **"Settings"**
2. Scroll ke bagian **"Pages"** di sidebar kiri
3. Pada bagian **"Source"**, pilih:
   - Branch: `main`
   - Folder: `/ (root)`
4. Klik **"Save"**
5. Tunggu beberapa menit, website Anda akan live di: `https://username.github.io`

## 🎨 Kustomisasi

### Mengubah Warna

Edit file `style.css` pada bagian CSS Variables:

```css
:root {
    --primary-color: #3498db;      /* Warna utama */
    --secondary-color: #2ecc71;    /* Warna sekunder */
    --accent-color: #e74c3c;       /* Warna aksen */
}
```

### Mengubah Konten

Edit file `index.html`:

- **Nama & Informasi**: Bagian `<section id="home">`
- **About**: Bagian `<section id="about">`
- **Skills**: Bagian `<section id="skills">`
- **Experience**: Bagian `<section id="experience">`
- **Education**: Bagian `<section id="education">`
- **Contact**: Bagian `<section id="contact">`

### Menambah Foto Profile

1. Tambahkan foto ke folder project (misal: `profile.jpg`)
2. Di `index.html`, ganti bagian profile icon:

```html
<!-- Ganti dari: -->
<div class="profile-icon">
    <i class="fas fa-user-circle"></i>
</div>

<!-- Menjadi: -->
<img src="profile.jpg" alt="Bima Pratama" style="width: 100%; height: 100%; object-fit: cover; border-radius: 30px;">
```

## 📧 Update Informasi Kontak

Edit bagian kontak di `index.html` dan `script.js`:

- Email: `pratamabima37@gmail.com`
- Phone: `081260991438`
- GitHub: `https://github.com/mbimbim`
- LinkedIn: `https://www.linkedin.com/in/bima-pratama-3419b7251`

## 🔧 Tips & Troubleshooting

### Website Tidak Muncul Setelah Deploy

1. Tunggu 5-10 menit setelah push
2. Pastikan nama repository benar: `username.github.io`
3. Clear browser cache (Ctrl + F5)
4. Cek status deploy di repository Settings > Pages

### Custom Domain (Opsional)

Jika ingin menggunakan domain sendiri (misal: `www.bimapratama.com`):

1. Beli domain dari provider (Namecheap, GoDaddy, dll)
2. Di GitHub Pages settings, masukkan custom domain
3. Update DNS records di domain provider:
   ```
   Type: CNAME
   Name: www
   Value: username.github.io
   ```

## 📱 Testing Responsive

Test website di berbagai device:

- Desktop: Chrome, Firefox, Safari
- Mobile: iPhone, Android
- Gunakan Chrome DevTools (F12) untuk simulasi device

## 🎯 Next Steps

Setelah website live, Anda bisa:

1. ✅ Tambahkan Google Analytics untuk tracking visitor
2. ✅ Tambahkan blog section untuk artikel
3. ✅ Integrasi dengan GitHub API untuk menampilkan projects
4. ✅ Tambahkan dark mode toggle
5. ✅ Buat sitemap.xml untuk SEO

## 📄 License

Free to use untuk portfolio personal Anda.

## 👤 Contact

Jika ada pertanyaan atau butuh bantuan:

- Email: pratamabima37@gmail.com
- GitHub: [@mbimbim](https://github.com/mbimbim)
- LinkedIn: [Bima Pratama](https://www.linkedin.com/in/bima-pratama-3419b7251)

---

**Dibuat dengan ❤️ untuk Mobile Developer**
