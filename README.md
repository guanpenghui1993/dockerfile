# centos - dockerfile

### 基于 centos官方镜像制作。


### 启动命令

docker run -itd -p 22:22 -p 80:80 -v 宿主机目录:容器目录 --name mycentos --privileged=true --restart=always mycentos
