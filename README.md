# mieru script

Mieru 协议一键安装脚本

```shell
wget -N --no-check-certificate https://raw.githubusercontent.com/Felix-zf/mieru-script/main/mieru.sh && bash mieru.sh
```

## 客户端配置
1. 如无意外的话，节点配置文件会在控制台显示，并且保存至/root/mieru/client_config.json文件中
2. 打开 mieru 的项目：https://github.com/enfein/mieru/releases ，下载适合的客户端。我这里以Windows为例
3. 在其目录下，创建一个名为client_config.json的文件，文件内容填写为节点文件内容
4. 在当前目录打开PowerShell命令行，然后输入以下命令，应用客户端配置
```
.\mieru apply config client_config.json
```
5. 启动客户端
```
.\mieru start
``` 
6. 停止客户端
```
.\mieru stop
```

## 鸣谢
- best trojan油管视频：https://www.youtube.com/watch?v=xc1eIj_yIcs
- Misaka的项目：https://github.com/Misaka-blog/mieru-script
