# Sistem Informasi Manajemen Kegiatan Ekstrakurikuler Pramuka

Paket awal berisi dokumen SOT, kontrak kerja coding agent, execution prompt, dan prototipe UI React + Vite dengan data dummy.

## Teknologi
- React
- Vite
- CSS responsif
- Data dummy lokal (tanpa backend/API/database)

## Menjalankan proyek
Pastikan Node.js LTS dan npm sudah terpasang.

```bash
npm install
npm run dev
```

Buka URL lokal yang ditampilkan Vite di terminal.

## Akun demo
- Admin: `admin@pramuka.local`
- Pembina: `pembina@pramuka.local`
- Anggota: `anggota@pramuka.local`
- Password demo: bebas diisi

Login hanya simulasi front-end. Tidak ada autentikasi produksi atau penyimpanan permanen.

## Struktur
- `docs/PRD.md` — kebutuhan produk dan batasan
- `docs/UI-GUIDELINE.md` — sistem visual dan aturan UI
- `docs/IMPLEMENTATION_PLAN.md` — rencana implementasi
- `AGENTS.md` — kontrak kerja agent
- `prompts/EXECUTION_PROMPT.md` — prompt eksekusi awal
- `src/` — prototipe antarmuka React

Seluruh data dapat diubah selama sesi berjalan dan akan kembali ke data awal saat halaman dimuat ulang.
