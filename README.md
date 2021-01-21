# mingw-w64-qt4
Files are a copy of https://github.com/msys2/MINGW-packages-dev/tree/master/mingw-w64-qt4 (using that [procedure](https://stackoverflow.com/a/24577293))

I reproduce here this legacy mingw-w64 package which is still currently used in TeXmacs for windows
but no longer available readily built in the [msys2 repo](http://repo.msys2.org/mingw/i686/).
Unfortunately, building the package anew also fails with the current msys2...

In the release, I provide the last i686 binary (32bit) that was in the repo and that is needed for building TeXmacs.  

2021-01-18: updated to build on Win10. Many new patches (several security patches) picked from [Mageia Cauldron qt4-4.8.7-35.mga8.src.rpm]( http://distrib-coffee.ipsl.jussieu.fr/pub/linux/Mageia/distrib/cauldron/SRPMS/core/release/qt4-4.8.7-35.mga8.src.rpm)
