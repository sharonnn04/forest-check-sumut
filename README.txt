FOREST CHECK SUMATERA UTARA - CLOUDFLARE PAGES (TAHAP 1)

File:
- index.html  : halaman publik Cloudflare yang memuat Web App Apps Script
- _headers    : header keamanan dasar untuk halaman Cloudflare
- robots.txt  : mengizinkan mesin pencari mengakses situs

Backend Apps Script yang dipakai:
https://script.google.com/macros/s/AKfycbyQum86Hjxgzv_i5Je3rL07ENg4JODsrFwo84zDV13ExXwqlQxFo434L5iDIcLUqs6_/exec

CARA DEPLOY:
1. Masuk Cloudflare Dashboard.
2. Workers & Pages.
3. Create application / Create.
4. Pilih Pages lalu Direct Upload / Drag and drop.
5. Nama project yang disarankan: forest-check-sumut
6. Upload isi folder ini atau ZIP "forest-check-sumut-cloudflare.zip".
7. Deploy.
8. Buka URL *.pages.dev yang diberikan Cloudflare.
9. Uji: peta, pencarian, login, riwayat, admin, link Google Maps.

CATATAN:
Tahap 1 hanya memberi alamat Cloudflare/HTTPS sebagai pintu masuk publik.
Backend Apps Script dan Supabase masih tetap seperti sebelumnya.
Perlindungan API/database yang lebih kuat dilakukan di tahap berikutnya.
