🔐 Firebase Authentication REST API Integration
Proyek ini mendokumentasikan implementasi dan pengujian alur Firebase Authentication menggunakan REST API. Dokumentasi ini mencakup proses registrasi pengguna hingga verifikasi email.

🛠️ 1. Persiapan Environment
Langkah pertama adalah mengatur variabel lingkungan di Postman agar API Key dan Token dapat dikelola secara dinamis.

Screenshot 1: Postman Environment Setup
<img width="1920" height="1008" alt="Screenshot 2026-03-13 054013" src="https://github.com/user-attachments/assets/88f4ed6f-12e8-4689-928f-645129565ce4" />

🚀 2. Alur Registrasi (Sign Up)
Mengirimkan permintaan POST ke endpoint Google Identity Toolkit untuk mendaftarkan akun baru.

Screenshot 2: User Sign Up Request
<img width="1920" height="1008" alt="Screenshot 2026-03-13 054045" src="https://github.com/user-attachments/assets/0e31b95c-f92c-4279-b08d-1b36dfaad4b9" />

📧 3. Pengiriman Email Verifikasi
Setelah user terdaftar, sistem mengirimkan email verifikasi menggunakan idToken yang didapat dari proses registrasi.

Screenshot 3: Send Verification Email
<img width="1920" height="1008" alt="Screenshot 2026-03-13 054122" src="https://github.com/user-attachments/assets/fe2e68e4-3890-4f22-be1b-74f61680406b" />

🖥️ 4. Monitoring Firebase Console
Memastikan data pengguna telah masuk ke dalam database autentikasi Firebase secara real-time.

Screenshot 4: Firebase Authentication Dashboard
<img width="1920" height="1008" alt="Screenshot 2026-03-13 054137" src="https://github.com/user-attachments/assets/f686f409-5f88-4e14-97ce-dae1685b701f" />

✅ 5. Verifikasi Akhir
Proses aktivasi akun melalui link yang dikirimkan ke email pengguna.

Screenshot 5: Email & Success Page
<img width="1920" height="1008" alt="Screenshot 2026-03-13 054340" src="https://github.com/user-attachments/assets/78ca9b73-3e34-4ded-9f8c-157d213b8b90" />
<img width="1920" height="1008" alt="Screenshot 2026-03-13 054353" src="https://github.com/user-attachments/assets/95c977ee-e95e-405f-9e10-30590d95dabc" />

🛠️ Tech Stack & Tools
Firebase Auth: Backend Identity Service.

Postman: API Testing & Documentation.

JSON: Data interchange format.
