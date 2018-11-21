## Souce file get
```
which iconv
/usr/bin/iconv

rpm -qf /usr/bin/iconv

yumdownloader --source glibc-common-2.17-222.el7.x86_64

rpm -ivh glibc-2.17-222.el7.src.rpm

tar xf ./rpmbuild/SOURCES/glibc-2.17-c758a686.tar.gz 

ls glibc-2.17-c758a686/iconv
Makefile            gconv_builtin.h  gconv_dl.c      iconv.h          iconvconfig.c  tst-iconv2.c
Versions            gconv_cache.c    gconv_int.h     iconv_charmap.c  iconvconfig.h  tst-iconv3.c
dummy-repertoire.c  gconv_charset.h  gconv_open.c    iconv_close.c    loop.c         tst-iconv4.c
gconv.c             gconv_close.c    gconv_simple.c  iconv_open.c     skeleton.c     tst-iconv5.c
gconv.h             gconv_conf.c     gconv_trans.c   iconv_prog.c     strtab.c
gconv_builtin.c     gconv_db.c       iconv.c         iconv_prog.h     tst-iconv1.c
```(


rpm -qfi `which iconv`
wget http://vault.centos.org/7.5.1804/os/Source/SPackages/glibc-2.17-222.el7.src.rpm

