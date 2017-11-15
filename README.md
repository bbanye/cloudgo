# cloudgo
开发简单 web 服务程序 cloudgo，了解 web 服务器工作原理。

## 任务要求
####
1. 熟悉go服务器工作原理，编程web服务程序，要求要有详细的注释，说明是否使用了哪些架构。
2. 基于现有web库，编写一个简单web应用类似 cloudgo。
3. 使用curl工具访问web程序。
4. 使用ab工具对 web执行压力测试。

## 实验说明
实验使用了Martini框架。
在src/github.com路径下新建文件夹go-martini 。
cd到go-martini路径下，下载martini包。
命令：git clone https://github.com/go-martini/martini.git 。
然后进入到go-martini下执行命令：go install 。
在安装martini架构的过程中还会提示需要你安装另一个包，用上面同样方法git clone 然后go install 就可以了。
Martini是一个非常新的 Go 语言的 Web 框架，使用 Go 的 net/http 接口开发，类似 Sinatra 或者 Flask 之类的框架，你可使用自己的 DB 层、会话管理和模板。

## Martini的特性：

1. 使用非常简单。
2. 无侵入设计。
3. 可与其他 Go 的包配合工作。
4. 超棒的路径匹配和路由。
5. 模块化设计，可轻松添加工具。
6. 大量很好的处理器和中间件。
7. 很棒的开箱即用特性。
8. 完全兼容 http.HandlerFunc 接口。
