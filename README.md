# Notes

Black Hat Go, chapter 14, 构建一个基本的命令和控制（C2, Command and Control）远控木马（RAT, Remote Access Trojan）。

## RAT

RAT （RAT, Remote Access Trojan）是攻击者用来在受感染的计算机上远程执行操作的工具，可进行 访问文件系统，执行代码，以及嗅探网络流量等操作。

构建RAT需编写3个独立工具：
- 客户端植入程序
- 服务端
- 管理组件

## Install Dependency

```
go get -u google.golang.org/grpc
```