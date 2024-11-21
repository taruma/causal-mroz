# causal-morz

Proyek ini menganalisis hubungan kausal antara pendidikan tinggi wanita dan partisipasi mereka dalam angkatan kerja menggunakan dataset Mroz (1975). Implementasi berbagai metode matching untuk mengungkap efek kausal pendidikan terhadap keputusan berkarir.

Untuk menjalankan notebook ini, Anda bisa menggunakan perintah `uv sync` setelah membuat virtual environment dengan `uv`.

Important notes:
- Python version 3.11 is used to avoid compatibility errors for [numpy.distutils](https://numpy.org/doc/2.1/reference/distutils_status_migration.html)
- In the `causalgraphicalmodels` package, you need to manually edit the `cgm.py` file and change line 4 from `from collections import Iterable` to `from collections.abc import Iterable`.