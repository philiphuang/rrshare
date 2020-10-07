## 《人人影视WEB远程管理版 rrshare》 Docker-Compose版本

### 三步运行起来

1. 拉取项目代码：

    ```
    git clone https://github.com/philiphuang/rrshare.git
    ```

2. 运行run.sh

    ```
    cd rrshare
    ./run.sh
    ```

    ![主菜单](./docs/main-menu.png)

    进入交互菜单，选择 ```a``` -> ```b``` ，启动所有服务。（第一次运行会经历漫长的拉取镜像过程，请耐心等候。）

3. 打开浏览器访问宿主机，例如：[http://localhost:3001/](http://localhost:3001/)


### 补充说明
1. 使用DC-Starter管理，详细使用说明:[https://github.com/philiphuang/docker-compose-starter](https://github.com/philiphuang/docker-compose-starter)
2. 镜像来自：https://hub.docker.com/r/pundits/rrshareweb（rrshare for Linux V2.20，源自：http://app.rrys.tv/）
3. 默认端口3001，登录密码123456