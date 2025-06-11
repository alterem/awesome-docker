[返回首页](../README.md)

# 📊 监控/日志类

此目录用于存放各种系统监控和日志管理工具。

### Prometheus

Prometheus 是一个开源的系统监控和警报工具包，广泛用于收集和存储时间序列数据。

*   **推荐镜像:** `prom/prometheus:latest`
*   **Docker Hub 链接:** [https://hub.docker.com/r/prom/prometheus](https://hub.docker.com/r/prom/prometheus)
*   **GitHub 链接:** [https://github.com/prometheus/prometheus](https://github.com/prometheus/prometheus)

### Grafana

Grafana 是一个开源的数据可视化和仪表板工具，常与 Prometheus 配合使用，用于创建美观的监控图表。

*   **推荐镜像:** `grafana/grafana:latest`
*   **Docker Hub 链接:** [https://hub.docker.com/r/grafana/grafana](https://hub.docker.com/r/grafana/grafana)
*   **GitHub 链接:** [https://github.com/grafana/grafana](https://github.com/grafana/grafana)

### ELKStack

ELK Stack 是一个流行的日志管理解决方案，用于收集、处理、存储和可视化日志数据。

*   **推荐镜像:** `docker.elastic.co/elasticsearch/elasticsearch:7.x.x`, `docker.elastic.co/logstash/logstash:7.x.x`, `docker.elastic.co/kibana/kibana:7.x.x`
*   **Docker Hub 链接:** [https://www.docker.elastic.co/](https://www.docker.elastic.co/)
*   **GitHub 链接:** [https://github.com/elastic/elasticsearch](https://github.com/elastic/elasticsearch) / [https://github.com/elastic/logstash](https://github.com/elastic/logstash) / [https://github.com/elastic/kibana](https://github.com/elastic/kibana)