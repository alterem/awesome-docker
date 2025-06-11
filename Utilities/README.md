# 🛠️ 实用工具类

提供各种提升效率、网络管理或系统监控的实用功能。

### SpeedTest
    
这类镜像通常提供一个 Web 界面，用于在你的 Docker 宿主机或网络内部进行网络速度测试，方便检测网络瓶颈。

*   **推荐镜像:** `librespeed/speedtest`
*   **Docker Hub 链接:** [https://hub.docker.com/r/librespeed/speedtest](https://hub.docker.com/r/librespeed/speedtest)
*   **GitHub 链接:** [https://github.com/librespeed/speedtest](https://github.com/librespeed/speedtest)

### Syncthing

Syncthing 是一个开源的去中心化文件同步工具。它可以让你在多台设备之间实时同步文件，而无需经过任何中心服务器。通过 Docker 部署，可以搭建一个私有的、安全的同步中心。
*   **推荐镜像:** `linuxserver/syncthing`
*   **Docker Hub 链接:** [https://hub.docker.com/r/linuxserver/syncthing](https://hub.docker.com/r/linuxserver/syncthing)
*   **GitHub 链接 (LinuxServer.io 官方维护):** [https://github.com/linuxserver/docker-syncthing](https://github.com/linuxserver/docker-syncthing)

### Heimdall

Heimdall 是一个简单而美观的导航页/仪表板，你可以将你常用的网站和自建服务添加到其中，作为你的浏览器主页或服务器管理入口。
*   **推荐镜像:** `linuxserver/heimdall`
*   **Docker Hub 链接:** [https://hub.docker.com/r/linuxserver/heimdall](https://hub.docker.com/r/linuxserver/heimdall)
*   **GitHub 链接 (LinuxServer.io 官方维护):** [https://github.com/linuxserver/docker-heimdall](https://github.com/linuxserver/docker-heimdall)

### Uptime Kuma

Uptime Kuma 是一个开源的自托管监控工具，可以监控你的网站、服务、API 等的运行状态，并在服务下线时通过多种方式（如邮件、Telegram、Discord 等）通知你。界面美观，功能强大。
*   **推荐镜像:** `louislam/uptime-kuma`
*   **Docker Hub 链接:** [https://hub.docker.com/r/louislam/uptime-kuma](https://hub.docker.com/r/louislam/uptime-kuma)
*   **GitHub 链接:** [https://github.com/louislam/uptime-kuma](https://github.com/louislam/uptime-kuma)

### Netdata

Netdata 是一个实时的、分布式性能监控工具，可以收集各种系统指标（CPU、内存、磁盘 I/O、网络等），并以交互式图表展示。通过 Docker 部署，可以轻松监控你的宿主机或容器性能。
*   **推荐镜像:** `netdata/netdata`
*   **Docker Hub 链接:** [https://hub.docker.com/r/netdata/netdata](https://hub.docker.com/r/netdata/netdata)
*   **GitHub 链接:** [https://github.com/netdata/netdata](https://github.com/netdata/netdata)

### WireGuard / OpenVPN

这类镜像可以帮助你快速部署一个私有的 VPN 服务器。WireGuard 以其高性能和简洁而闻名，OpenVPN 则更为成熟和广泛兼容。自建 VPN 可以用于安全访问家庭网络、突破网络限制等。

*   **推荐镜像 (WireGuard):** `linuxserver/wireguard`
*   **Docker Hub 链接 (WireGuard):** [https://hub.docker.com/r/linuxserver/wireguard](https://hub.docker.com/r/linuxserver/wireguard)
*   **GitHub 链接 (WireGuard - LinuxServer.io 官方维护):** [https://github.com/linuxserver/docker-wireguard](https://github.com/linuxserver/docker-wireguard)
*   **推荐镜像 (OpenVPN):** `kylemanna/openvpn`
*   **Docker Hub 链接 (OpenVPN):** [https://hub.docker.com/r/kylemanna/openvpn](https://hub.docker.com/r/kylemanna/openvpn)
*   **GitHub 链接 (OpenVPN):** [https://github.com/kylemanna/docker-openvpn](https://github.com/kylemanna/docker-openvpn)

### AdGuard Home

AdGuard Home 是一个全网络范围的广告和追踪器拦截 DNS 服务器。部署后，网络中所有设备的广告和追踪器都将被拦截，无需安装客户端软件，有效提升上网体验和隐私保护。

*   **推荐镜像:** `adguard/adguardhome`
*   **Docker Hub 链接:** [https://hub.docker.com/r/adguard/adguardhome](https://hub.docker.com/r/adguard/adguardhome)
*   **GitHub 链接:** [https://github.com/AdguardTeam/AdGuardHome](https://github.com/AdguardTeam/AdGuardHome)

### Vaultwarden

Vaultwarden (以前叫 Bitwarden_RS) 是一个用 Rust 编写的 Bitwarden 服务器的兼容实现，资源占用极低。你可以自托管你的密码管理器，确保密码数据完全掌握在自己手中，并通过 Bitwarden 官方客户端进行访问。

*   **推荐镜像:** `vaultwarden/server`
*   **Docker Hub 链接:** [https://hub.docker.com/r/vaultwarden/server](https://hub.docker.com/r/vaultwarden/server)
*   **GitHub 链接:** [https://github.com/dani-garcia/vaultwarden](https://github.com/dani-garcia/vaultwarden)