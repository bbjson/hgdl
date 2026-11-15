# 红果下载器（hgdl）

红果短剧桌面端下载器。**本仓库只放安装包**，不含任何源码。

> 页面底部的 `Source code (zip/tar.gz)` 是 GitHub 对每个 tag 自动生成的归档，
> 里面只有这个 README（4 KB），没有任何代码，也无法关闭。

## 下载

| 平台 | 镜像（推荐，快约 5 倍） | 直连 |
|---|---|---|
| Ubuntu / Debian x64 | [deb · 镜像](https://gh-proxy.com/https://github.com/bbjson/hgdl/releases/download/v1.0.0/hgdl_1.0.0_amd64.deb) | [deb · GitHub](https://github.com/bbjson/hgdl/releases/download/v1.0.0/hgdl_1.0.0_amd64.deb) |
| Windows 10/11 x64 | [exe · 镜像](https://gh-proxy.com/https://github.com/bbjson/hgdl/releases/download/v1.0.0/hgdl-1.0.0-setup.exe) | [exe · GitHub](https://github.com/bbjson/hgdl/releases/download/v1.0.0/hgdl-1.0.0-setup.exe) |

镜像挂掉时可以换这些前缀（用法相同，前缀 + GitHub 地址）：

```
https://gh-proxy.com/     https://ghfast.top/
https://ghproxy.cc/       https://gh-proxy.org/
```

### 安装

- Linux：`sudo apt install ./hgdl_1.0.0_amd64.deb`，然后运行 `hgdl`
- Windows：双击 `hgdl-1.0.0-setup.exe`（用户级安装，不需要管理员）

两个包都内置 Python 3.12 + PySide6(Qt6) + cryptography，**目标机不需要安装 Python 或任何依赖**。

### 校验

```
hgdl_1.0.0_amd64.deb   1656eac9d245a44eb9b72076084d515b6046e75c03e13a967ce1b068e8b77b91
hgdl-1.0.0-setup.exe   a209e4d2bc8cbcc3afe6b7c2068314b00535ab3c57164cc50946ba71ef307f17
```

下载目录：`~/Videos/红果短剧/<剧名>/第NNN集.mp4`
