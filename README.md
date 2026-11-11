# ALKP Radar

Situs lomba dan olimpiade pelajar. Halaman statis (`index.html`) dengan satu API (`api/items.js`) untuk menyimpan data.

## Pasang di Vercel
1. Unggah folder ini ke repositori GitHub.
2. Di Vercel: Add New > Project, pilih repositori itu, lalu Deploy.
3. Buka proyek > tab Storage > Create > Blob, lalu hubungkan ke proyek ini (variabel BLOB_READ_WRITE_TOKEN terisi otomatis).
4. Buka Settings > Environment Variables, tambahkan `ADMIN_PASSWORD` berisi password admin pilihanmu.
5. Buka Deployments > Redeploy agar variabel terbaca.

Siapa pun yang tahu password bisa masuk lewat tombol Admin dan mengubah data. Perubahan langsung terlihat oleh semua pengunjung.
Ganti password: ubah `ADMIN_PASSWORD` lalu redeploy.
