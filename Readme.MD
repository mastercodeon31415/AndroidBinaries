```
cd /data/data/com.termux/files/usr/bin && \
pkg update -y && \
pkg upgrade -y -o Dpkg::Options::="--force-confnew" && \
pkg install -y wget && \
wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/armhf/nc && \
chmod 777 ./nc && \
cd /data/data/com.termux/files/usr/lib && \
wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/armhf/libbsd.so.0 && \
chmod 777 ./libbsd.so.0 && \
wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/armhf/libmd.so.0 && \
chmod 777 ./libmd.so.0 && \
wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libc_malloc_debug.so.0 && \
chmod 777 ./libc_malloc_debug.so.0 && \
wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libpthread.so.0 && \
chmod 777 ./libpthread.so.0 && \
wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/ld-linux-aarch64.so.1 && \
chmod 777 ./ld-linux-aarch64.so.1 && \
wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libanl.so.1 && \
chmod 777 ./libanl.so.1 && \
wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libBrokenLocale.so.1 && \
chmod 777 ./libBrokenLocale.so.1 && \
wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libnsl.so.1 && \
chmod 777 ./libnsl.so.1 && \
wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/librt.so.1 && \
chmod 777 ./librt.so.1 && \
wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libthread_db.so.1 && \
chmod 777 ./libthread_db.so.1 && \
wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libutil.so.1 && \
chmod 777 ./libutil.so.1 && \
wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libdl.so.2 && \
chmod 777 ./libdl.so.2 && \
wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libnss_compat.so.2 && \
chmod 777 ./libnss_compat.so.2 && \
wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libnss_dns.so.2 && \
chmod 777 ./libnss_dns.so.2 && \
wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libnss_files.so.2 && \
chmod 777 ./libnss_files.so.2 && \
wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libnss_hesiod.so.2 && \
chmod 777 ./libnss_hesiod.so.2 && \
wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libresolv.so.2 && \
chmod 777 ./libresolv.so.2 && \
wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libc.so.6 && \
chmod 777 ./libc.so.6 && \
wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libm.so.6 && \
chmod 777 ./libm.so.6 && \
wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libmemusage.so && \
chmod 777 ./libmemusage.so && \
wget https://raw.githubusercontent.com/mastercodeon31415/AndroidBinaries/refs/heads/main/libpcprofile.so && \
chmod 777 ./libpcprofile.so && \
cd ../bin && \
export LD_LIBRARY_PATH=/data/data/com.termux/files/usr/lib && \
cd /data/data/com.termux/files/home
```

