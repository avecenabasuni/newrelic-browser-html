# New Relic Browser HTML Example

Selamat datang! 🙌  
Repositori ini memberikan penjelasan tentang **cara mengintegrasikan New Relic Browser** ke dalam aplikasi frontend kamu. Dengan menambahkan skrip New Relic ke halaman HTML, kamu bisa memantau dan menganalisa performa aplikasi web dari sisi pengguna secara langsung.

## Apa Itu New Relic Browser?

**New Relic Browser** adalah produk dari New Relic yang memungkinkan kamu memantau performa aplikasi web di sisi frontend. Dengan New Relic, kamu bisa melihat data penting seperti waktu muat halaman, interaksi pengguna, dan performa JavaScript. Semua data ini akan sangat berguna untuk mengoptimalkan pengalaman pengguna (UX).

New Relic memberikan **insight** tentang bagaimana aplikasi kamu berperforma di browser pengguna, termasuk tracking seperti:
- Waktu loading halaman
- Waktu tunggu untuk memuat komponen
- Interaksi pengguna (klik, scroll, dll)
- Error yang terjadi di browser
- Dan lainnya...

## Kenapa Harus Menggunakan New Relic di Frontend?

Dengan mengintegrasikan New Relic ke aplikasi frontend kamu, kamu bisa:
- **Memantau performa real-time** dari sisi pengguna.
- Mengetahui halaman mana yang **memerlukan optimasi lebih lanjut**.
- **Mendeteksi dan melacak bug atau error** yang terjadi hanya di sisi frontend.
- Mendapatkan **data yang lebih akurat** tentang apa yang dialami pengguna di browser mereka.

## Cara Integrasi New Relic ke HTML

### 1. Dapatkan New Relic Browser Key
Untuk menggunakan New Relic Browser, pertama kamu perlu mendaftar di New Relic dan mendapatkan `Browser Key` dari dashboard mereka. Browser Key ini yang akan menghubungkan aplikasi kamu dengan New Relic.

### 2. Sisipkan Skrip New Relic ke dalam HTML
Setelah mendapatkan `Browser Key`, kamu perlu menambahkan skrip New Relic ke dalam file HTML. Skrip ini akan memuat data performa aplikasi kamu dan mengirimkannya ke New Relic. Semua skrip ini sudah disediakan langsung oleh New Relic.

### 3. Verifikasi Data di New Relic
Setelah menambahkan skrip ke aplikasi kamu dan meng-upload file HTML, kamu bisa memverifikasi bahwa data performa mulai muncul di dashboard New Relic. Pastikan kamu bisa melihat metrik yang dilaporkan oleh browser agent, seperti **page load time**, **error monitoring**, dan lainnya.

## Apa yang Dapat Dipantau dengan New Relic?

Setelah integrasi, New Relic akan melaporkan berbagai metrik dan data, seperti:
- **Page Load Time**: Berapa lama halaman membutuhkan waktu untuk dimuat.
- **User Interaction**: Seberapa cepat interaksi pengguna (klik, scroll, dll) ditangani.
- **JavaScript Errors**: Error yang terjadi di browser pengguna.
- **Frontend Performance Metrics**: Statistik tentang performa sisi klien (seperti waktu rendering dan responsivitas).

Dengan data ini, kamu bisa mengoptimalkan performa aplikasi web kamu, meminimalkan masalah, dan meningkatkan pengalaman pengguna.

## Kebutuhan

- **Akun New Relic**: Diperlukan untuk mendapatkan `Browser Key`.
- **Browser yang Mendukung JavaScript**: New Relic Browser membutuhkan JavaScript yang aktif untuk dapat memantau performa.

## Lisensi

Repositori ini menggunakan lisensi **MIT**. Kamu bebas menggunakan dan memodifikasinya sesuai kebutuhan. Cek file `LICENSE` untuk detail lebih lanjut.

---

Terima kasih sudah melihat contoh integrasi New Relic ini! Kalau ada pertanyaan atau butuh bantuan, jangan ragu untuk membuka *Issues* di GitHub ya! 🚀
