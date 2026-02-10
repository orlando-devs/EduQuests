# EduQuest - Modern Learning Platform

Platform pembelajaran interaktif berbasis React dan Firebase untuk menghubungkan guru dan siswa.

## 🚀 Quick Start

### Development
```bash
npm install
npm run dev
```

### Build
```bash
npm run build
```

## 📦 Deployment ke GitHub Pages

### Langkah-langkah Manual:

1. **Pastikan GitHub Actions sudah aktif:**
   - Buka repository di GitHub
   - Klik tab **Actions**
   - Jika ada pesan "Workflows aren't being run on this forked repository", klik tombol hijau **"I understand my workflows, go ahead and enable them"**

2. **Aktifkan GitHub Pages:**
   - Buka **Settings** → **Pages**
   - Di bagian **Build and deployment**:
     - **Source**: Pilih **GitHub Actions** (bukan Deploy from a branch)
   - Klik **Save**

3. **Tunggu Build Selesai:**
   - Kembali ke tab **Actions**
   - Tunggu workflow "Deploy static content to Pages" selesai (centang hijau ✅)
   - Biasanya memakan waktu 1-2 menit

4. **Akses Website:**
   - Setelah workflow selesai, buka: `https://orlando-devs.github.io/EduQuests/`

## 🛠️ Tech Stack

- **Framework**: React 19 + Vite 6
- **Styling**: Tailwind CSS v4
- **Icons**: Lucide React
- **Backend**: Firebase (Firestore & Auth)
- **Animations**: Framer Motion

## 📝 Troubleshooting

### Halaman Masih Blank?

1. Pastikan GitHub Pages **Source** di-set ke **GitHub Actions** (bukan branch)
2. Cek tab Actions - pastikan workflow berhasil (hijau ✅, bukan merah ❌)
3. Clear cache browser (Ctrl+Shift+R atau Cmd+Shift+R)
4. Tunggu 2-3 menit setelah deployment selesai

### Workflow Tidak Berjalan?

Jika workflow tidak otomatis berjalan:
1. Buka tab **Actions**
2. Klik workflow "Deploy static content to Pages"
3. Klik tombol **Run workflow** → **Run workflow**

---

Made with ❤️ by Orlando Devs
