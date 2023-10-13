## AutoJs Web Control


nodejs typescript vuejs  [SoulJs](https://github.com/zrk1993/souljs) [AutoJs](https://github.com/hyb1996/Auto.js)

### 特性(character)

1. 支持群控
2. 脚本开发
3. 定时任务
4. 实时日志

## 部署(deploy)
1.复制deploy文件夹内容到服务器需要部署的目录下;
2.cd到该目录; 
```
    cd %your_file_path%
```
3.使用docker-compose部署镜像;
```
    docker-compose up -d
```
4.启动后访问80端口即可访问控制端页面,9317端口用于autojs远程连接;
5.修改docker-compose文件可重新映射上面的端口;

## 使用(USE)
1. 下载Autojs 4.x版本
2. 连接服务端，地址 <ip>:9317


## image

![screen-develop](https://raw.githubusercontent.com/zrk1993/autojs-web-control/master/image/develop.png)
![screen-device](https://raw.githubusercontent.com/zrk1993/autojs-web-control/master/image/device.png)
![screen-scheduler](https://raw.githubusercontent.com/zrk1993/autojs-web-control/master/image/scheduler.png)
![screen-workspaces](https://raw.githubusercontent.com/zrk1993/autojs-web-control/master/image/workspaces.png)

## License

application is [MIT licensed](LICENSE).
