# Sistem Terintegrasi Monitoring Akreditasi & Prodi PNL

Dashboard monitoring status akreditasi dan program studi Politeknik Negeri Lhokseumawe (PNL) berbasis simulasi feeder PDDikti Kemendiktisaintek.

## 🚀 Fitur Utama
- **Monitoring Akreditasi:** Real-time data akreditasi (Unggul, Baik Sekali, Baik) untuk seluruh program studi di 6 Jurusan PNL.
- **Pencarian & Multi-Filter:** Filter interaktif berdasarkan Jurusan, Jenjang (D2, D3, D4, S2), dan Peringkat Akreditasi.
- **Modal Detail:** Detail SK Akreditasi, Masa Berlaku, Daya Tampung, dan deskripsi kompetensi tiap prodi.
- **Simulasi API Feeder PDDikti:** Tombol sinkronisasi dengan indikator latensi & feedback interaktif.
- **Ekspor Data:** Fitur ekspor tabel ke format CSV.
- **Desain Modern:** Menggunakan Tailwind CSS Dark Mode, Glassmorphism, dan Lucide Icons.

## 📁 Struktur File
- `index.html`: Entry point aplikasi untuk deployment ke Vercel (Production Ready).
- `index.php`: Versi backend PHP untuk pengujian lokal di XAMPP (`localhost/pnl-akreditasi`).
- `api/pddikti.json`: Mock data endpoint API Feeder PDDikti.
- `vercel.json`: Konfigurasi routing untuk Vercel.

## 🌐 Cara Deploy ke Vercel
1. Upload repository ini ke akun GitHub Anda.
2. Login ke [vercel.com](https://vercel.com) menggunakan akun GitHub.
3. Klik **"Add New..."** > **"Project"**, lalu import repository ini.
4. Klik **Deploy** (tanpa perlu ubah build command).
