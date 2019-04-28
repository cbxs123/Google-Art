# Google-Art （翻墙是一种艺术）

> [科学上网汇总-190425更新](https://ysai.work/2019/03/02/科学上网/)
> **[参考GFWdata](https://github.com/wcmbeta/GFWdata)**

免费版
----
## 1、蓝灯(500M/月免费)  [官网](https://getlantern.org/zh_CN/index.html)  [Github](https://github.com/getlantern/lantern/releases/tag/latest)
- [Win客户端](https://raw.githubusercontent.com/getlantern/lantern-binaries/master/lantern-installer.exe)
- [Mac客户端](https://raw.githubusercontent.com/getlantern/lantern-binaries/master/lantern-installer.dmg)
- [Ubuntu客户端](https://raw.githubusercontent.com/getlantern/lantern-binaries/master/lantern-installer-64-bit.deb)
- [Android客户端](https://raw.githubusercontent.com/getlantern/lantern-binaries/master/lantern-installer.apk)

## 2、Windscribe(10G/月免费)  [官网](https://windscribe.com/) 注册可能翻墙
- [Win客户端](https://raw.githubusercontent.com/cbxs123/Google-Art/master/Windscribe/Windscribe.exe)
- [Mac客户端](https://raw.githubusercontent.com/cbxs123/Google-Art/master/Windscribe/Windscribe.dmg)
- [Linux客户端](https://windscribe.com/guides/linux)
- [Android客户端](https://raw.githubusercontent.com/cbxs123/Google-Art/master/Windscribe/Windscribe2-130.apk)
- [Google插件](https://windscribe.com/install/extension/chrome)

自建服务器
----
## 1、[ssr](https://github.com/shadowsocksrr/shadowsocksr-csharp/releases)
### 服务端

```
wget --no-check-certificate https://raw.githubusercontent.com/cbxs123/Google-Art/master/ssr/bbr.sh && chmod +x bbr.sh && ./bbr.sh 
wget "https://github.com/chiakge/Linux-NetSpeed/raw/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh
wget -N --no-check-certificate https://raw.githubusercontent.com/cbxs123/Google-Art/master/ssr/ssr.sh && chmod +x ssr.sh && bash ssr.sh 
```

### 客户端

- [Win客户端](https://github.com/shadowsocksrr/shadowsocksr-csharp/releases/download/4.9.0/ShadowsocksR-win-4.9.0.zip)
- [Mac客户端](https://github.com/qinyuhang/ShadowsocksX-NG-R/releases/download/1.4.3-R8-build3/ShadowsocksX-NG-R8.dmg)
- [Linux客户端](https://github.com/erguotou520/electron-ssr/releases/download/v0.2.6/electron-ssr-0.2.6.deb)
- [Android客户端](https://github.com/shadowsocksrr/shadowsocksr-android/releases/download/3.5.4/shadowsocksr-android-3.5.4.apk)

## 2、[v2ray](https://github.com/v2ray/v2ray-core/releases)

### 服务端

```
wget --no-check-certificate https://raw.githubusercontent.com/cbxs123/Google-Art/master/ssr/bbr.sh && chmod +x bbr.sh && ./bbr.sh 
bash <(curl -s -L https://raw.githubusercontent.com/cbxs123/Google-Art/master/v2ray/v2ray.sh) 
```

### 客户端
- [Win内核](https://github.com/v2ray/v2ray-core/releases)+[Win图形界面](https://github.com/2dust/v2rayN/releases)
- [Android客户端](https://github.com/2dust/v2rayNG/releases/download/0.5.1/app-universal-release.apk)

## 3、[Brook](https://github.com/txthinking/brook/releases)

### 服务端

```
wget --no-check-certificate https://raw.githubusercontent.com/cbxs123/Google-Art/master/ssr/bbr.sh && chmod +x bbr.sh && ./bbr.sh 
wget -N --no-check-certificate https://raw.githubusercontent.com/cbxs123/Google-Art/master/brook/brook.sh && chmod +x brook.sh && bash brook.sh
```

### 客户端

- [Win客户端](https://github.com/txthinking/brook/releases/download/v20190401/brook_windows_amd64.exe)+[UI](https://raw.githubusercontent.com/cbxs123/Google-Art/master/brook/Brook_Tools.exe)
- [Mac客户端](https://github.com/txthinking/brook/releases/download/v20190401/Brook.dmg)
- [Linux客户端](https://github.com/txthinking/brook/releases/download/v20190401/brook_linux_arm64)
- [Android客户端](https://github.com/txthinking/brook/releases/download/v20190401/Brook.apk)

## 4、[WireGuard](https://www.atrandys.com/2018/1345.html)

### 服务端

```
wget https://raw.githubusercontent.com/atrandys/wireguard/master/wireguard_install_ubuntu.sh && chmod +x wireguard_install_ubuntu.sh && ./wireguard_install_ubuntu.sh
```

### 客户端

- [Win1.4](https://raw.githubusercontent.com/cbxs123/Google-Art/master/wireguard/TunSafe-1.4.exe)+[Win1.5](https://raw.githubusercontent.com/cbxs123/Google-Art/master/wireguard/TunSafe-1.5-rc2.exe)
- [Mac+Linux](https://raw.githubusercontent.com/cbxs123/Google-Art/master/wireguard/1.pdf)
- [Android客户端](https://raw.githubusercontent.com/cbxs123/Google-Art/master/wireguard/TunSafe-Android-Build4-2019-02-19.apk)



