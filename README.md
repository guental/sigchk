# Signature Check
Check integrity of GOG games and goodies.

Filetypes: 7Z, APK, AVI, BIN, BR, BZ2, DEB, EXE, GZ, JPG, MKV, MP4, PDF, PNG, RAR, XZ, ZIP, ZST.

# Usage
sigchk [OPTION]... [FILE]...

**Options** 

***--dry-run*** find non-verifiable installers only

***--fingerprint*** show unknown installer fingerprints

***-t, --timestamp*** try to recover modification dates

***-s, --strict-gog*** verify GOG installer authenticity

***--ignore-missing*** ignore missing installer BINs

***--no-gog*** do not expect GOG installers

***--no-exceptions*** do not use built-in checksums

***--no-local*** do not use local checksums

***-x, --xattrs*** use BLAKE2b extended attributes

***-dx, --delete-xattrs*** delete BLAKE2b extended attributes

***-v, --verbose*** verbose mode

***-q, --quiet*** quiet mode

# Requirements
`sh awk binutils bzip2 coreutils find grep gzip osslsigncode sed tar unzip xz`

**Optional Packages**

`7zip-full ar attr b2sum brotli ffmpeg ghostscript imagemagick jpeginfo moreutils parallel pngcheck unrar zip zstd`

**Supported OS**

Guaranteed to work on GNU/Linux like Debian 10, Ubuntu 20.04 or higher
