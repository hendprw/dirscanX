```markdown
# Web Status Checker

Web Status Checker adalah alat sederhana untuk memeriksa status kode HTTP dari berbagai path pada sebuah website.

## Penggunaan

1. Instal dependensi dengan menjalankan perintah berikut:

   ```bash
   pip install -r requirements.txt
   ```

2. Jalankan skrip dengan perintah berikut:

   ```bash
   python web_status_checker.py -u example.com -t 5 -w db.txt -save json
   ```

   - `-u` atau `--url`: URL website target.
   - `-t` atau `--workers`: Jumlah thread pekerja (opsional, default 5).
   - `-w` atau `--file`: Path ke berkas daftar URL (opsional, default db.txt).
   - `-save`: Simpan hasil sebagai JSON, HTML, TXT, atau CSV (opsional).

## Dependensi

- [colorama](https://pypi.org/project/colorama/)
- [fake-useragent](https://pypi.org/project/fake-useragent/)
- [requests](https://pypi.org/project/requests/)
- [urllib3](https://pypi.org/project/urllib3/)

## Kontribusi

Anda dapat berkontribusi pada proyek ini dengan melakukan pull request.

## Lisensi

Proyek ini dilisensikan di bawah [Lisensi Freeware](LICENSE.txt). Anda bebas menggunakan, memodifikasi, dan mendistribusikan proyek ini untuk tujuan pribadi dan non-komersial.

---
© [Your Name](https://github.com/yourusername)
```

Pastikan untuk mengganti bagian `[Your Name](https://github.com/yourusername)` dengan informasi Anda sendiri. Anda juga dapat menambahkan lebih banyak detail atau dokumentasi yang sesuai dengan proyek Anda.
