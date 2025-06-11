# awesome-docker
整理搜集有趣好玩的docker项目

---
[toc]
---

## 💻 面板类

提供图形化界面，方便管理 Docker 环境或其他服务。

*   **Portainer**
    
    Portainer 是一款开源的 Docker 管理工具，它可以让用户通过 Web 界面管理 Docker 环境。它提供了一个友好的用户界面，可以让用户轻松管理容器、镜像和网络。Portainer 还支持多种操作系统，包括 Windows、macOS 和 Linux。它可以让用户快速部署和管理 Docker 环境，可以极大提高工作效率。
    
    *   **推荐镜像:** `portainer/portainer-ce:latest`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/portainer/portainer-ce](https://hub.docker.com/r/portainer/portainer-ce)
    *   **GitHub 链接:** [https://github.com/portainer/portainer](https://github.com/portainer/portainer)
    
*   **CasaOS**
    
    CasaOS 是一个以社区为中心，简单、易用、优雅的家庭云系统，旨在让所有人都能够轻松地管理他们的个人数据和智能家居设备。它提供了一个直观的 Web 界面，让用户可以轻松安装和管理各种 Docker 应用程序，类似于一个家庭服务器的操作系统。
    
    *   **推荐镜像:** `zimaboard/casaos` (通常直接安装在Linux系统上使用，但其核心功能也是基于Docker)
    *   **Docker Hub 链接:** [https://hub.docker.com/r/zimaboard/casaos](https://hub.docker.com/r/zimaboard/casaos)
    *   **GitHub 链接:** [https://github.com/IceWhaleTech/CasaOS](https://github.com/IceWhaleTech/CasaOS)
    
*   **Dashy**
    
    Dashy 是一个高度可定制的个人仪表板，用于集中管理你的各种应用程序和服务。你可以将其作为你的个人主页，快速访问你部署的各种 Docker 应用、书签、系统信息等。它支持多种小部件和主题，美观且实用。
    
    *   **推荐镜像:** `lissy93/dashy`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/lissy93/dashy](https://hub.docker.com/r/lissy93/dashy)
    *   **GitHub 链接:** [https://github.com/Lissy93/dashy](https://github.com/Lissy93/dashy)
    
*   **Homarr**
    
    Homarr 是另一个美观且功能丰富的自托管仪表板，旨在成为你所有服务的中心枢纽。它允许你添加服务快捷方式、应用程序状态监控、动态背景等，并提供丰富的定制选项，帮助你打造个性化的启动页。
    
    *   **推荐镜像:** `ghcr.io/ajnart/homarr`
    *   **Docker Hub 链接:** [https://github.com/ajnart/homarr/pkgs/container/homarr](https://github.com/ajnart/homarr/pkgs/container/homarr) (这是 GitHub Container Registry 的链接)
    *   **GitHub 链接:** [https://github.com/ajnart/homarr](https://github.com/ajnart/homarr)
    
*   **dpanel**
    
    dpanel 是一个轻量级、易于使用的 Docker 容器管理面板。它旨在提供一个简单直观的 Web 界面来管理 Docker 容器，包括查看日志、启动/停止/重启容器、查看容器状态等基本操作，适合对复杂功能要求不高的用户。
    
    *   **推荐镜像:** `ghcr.io/dpanel-io/dpanel` (或 `dpanel/dpanel` 如果官方有发布到 Docker Hub)
    *   **Docker Hub 链接:** [https://hub.docker.com/r/dpanel/dpanel](https://hub.docker.com/r/dpanel/dpanel)
    *   **GitHub 链接:** [https://github.com/donknap/dpanel](https://github.com/donknap/dpanel)

---

## 📜 脚本类

通常用于自动化任务、签到、数据抓取等。

*   **青龙 (qinglong)**
    
    青龙面板是一个支持多种脚本运行环境（如 Node.js, Python, Shell, Go, PHP）的自动化脚本管理面板，常用于定时执行各种薅羊毛、签到、数据采集等脚本。它提供 Web 界面，方便用户管理脚本、查看日志和配置定时任务。
    
    *   **推荐镜像:** `whyour/qinglong:latest`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/whyour/qinglong](https://hub.docker.com/r/whyour/qinglong)
    *   **GitHub 链接:** [https://github.com/whyour/qinglong](https://github.com/whyour/qinglong)
    
*   **签到类 (qiandao)**
    
    这类镜像通常包含或支持执行各种网站的自动化签到脚本，例如一些视频网站、论坛、网盘等。目的是帮助用户自动获取积分、会员权益或保持活跃。
    
    *   **推荐镜像:** `chishin/web-auto-sign-in` (一个例子，具体名称可能因脚本而异)
    *   **Docker Hub 链接:** [https://hub.docker.com/r/chishin/web-auto-sign-in](https://hub.docker.com/r/chishin/web-auto-sign-in)
    *   **GitHub 链接:** [https://github.com/chishin/web-auto-sign-in](https://github.com/chishin/web-auto-sign-in)
    
*   **自动化任务类**
    
    这类镜像包含了用于执行各种自动化任务的脚本，可以是爬虫、数据同步、文件清理等。例如，有些镜像可能集成了 Selenium 或 Puppeteer，用于模拟浏览器操作。
    
    *   **推荐镜像:** `jynneos/taskpilot` (一个通用的任务执行平台)
    *   **Docker Hub 链接:** [https://hub.docker.com/r/jynneos/taskpilot](https://hub.docker.com/r/jynneos/taskpilot)
    *   **GitHub 链接:** [https://github.com/Jynneos/taskpilot](https://github.com/Jynneos/taskpilot)
    

---

## ⬇️ 下载类

提供文件下载、管理和分享功能。

*   **qBittorrent**
    
    qBittorrent 是一个免费、开源的 BitTorrent 客户端，支持多种操作系统。通过 Docker 部署，可以轻松搭建一个高性能的下载服务器，支持 Web UI 远程管理，适合 24 小时挂机下载。
    
    *   **推荐镜像:** `linuxserver/qbittorrent`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/linuxserver/qbittorrent](https://hub.docker.com/r/linuxserver/qbittorrent)
    *   **GitHub 链接 (LinuxServer.io 官方维护):** [https://github.com/linuxserver/docker-qbittorrent](https://github.com/linuxserver/docker-qbittorrent)
    
*   **Transmission**
    
    Transmission 是一个轻量级的 BitTorrent 客户端，以其简洁的界面和低资源占用而闻名。通过 Docker 部署，可以搭建一个轻量级的下载服务器，同样支持 Web UI 远程管理。
    
    *   **推荐镜像:** `linuxserver/transmission`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/linuxserver/transmission](https://hub.docker.com/r/linuxserver/transmission)
    *   **GitHub 链接 (LinuxServer.io 官方维护):** [https://github.com/linuxserver/docker-transmission](https://github.com/linuxserver/docker-transmission)
    
*   **aria2-pro**
    
    aria2-pro 是一个功能强大的命令行下载工具 aria2 的增强版，支持 HTTP/HTTPS, FTP, SFTP, BitTorrent 和 Metalink。通常结合 Web UI 或面板（如 AriaNg）使用，可以实现高速下载和远程管理。
    
    *   **推荐镜像:** `p3terx/aria2-pro`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/p3terx/aria2-pro](https://hub.docker.com/r/p3terx/aria2-pro)
    *   **GitHub 链接:** [https://github.com/P3TERX/aria2-pro](https://github.com/P3TERX/aria2-pro)
    
*   **Cloudreve**
    
    Cloudreve 是一款支持多家云存储（如阿里云盘、OneDrive、又拍云、七牛云等）和本地存储的网盘系统。它提供统一的 Web 界面，可以实现文件上传、下载、分享、在线预览等功能，是自建个人或团队网盘的优秀选择。
    
    *   **推荐镜像:** `cloudreve/cloudreve:latest`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/cloudreve/cloudreve](https://hub.docker.com/r/cloudreve/cloudreve)
    *   **GitHub 链接:** [https://github.com/cloudreve/Cloudreve](https://github.com/cloudreve/Cloudreve)
    

---

## 🎬 影音类

用于媒体内容管理、播放和流媒体服务。

*   **EMBY**
    
    Emby 是一款流行的媒体服务器软件，它能将你的电影、电视节目、音乐、照片等媒体内容进行整理、索引和转码，并通过各种客户端（Web 浏览器、手机 App、智能电视、游戏机等）在任何设备上播放。
    
    *   **推荐镜像:** `emby/embyserver`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/emby/embyserver](https://hub.docker.com/r/emby/embyserver)
    *   **GitHub 链接 (Emby 官方构建相关仓库):** [https://github.com/MediaBrowser/Emby.Build](https://github.com/MediaBrowser/Emby.Build)
    
*   **Jellyfin**
    
    Jellyfin 是一个免费、开源的媒体系统，是 Emby 和 Plex 的一个开源替代品。它提供类似的功能，可以管理和流媒体你的媒体库，并且完全由社区维护，没有高级付费功能。
    *   **推荐镜像:** `jellyfin/jellyfin`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/jellyfin/jellyfin](https://hub.docker.com/r/jellyfin/jellyfin)
    *   **GitHub 链接:** [https://github.com/jellyfin/jellyfin](https://github.com/jellyfin/jellyfin)
    
*   **Plex**
    
    Plex 是一款功能强大的媒体服务器，与 Emby 和 Jellyfin 类似，可以将你的个人媒体库组织得井井有条，并流式传输到各种设备上。它拥有非常完善的客户端生态和用户界面。
    *   **推荐镜像:** `plexinc/pms-docker`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/plexinc/pms-docker](https://hub.docker.com/r/plexinc/pms-docker)
    *   **GitHub 链接 (官方维护的 Docker 配置):** [https://github.com/plexinc/pms-docker](https://github.com/plexinc/pms-docker)
    
*   **Navidrome**
    
    Navidrome 是一款现代的音乐流媒体服务器，用于自托管你的音乐收藏。它支持 Subsonic API，因此可以使用各种 Subsonic 客户端进行连接和播放。界面简洁美观，资源占用低。
    *   **推荐镜像:** `deluan/navidrome`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/deluan/navidrome](https://hub.docker.com/r/deluan/navidrome)
    *   **GitHub 链接:** [https://github.com/deluan/navidrome](https://github.com/deluan/navidrome)
    
*   **PhotoPrism**
    
    PhotoPrism 是一个人工智能驱动的私人照片管理系统。它可以自动对你的照片进行分类、标记、去重，并提供 Web 界面进行浏览、搜索和分享，是自建图片云盘的绝佳选择。
    *   **推荐镜像:** `photoprism/photoprism`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/photoprism/photoprism](https://hub.docker.com/r/photoprism/photoprism)
    *   **GitHub 链接:** [https://github.com/photoprism/photoprism](https://github.com/photoprism/photoprism)
    

---

## 🤖 自动化类

用于实现各种自动化任务，例如内容订阅、下载、文件处理等。

*   **bilibili-go (自动录制)**
    
    这类镜像通常包含用于 Bilibili 自动直播录制、弹幕存档、动态监控等功能的工具。具体实现可能基于不同的开源项目。
    
    *   **推荐镜像:** 寻找特定功能（如 `zhangh414/bilibili-live-monitor` 等），具体名称因项目而异。
    *   **Docker Hub 链接 (示例):** [https://hub.docker.com/r/zhangh414/bilibili-live-monitor](https://hub.docker.com/r/zhangh414/bilibili-live-monitor)
    *   **GitHub 链接 (示例):** [https://github.com/zhangh414/bilibili-live-monitor](https://github.com/zhangh414/bilibili-live-monitor)
    
*   **Radarr**
    
    Radarr 是一个用于自动化电影下载和管理的工具。它可以监控电影上映、自动搜索并下载高质量的电影文件，并与媒体服务器（如 Plex/Jellyfin/Emby）集成。
    *   **推荐镜像:** `linuxserver/radarr`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/linuxserver/radarr](https://hub.docker.com/r/linuxserver/radarr)
    *   **GitHub 链接 (LinuxServer.io 官方维护):** [https://github.com/linuxserver/docker-radarr](https://github.com/linuxserver/docker-radarr)
    
*   **Sonarr**
    
    Sonarr 与 Radarr 类似，但专注于电视剧的自动化下载和管理。它可以监控电视剧更新、自动搜索并下载最新剧集，并与媒体服务器集成。
    *   **推荐镜像:** `linuxserver/sonarr`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/linuxserver/sonarr](https://hub.docker.com/r/linuxserver/sonarr)
    *   **GitHub 链接 (LinuxServer.io 官方维护):** [https://github.com/linuxserver/docker-sonarr](https://github.com/linuxserver/docker-sonarr)
    
*   **Prowlarr**
    
    Prowlarr 是一个索引器管理器/代理，旨在与 Radarr、Sonarr、Lidarr 和 Readarr 等应用配合使用，管理和搜索各种索引器（如 Torrent 追踪器、Usenet 提供商），统一它们的搜索和下载功能。
    *   **推荐镜像:** `linuxserver/prowlarr`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/linuxserver/prowlarr](https://hub.docker.com/r/linuxserver/prowlarr)
    *   **GitHub 链接 (LinuxServer.io 官方维护):** [https://github.com/linuxserver/docker-prowlarr](https://github.com/linuxserver/docker-prowlarr)
    
*   **Lidarr**
    
    Lidarr 是一个音乐集管理和自动化下载工具，类似于 Radarr 和 Sonarr，但专注于音乐。它可以自动搜索、下载和管理你的音乐收藏。
    *   **推荐镜像:** `linuxserver/lidarr`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/linuxserver/lidarr](https://hub.docker.com/r/linuxserver/lidarr)
    *   **GitHub 链接 (LinuxServer.io 官方维护):** [https://github.com/linuxserver/docker-lidarr](https://github.com/linuxserver/docker-lidarr)
    
*   **Bazarr**
    
    Bazarr 是一个用于管理和下载电影和电视剧字幕的工具，与 Sonarr 和 Radarr 完美集成。它能自动搜索并下载缺失或更高质量的字幕。
    *   **推荐镜像:** `linuxserver/bazarr`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/linuxserver/bazarr](https://hub.docker.com/r/linuxserver/bazarr)
    *   **GitHub 链接 (LinuxServer.io 官方维护):** [https://github.com/linuxserver/docker-bazarr](https://github.com/linuxserver/docker-bazarr)
    
*   **RSSHub**
    
    RSSHub 是一个轻量、易于扩展的 RSS 生成器，可以为各种不提供 RSS 订阅源的内容（如微博、知乎、Bilibili 动态等）生成 RSS 订阅。结合 RSS 阅读器，可以方便地订阅和聚合信息。
    *   **推荐镜像:** `diygod/rsshub`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/diygod/rsshub](https://hub.docker.com/r/diygod/rsshub)
    *   **GitHub 链接:** [https://github.com/DIYgod/RSSHub](https://github.com/DIYgod/RSSHub)
    

---

## 🛠️ 实用工具类

提供各种提升效率、网络管理或系统监控的实用功能。

*   **SpeedTest (测速)**
    
    这类镜像通常提供一个 Web 界面，用于在你的 Docker 宿主机或网络内部进行网络速度测试，方便检测网络瓶颈。
    
    *   **推荐镜像:** `librespeed/speedtest`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/librespeed/speedtest](https://hub.docker.com/r/librespeed/speedtest)
    *   **GitHub 链接:** [https://github.com/librespeed/speedtest](https://github.com/librespeed/speedtest)
    
*   **Syncthing (同步)**
    
    Syncthing 是一个开源的去中心化文件同步工具。它可以让你在多台设备之间实时同步文件，而无需经过任何中心服务器。通过 Docker 部署，可以搭建一个私有的、安全的同步中心。
    *   **推荐镜像:** `linuxserver/syncthing`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/linuxserver/syncthing](https://hub.docker.com/r/linuxserver/syncthing)
    *   **GitHub 链接 (LinuxServer.io 官方维护):** [https://github.com/linuxserver/docker-syncthing](https://github.com/linuxserver/docker-syncthing)
    
*   **Heimdall (导航)**
    
    Heimdall 是一个简单而美观的导航页/仪表板，你可以将你常用的网站和自建服务添加到其中，作为你的浏览器主页或服务器管理入口。
    *   **推荐镜像:** `linuxserver/heimdall`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/linuxserver/heimdall](https://hub.docker.com/r/linuxserver/heimdall)
    *   **GitHub 链接 (LinuxServer.io 官方维护):** [https://github.com/linuxserver/docker-heimdall](https://github.com/linuxserver/docker-heimdall)
    
*   **Uptime Kuma (监控)**
    
    Uptime Kuma 是一个开源的自托管监控工具，可以监控你的网站、服务、API 等的运行状态，并在服务下线时通过多种方式（如邮件、Telegram、Discord 等）通知你。界面美观，功能强大。
    *   **推荐镜像:** `louislam/uptime-kuma`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/louislam/uptime-kuma](https://hub.docker.com/r/louislam/uptime-kuma)
    *   **GitHub 链接:** [https://github.com/louislam/uptime-kuma](https://github.com/louislam/uptime-kuma)
    
*   **Netdata (系统监控)**
    
    Netdata 是一个实时的、分布式性能监控工具，可以收集各种系统指标（CPU、内存、磁盘 I/O、网络等），并以交互式图表展示。通过 Docker 部署，可以轻松监控你的宿主机或容器性能。
    *   **推荐镜像:** `netdata/netdata`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/netdata/netdata](https://hub.docker.com/r/netdata/netdata)
    *   **GitHub 链接:** [https://github.com/netdata/netdata](https://github.com/netdata/netdata)
    
*   **WireGuard / OpenVPN (VPN 服务器)**
    
    这类镜像可以帮助你快速部署一个私有的 VPN 服务器。WireGuard 以其高性能和简洁而闻名，OpenVPN 则更为成熟和广泛兼容。自建 VPN 可以用于安全访问家庭网络、突破网络限制等。
    
    *   **推荐镜像 (WireGuard):** `linuxserver/wireguard`
    *   **Docker Hub 链接 (WireGuard):** [https://hub.docker.com/r/linuxserver/wireguard](https://hub.docker.com/r/linuxserver/wireguard)
    *   **GitHub 链接 (WireGuard - LinuxServer.io 官方维护):** [https://github.com/linuxserver/docker-wireguard](https://github.com/linuxserver/docker-wireguard)
    *   **推荐镜像 (OpenVPN):** `kylemanna/openvpn`
    *   **Docker Hub 链接 (OpenVPN):** [https://hub.docker.com/r/kylemanna/openvpn](https://hub.docker.com/r/kylemanna/openvpn)
    *   **GitHub 链接 (OpenVPN):** [https://github.com/kylemanna/docker-openvpn](https://github.com/kylemanna/docker-openvpn)
    
*   **AdGuard Home (广告过滤)**
    
    AdGuard Home 是一个全网络范围的广告和追踪器拦截 DNS 服务器。部署后，网络中所有设备的广告和追踪器都将被拦截，无需安装客户端软件，有效提升上网体验和隐私保护。
    
    *   **推荐镜像:** `adguard/adguardhome`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/adguard/adguardhome](https://hub.docker.com/r/adguard/adguardhome)
    *   **GitHub 链接:** [https://github.com/AdguardTeam/AdGuardHome](https://github.com/AdguardTeam/AdGuardHome)
    
*   **Vaultwarden (密码管理器)**
    
    Vaultwarden (以前叫 Bitwarden_RS) 是一个用 Rust 编写的 Bitwarden 服务器的兼容实现，资源占用极低。你可以自托管你的密码管理器，确保密码数据完全掌握在自己手中，并通过 Bitwarden 官方客户端进行访问。
    
    *   **推荐镜像:** `vaultwarden/server`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/vaultwarden/server](https://hub.docker.com/r/vaultwarden/server)
    *   **GitHub 链接:** [https://github.com/dani-garcia/vaultwarden](https://github.com/dani-garcia/vaultwarden)
    

---

## 📚 电子书类

用于电子书管理、阅读和分享。

*   **BookBrowser**
    
    BookBrowser 是一个自托管的电子书阅读器和管理工具，提供 Web 界面，方便你在浏览器中阅读和管理你的电子书。
    *   **推荐镜像:** `ghcr.io/sebt3/bookbrowser`
    *   **Docker Hub 链接:** [https://github.com/sebt3/bookbrowser/pkgs/container/bookbrowser](https://github.com/sebt3/bookbrowser/pkgs/container/bookbrowser) (GitHub Container Registry)
    *   **GitHub 链接:** [https://github.com/sebt3/bookbrowser](https://github.com/sebt3/bookbrowser)
    
*   **Calibre-Web**
    
    Calibre-Web 是 Calibre (一个强大的电子书管理软件) 的 Web 界面。它允许你通过浏览器访问和管理你的 Calibre 电子书库，进行在线阅读、搜索和下载。
    *   **推荐镜像:** `linuxserver/calibre-web`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/linuxserver/calibre-web](https://hub.docker.com/r/linuxserver/calibre-web)
    *   **GitHub 链接 (LinuxServer.io 官方维护):** [https://github.com/linuxserver/docker-calibre-web](https://github.com/linuxserver/docker-calibre-web)
    
*   **TaleBook**
    
    TaleBook 是一个简洁的私人云端电子书库，提供 Web 界面，支持多种电子书格式的上传、下载、在线阅读和管理。
    *   **推荐镜像:** `talebook/talebook`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/talebook/talebook](https://hub.docker.com/r/talebook/talebook)
    *   **GitHub 链接:** [https://github.com/talebook/talebook](https://github.com/talebook/talebook)
    

---

## ☁️ 网盘/文件管理类

自建个人网盘、文件共享或同步服务。

*   **Nextcloud**
    
    Nextcloud 是一个功能强大的自托管云存储和协作平台。它提供文件同步与共享、日历、联系人、任务管理、视频通话等多种功能，是 Dropbox 和 Google Drive 的开源替代品。
    *   **推荐镜像:** `nextcloud` (通常配合数据库镜像使用)
    *   **Docker Hub 链接:** [https://hub.docker.com/_/nextcloud](https://hub.docker.com/_/nextcloud)
    *   **GitHub 链接:** [https://github.com/nextcloud/server](https://github.com/nextcloud/server)
    
*   **ownCloud**
    
    ownCloud 是另一个开源的自托管云存储解决方案，与 Nextcloud 类似，提供文件同步、共享和协作功能。
    *   **推荐镜像:** `owncloud/server`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/owncloud/server](https://hub.docker.com/r/owncloud/server)
    *   **GitHub 链接:** [https://github.com/owncloud/core](https://github.com/owncloud/core)
    
*   **Filebrowser**
    
    Filebrowser 提供一个 Web 界面，让你可以通过浏览器轻松管理服务器上的文件。它轻量、简单，适合作为个人文件服务器或小型共享盘。
    *   **推荐镜像:** `filebrowser/filebrowser`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/filebrowser/filebrowser](https://hub.docker.com/r/filebrowser/filebrowser)
    *   **GitHub 链接:** [https://github.com/filebrowser/filebrowser](https://github.com/filebrowser/filebrowser)
    

---

## 🌐 博客/建站类

用于搭建个人博客、网站或内容管理系统。

*   **WordPress**
    
    WordPress 是世界上最流行的内容管理系统（CMS），用于搭建博客、网站、电子商务网站等。通过 Docker 部署，可以快速搭建一个 WordPress 站点。
    *   **推荐镜像:** `wordpress` (通常配合数据库镜像使用)
    *   **Docker Hub 链接:** [https://hub.docker.com/_/wordpress](https://hub.docker.com/_/wordpress)
    *   **GitHub 链接 (官方 Docker 仓库):** [https://github.com/docker-library/wordpress](https://github.com/docker-library/wordpress)
    
*   **Ghost**
    
    Ghost 是一个现代、开源的专业发布平台，专注于博客和媒体发布。它提供简洁的写作界面和快速的性能。
    *   **推荐镜像:** `ghost`
    *   **Docker Hub 链接:** [https://hub.docker.com/_/ghost](https://hub.docker.com/_/ghost)
    *   **GitHub 链接:** [https://github.com/TryGhost/Ghost](https://github.com/TryGhost/Ghost)
    
*   **Typecho**
    
    Typecho 是一个轻量级、开源的博客程序，速度快、资源占用低，适合搭建个人博客。
    *   **推荐镜像:** `joyqi/typecho` (社区维护镜像)
    *   **Docker Hub 链接:** [https://hub.docker.com/r/joyqi/typecho](https://hub.docker.com/r/joyqi/typecho)
    *   **GitHub 链接:** [https://github.com/typecho/typecho](https://github.com/typecho/typecho)
    
*   **Wiki.js**
    
    Wiki.js 是一个现代化、功能强大的 Wiki 引擎，用于创建和管理知识库、文档或团队 Wiki。
    *   **推荐镜像:** `requarks/wiki`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/requarks/wiki](https://hub.docker.com/r/requarks/wiki)
    *   **GitHub 链接:** [https://github.com/Requarks/wiki](https://github.com/Requarks/wiki)
    

---

## 🎮 游戏类

一些与游戏相关的服务器或工具。

*   **Minecraft Server**
    
    你可以部署一个 Minecraft 服务器，与朋友一起玩游戏。有很多社区维护的镜像提供了不同的 Minecraft 版本或 Mod 包。
    *   **推荐镜像:** `itzg/minecraft-server`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/itzg/minecraft-server](https://hub.docker.com/r/itzg/minecraft-server)
    *   **GitHub 链接:** [https://github.com/itzg/docker-minecraft-server](https://github.com/itzg/docker-minecraft-server)
    
*   **GameStream (示例)**
    
    例如 Sunshine，一个开源的 GameStream 主机端，可以让你从非 NVIDIA GPU 设备串流游戏。
    *   **推荐镜像:** `lsh340/sunshine`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/lsh340/sunshine](https://hub.docker.com/r/lsh340/sunshine)
    *   **GitHub 链接:** [https://github.com/lsh340/sunshine-docker](https://github.com/lsh340/sunshine-docker) (针对 Docker 的打包)
    

---

## ✉️ 通信类

用于搭建私有聊天、论坛或邮件服务。

*   **Mattermost**
    
    Mattermost 是一个开源的团队协作平台，是 Slack 的开源替代品。它支持群聊、私聊、文件共享、集成等功能，适合团队内部沟通。
    *   **推荐镜像:** `mattermost/mattermost-team-edition`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/mattermost/mattermost-team-edition](https://hub.docker.com/r/mattermost/mattermost-team-edition)
    *   **GitHub 链接:** [https://github.com/mattermost/mattermost-server](https://github.com/mattermost/mattermost-server)
    
*   **Gitea**
    
    Gitea 是一个轻量级的自托管 Git 服务，功能类似于 GitHub 或 GitLab。你可以用它来搭建自己的代码仓库，进行版本控制。
    *   **推荐镜像:** `gitea/gitea`
    *   **Docker Hub 链接:** [https://hub.docker.com/r/gitea/gitea](https://hub.docker.com/r/gitea/gitea)
    *   **GitHub 链接:** [https://github.com/go-gitea/gitea](https://github.com/go-gitea/gitea)
    
*   **Discourse**
    
    Discourse 是一个现代化、开源的论坛软件，专注于提高讨论的质量和参与度。
    *   **推荐镜像:** 通常推荐使用官方的 Docker 安装脚本，而不是简单的 `docker run`。
    *   **官方安装指南 (含Docker):** [https://github.com/discourse/discourse_docker](https://github.com/discourse/discourse_docker) (这是一个完整的 Dockerized 部署方案，而非单个应用镜像的 GitHub 仓库)
