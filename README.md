**Quality Assurance - Sistem Absensi Karyawan PT Indotama Tunas Mandiri**

**1. Ringkasan Proyek (Project Overview)**
    Deskripsi: Aplikasi berbasis web yang dirancang untuk mengelola absensi harian karyawan di PT Indotama Tunas Mandiri. Sistem ini bersifat tertutup (internal enterprise), di mana pengelolaan data karyawan dilakukan secara terpusat melalui database tanpa fitur registrasi mandiri untuk menjaga keamanan data.

    Peran: Quality Assurance (QA)
    Tools: Spreadsheet (Test Case)
    SQL/DBeaver (Database Validation)
    Browser DevTools.

**2. Cakupan Pengujian (Scope of Work)**
  Fokus utama pengujian adalah memastikan integritas data pengguna yang sudah ada di database (Pre-seeded Data) dan validasi hak akses (Role-Based Access Control) antara Super Admin dan karyawan biasa.
    
    Functional Testing: Login, Check-in/Check-out, Rekap Absensi.
    
    Database Testing: Validasi data user sesuai tabel database.
    
    Security Testing (Basic): Memastikan tidak ada celah akses untuk user tanpa kredensial database.

**3. Skenario Pengujian Utama (Key Test Scenarios)**
  Karena sistem ini tidak memiliki fitur registrasi, strategi pengujian difokuskan pada validasi data yang sudah ada
