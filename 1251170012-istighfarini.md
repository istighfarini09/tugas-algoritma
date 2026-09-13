# tugas-algoritma
**Nama:** istighfarini  
**NIM:** 1251170012  
**kelas:** 3B

---  
# BAGIAN A: RANCANGAN ALGORITMA DENGAN KARAKTERISTIK LENGKAP  
### CASE KELAS B (Pendaftaran & Otentikasi pengguna Baru)
**Langkah-langkah (Instruksi Tersruktur):**  
Mulai 
1. Tampilkan formulir pendaftaran kepada pengguna.
2. Pengguna mengisi 'email' dan 'password' pada halaman pendaftaran.
3. Sistem memeriksa format email  
     (harus mengandung @ dan minimal 8 karakter) dan kekuatan password.
4. Jika validasi gagal, tampilkan pesan error dan kembali ke langkah 2.  
5. Jika validasi berhasil, sistem mengirim kode OTP.
6. Sistem meminta pengguna mengisi kode OTP yang di terima.
7. pengguna mengisi kode OTP.
8. Sistem memverivikasi kode OTP.  
    Jika kode OTP salah tampilkan pesan error dan minta pengguna mengisi ulang.
9. Jika Kode OTP benar, sistem menyimpan data kedalam database.
10. Tampilkan notifikasi "pendaftaran akun berhasil".
11. Selesai.
    
**Karakteristik Algoritma:**
1. **Input:** Email, password, kode OTP.  
2. **Output:** pesan eror (jika gagal) atau pesan pembuatan akun berhasil dan data tersimpan.
3. **Definiteness:** syarat password yang jelas, kondisi validasi email dan pencocokan kode OTP bernilai pasti tanpa ada makna ganda.  
4. **Finiteness:** proses berakhir dengan jelas pada dua kemungkinan: berhasil membuat akun atau proses dihentikan oleh pengguna.  
5. **Effectiveness:** setiap langkah terstruktur dari pengumpulan data hingga verifikasi 2 langkah, menjadikannya logis dan bisa diterapkan oleh sistem secara nyata.

   ---
   # BAGIAN B: ANALISIS PEMILIHAN STRUKTUR DATA
   **1.Skenario 1 (Fitur Undo / Redo)**
   * **Struktur Data Terpilih:** Stack 
