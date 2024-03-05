# SkyEditor
### C++20 glb(gltf) resource viewer
- Qt6.4.2.0
- Filament - Google cross-platform real-time physically based rendering engine
- CMake
### Screenshot
![SkyEditor1](screenshot/SkyEditor1.png)


# SkyServer
### C++17 cross-platform realtime server
- Windows ubuntu测试通过
- CMake组织工程
- 工作在传输层/网络层(TCP/IP)
- Asio实现网络跨平台(IOCP/EPOLL)
- 同时支持TCP/WEBSOCKET连接
- Accept/NetIO线程可配置
- Protobuf格式网络协议
- MySQL存储冷数据
- Redis存储热数据
- Recast自动寻路
- Yaml格式配置
- 使用Curl进行HTTP访问
### Screenshot
![ServerDB](screenshot/ServerDB.png)
![ServerLogin](screenshot/ServerLogin.png)
![ServerWorld](screenshot/ServerWorld.png)
![ServerClient](screenshot/ServerClient.png)
![SkyServer](screenshot/SkyServer.png)

### Usage
- Run redis
- Run mysql
```
start ServerDB.exe
start ServerLogin.exe
start ServerWorld.exe
start ServerClient.exe
```



