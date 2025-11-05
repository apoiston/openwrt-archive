# OpenWrt SNAPSHOT

---

### 基本信息

- **LAN 地址**: `10.0.0.1`
- **固件版本**: OpenWrt SNAPSHOT
- **目标平台**: x86_64
- **默认用户名**: `root`
- **默认密码**: 无
- **源码仓库**: [OpenWrt Git](https://git.openwrt.org/openwrt/openwrt.git)

---

## 下载地址

固件下载链接：  
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

# 查看系统信息
cat /etc/openwrt_version
cat /proc/version

# 重启网络服务
/etc/init.d/network restart

# 保留配置升级
sysupgrade /tmp/openwrt-x86-64-generic-erofs-combined-efi.img.gz

# 不保留配置升级
sysupgrade -n /tmp/openwrt-x86-64-generic-erofs-combined-efi.img.gz