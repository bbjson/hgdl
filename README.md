# 红果下载器（hgdl）

红果短剧桌面端下载器。**本仓库只放安装包**，不含任何源码。

> 页面底部的 `Source code (zip/tar.gz)` 是 GitHub 对每个 tag 自动生成的归档，
> 里面只有这个 README（4 KB），没有任何代码，也无法关闭。

## 下载

| 平台 | 镜像（推荐，快约 5 倍） | 直连 |
|---|---|---|
| Ubuntu / Debian x64 | [deb · 镜像](https://gh-proxy.com/https://github.com/bbjson/hgdl/releases/download/v0.4.1/hgdl_0.4.1_amd64.deb) | [deb · GitHub](https://github.com/bbjson/hgdl/releases/download/v0.4.1/hgdl_0.4.1_amd64.deb) |
| Windows 10/11 x64 | [exe · 镜像](https://gh-proxy.com/https://github.com/bbjson/hgdl/releases/download/v0.4.1/hgdl-0.4.1-setup.exe) | [exe · GitHub](https://github.com/bbjson/hgdl/releases/download/v0.4.1/hgdl-0.4.1-setup.exe) |

镜像挂掉时可以换这些前缀（用法相同，前缀 + GitHub 地址）：

```
https://gh-proxy.com/     https://ghfast.top/
https://ghproxy.cc/       https://gh-proxy.org/
```

### 安装

- Linux：`sudo apt install ./hgdl_0.4.1_amd64.deb`，然后运行 `hgdl`
- Windows：双击 `hgdl-0.4.1-setup.exe`（用户级安装，不需要管理员）

两个包都内置 Python 3.12 + PySide6(Qt6) + cryptography，**目标机不需要安装 Python 或任何依赖**。

### 校验

```
hgdl_0.4.1_amd64.deb   859ab8653da63070545d885f58d46de8a84226ff7691bd9ce589c0c2f4fb1b43
hgdl-0.4.1-setup.exe   13cc8be5acf9855e80582d9df2411cd11b39f7f3697420e526cf5ed455828931
```

下载目录：`~/Videos/红果短剧/<剧名>/第NNN集.mp4`
