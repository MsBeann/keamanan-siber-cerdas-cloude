# Roadmap Pembelajaran PS KSCC - Semester 1 (Minggu 1 - Minggu 24)

**Fokus Utama Semester 1:** Membangun fondasi kuat di Python, Linux, Jaringan, dan pengantar Cloud serta Machine Learning.

---

## Modul 1: Fondasi Digital & Logika Komputasi (Minggu 1 - Minggu 5)

### Minggu 1: Logika Pemrograman & Pengantar Python
- **Materi:** Algoritma dasar (flowchart, pseudo-code), instalasi Python, variabel, tipe data, operator.
- **Praktik:** Program "Hello World!", kalkulator sederhana, latihan dasar tipe data/operator.
- **Tugas:** Buat program Python sederhana yang menerima input nama dan usia, lalu mencetak pesan selamat datang.

### Minggu 2: Struktur Kontrol Python & Fungsi
- **Materi:** `if/elif/else`, `for`/`while` loops, membuat dan memanggil fungsi.
- **Praktik:** Program tebak angka, piramida bintang, fungsi dengan parameter.
- **Tugas:** Buat fungsi Python yang menentukan apakah sebuah angka genap atau ganjil.

### Minggu 3: Struktur Data Python & Error Handling
- **Materi:** `list`, `tuple`, `dictionary`, `set`. `try-except` blocks.
- **Praktik:** Manipulasi data dalam list/dict, program yang menangani input salah.
- **Tugas:** Buat program yang mengelola daftar belanja (tambah, hapus, tampilkan item).

### Minggu 4: Pengantar Sistem Operasi Linux (CLI)
- **Materi:** Instalasi Linux VM (Ubuntu/Kali), perintah navigasi (`ls`, `cd`, `pwd`), manajemen file dasar (`cp`, `mv`, `rm`, `cat`).
- **Praktik:** Eksplorasi sistem file Linux Anda di terminal.
- **Tugas:** Buat beberapa file dan folder di Linux CLI, lalu pindahkan dan hapus.

### Minggu 5: Linux CLI Lanjut & Jaringan Komputer Dasar
- **Materi:** Hak akses (`chmod`, `chown`), manajemen user/proses (`ps`, `top`, `kill`), dasar *shell scripting*. Pengenalan model OSI/TCP/IP, IP addresses, `ping`, `traceroute`.
- **Praktik:** Buat *user* baru, ubah izin file. Gunakan `ping` dan `traceroute` di terminal Anda.
- **Tugas:** Buat *shell script* sederhana untuk mencetak tanggal dan waktu saat ini.

---

## Modul 2: Dasar Keamanan Siber & Pengantar Cloud/ML (Minggu 6 - Minggu 12)

### Minggu 6: Dasar-dasar Keamanan Informasi
- **Materi:** CIA Triad (Confidentiality, Integrity, Availability), ancaman siber umum (malware, phishing, DoS), manajemen risiko dasar.
- **Praktik:** Analisis studi kasus pelanggaran keamanan sederhana.
- **Tugas:** Identifikasi 3 ancaman siber paling umum dan berikan contohnya.

### Minggu 7: Kriptografi Dasar & Keamanan Jaringan
- **Materi:** Konsep enkripsi/dekripsi (simetris/asimetris), *hashing*, digital signature. Pengenalan fungsi *firewall* dan VPN.
- **Praktik:** Enkripsi/dekripsi teks sederhana dengan Python menggunakan *library* kriptografi.
- **Tugas:** Jelaskan perbedaan antara enkripsi simetris dan asimetris.

### Minggu 8: Keamanan Aplikasi Web Dasar
- **Materi:** OWASP Top 10 (SQL Injection, XSS, Broken Authentication) secara konseptual. Validasi input, penanganan sesi.
- **Praktik:** Identifikasi celah keamanan dasar di aplikasi web contoh (gunakan Burp Suite Community Edition).
- **Tugas:** Jelaskan bagaimana SQL Injection dapat terjadi dan cara mencegahnya.

### Minggu 9: Pengenalan Komputasi Awan (AWS)
- **Materi:** Model *cloud* (IaaS, PaaS, SaaS), model tanggung jawab bersama AWS. Layanan AWS utama: EC2, S3, VPC dasar.
- **Praktik:** Buat akun AWS (gratis tier), *launch* instance EC2, *upload* file ke S3.
- **Tugas:** Jelaskan perbedaan antara IaaS, PaaS, dan SaaS.

### Minggu 10: IAM (Identity & Access Management) di AWS
- **Materi:** Konsep *users*, *groups*, *roles*, *policies* di AWS IAM. Prinsip *least privilege*.
- **Praktik:** Buat user IAM baru dengan policy yang spesifik, coba batasi aksesnya ke S3.
- **Tugas:** Buat diagram sederhana yang menunjukkan bagaimana IAM bekerja di AWS.

### Minggu 11: Pengantar Machine Learning
- **Materi:** Apa itu ML? Jenis-jenis pembelajaran (supervised, unsupervised). Konsep data training/testing.
- **Praktik:** Implementasi Regresi Linear sederhana dengan scikit-learn di Python.
- **Tugas:** Berikan contoh penggunaan Machine Learning dalam keamanan siber.

### Minggu 12: Statistika & Aljabar Linear untuk ML
- **Materi:** Ulasan cepat statistika deskriptif (mean, median, mode, standar deviasi), probabilitas dasar. Konsep vektor dan matriks dasar.
- **Praktik:** Latihan dengan NumPy dan Pandas untuk manipulasi data numerik.
- **Tugas:** Hitung rata-rata dan standar deviasi dari sebuah *list* angka di Python.

---

## Modul 3: Keamanan Cloud Lanjutan & ML Awal untuk Keamanan (Minggu 13 - Minggu 24)

### Minggu 13: Jaringan Keamanan Cloud Lanjut (AWS VPC)
- **Materi:** Konfigurasi VPC multi-subnet (public/private), Security Groups, NACL, routing tables, VPC peering.
- **Praktik:** Bangun arsitektur VPC 2-tier (web & database) yang terisolasi di AWS.
- **Tugas:** Jelaskan fungsi Security Groups dan NACL di AWS VPC.

### Minggu 14: AWS WAF & AWS Shield
- **Materi:** Melindungi aplikasi web dari serangan umum (SQLi, XSS) dengan AWS WAF. Perlindungan DDoS dengan AWS Shield.
- **Praktik:** Konfigurasi AWS WAF untuk sebuah aplikasi web contoh.
- **Tugas:** Bedakan antara AWS WAF dan AWS Shield.

### Minggu 15: Deteksi Ancaman di AWS (GuardDuty & Security Hub)
- **Materi:** Bagaimana AWS GuardDuty mendeteksi aktivitas mencurigakan. Fungsi AWS Security Hub untuk *centralized security view*.
- **Praktik:** Aktifkan GuardDuty, buat beberapa skenario *dummy* untuk memicu *alert*.
- **Tugas:** Jelaskan bagaimana GuardDuty membantu dalam deteksi ancaman.

### Minggu 16: Log & Audit Keamanan di Cloud (CloudTrail & CloudWatch)
- **Materi:** Peran CloudTrail untuk *API call logging*. CloudWatch untuk metrik dan log aplikasi.
- **Praktik:** Analisis log CloudTrail untuk mengidentifikasi aktivitas tidak sah. Buat *custom metric* di CloudWatch.
- **Tugas:** Berikan contoh informasi yang bisa ditemukan di log CloudTrail.

### Minggu 17: Machine Learning untuk Klasifikasi
- **Materi:** Algoritma klasifikasi (Logistic Regression, Decision Trees, Random Forest). Metrik evaluasi (accuracy, precision, recall, F1-score).
- **Praktik:** Bangun model klasifikasi sederhana (misalnya, memprediksi apakah email adalah spam atau bukan) menggunakan dataset contoh.
- **Tugas:** Jelaskan konsep *confusion matrix* dalam klasifikasi.

### Minggu 18: Machine Learning untuk Deteksi Anomali
- **Materi:** Konsep deteksi anomali. Algoritma (Isolation Forest, One-Class SVM).
- **Praktik:** Terapkan algoritma deteksi anomali pada dataset *network traffic* atau *user behavior* yang sederhana.
- **Tugas:** Berikan contoh anomali yang relevan dalam konteks keamanan siber.

### Minggu 19: Pra-pemrosesan Data untuk ML Keamanan
- **Materi:** Teknik membersihkan, menormalisasi, dan merepresentasikan data (fitur engineering) dari log keamanan atau *network packet* untuk input ML.
- **Praktik:** Siapkan *dataset* keamanan mentah untuk model ML.
- **Tugas:** Jelaskan mengapa pra-pemrosesan data penting dalam ML.

### Minggu 20: Keamanan Data di Cloud (KMS & Enkripsi)
- **Materi:** AWS KMS (Key Management Service) untuk mengelola kunci enkripsi. Enkripsi data at-rest (S3, EBS, RDS) dan in-transit (TLS).
- **Praktik:** Enkripsi bucket S3 Anda menggunakan KMS.
- **Tugas:** Jelaskan perbedaan antara enkripsi data *at-rest* dan *in-transit*.

### Minggu 21: Forensik Digital Dasar & Analisis Malware
- **Materi:** Langkah-langkah forensik digital. Pengumpulan bukti. Konsep *malware* (virus, worm, trojan, ransomware). Dasar analisis statis *malware*.
- **Praktik:** Gunakan alat seperti *strings* atau *file* di Linux untuk menganalisis *binary* yang mencurigakan (di lingkungan aman/sandbox).
- **Tugas:** Sebutkan 3 jenis *malware* dan karakteristiknya.

### Minggu 22: Pengantar Manajemen Risiko & Tata Kelola Keamanan
- **Materi:** Identifikasi aset, penilaian risiko, mitigasi risiko. Konsep standar ISO 27001 dan NIST Cybersecurity Framework.
- **Praktik:** Lakukan penilaian risiko sederhana untuk sistem contoh.
- **Tugas:** Jelaskan pentingnya manajemen risiko dalam keamanan siber.

### Minggu 23: DevSecOps di Cloud (Konseptual)
- **Materi:** Integrasi keamanan ke dalam siklus hidup pengembangan *software* (CI/CD) di lingkungan *cloud-native*. Konsep *Infrastructure as Code (IaC)*.
- **Praktik:** Pelajari dasar Terraform/CloudFormation untuk membuat infrastruktur sederhana.
- **Tugas:** Jelaskan konsep DevSecOps dan mengapa itu penting.

### Minggu 24: Proyek Mini Semester 1 & Ujian Evaluasi
- **Materi:** Integrasi pengetahuan dari seluruh Semester 1 dalam sebuah proyek kecil (misalnya, membangun web app sederhana yang aman di AWS dengan *basic* *logging* dan deteksi anomali *user* menggunakan ML).
- **Praktik:** Kerjakan proyek, presentasi hasil, dan persiapkan diri untuk ujian komprehensif.
- **Tugas:** Presentasikan proyek mini Anda dan siapkan diri untuk evaluasi.

---
