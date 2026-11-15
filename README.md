# 红果下载器（hgdl）

红果短剧桌面端下载器。**本仓库只放安装包**，不含任何源码。

## 下载

到 [Releases](../../releases/latest) 页面下载：

| 平台 | 文件 |
|---|---|
| Ubuntu / Debian x64 | `hgdl_0.4.1_amd64.deb` |
| Windows 10/11 x64 | `hgdl-0.4.1-setup.exe` |

- Linux：`sudo apt install ./hgdl_0.4.1_amd64.deb`，然后运行 `hgdl`
- Windows：双击 setup.exe（用户级安装，不需要管理员）

两个包都内置 Python 3.12 + PySide6(Qt6) + cryptography，**目标机不需要安装 Python 或任何依赖**。

下载目录：`~/Videos/红果短剧/<剧名>/第NNN集.mp4`
