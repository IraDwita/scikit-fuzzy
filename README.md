Nama : Ira Dwita Syafitri 

Kelas : D4 TI 3A

NPM : 1184024

SCIKIT FUZZY

- SCIKIT FUZZY adalah toolkit logika fuzzy untuk SciPy.

Tujuan scikit-fuzzy adalah:
1.  Untuk menyediakan komunitas dengan perangkat yang kuat yang dikembangkan secara mandiri dan
  menerapkan algoritma logika fuzzy
2.  Untuk meningkatkan daya tarik Python ilmiah sebagai alternatif yang valid
  opsi sumber tertutup.

-  Instalasi

Scikit-Fuzzy bergantung pada

  * NumPy> = 1,6
  * SciPy> = 0,9
  * JaringanX> = 1.9

dan tersedia di PyPi! Rilis stabil terbaru selalu dapat diperoleh
dan diinstal hanya dengan menjalankan

    $ pip install -U scikit-fuzzy

yang juga akan berfungsi untuk meningkatkan instalasi yang ada ke rilis terbaru.


Jika lebih suka menginstal dari sumber atau mengembangkan paket ini, dapat bercabang dan
klon repositori ini lalu instal SciKit-Fuzzy dengan menjalankan

$ python setup.py install

atau kembangkan secara lokal dengan menjalankan

$ python setup.py develop

Dapat menggunakan SciKit-Fuzzy tanpa menginstal hanya dengan mengekspor
jalur ini ke variabel PYTHONPATH Anda.

- Pembulatan IEEE untuk pengguna Matlab

Putaran Matlab salah. Standar IEEE (yaitu
bagaimana paket ini berperilaku) membutuhkan pembulatan ke nomor GENAP terdekat jika
persis di antara, mis. 1,5 -> 2; 2,5 -> 2; 3,5 -> 4; 4,5 -> 4, dll. Ini
meminimalkan kesalahan pembulatan sistematis. Jadi, jika menerapkan kembali algoritma dari
Kode Matlab, diharapkan sedikit inkonsistensi dalam hasil yang dibulatkan. Ini adalah
bukan bug, dan tidak akan diperbaiki.
