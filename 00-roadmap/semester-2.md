# Roadmap Pembelajaran KSCC (Minggu 25–48)

**Fokus Utama Semester 2:**  
Mendalami keamanan aplikasi, automasi keamanan, infrastruktur cloud lanjutan, dan integrasi AI/ML ke sistem keamanan.

---

## Modul 4: Otomasi & Keamanan Infrastruktur Cloud (Minggu 25–36)

### Minggu 25: Infrastructure as Code (IaC) dengan Terraform
- **Materi:** Dasar Terraform, resource, state, variable.
- **Praktik:** Deploy VPC dan EC2 otomatis via Terraform.
- **Tugas:** Buat file `.tf` untuk membuat satu VPC dan dua subnet.

### Minggu 26: CI/CD Aman dengan GitHub Actions & AWS
- **Materi:** Workflow dasar GitHub Actions, prinsip keamanan pipeline.
- **Praktik:** Build & deploy otomatis ke EC2 atau S3 dari repo GitHub.
- **Tugas:** Buat workflow `.yml` untuk deploy aplikasi sederhana ke EC2.

### Minggu 27: Serverless Security (AWS Lambda & API Gateway)
- **Materi:** Keamanan pada arsitektur tanpa server, prinsip least privilege.
- **Praktik:** Buat fungsi Lambda dan lindungi endpoint API Gateway.
- **Tugas:** Buat Lambda fungsi login dengan logging ke CloudWatch.

### Minggu 28: Keamanan Container (Docker & ECR)
- **Materi:** Dasar Docker, image hardening, scanning vulnerability.
- **Praktik:** Build image lokal, push ke AWS ECR, dan scan.
- **Tugas:** Buat Dockerfile sederhana untuk aplikasi Python Flask.

### Minggu 29: Monitoring & Logging Keamanan (CloudWatch & CloudTrail)
- **Materi:** Centralized logging, alarm keamanan, analisis aktivitas.
- **Praktik:** Buat custom metric, alarm login gagal, audit via CloudTrail.
- **Tugas:** Setup notifikasi email jika terjadi 5x login gagal ke EC2.

### Minggu 30: Keamanan Database di Cloud
- **Materi:** Enkripsi RDS/DynamoDB, audit, konfigurasi firewall database.
- **Praktik:** Buat RDS PostgreSQL, aktifkan enkripsi & backup.
- **Tugas:** Dokumentasikan konfigurasi aman untuk RDS.

### Minggu 31: IAM Lanjutan & Federation
- **Materi:** IAM policy berbasis kondisi, cross-account access, SSO.
- **Praktik:** Buat role dengan permission minimal & federasi IAM dengan user eksternal.
- **Tugas:** Simulasikan dua user dengan hak akses berbeda ke bucket S3.

### Minggu 32: AWS Config & Audit Manager
- **Materi:** Audit konfigurasi & compliance otomatis.
- **Praktik:** Buat rule Config dan jalankan audit otomatis.
- **Tugas:** Laporkan resource mana saja yang non-compliant dari Config.

### Minggu 33: Keamanan Jaringan Cloud Lanjutan
- **Materi:** Transit Gateway, Direct Connect, VPC peering & flow log.
- **Praktik:** Konfigurasi peering antar VPC dan logging ke S3.
- **Tugas:** Visualisasikan traffic jaringan dari flow log.

### Minggu 34: Implementasi Web Application Firewall (WAF)
- **Materi:** Proteksi aplikasi dari OWASP Top 10 dengan AWS WAF.
- **Praktik:** Deploy WAF ke CloudFront/API Gateway.
- **Tugas:** Uji XSS & SQLi menggunakan dummy app dan WAF log.

### Minggu 35: Threat Intelligence (STIX, TAXII, MITRE ATT&CK)
- **Materi:** Threat sharing format, analisis taktik penyerang.
- **Praktik:** Mapping skenario penyerang dengan MITRE ATT&CK.
- **Tugas:** Simulasikan satu TTP penyerang dan buat analisisnya.

### Minggu 36: Otomasi Respon Insiden di AWS
- **Materi:** EventBridge, Lambda, GuardDuty Trigger, auto-remediation.
- **Praktik:** Blok IP otomatis jika terdeteksi scanning mencurigakan.
- **Tugas:** Buat diagram alur respon otomatis dan skenario uji.

---

## Modul 5: Integrasi AI/ML & Forensik Digital (Minggu 37–47)

### Minggu 37: ML untuk Deteksi Anomali Jaringan
- **Materi:** Isolation Forest, autoencoder, unsupervised anomaly detection.
- **Praktik:** Latih model pada data flow log, klasifikasikan traffic mencurigakan.
- **Tugas:** Bandingkan hasil klasifikasi dengan Ground Truth (jika ada).

### Minggu 38: Deteksi Phishing dengan NLP
- **Materi:** Text classification, spam/phishing classifier.
- **Praktik:** Bangun model klasifikasi teks email.
- **Tugas:** Buat dataset 100 email dan latih model deteksi phishing.

### Minggu 39: User & Entity Behavior Analytics (UEBA)
- **Materi:** Analisis perilaku user untuk deteksi insider threat.
- **Praktik:** Bangun baseline aktivitas user dari log.
- **Tugas:** Buat visualisasi anomali perilaku user.

### Minggu 40: Forensik Digital Lanjutan
- **Materi:** Timeline analysis, hash file, image carving.
- **Praktik:** Analisis disk image dengan Autopsy atau sleuthkit.
- **Tugas:** Temukan artefak file mencurigakan dalam disk image.

### Minggu 41: Deep Learning untuk Keamanan Siber
- **Materi:** CNN & RNN untuk security log.
- **Praktik:** Gunakan TensorFlow/Keras untuk klasifikasi aktivitas.
- **Tugas:** Latih model klasifikasi aktivitas login mencurigakan.

### Minggu 42: Threat Hunting dengan AI
- **Materi:** Menggunakan AI untuk mencari indikator kompromi tersembunyi.
- **Praktik:** Bangun pipeline AI sederhana untuk threat hunting.
- **Tugas:** Buat laporan threat hunting dari dataset publik.

### Minggu 43: Cloud Forensic & Snapshot Analysis
- **Materi:** Mengambil snapshot EBS, log analysis dari backup.
- **Praktik:** Simulasi insiden, snapshot, analisis file.
- **Tugas:** Dokumentasi proses forensik cloud.

### Minggu 44: Automasi Audit & Compliance Reporting
- **Materi:** Kustom report keamanan otomatis dengan Python/Boto3.
- **Praktik:** Generate laporan penggunaan dan konfigurasi IAM otomatis.
- **Tugas:** Kirim laporan keamanan mingguan ke email otomatis.

### Minggu 45: Simulasi Serangan & Penetration Testing
- **Materi:** Metodologi pentest, tools (nmap, metasploit), etika.
- **Praktik:** Simulasi serangan XSS dan scanning server internal.
- **Tugas:** Buat laporan pentest dengan rekomendasi mitigasi.

### Minggu 46: Evaluasi Sistem & Perbaikan Desain
- **Materi:** Evaluasi arsitektur keamanan, post-mortem insiden.
- **Praktik:** Uji sistem dari sisi attacker & defender.
- **Tugas:** Buat laporan evaluasi arsitektur keamanan.

---

## Minggu 47–48: Proyek Akhir Semester 2

- **Tujuan:** Integrasi seluruh pembelajaran ke proyek nyata.
- **Contoh Proyek:**
  - Sistem Deteksi Intrusi berbasis ML di AWS.
  - Dashboard Audit Keamanan Otomatis.
  - Sistem Otomatis Respon Ancaman Real-Time.
- **Output:** Source code, dokumentasi, presentasi, dan video demo proyek.

---

**Catatan:**
- Gunakan GitHub untuk menyimpan seluruh script, data, laporan mingguan, dan proyek mini.
- Dokumentasi setiap minggu bisa disimpan dalam `docs/week-xx/` dengan format `.md`.

