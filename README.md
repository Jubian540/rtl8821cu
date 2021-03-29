# rtl8821cu
rtl8821cu linux driver.

## build

```shell
$ make -C "path of rtl8821cu driver" ARCH="target platform" CROSSCOMPILE="target platform crosstools" KSRC="linux kernel path"
```

Quickly to build for hi35xx: `./build.sh`.

## install

1. After build compile, copy 8821cu.ko in rtl8821cu directory to target rootfs.
2. Use 'insmod 8821cu.ko' loading: driver.
