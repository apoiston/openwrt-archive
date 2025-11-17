# OpenWrt SNAPSHOT

---

### 基本信息

- **LAN地址**: `10.0.0.1`
- **目标平台**: `x86/64`
- **固件版本**: `OpenWrt SNAPSHOT`
- **用户名**: `root`
- **密码**: `无`
- **源码**: [OpenWrt](https://github.com/openwrt/openwrt)

---

## 固件下载

下载地址：  
[GitHub Releases](https://github.com/apoiston/openwrt-archive/releases)

---

### 常用命令

```bash
# 更新软件包列表
apk update

# 更新所有软件包
apk upgrade

# 安装软件包
apk add <package_name>

# 查看系统版本
cat /etc/openwrt_version

# 查看编译信息
cat /proc/version

# 重启网络服务
service network restart

# 保留配置升级
sysupgrade /tmp/openwrt-x86-64-generic-erofs-combined-efi.img.gz

# 不保留配置升级
sysupgrade -n /tmp/openwrt-x86-64-generic-erofs-combined-efi.img.gz