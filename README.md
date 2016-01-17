# libpng-releases

This repository contains libpng tar.xz and .7z distributions, intended
for direct download via scripts containing "wget" or "curl" directives
such as

 wget http://github.com/glennrp/libpng-releases/raw/master/libpng-1.6.21.tar.xz

 wget http://github.com/glennrp/libpng-releases/raw/master/lpng1621.7z

The *.tar.xz files contain source files with *nix-style line endings and
contain a "configure" script and associated files for building a Makefile.

The *.7z files have DOS-style line endings and don't have "configure".

You can obtain the PGP armored signature for each file by appending .asc, e.g.,

 wget http://github.com/glennrp/libpng-releases/raw/master/lpng1621.7z.asc

If you want to access individual source files, go to the libpng repository at

 https://github.com/glennrp/libpng instead.

