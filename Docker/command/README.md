## Docker(centOS 7)

##### 设置 docker 仓库

yum install -y yum -utils device-mapper-persistent-data lvm2 

yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo

##### 安装 docker-ce

yum install docker-ce

##### 启动 docker

systemctl start docker

##### 验证 docker 是否安装成功

docker run hello-world

##### 卸载 docker-ce

yum remove docker-ce

rm -rf varlib/docker

##### 查看 docker 版本号

docker version

##### 查看 docker 信息 

docker info

##### 列出 docker 容器

docker image ls



[Dockerfile 配置]('./Dockerfile')

