# ⬇️ 下载类

提供文件下载、管理和分享功能。

### qBittorrent
    
qBittorrent 是一个免费、开源的 BitTorrent 客户端，支持多种操作系统。通过 Docker 部署，可以轻松搭建一个高性能的下载服务器，支持 Web UI 远程管理，适合 24 小时挂机下载。

*   **推荐镜像:** `linuxserver/qbittorrent`
*   **Docker Hub 链接:** [https://hub.docker.com/r/linuxserver/qbittorrent](https://hub.docker.com/r/linuxserver/qbittorrent)
*   **GitHub 链接 (LinuxServer.io 官方维护):** [https://github.com/linuxserver/docker-qbittorrent](https://github.com/linuxserver/docker-qbittorrent)

### Transmission

Transmission 是一个轻量级的 BitTorrent 客户端，以其简洁的界面和低资源占用而闻名。通过 Docker 部署，可以搭建一个轻量级的下载服务器，同样支持 Web UI 远程管理。

*   **推荐镜像:** `linuxserver/transmission`
*   **Docker Hub 链接:** [https://hub.docker.com/r/linuxserver/transmission](https://hub.docker.com/r/linuxserver/transmission)
*   **GitHub 链接 (LinuxServer.io 官方维护):** [https://github.com/linuxserver/docker-transmission](https://github.com/linuxserver/docker-transmission)

### aria2-pro

aria2-pro 是一个功能强大的命令行下载工具 aria2 的增强版，支持 HTTP/HTTPS, FTP, SFTP, BitTorrent 和 Metalink。通常结合 Web UI 或面板（如 AriaNg）使用，可以实现高速下载和远程管理。

*   **推荐镜像:** `p3terx/aria2-pro`
*   **Docker Hub 链接:** [https://hub.docker.com/r/p3terx/aria2-pro](https://hub.docker.com/r/p3terx/aria2-pro)
*   **GitHub 链接:** [https://github.com/P3TERX/aria2-pro](https://github.com/P3TERX/aria2-pro)

### Cloudreve

Cloudreve 是一款支持多家云存储（如阿里云盘、OneDrive、又拍云、七牛云等）和本地存储的网盘系统。它提供统一的 Web 界面，可以实现文件上传、下载、分享、在线预览等功能，是自建个人或团队网盘的优秀选择。

*   **推荐镜像:** `cloudreve/cloudreve:latest`
*   **Docker Hub 链接:** [https://hub.docker.com/r/cloudreve/cloudreve](https://hub.docker.com/r/cloudreve/cloudreve)
*   **GitHub 链接:** [https://github.com/cloudreve/Cloudreve](https://github.com/cloudreve/Cloudreve)