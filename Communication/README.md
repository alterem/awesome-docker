# ✉️ 通信类

用于搭建私有聊天、论坛或邮件服务。

### Mattermost
    
Mattermost 是一个开源的团队协作平台，是 Slack 的开源替代品。它支持群聊、私聊、文件共享、集成等功能，适合团队内部沟通。

*   **推荐镜像:** `mattermost/mattermost-team-edition`
*   **Docker Hub 链接:** [https://hub.docker.com/r/mattermost/mattermost-team-edition](https://hub.docker.com/r/mattermost/mattermost-team-edition)
*   **GitHub 链接:** [https://github.com/mattermost/mattermost-server](https://github.com/mattermost/mattermost-server)

### Gitea

Gitea 是一个轻量级的自托管 Git 服务，功能类似于 GitHub 或 GitLab。你可以用它来搭建自己的代码仓库，进行版本控制。

*   **推荐镜像:** `gitea/gitea`
*   **Docker Hub 链接:** [https://hub.docker.com/r/gitea/gitea](https://hub.docker.com/r/gitea/gitea)
*   **GitHub 链接:** [https://github.com/go-gitea/gitea](https://github.com/go-gitea/gitea)

### Discourse

Discourse 是一个现代化、开源的论坛软件，专注于提高讨论的质量和参与度。

*   **推荐镜像:** 通常推荐使用官方的 Docker 安装脚本，而不是简单的 `docker run`。
*   **官方安装指南 (含Docker):** [https://github.com/discourse/discourse_docker](https://github.com/discourse/discourse_docker) (这是一个完整的 Dockerized 部署方案，而非单个应用镜像的 GitHub 仓库)