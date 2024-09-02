## 启动本地开发环境

### 启动本地Mysql和Redis

1. [安装docker环境](https://docs.docker.com/desktop/install/linux-install/)

2. 在 '/Code/medical2.0/back'目录下执行以下命令

```shell
docker compose up -d
```

### 配置并启动项目

1. 安装配置JDK8
* [下载JDK8](https://www.oracle.com/cn/java/technologies/downloads/)
* 配置环境变量

2. 安装配置maven

* [下载maven](https://maven.apache.org/download.cgi)
* 配置maven环境变量

3. 配置启动项目
* 配置JDK8以及maven,导入依赖
* 修改application.dev.yml中的Mysql连接配置和redis配置
* 启动项目

