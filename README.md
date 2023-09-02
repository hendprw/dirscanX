## DirscanX

DirscanX merupakan sebuah alat simple yang dirancang untuk mencari sebuah path ataupun direktori pada sebuah website.

# instalasi 

1. Instal dependensi dengan menjalankan perintah berikut:

   ```bash
   pip install -r requirements.txt
   ```

2. Jalankan skrip dengan perintah berikut:

   ```bash
   python main.py -u example.com
   ```

   - `-u` atau `--url`: URL website target.
   - `-t` atau `--workers`: Jumlah thread workets (opsional, default 5).
   - `-w` atau `--file`: Untuk menggunakan file wordliss khusus (opsional) .
   - `-save`: Simpan hasil scanning sebagai format JSON, HTML, TXT, atau CSV (opsional).

## Dependensi

- [colorama](https://pypi.org/project/colorama/)
- [fake-useragent](https://pypi.org/project/fake-useragent/)
- [requests](https://pypi.org/project/requests/)
- [urllib3](https://pypi.org/project/urllib3/)
