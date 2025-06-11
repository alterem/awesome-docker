[返回首页](../README.md)

# 🤖 自动化类

用于实现各种自动化任务，例如内容订阅、下载、文件处理等。

### bilibili-go
    
这类镜像通常包含用于 Bilibili 自动直播录制、弹幕存档、动态监控等功能的工具。具体实现可能基于不同的开源项目。

*   **推荐镜像:** 寻找特定功能（如 `zhangh414/bilibili-live-monitor` 等），具体名称因项目而异。
*   **Docker Hub 链接 (示例):** [https://hub.docker.com/r/zhangh414/bilibili-live-monitor](https://hub.docker.com/r/zhangh414/bilibili-live-monitor)
*   **GitHub 链接 (示例):** [https://github.com/zhangh414/bilibili-live-monitor](https://github.com/zhangh414/bilibili-live-monitor)

### Radarr

Radarr 是一个用于自动化电影下载和管理的工具。它可以监控电影上映、自动搜索并下载高质量的电影文件，并与媒体服务器（如 Plex/Jellyfin/Emby）集成。
*   **推荐镜像:** `linuxserver/radarr`
*   **Docker Hub 链接:** [https://hub.docker.com/r/linuxserver/radarr](https://hub.docker.com/r/linuxserver/radarr)
*   **GitHub 链接 (LinuxServer.io 官方维护):** [https://github.com/linuxserver/docker-radarr](https://github.com/linuxserver/docker-radarr)

### Sonarr

Sonarr 与 Radarr 类似，但专注于电视剧的自动化下载和管理。它可以监控电视剧更新、自动搜索并下载最新剧集，并与媒体服务器集成。
*   **推荐镜像:** `linuxserver/sonarr`
*   **Docker Hub 链接:** [https://hub.docker.com/r/linuxserver/sonarr](https://hub.docker.com/r/linuxserver/sonarr)
*   **GitHub 链接 (LinuxServer.io 官方维护):** [https://github.com/linuxserver/docker-sonarr](https://github.com/linuxserver/docker-sonarr)

### Prowlarr

Prowlarr 是一个索引器管理器/代理，旨在与 Radarr、Sonarr、Lidarr 和 Readarr 等应用配合使用，管理和搜索各种索引器（如 Torrent 追踪器、Usenet 提供商），统一它们的搜索和下载功能。
*   **推荐镜像:** `linuxserver/prowlarr`
*   **Docker Hub 链接:** [https://hub.docker.com/r/linuxserver/prowlarr](https://hub.docker.com/r/linuxserver/prowlarr)
*   **GitHub 链接 (LinuxServer.io 官方维护):** [https://github.com/linuxserver/docker-prowlarr](https://github.com/linuxserver/docker-prowlarr)

### Lidarr

Lidarr 是一个音乐集管理和自动化下载工具，类似于 Radarr 和 Sonarr，但专注于音乐。它可以自动搜索、下载和管理你的音乐收藏。
*   **推荐镜像:** `linuxserver/lidarr`
*   **Docker Hub 链接:** [https://hub.docker.com/r/linuxserver/lidarr](https://hub.docker.com/r/linuxserver/lidarr)
*   **GitHub 链接 (LinuxServer.io 官方维护):** [https://github.com/linuxserver/docker-lidarr](https://github.com/linuxserver/docker-lidarr)

### Bazarr

Bazarr 是一个用于管理和下载电影和电视剧字幕的工具，与 Sonarr 和 Radarr 完美集成。它能自动搜索并下载缺失或更高质量的字幕。
*   **推荐镜像:** `linuxserver/bazarr`
*   **Docker Hub 链接:** [https://hub.docker.com/r/linuxserver/bazarr](https://hub.docker.com/r/linuxserver/bazarr)
*   **GitHub 链接 (LinuxServer.io 官方维护):** [https://github.com/linuxserver/docker-bazarr](https://github.com/linuxserver/docker-bazarr)

### RSSHub

RSSHub 是一个轻量、易于扩展的 RSS 生成器，可以为各种不提供 RSS 订阅源的内容（如微博、知乎、Bilibili 动态等）生成 RSS 订阅。结合 RSS 阅读器，可以方便地订阅和聚合信息。
*   **推荐镜像:** `diygod/rsshub`
*   **Docker Hub 链接:** [https://hub.docker.com/r/diygod/rsshub](https://hub.docker.com/r/diygod/rsshub)
*   **GitHub 链接:** [https://github.com/DIYgod/RSSHub](https://github.com/DIYgod/RSSHub)