# dockerfile

基于 centos官方镜像制作。

docker run -itd -p 2223:22 -p 80:80 -v D:/product/home/centos --name mycentos --privileged=true --restart=always guanpenghui/centos 
