# OpenWrt SNAPSHOT

The new repository has been activated.
- [openwrt-builder](https://github.com/apoiston/openwrt-builder)

---

### Firmware Download

- [Releases](https://github.com/apoiston/openwrt-builder/releases)

### Package Repositories

- [apps](https://infinityapps.pages.dev/)

- [kmods](https://infinitykmods.pages.dev/)

- [packages](https://infinitypackages.pages.dev/)

```shell
# add key
wget -O /etc/apk/keys/infinity.pem https://infinityapps.pages.dev/public-key.pem
```

```shell
# add feed
echo https://infinityapps.pages.dev/snapshots/x86_64/apps/packages.adb >> /etc/apk/repositories.d/customfeeds.list
```

### Special Thanks

- [Joseph Mory](http://github.com/morytyann)

- [OpenWrt](https://github.com/openwrt/openwrt)

- [OpenWrt LuCI](https://github.com/openwrt/luci)

- [OpenWrt Packages](https://github.com/openwrt/packages)

- [GitHub](https://github.com)

- [GitHub Actions](https://github.com/features/actions)
