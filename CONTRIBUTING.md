# Contributing

Repo ini mengikuti gaya Awesome List.

## Cara menambah proyek

1. Tambahkan nama repo ke `repos.json` dengan format `owner/repo`.
2. Jalankan `python scripts/update-readme.py`.
3. Jalankan `npx --yes markdownlint-cli --config .markdownlint.json README.md CONTRIBUTING.md SECURITY.md CODE_OF_CONDUCT.md`.
4. Buat pull request dengan ringkasan proyek yang ditambahkan.

## Standar kontribusi

- Tambahkan proyek open source yang relevan dengan ekosistem Indonesia.
- Pastikan repo publik dan bisa diakses dari GitHub.
- Pastikan repo bukan duplikasi dari entri yang sudah ada.
- Jangan edit tabel README secara manual jika metadata bisa dihasilkan dari GitHub API.
- Deskripsi, pembuat, bahasa, lisensi, stars, forks, issue, tanggal update, dan tags diambil otomatis dari GitHub API.

## Format repos.json

```json
[
  "owner/repo",
  "another-owner/another-repo"
]
```

## Rekomendasi update

- Gunakan nama owner dan repo yang valid.
- Jika metadata di README terlihat kurang lengkap, update metadata di repo asalnya terlebih dahulu.
- README diurutkan otomatis berdasarkan jumlah stars terbanyak.
- Workflow `Update README` berjalan harian dan bisa dipicu manual dari tab Actions.
