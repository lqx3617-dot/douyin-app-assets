# APP 运行时资源

这个仓库只放 APK 首次启动要下载的大文件，不放源码。

## assets-v1

| 文件 | 大小 | 说明 |
|---|---|---|
| rootfs_v4.tar.gz | 395MB | 精简 Ubuntu 环境（aarch64），解压约 1.03GB |

## 用途

配合 douyin-autoreply 的 Android 分体版使用。APK 本体 40MB，首次启动下载这里的 rootfs。

下载走 GitHub Release，支持 Range 断点续传。
