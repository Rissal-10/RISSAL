# 🌟 Personal Portfolio Website

<div align="center">

![Portfolio Banner](https://img.shields.io/badge/Portfolio-Rissal-00d4ff?style=for-the-badge)
![Version](https://img.shields.io/badge/version-1.0.0-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/status-active-success?style=for-the-badge)

**Modern & Responsive Portfolio Website**

[View Demo](#) · [Report Bug](#) · [Request Feature](#)

</div>

---

## 📋 Daftar Isi

- [Tentang Proyek](#-tentang-proyek)
- [Fitur Utama](#-fitur-utama)
- [Teknologi](#-teknologi)
- [Struktur Proyek](#-struktur-proyek)
- [Instalasi](#-instalasi)
- [Screenshot](#-screenshot)
- [Kontak](#-kontak)
- [Lisensi](#-lisensi)

---

## 🎯 Tentang Proyek

Website portfolio pribadi yang dirancang dengan desain modern dan interaktif untuk menampilkan karya, keahlian, dan pengalaman profesional saya sebagai **Web Developer** dan **UI/UX Designer**. Website ini dibangun dengan fokus pada performa, responsivitas, dan user experience yang optimal.

### ✨ Highlights

- 🎨 Desain modern dengan gradien cyan dan animasi smooth
- 📱 Fully responsive untuk semua perangkat
- ⚡ Fast loading dengan optimasi performa
- 🌈 Interactive UI dengan hover effects
- 🔄 Flip card animation untuk profile image
- 💫 Typewriter effect untuk dynamic professions
- 📧 Contact form terintegrasi

---

## 🚀 Fitur Utama

### 1. **Home Section**
- Hero section dengan animated greeting
- Dynamic profession typewriter effect
- Statistik profesional (Projects, Experience, Clients)
- Call-to-action buttons (Hire Me, Download CV)
- Social media links terintegrasi
- Animated flip card profile image

### 2. **About Section**
- Profil profesional lengkap
- Experience badge dengan tahun pengalaman
- Highlight cards untuk Education, Location, dan Experience
- Tombol download CV

### 3. **Skills Section**
Menampilkan keahlian dalam 4 kategori:
- **Frontend Development**: HTML5, CSS3, JavaScript
- **Backend Development**: Node.js, Python, Express.js
- **UI/UX Design**: Figma, Adobe XD, Responsive Design
- **Mobile Development**: React Native, Android, iOS

Setiap skill dilengkapi dengan progress bar visual.

### 4. **Services Section**
6 layanan profesional yang ditawarkan:
- Web Development
- Mobile Development
- UI/UX Design
- Performance Optimization
- E-commerce Solutions
- API Development

### 5. **Projects Section**
Portfolio karya terbaru termasuk:
- **ABISMA** - Aplikasi manajemen bisnis UMKM (Figma)
- **HydrateMe** - Aplikasi pengingat minum air (Figma)
- **Pelaporan Infrastruktur** - Web Django project
- **Film Lunga, Sradha, Wiguna** - Proyek film sebagai Cameraman & Editor

### 6. **Contact Section**
- Form kontak interaktif dengan validasi
- Informasi kontak lengkap (Email, Phone, Location, WhatsApp)
- Animated contact cards
- Direct links untuk komunikasi

---

## 🛠 Teknologi

### Frontend
```
HTML5          - Struktur website
CSS3           - Styling & animasi
JavaScript     - Interaktivitas & dynamic content
```

### Design & UX
```
Custom CSS Variables    - Consistent theming
Glassmorphism          - Modern UI effects
CSS Grid & Flexbox     - Responsive layouts
CSS Animations         - Smooth transitions
```

### Fonts & Icons
```
Google Fonts (Inter)    - Typography
Font Awesome 6.4.0      - Icon library
```

### External Resources
```
Google Fonts API
Cloudflare CDN (Font Awesome)
```

---

## 📁 Struktur Proyek

```
portfolio-website/
│
├── indek.html              # Halaman utama (Home page)
├── services.html           # Halaman layanan
├── project.html            # Halaman portfolio proyek
├── contact.html            # Halaman kontak
│
├── styele.css              # Stylesheet utama
├── script.js               # JavaScript untuk interaktivitas
│
├── assets/
│   └── Cv_Muhamad_Rizaldhani_Darmawan3.pdf
│
├── img/
│   ├── fotosaya1.png       # Profile image about
│   ├── fotosaya2.png       # Profile image front
│   ├── fotosaya3.png       # Profile image back
│   ├── IG 1.png            # ABISMA project
│   ├── Thumbnail.png       # HydrateMe project
│   ├── project djngo.png   # Django project
│   ├── film1.png           # Film Lunga
│   ├── film2.png           # Film Sradha
│   └── film3.png           # Film Wiguna
│
└── README.md               # Dokumentasi proyek
```

---

## 💻 Instalasi

### Prerequisites
- Web browser modern (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, dll.)
- Git (optional)

### Langkah Instalasi

1. **Clone repository**
```bash
git clone https://github.com/username/portfolio-website.git
```

2. **Masuk ke direktori proyek**
```bash
cd portfolio-website
```

3. **Buka di browser**
- Buka file `indek.html` di browser
- Atau gunakan Live Server di VS Code

### Deployment Options

#### GitHub Pages
```bash
# Push ke branch gh-pages
git checkout -b gh-pages
git push origin gh-pages
```

#### Netlify
- Drag & drop folder ke Netlify
- Atau connect ke GitHub repository

#### Vercel
```bash
vercel --prod
```

---

## 📸 Screenshot

### Desktop View
![Desktop Home](https://via.placeholder.com/800x400/0a0a0a/00d4ff?text=Desktop+Home+View)

### Mobile View
![Mobile View](https://via.placeholder.com/400x800/0a0a0a/00d4ff?text=Mobile+View)

### Projects Section
![Projects](https://via.placeholder.com/800x400/111111/00d4ff?text=Projects+Section)

---

## 🎨 Customization

### Mengubah Warna Tema
Edit variabel CSS di `styele.css`:
```css
:root {
    --accent-primary: #00d4ff;      /* Warna utama */
    --accent-secondary: #0099cc;    /* Warna sekunder */
    --bg-primary: #0a0a0a;          /* Background utama */
}
```

### Mengubah Konten
Edit teks dan informasi di file HTML sesuai kebutuhan:
- `indek.html` - Informasi personal, stats, skills
- `services.html` - Layanan yang ditawarkan
- `project.html` - Portfolio proyek
- `contact.html` - Informasi kontak

### Menambah Proyek Baru
Tambahkan project card di `project.html`:
```html
<div class="project-card">
    <div class="project-image">
        <img src="./img/your-image.png" alt="Project Name">
        <!-- ... -->
    </div>
    <div class="project-info">
        <h3>Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span>Tech 1</span>
            <span>Tech 2</span>
        </div>
    </div>
</div>
```

---

## 🌐 Browser Support

| Browser | Version |
|---------|---------|
| Chrome | ✅ Latest |
| Firefox | ✅ Latest |
| Safari | ✅ Latest |
| Edge | ✅ Latest |
| Opera | ✅ Latest |

---

## 📱 Responsive Breakpoints

```css
/* Mobile devices */
@media (max-width: 480px) { }

/* Tablets */
@media (max-width: 768px) { }

/* Laptops */
@media (max-width: 1200px) { }

/* Desktop */
@media (min-width: 1201px) { }
```

---

## ✨ Fitur JavaScript

### Typewriter Effect
Animasi text yang berganti-ganti untuk profesi

### Smooth Scrolling
Navigasi halus antar section

### Mobile Menu Toggle
Menu hamburger responsif untuk mobile

### Form Validation
Validasi input pada contact form

### Scroll Animations
Element animation saat di-scroll

### Performance Monitoring
Tracking loading time dan performa

---

## 📊 Performance

- ⚡ **Page Load Time**: < 2 detik
- 📦 **Total Size**: ~500KB (tanpa gambar)
- 🎯 **Lighthouse Score**: 90+
- ♿ **Accessibility**: WCAG 2.1 AA compliant

---

## 🔜 Roadmap

- [ ] Tambah mode dark/light toggle
- [ ] Integrasi blog section
- [ ] Animasi page transition
- [ ] Progressive Web App (PWA)
- [ ] Multi-language support (EN/ID)
- [ ] Backend integration untuk contact form
- [ ] Admin panel untuk update content

---

## 🤝 Contributing

Kontribusi selalu diterima! Jika Anda ingin berkontribusi:

1. Fork repository
2. Buat branch baru (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buat Pull Request

---

## 📞 Kontak

**Muhamad Rizaldhani Darmawan (Rissal)**

- 📧 Email: muhrizaldhanidarmawan@gmail.com
- 📱 Phone: +62 895-3672-5492
- 💼 LinkedIn: [Rizal Dhani](https://www.linkedin.com/in/rizal-dhani-195765365)
- 🐙 GitHub: [@Rissal-10](https://github.com/Rissal-10)
- 📸 Instagram: [@vxrizalzzz](https://www.instagram.com/vxrizalzzz/)
- 💬 WhatsApp: [Chat Now](https://wa.me/62895367254929)

📍 **Location**: Surabaya, Jawa Timur, Indonesia

---

## 📄 Lisensi

Distributed under the MIT License. See `LICENSE` for more information.

---

## 🙏 Acknowledgments

- [Font Awesome](https://fontawesome.com) - Icons
- [Google Fonts](https://fonts.google.com) - Typography
- [Figma](https://figma.com) - Design inspiration
- [Unsplash](https://unsplash.com) - Image resources

---

<div align="center">

### ⭐ Don't forget to star this repo if you like it!

**Made with ❤️ by Rissal**

![Thanks](https://img.shields.io/badge/Thanks%20for-Visiting-00d4ff?style=for-the-badge)

</div>
