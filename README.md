# libtorrent-windows-dll


This package exports OpenSSL dll's for libtorrent.

The noted DLL's are:
- `libcrypto-1_1-x64.dll`
- `libssl-1_1-x64.dll`

They are installed in `libtorrent` namespace to facilate the missing dll error in libtorrent. 

Solution for the [arvidn/libtorrent#7338](https://github.com/arvidn/libtorrent/issues/7338) 
