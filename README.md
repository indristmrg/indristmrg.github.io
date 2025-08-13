# Portofolio Pribadi - Indri Br Situmorang

Selamat datang di repositori kode untuk situs portofolio pribadi saya. Situs ini dibangun menggunakan Jekyll dan tema portfolYOU.

Situs ini menampilkan profil, daftar proyek, dan tulisan blog saya.


## Menjalankan Situs Secara Lokal

Anda dapat menjalankan situs ini di komputer Anda untuk melihat pratinjau perubahan sebelum melakukan push ke GitHub.

### Prasyarat

Pastikan Anda memiliki Ruby dan Bundler terinstal.

**Ruby**: Untuk memeriksa, buka Terminal (macOS/Linux) atau Command Prompt (Windows) dan jalankan `ruby -v`. Jika belum terinstal, unduh dan instal dari situs resmi Ruby.

**Bundler**: Setelah Ruby terinstal, instal Bundler dengan perintah:

```bash
gem install bundler
```

### Langkah-langkah Instalasi dan Menjalankan

1. **Clone Repositori (Jika Diperlukan)**
   Jika Anda belum memiliki proyek ini di komputer Anda, clone repositori ini:
   ```bash
   git clone https://github.com/indristmrg/indristmrg.github.io.git
   ```

2. **Masuk ke Direktori Proyek**
   ```bash
   cd indristmrg.github.io
   ```

3. **Instal Kebutuhan Proyek**
   Jalankan perintah ini satu kali untuk mengunduh semua gem (paket Ruby) yang dibutuhkan oleh proyek:
   ```bash
   bundle install
   ```

4. **Jalankan Server Lokal Jekyll**
   Untuk memulai server lokal, gunakan perintah:
   ```bash
   bundle exec jekyll serve
   ```
   
   Tips: Untuk pengembangan yang lebih efisien, gunakan flag `--livereload` agar browser otomatis me-refresh halaman setiap kali Anda menyimpan perubahan pada file.
   ```bash
   bundle exec jekyll serve --livereload
   ```

5. **Buka Situs di Browser**
   Setelah server berjalan, buka browser Anda dan kunjungi alamat `http://localhost:4000`. Anda akan melihat pratinjau situs Anda.

## Struktur Folder Utama

- `_projects`: Berisi file-file markdown untuk setiap proyek yang ditampilkan di halaman "Projects".
- `_posts`: Berisi file-file markdown untuk setiap tulisan blog.
- `_data`: Berisi file data YAML (seperti timeline.yml dan skills.yml) yang digunakan untuk mengisi konten di halaman "About".
- `_includes`: Berisi komponen HTML yang dapat digunakan kembali di seluruh situs.
- `_layouts`: Berisi templat tata letak utama untuk berbagai jenis halaman (misalnya post.html, page.html).
- `assets`: Berisi file-file statis seperti gambar, CSS, dan JavaScript.
- `_config.yml`: File konfigurasi utama untuk situs Jekyll.