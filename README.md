# docker-lnmp，基于Docker的一键lnmp环境
从零开始，基于Docker容器技术的php开发、生产环境。系统要求(centos7.0以上,最好是minimal安装的纯净系统)


### 一键安装命令（安装docker与docker-compose环境）
    curl -sSL https://raw.githubusercontent.com/myriver/docker-tool/master/install-docker.sh | sh

### 启动命令
    cd /data/Docker/compose && docker-compose up -d

### 项目结构
Docker   docker容器相关目录，里面包含docker-compose文件以及php mysql nginx日志和全部配置文件，按版本号分目录存放，可以根据需要更改配置项
Project  项目代码文件夹  
  
### License

MIT
  

