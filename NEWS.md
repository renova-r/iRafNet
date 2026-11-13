# iRafNet 1.1.1.9001

Renova release, based on CRAN iRafNet 1.1-1 (archived on CRAN 2024-11-11).

- `src/regTree.c` and `src/rfutils.c`: `Calloc(...)` became `R_Calloc(...)` and `Free(...)` became `R_Free(...)` throughout.
- No R code, `NAMESPACE`, `DESCRIPTION` field or help page changed.
- `DESCRIPTION`: `Version` set to `1.1.1.9001`; "Compatibility updates by Renova." appended to `Description`.
- The stale `MD5` file was removed.
- `COPYING` (GNU GPL text) was added; the `License` field is unchanged.
- `README.md` was added and `.Rbuildignore` keeps `README.md` and `NEWS.md` out of the built package.
