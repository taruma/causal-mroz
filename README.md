# causal-morz
 

Important notes:
- Python version 3.11 is used to avoid compatibility errors for [numpy.distutils](https://numpy.org/doc/2.1/reference/distutils_status_migration.html)
- In the `causalgraphicalmodels` package, you need to manually edit the `cgm.py` file and change line 4 from `from collections import Iterable` to `from collections.abc import Iterable`.