# TEAM MANIFESTO & KEBIJAKAN KOMUNIKASI TIM
## Proyek: Aplikasi Mobile Kantin Pintar Kampus (Scrum Team Baru)

Dokumen ini disusun sebagai pedoman utama bagi seluruh anggota tim untuk membangun lingkungan kerja yang sehat, kolaboratif, profesional, dan bebas dari konflik destruktif. Manifesto ini menjadi acuan mutlak dalam berinteraksi, melakukan peninjauan kode (*code review*), serta mengelola waktu kerja demi mencegah *burnout*.

---

## 1. STANDAR OPERASIONAL PROSEDUR (SOP) CODE REVIEW (GitHub)

Proses *Code Review* bukan sarana untuk menjatuhkan atau mencari kesalahan personal, melainkan sebuah mekanisme penjaminan mutu (*quality assurance*) demi keberhasilan proyek bersama. Setiap anggota tim wajib menjunjung tinggi empati, objektivitas, dan profesionalisme.

### A. Prinsip Utama Peninjauan Kode
1. **Fokus pada Kode, Bukan Individu:** Kritik ditujukan kepada baris kode atau arsitektur sistem, bukan kapabilitas personal penulis kode. Gunakan subjek "kode ini" atau "fungsi ini" daripada kata "kamu" atau "Anda" secara berlebihan saat mengkritik.
2. **Sertakan Alasan dan Solusi:** Jangan hanya mengatakan sebuah baris kode "salah" atau "jelek". Jelaskan *mengapa* hal tersebut kurang optimal dan berikan saran atau referensi perbaikan yang konkret.
3. **Apresiasi Hal Positif:** Jika melihat implementasi kode yang rapi, efisien, atau cerdas, berikan pujian atau emoji positif (seperti: 👍, 🚀, 🎉) untuk membangun motivasi tim.

### B. Matriks Contoh Kalimat dalam Review

| Kategori | ❌ Kalimat yang DILARANG |  Kalimat yang DIANJURKAN (Konstruktif) |
| :--- | :--- | :--- |
| **Penyampaian Masalah** | *"Ini kode siapa sih? Berantakan banget dan bikin fungsi payment jadi error."* | *"Fungsi pembayaran di baris ini tampaknya mengalami conflict dengan format JSON yang baru. Mari kita sesuaikan kembali strukturnya."* |
| **Kritik Format Data** | *"Bisa kerja gak sih? Format JSON di backend berubah terus tanpa info. Pantesan frontend pecah."* | *"Ada perubahan schema JSON pada respons API ini yang menyebabkan error di sisi Frontend. Agar sinkron, ke depannya mari kita sepakati perubahan field lewat dokumentasi/kontrak API terlebih dahulu ya."* |
| **Saran Perbaikan** | *"Kodenya lambat, ganti pakai perulangan yang bener."* | *"Optimasi di bagian ini bisa ditingkatkan jika kita menggunakan metode asynchronous agar tidak blocking I/O. Bagaimana menurutmu jika dicoba dengan pendekatan berikut: `[Contoh Snippet Kode]`?"* |
| **Pemberian Komentar Singkat** | *"Hapus ini. Gak guna."* | *"Variabel ini tampaknya sudah tidak digunakan lagi setelah refactoring terakhir. Boleh tolong dihapus agar menjaga kebersihan kode (*clean code*)?"* |

---

## 2. PROTOKOL KOMUNIKASI & MANAJEMEN WAKTU (Pencegahan Burnout)

Mengingat proyek ini berada dalam fase kritis (sisa waktu 2 minggu menjelang *deployment*), manajemen energi tim sangatlah krusial. Kebijakan ini dibuat agar seluruh anggota tim dapat bekerja secara optimal tanpa mengorbankan kesehatan mental.

### A. Jam Kerja dan Batasan Koordinasi
1. **Waktu Kerja Standar:** Koordinasi rutin, diskusi teknis, dan pengerjaan tugas dilakukan pada hari kerja (Senin - Jumat) mulai pukul **08.00 WIB hingga 17.00 WIB**.
2. **Jam Tenang (*Quiet Hours*):** Dilarang keras melakukan *chat* koordinasi, menanyakan progres, atau mengirimkan permintaan pengerjaan tugas di atas **jam 21.00 WIB**.
3. **Hak untuk Tidak Merespons:** Anggota tim berhak penuh untuk tidak merespons pesan yang masuk di atas jam 21.00 WIB hingga keesokan harinya, tanpa sanksi atau penilaian negatif apa pun dari pimpinan maupun rekan setim.

### B. Saluran Komunikasi Berdasarkan Tingkat Urgensi

* **Urgensi Rendah sampai Sedang (Trello / GitHub Issues / WhatsApp Group):**
  * Digunakan untuk pembaruan harian (*daily standup* tertulis), diskusi fitur standar, penyerahan tugas, dan *code review*. Tanggapan diharapkan dalam kurun waktu jam kerja normal.
* **Urgensi Tinggi (Khusus Kondisi Darurat / Sistem Down):**
  * Pengecualian mutlak untuk aturan Jam Tenang berlaku **hanya jika terjadi kondisi darurat kritis**, seperti:
    * Server pengembangan/pementasan *down* total yang menghentikan kerja seluruh tim.
    * Terjadi kebocoran data atau celah keamanan fatal pada aplikasi.
  * **Prosedur Penanganan Darurat:** Anggota tim diperbolehkan melakukan panggilan langsung (*direct call* / telepon) kepada penanggung jawab komponen terkait (misalnya *DevOps* atau *Backend Lead*) untuk penanganan instan secara langsung, meskipun di luar jam kerja.

---

## 3. MEKANISME RESOLUSI KONFLIK (Integrasi Backend-Frontend)

Jika terjadi perbedaan pendapat teknis atau miskomunikasi antar anggota tim terkait integrasi fitur:
1. **Pindah Jalur ke Komunikasi Sinkron:** Jangan berdebat panjang lewat teks tertulis (WhatsApp/GitHub). Segera adakan *sync-up meeting* singkat (Google Meet / Zoom) maksimal 10-15 menit untuk meluruskan masalah.
2. **Keterlibatan Scrum Master / Product Owner:** Jika diskusi teknis menemui jalan buntu, serahkan kedua opsi solusi kepada *Scrum Master* dan *Product Owner* untuk diputuskan berdasarkan prioritas *Sprint backlog*.

---
**Komitmen Bersama Tim:**
*"Kita adalah satu tim dengan satu tujuan: Menyelesaikan Aplikasi Kantin Pintar Kampus tepat waktu dengan kualitas terbaik, tanpa menjatuhkan satu sama lain."*

