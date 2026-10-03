# HRDBest

Aplikasi HRIS untuk pengelolaan karyawan: absensi, izin, penggajian, dan laporan dalam satu web app. Dikembangkan sebagai PWA dan siap deploy ke Cloudflare.

## Fitur

- Absensi harian dengan QR code dan verifikasi wajah (face-api.js)
- Pencatatan lokasi absensi dengan peta (Leaflet)
- Pengajuan izin dengan persetujuan admin
- Slip gaji dan pencatatan pinjaman karyawan
- Kartu pegawai (ID card) dengan QR code
- Laporan dan rekap absensi
- Notifikasi via Firebase Cloud Messaging

## Tech Stack

- Next.js (App Router), React, TypeScript
- Tailwind CSS
- Neon PostgreSQL (@neondatabase/serverless)
- Autentikasi JWT
- OpenNext untuk deploy ke Cloudflare

## Cara Menjalankan

```bash
npm install
npm run dev
```

Buka http://localhost:3000.

Build dan deploy ke Cloudflare:

```bash
npm run cf:build
npm run cf:deploy
```

## Lisensi

MIT. Lihat [LICENSE](LICENSE).
