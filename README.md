# portainer.shangxian.app

Docker Web 可视化管理平台，基于 [Portainer](https://github.com/portainer/portainer) 。使用 Jenkins Pipeline 向 sg02 推送 Docker Compose 推送配置文件，并推送 `nginx.conf` 到 sg02 的虚拟主机目录中实现反向代理。