# i2p
i2p代理，基于https://github.com/i2p/i2p.i2p，添加 privoxy 转发4444端口，提供对外访问

构建docker 镜像
docker build . -t demo

运行
docker run -it -p 1080:1080 demo:latest
