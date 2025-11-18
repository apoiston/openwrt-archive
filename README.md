# OpenWrt SNAPSHOT

---

### 基本信息

- **LAN地址**: `10.0.0.1`
- **目标平台**: `x86/64`
- **固件版本**: `OpenWrt SNAPSHOT`
- **用户名**: `root`
- **密码**: `无`

### 常用命令

```shell
# 更新软件包列表
apk update
```
```shell
# 更新所有软件包
apk upgrade
```
```shell
# 安装软件包
apk add <package_name>
```
```shell
# 查看系统版本
cat /etc/openwrt_version
```
```shell
# 查看编译信息
cat /proc/version
```
```shell
# 重启网络服务
service network restart
```
```shell
# 保留配置升级
sysupgrade /tmp/openwrt-x86-64-generic-erofs-combined-efi.img.gz
```
```shell
# 不保留配置升级
sysupgrade -n /tmp/openwrt-x86-64-generic-erofs-combined-efi.img.gz
```

### 关于

- **源码**: [OpenWrt](https://github.com/openwrt/openwrt)
