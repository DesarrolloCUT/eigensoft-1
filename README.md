# eigensoft
Minor improvements for EIGENSOFT.  http://www.hsph.harvard.edu/alkes-price/software/

## Note: Requirements
* GSL http://www.gnu.org/software/gsl/
* lapack http://www.netlib.org/lapack/
```{shell}
make blaslib
make lapacklib
```
* OpenBLAS https://github.com/xianyi/OpenBLAS
```{shell}
make FC=gfortran
make install
```

## Copyright
EIGENSOFT is copyright by Harvard University and The Broad Institute.

