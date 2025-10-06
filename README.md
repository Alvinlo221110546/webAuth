🔐 WebAuthn Demo — Autentikasi Biometrik (PIN)

Proyek ini adalah demo sederhana WebAuthn yang menggunakan autentikasi biometrik seperti PIN.
Cocok digunakan sebagai contoh penerapan login tanpa password, atau sebagai pengganti TOTP / 2FA / MFA.

📘 Tentang WebAuthn

WebAuthn (Web Authentication API) memungkinkan pengguna untuk login dengan aman menggunakan perangkat mereka —
seperti fingerprint sensor, Face ID, atau kunci keamanan (security key) — tanpa perlu password tradisional.

Dokumentasi resmi:

MDN - navigator.credentials.create()

MDN - navigator.credentials.get()

⚠️ Contoh ini belum mencakup tahap verifikasi (assertion check) di server,
namun sudah dapat berfungsi sebagai sistem otentikasi dasar (mis. pengganti OTP atau MFA).

🧩 Persiapan Proyek

Clone repositori:

git clone https://github.com/peterdee/webauthn-demo
cd ./webauthn-demo


Gunakan Node.js versi 22:

nvm use 22


Instal dependensi:

npm ci

🚀 Jalankan Aplikasi Secara Lokal

Untuk menjalankan aplikasi di mode pengembangan:

npm run dev


Aplikasi akan tersedia di:

https://localhost:3000 atau https://localhost:3001 


⚠️ WebAuthn memerlukan koneksi HTTPS,
jadi pastikan kamu mengakses menggunakan https://localhost, bukan alamat IP langsung.