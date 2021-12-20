# Hello-World-Cmake

Hello app tested with yocto. Check the complete tutorial in [this](https://github.com/amamory-embedded/learning-yocto/) repository.

Run the following command to compile it in stand-alone mode (i.e. wo Yocto):

```
libtoolize --force
aclocal
autoheader
automake --force-missing --add-missing
autoconf
./configure
```
