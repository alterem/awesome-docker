[返回首页](../README.md)

# ✉️ 通信类

用于搭建私有聊天、论坛或邮件服务。

### Mattermost
    
Mattermost 是一个开源的团队协作平台，是 Slack 的开源替代品。它支持群聊、私聊、文件共享、集成等功能，适合团队内部沟通。

*   **推荐镜像:** `mattermost/mattermost-team-edition`
*   **Docker Hub 链接:** [https://hub.docker.com/r/mattermost/mattermost-team-edition](https://hub.docker.com/r/mattermost/mattermost-team-edition)
*   **GitHub 链接:** [https://github.com/mattermost/mattermost-server](https://github.com/mattermost/mattermost-server)

### Discourse

Discourse 是一个现代化、开源的论坛软件，专注于提高讨论的质量和参与度。

*   **推荐镜像:** 通常推荐使用官方的 Docker 安装脚本，而不是简单的 `docker run`。
*   **官方安装指南 (含Docker):** [https://github.com/discourse/discourse_docker](https://github.com/discourse/discourse_docker) (这是一个完整的 Dockerized 部署方案，而非单个应用镜像的 GitHub 仓库)

### MailcowDockerized

mailcow-dockerized 是一个功能齐全的邮件服务器套件，包含邮件服务器、反垃圾邮件、反病毒、Webmail 等组件，全部通过 Docker 容器部署。

*   **推荐镜像:** `mailcow/mailcow-dockerized` (通过官方脚本部署)
*   **Docker Hub 链接:** [https://hub.docker.com/r/mailcow/mailcow-dockerized](https://hub.docker.com/r/mailcow/mailcow-dockerized)
*   **GitHub 链接:** [https://github.com/mailcow/mailcow-dockerized](https://github.com/mailcow/mailcow-dockerized)

### Flarum

Flarum 是一个优雅、简单、快速的论坛平台，专注于用户体验和可扩展性。

*   **推荐镜像:** `fof/flarum` (非官方，但常用)
*   **Docker Hub 链接:** [https://hub.docker.com/r/fof/flarum](https://hub.docker.com/r/fof/flarum)
*   **GitHub 链接:** [https://github.com/flarum/flarum](https://github.com/flarum/flarum)

### Nextcloud Talk

Nextcloud Talk 是 Nextcloud 的一个插件，提供实时音视频通话、群聊和屏幕共享功能，适合作为私有化的通信工具。

*   **推荐镜像:** (作为 Nextcloud 的一部分，通常不单独部署)
*   **Docker Hub 链接:** [https://hub.docker.com/_/nextcloud](https://hub.docker.com/_/nextcloud) (Nextcloud 主镜像)
*   **GitHub 链接:** [https://github.com/nextcloud/spreed](https://github.com/nextcloud/spreed) (Nextcloud Talk 仓库)