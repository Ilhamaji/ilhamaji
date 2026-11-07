<div align="left">

<img src="https://komarev.com/ghpvc/?username=ilhamaji&label=Profile%20Views&color=0e75b6&style=flat-square" alt="Profile views" />

# Ilham Aji

Mahasiswa ilmu komputer di Indonesia. Saya membangun aplikasi web dari ujung ke ujung, dan paling peduli pada bagian yang mudah dilewati: fallback saat API gagal, skema yang tetap waras saat datanya nyata, README yang benar-benar bisa diikuti.

<a href="mailto:ilhmsap@gmail.com"><img src="https://img.shields.io/badge/Email-ilhmsap%40gmail.com-blue?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://ilhamaji.github.io"><img src="https://img.shields.io/badge/Portfolio-ilhamaji.github.io-0e75b6?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>

<!-- lang-switcher -->
[English](README.md) · **Bahasa Indonesia**

</div>

---

## Proyek Pilihan

Empat proyek yang menunjukkan apa yang sebenarnya saya kerjakan. Sisanya ada di [halaman repositori](https://github.com/Ilhamaji?tab=repositories).

### [groq-article-summarizer](https://github.com/Ilhamaji/groq-article-summarizer)

Mengumpulkan literatur jurnal untuk skripsi itu lambat: buka artikel, unduh PDF, baca abstrak dan kesimpulan, ulangi. Pipeline ini mengerjakan alur itu dalam satu pemanggilan — beri URL artikel, ia mencari tautan PDF, mengekstrak teks dengan PyMuPDF, memisahkan badan tulisan dari daftar pustaka agar sitasi tidak mengotori ringkasan, lalu mengembalikan ringkasan terstruktur dari `llama-3.3-70b-versatile` lewat Groq.

Bagian yang saya soroti: ada mode evaluasi yang mengukur latensi dan kemiripan judul/penulis dengan `SequenceMatcher`, karena peringkas ini butuh angka untuk bab skripsi, bukan sekadar demo.

`Python` · `Groq` · `PyMuPDF` · `BeautifulSoup`

### [skin-cancer-inference-api](https://github.com/Ilhamaji/skin-cancer-inference-api)

REST API klasifikasi gambar dari kelas machine learning Dicoding. Dua kelas, Cancer dan Non-cancer, dengan ambang keyakinan 50% — di bawah itu jawabannya *Non-cancer*, karena kesalahan yang mahal di sini adalah false positive. Setiap prediksi ditulis ke Firestore agar bisa ditelusuri kembali.

`Hapi.js` · `TensorFlow.js` · `Firestore` · `Google Cloud`

### [cheting](https://github.com/Ilhamaji/cheting)

Aplikasi chat real-time dengan bentuk Discord/Slack: DM, grup yang berisi kategori dan channel, sistem pertemanan, dan voice channel WebRTC. NextAuth untuk autentikasi, Prisma di atas PostgreSQL, Radix/Shadcn untuk antarmuka.

Kendala yang menarik: menjalankan signalling real-time di Next.js App Router, yang tidak punya server berumur panjang untuk menaruh socket.

`Next.js 15` · `Prisma` · `PostgreSQL` · `WebRTC`

### [academy-dashboard](https://github.com/Ilhamaji/academy-dashboard)

Aplikasi Laravel untuk keuangan sekolah: pembayaran SPP, pengeluaran, dan laporan untuk keduanya. Menggantikan buku kas dan spreadsheet berserakan dengan satu database yang bisa dicari plus ekspor Excel/PDF.

Ini yang paling tidak bergaya di daftar ini, dan mungkin paling banyak dipakai. Perlu diketahui sebelum membukanya: tidak ada pemisahan peran — semua route di grup `auth` bisa diakses akun mana pun yang sudah login.

`Laravel` · `PHP` · `MySQL` · `Blade`

---

## Sedang Dikerjakan

- **[ats-cv-maker](https://github.com/Ilhamaji/ats-cv-maker)** — editor CV Nuxt 4 yang mengekspor lewat Puppeteer. Editor dan ekspor PDF sudah jalan; penyimpanan belum ada, jadi refresh menghilangkan data Anda.
- **[haclash](https://github.com/Ilhamaji/haclash)** — game hack-and-slash 2D di Godot. Gerak, platform, dan animasi serangan sudah ada; musuhnya belum, jadi belum bisa dimainkan sebagai game.

Keduanya punya roadmap di README masing-masing.

---

## Stack

Sehari-hari: TypeScript, React, Next.js, Tailwind. Backend Node/Express atau Laravel dengan PostgreSQL atau MySQL. Python untuk pekerjaan NLP.

<p align="left">
  <img src="https://skillicons.dev/icons?i=ts,react,nextjs,tailwind,nodejs,express,php,laravel,mysql,postgres,python,docker,git" alt="Tech stack" />
</p>
