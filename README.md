# Linux Bostan

## Linux kernel Kalray Bostan port

In this repository you will find patches that can be applied on different version
of the Linux kernel. Currently the only path available has been tested on Linux
4.9.83 but should work with all Linux 4.9 release. There are some hunks with
version 4.9.133 but it is working.

```
patch -p1 < Add-support-for-k1-architecture.patch
```

You will need our toolchain to build the kernel.
Feel free to contact us at https://www.kalray.eu/contact-us/ for more details.
