# Landing Page Klinik AR-Ridlo

Sebuah landing page modern untuk Klinik AR-Ridlo yang dikembangkan sebagai tugas mata kuliah Essential Web Development & UI/UX.

## 👥 Tim Pengembang - Kelompok 4

| Nama | NIM | Bagian |
|------|-----|--------|
| Faathir Akbar Nugroho | 4522210033 | Hero Section |
| Jati Rahmatulloh | 4522210039 | Stats & About Section |
| Dzaki Yushiibanaa | 4522210041 | Stats & About Section |
| Daniel Daud Alberthus | 4522210055 | Footer Section |
| Bahrudin Yusuf | 4522210076 | Team Section |

## 🎯 Fitur Utama

- **Header & Navigation**: Logo klinik, menu navigasi dengan dropdown service, dan tombol CTA
- **Hero Section**: Judul klinik, deskripsi, call-to-action buttons, dan placeholder gambar
- **Statistics Section**: Menampilkan statistik real-time (3 Terapis, 32 Antrean, 32 Dokter)
- **About Section**: Deskripsi lengkap klinik dengan latar belakang mint dan placeholder media
- **Team Section**: Daftar dokter spesialis dan terapis dengan jadwal dan status ketersediaan
- **Footer**: Informasi produk, company, support, downloads, newsletter, dan social media links

## 📁 Struktur Proyek

```
landing-page-klinik-ar-ridlo/
├── index.html
├── style/
│   └── style.css
└── README.md
```

## 🚀 Cara Menjalankan

1. Clone atau download repository ini
2. Buka file `index.html` di browser
3. Landing page akan langsung dapat diakses

## 🛠️ Teknologi yang Digunakan

- **HTML5**: Struktur semantik dengan section-section yang jelas
- **CSS3**: 
  - CSS Custom Properties (CSS Variables)
  - CSS Grid & Flexbox untuk layout responsive
  - Sticky positioning untuk header
  - CSS Animations dan hover effects
- **JavaScript**: Mobile navigation toggle functionality
- **Responsive Design**: Mobile-first approach dengan breakpoints

## 🎨 Design System

### Color Palette
- **Primary Green**: `#2f8d45` - Tombol dan heading utama
- **Primary Dark**: `#0d3d1e` - Title besar
- **Mint Background**: `#cfe2dc` - Background sections
- **Chip Color**: `#eceff3` - Card dan placeholder
- **Text**: `#1f2937` - Teks utama
- **Muted**: `#6b7280` - Teks sekunder

### Typography
- Font Family: Inter, system-ui, Segoe UI, Arial, sans-serif
- Line Height: 1.6 untuk readability
- Font Weights: 600, 700, 800, 900 untuk hierarchy

## 📱 Responsive Breakpoints

- **Desktop**: > 960px (Grid layout penuh)
- **Tablet**: ≤ 960px (Grid 2 kolom, navigation mobile)
- **Mobile**: ≤ 560px (Single column layout)

## 📝 Catatan Pengembangan

Proyek ini menggunakan satu file CSS terpusat (`style.css`) dengan struktur modular berdasarkan sections:
- **Header/Navigation**: Sticky header dengan dropdown menu dan mobile toggle
- **Hero + Statistics**: Grid layout dengan call-to-action dan statistik real-time
- **About**: Section dengan background mint dan content center-aligned
- **Team**: Grid card layout untuk dokter dan terapis
- **Footer**: Multi-column footer dengan social media dan newsletter

### Fitur Interaktif
- Mobile navigation toggle dengan JavaScript
- Hover effects pada menu dan buttons
- Dropdown menu untuk Services
- Responsive grid layouts

---

**Essential Web Development & UI/UX - Semester 7**
