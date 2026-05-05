# 🚀 Febrian Valentino Agape — Portfolio

Website portofolio pribadi yang di-deploy di [Vercel](https://vercel.com).

---

## 📁 Struktur File

```
portfolio-vercel/
├── index.html      ← File utama portofolio
├── vercel.json     ← Konfigurasi deployment Vercel
├── .gitignore      ← File yang diabaikan Git
└── README.md       ← Dokumentasi ini
```

---

## 🛠️ Tutorial Deploy ke Vercel

### Metode 1: Via GitHub (Rekomendasi)

#### Langkah 1 — Buat Repository GitHub
1. Buka [github.com](https://github.com) → login
2. Klik tombol **"New"** (pojok kiri atas)
3. Isi nama repo, contoh: `portfolio`
4. Pilih **Public**, lalu klik **"Create repository"**

#### Langkah 2 — Upload File ke GitHub
Jalankan perintah berikut di terminal:

```bash
# Masuk ke folder ini
cd portfolio-vercel

# Inisialisasi Git
git init
git add .
git commit -m "Initial commit: portfolio website"

# Hubungkan ke GitHub (ganti URL dengan repo kamu)
git remote add origin https://github.com/USERNAME/portfolio.git
git branch -M main
git push -u origin main
```

> **Ganti** `USERNAME` dengan username GitHub kamu.

#### Langkah 3 — Deploy ke Vercel
1. Buka [vercel.com](https://vercel.com) → **Sign Up / Login** (bisa pakai akun GitHub)
2. Klik **"Add New Project"**
3. Klik **"Import"** di sebelah repo `portfolio`
4. Biarkan semua setting default → klik **"Deploy"**
5. ✅ Tunggu ~30 detik — portofolio kamu langsung live!

Vercel akan memberi URL seperti: `https://portfolio-username.vercel.app`

---

### Metode 2: Drag & Drop (Paling Cepat, Tanpa Git)

1. Buka [vercel.com/new](https://vercel.com/new) → login
2. Scroll ke bawah, cari bagian **"Deploy without Git"**
3. **Drag & drop** folder `portfolio-vercel` ke area tersebut
4. Klik **"Deploy"**
5. ✅ Selesai! Situs langsung online.

> ⚠️ Metode ini tidak mendukung auto-deploy saat file diubah.

---

### Metode 3: Via Vercel CLI

```bash
# Install Vercel CLI
npm install -g vercel

# Masuk ke folder project
cd portfolio-vercel

# Deploy (ikuti instruksi di terminal)
vercel

# Untuk deploy ke production
vercel --prod
```

---

## 🌐 Custom Domain (Opsional)

Setelah deploy berhasil:
1. Buka dashboard project di Vercel
2. Klik tab **"Settings"** → **"Domains"**
3. Tambahkan domain kamu (contoh: `febrianvalentino.com`)
4. Ikuti instruksi DNS yang diberikan Vercel

---

## 🔄 Update Portofolio

Setiap kali kamu push perubahan ke GitHub (`git push`), Vercel akan otomatis **re-deploy** — tidak perlu melakukan apapun lagi.

```bash
# Setelah mengubah index.html
git add index.html
git commit -m "Update portfolio content"
git push
```

---

## 📬 Kontak

**Febrian Valentino Agape**  
📧 febrian.valentino1402@gmail.com  
🔗 [linkedin.com/in/febrian-valentino-agape](https://linkedin.com/in/febrian-valentino-agape)  
💻 [github.com/CaptTino](https://github.com/CaptTino)
