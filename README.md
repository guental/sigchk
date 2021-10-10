# Signature Check
Check integrity of GOG games and goodies.

Filetypes: 7Z, AVI, BIN, EXE, GZ, JPG, MKV, MP4, PDF, PNG, RAR, ZIP.

# Usage
sigchk [OPTION]... [FILE]...

**Options** 

***-f, ---fingerprint*** show unknown installer fingerprints

***-t, --timestamp*** try to recover modification dates

***-s, --strict*** verify installer authenticity

***--ignore-missing*** ignore missing installer BINs

***--no-exceptions*** do not use built-in checksums

***--no-cert-exceptions*** do not use built-in certificates

***--no-local*** do not use local checksums

***-q, --quiet*** quiet mode

# Requirements
`sh awk bzip2 coreutils find grep gzip osslsigncode sed tar unzip`

**Optional Packages**

`7zip-full ar attr b2sum brotli ffmpeg ghostscript imagemagick jpeginfo moreutils parallel pngcheck unrar xz zip zstd`

**Supported OS**

Guaranteed to work on GNU/Linux like Debian 10, Ubuntu 20.04 or higher
