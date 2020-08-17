## 介绍
本项目是一个使用 `javafx` + `netty` 技术构建的一个桌面应用，
是对[ratel](https://github.com/ainilili/ratel)应用命令行客户端的扩展，为[ratel](https://github.com/ainilili/ratel)应用提供可视化界面操作方式。

### 系统架构
* 使用`netty`构建和**ratel**服务端的通讯
* 使用`javafx`构建`GUI`界面

## 快速启动
### 前提
* `jdk`  
本项目是一个`java`应用，所以运行需要`java`环境，前往[oracle](https://www.oracle.com/java/technologies/java-downloads.html)下载最新版本jdk进行安装

* `maven`  
本项目由maven构建，构建本应用需要先安装maven，前往[apache maven](https://maven.apache.org)下载最新版本maven进行安装

### 安装
```powershell
git clone https://github.com/marmot-z/javafx-ratel-client.git
cd javafx-ratel-client
mvn install package
```

#### 启动`javafx`客户端
```shell
jjava -jar target\javafx-ratel-client-#{version}.jar
```

## 使用
1. 选择服务器地址连接
![连接服务器](images/connect.png)  
2. 输入昵称
![输入昵称](images/input-nickname.png)  
3. 选择模式
![选择模式](images/select-modal.png)  
4. 选择房间
![选择房间](images/choose-room.png)  
5. 开始游戏
![开始游戏](images/play.png)  

## TODO List
- [X] PVE模式  
- [ ] PVP模式  
- [ ] 优化界面    
- [ ] 页面切换  
- [ ] 挂机检测

## 贡献与反馈
- 如果您想贡献代码，非常欢迎提``PR``，我们将会合并优秀的代码
- 如果你发现此客户端的bug或有任何疑问，欢迎提[issue](https://github.com/marmot-z/javafx-ratel-client/issues)
- 我的联系方式（15870664270@163.com）

## 参考
* [NaiveChat](https://github.com/fuzhengwei/NaiveChat)
* [ratel部分协议](https://github.com/ainilili/ratel/blob/master/PROTOCO_CN.md)
* [javafx和netty之间的通信](./javafx-netty-communication.md)
