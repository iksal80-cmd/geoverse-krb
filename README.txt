GeoVerse KRB Kota Bogor - metaverse geospasial media pembelajaran
=================================================================
Isi paket:
  index.html     aplikasi (Three.js r160 + WebXR, dimuat dari cdn.jsdelivr.net)
  krb_data.json  68 poligon kelurahan (UTM 48S, disederhanakan) + atribut risiko
                 per bahaya dari Matriks Kelurahan KRB + batas kecamatan + situ
  img/           8 peta kerentanan, sampul Album Peta, grafik tren kejadian

Cara pasang: unggah folder ini ke server web (mis. subfolder /geoverse-krb/ di
vr.ti.fts.uika-bogor.ac.id). Harus dibuka lewat http(s), bukan file://, karena
data dimuat dengan fetch(). Mode VR butuh HTTPS dan peramban WebXR (Quest Browser).

Sumber data: Folder KRB Kota Bogor (Bapperida Kota Bogor & FT Universitas Pakuan):
Lampiran Matriks Kelurahan.xlsx, Data Dasar/01 Batas Administrasi (Kelurahan,
Kecamatan), 03 Perairan (Perairan_Lainnya_AR), Data Spasial/Kerentanan/Jpg (PNG),
Album Peta KRB (sampul). Peta layout JPG resolusi penuh ditautkan ke Drive.

Pemasangan di Google Sites (krn.web.id): unggah folder ini ke GitHub Pages, lalu di
Google Sites buat halaman baru > Sisipkan > Sematkan > Berdasarkan URL > tempel alamat
GitHub Pages. Tombol "Buka layar penuh" muncul otomatis saat aplikasi berada di dalam embed.
