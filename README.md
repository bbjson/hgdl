# 红果下载器（hgdl）

红果短剧桌面端下载器。**本仓库只放安装包**，不含任何源码。

> 页面底部的 `Source code (zip/tar.gz)` 是 GitHub 对每个 tag 自动生成的归档，
> 里面只有这个 README（4 KB），没有任何代码，也无法关闭。

## 下载

| 平台 | 镜像（推荐，快约 5 倍） | 直连 |
|---|---|---|
| Ubuntu / Debian x64 | [deb · 镜像](https://gh-proxy.com/https://github.com/bbjson/hgdl/releases/download/v0.4.3/hgdl_0.4.3_amd64.deb) | [deb · GitHub](https://github.com/bbjson/hgdl/releases/download/v0.4.3/hgdl_0.4.3_amd64.deb) |
| Windows 10/11 x64 | [exe · 镜像](https://gh-proxy.com/https://github.com/bbjson/hgdl/releases/download/v0.4.3/hgdl-0.4.3-setup.exe) | [exe · GitHub](https://github.com/bbjson/hgdl/releases/download/v0.4.3/hgdl-0.4.3-setup.exe) |

镜像挂掉时可以换这些前缀（用法相同，前缀 + GitHub 地址）：

```
https://gh-proxy.com/     https://ghfast.top/
https://ghproxy.cc/       https://gh-proxy.org/
```

### 安装

- Linux：`sudo apt install ./hgdl_0.4.3_amd64.deb`，然后运行 `hgdl`
- Windows：双击 `hgdl-0.4.3-setup.exe`（用户级安装，不需要管理员）

两个包都内置 Python 3.12 + PySide6(Qt6) + cryptography，**目标机不需要安装 Python 或任何依赖**。

### 校验

```
hgdl_0.4.3_amd64.deb   caaf0c1decdfbdf31e74a9efb95e3b2c718767124c94e3a07c83cf7ee6f57a1d
hgdl-0.4.3-setup.exe   620a23006e19f66d1d8dae4cd4df82b129231e551a401ba0ce19cdeaaf4043e0
```

下载目录：`~/Videos/红果短剧/<剧名>/第NNN集.mp4`
