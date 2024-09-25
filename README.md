# spdx-purl2url
Extract PURLs from SPDX Json and convert them to Download URLs

# Installation

Encure you have `packageurl-python` installed, i.e. with `pip install packageurl-python`

# Example usage

```
$ ./spdx-purl2url ~/Downloads/wolfi-base.latest.spdx.json
https://ftp.gnu.org/gnu/libc/glibc-2.40.tar.xz
https://github.com/besser82/libxcrypt/archive/f531a36aa916a22ef2ce7d270ba381e264250cbf.tar.gz
https://github.com/besser82/libxcrypt/archive/v4.4.36.tar.gz
https://github.com/madler/zlib.git/archive/51b7f2abdade71cd9bb0e7a373ef2610ec6f9daf.tar.gz
https://github.com/madler/zlib.git/archive/v1.3.1.tar.gz
https://github.com/openssl/openssl.git/archive/fb7fab9fa6f4869eaa8fbb97e0d593159f03ffe4.tar.gz
https://github.com/openssl/openssl.git/archive/openssl-3.3.2.tar.gz
https://github.com/wolfi-dev/os/archive/29dabcaa9232d7814e05f5e311ca6562ab42efda.tar.gz
https://github.com/wolfi-dev/os/archive/47793bfd95deb14489d0a0d187ff9abbd31f970a.tar.gz
https://github.com/wolfi-dev/os/archive/4ebd3d015479571d2e909f74b756e08c9379a602.tar.gz
https://github.com/wolfi-dev/os/archive/71d8c809791db5fb95781c7c1eab528930109f92.tar.gz
https://github.com/wolfi-dev/os/archive/72687401a7b3e8a12bf78c5e0d1a29bf6fb14669.tar.gz
https://github.com/wolfi-dev/os/archive/a210624b093af744aa09b69372345cf3356ae18b.tar.gz
https://github.com/wolfi-dev/os/archive/d2921addb9f3d820f54f16e910df63eac803614a.tar.gz
https://github.com/wolfi-dev/os/archive/dd9d55c9154e78ff5d0d2eb513de2a198ef7f00f.tar.gz
```
