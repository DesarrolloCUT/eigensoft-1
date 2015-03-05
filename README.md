# eigensoft
Minor improvements for EIGENSOFT.  http://www.hsph.harvard.edu/alkes-price/software/

## Change Log
+ Accept variants ID length up to 16,000, which is the maximum ID length that current PLINK 1.9 can handle.
+ Accept snpmapfile with long lines (up to 10,000 chars per line).

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

