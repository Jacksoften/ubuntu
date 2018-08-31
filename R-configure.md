## ubuntu version

missing F77 compiler

```
sudo apt-get install gfortran
```

configure: error: --with-readline=yes (default) and headers/libs are not available

```
./configure --with-readline=no --with-x=no

```
checking whether zlib support suffices... configure: error: zlib library and headers are required

```
sudo apt install lib32z1-dev 
```
checking whether bzip2 support suffices... configure: error: bzip2 library and headers are required

```
sudo apt install libbz2-dev
```
configure: error: "liblzma library and headers are required"

```
sudo apt install liblzma-dev
```
checking whether PCRE support suffices... configure: error: pcre >= 8.20 library and headers are required

```
sudo apt install libpcre3-dev
```
configure: error: libcurl >= 7.22.0 library and headers are required with support for https

```
sudo apt install libcurl4-openssl-dev
```
Capabilities skipped:      PNG, JPEG, TIFF, cairo, ICU


```
sudo apt install libgd-dev
```
fixed PNG, JPEG, TIFF


Capabilities skipped:      cairo, ICU

```
sudo apt install libicu-dev
```
all capabilities are installed

R shared library (/usr/local/lib64/R/lib/libR.so) not found. If this is a custom build of R, was it built with the --enable-R-shlib option?

```
./configure --with-readline=no --with-x=no --enable-R-shlibmak
make clean
make
```

configure: WARNING: you cannot build info or HTML versions of the R manuals
configure: WARNING: you cannot build PDF versions of the R manuals
configure: WARNING: you cannot build PDF versions of vignettes and help pages

```
sudo apt-get install texlive
```

configure: WARNING: you cannot build info or HTML versions of the R manuals
configure: WARNING: neither inconsolata.sty nor zi4.sty found: PDF vignettes and package manuals will not be rendered optimally

```
sudo apt-get install texlive-fonts-extra
sudo apt-get install texinfo
```
all done


conftest.c:1:17: fatal error: jni.h: No such file or directory
```
sudo apt install openjdk-8-jdk 
```



## MacOS version 
## Configure R with all capabilities open. (used pkg file downloaded from R-cran 


## Link old packages to new installed R

`.libPaths()` returns the path of libraries

