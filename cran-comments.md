## Test environments

* local OS X install, R 3.4.2
* local ubuntu 16.04.2 install, R 3.4.2
* ubuntu 14.04.5 (on travis-ci), R 3.3.3, 3.4.2, 3.5.0
* win-builder (devel and release)

## R CMD check results

0 errors | 0 warnings | 1 note

* checking installed package size ... NOTE
  installed size is  5.5Mb
  sub-directories of 1Mb or more:
    data   5.4Mb
* We plead for mercy with respect to the package size. The data sets included
are used in the corresponding book, and are necessary for reproducibility. 

* There is [one outstanding issue](https://github.com/beanumber/mdsr/issues/28)
but it only affects old releases of Windows. I haven't been able to reproduce it. 

## Reverse dependencies

There are no reverse dependencies.

