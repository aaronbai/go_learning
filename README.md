# Go_Learning

## GoAwosome
1. WebFrameWork
    * [gin](https://gin-gonic.github.io/gin/) 
    * [beego](https://github.com/astaxie/beego)
2. FunnyRepos
    * [websocketd](https://github.com/joewalnes/websocketd)
3. Logs
    * [logrus](https://github.com/sirupsen/logrus)

## Books
1. [《Go实战开发》](https://github.com/astaxie/go-best-practice)
2. [《Go Web 编程》](https://wizardforcel.gitbooks.io/build-web-application-with-golang/content/)
3. [《Go Commamnd Tutorial》](https://github.com/hyper0x/go_command_tutorial)
4. [《Go语言圣经》](https://yar999.gitbooks.io/gopl-zh/content/)
5. [《Effective Go》](https://godoc.golangtc.com/doc/effective_go.html)

## Geek
1. [astaxie](https://github.com/astaxie)

## 微服务和Go语言应用
微服务关心什么?
1. 高可用
    1. 负载均衡([seesaw](https://github.com/google/seesaw), [caddy](https://github.com/mholt/caddy))
    2. 服务注册与发现([etcd](https://github.com/etcd-io/etcd), [consul](https://github.com/hashicorp/consul), [serf](https://github.com/hashicorp/serf))
2. 易扩展
    1. 应用无状态([tyk](), [fabio](), [valcand](), [traefik]())
    2. 异步消息([NSQ](), [NATS]())
    3. 标准接口([gRPC](), HTTP)
3. 可实施
    1. 入门容易
    2. 部署方便(docker化)
4. 易扩容
    1. 分布式调度([k8s](), [swarm]())
    2. 机器扩容
5. 可追踪
    1. 服务器监控/告警([Prometheus](), [open-falcon](), [grafana]())
    2. 日志分析([Beats](), [Heka]())
6. 微服务框架([beego](), [go-kit](), [go-micro](), [gin](), [iris]())

## Important
1. 变量逃逸
2. GPM模型
3. 内存管理
4. Goroutine调度
5. 通道
6. 闭包
7. 接口、反射
8. 测试
9. 版本管理

## Senior
1. tmalloc内存管理
2. GC 三色标记、写屏障

## 编译
1. go build -race 竟态检测
2. go vet 语法检测

## 重要区别
1. 多CPU利用模型: 多进程->多线程->GPM
    1. 通讯模型: 共享内存->锁->通道 sharig memory by communication 
2. 网络模型
    1. 多路复用+异步IO->Goroutine
2. 编程模式
    1. 接口式编程
    2. 反射、内嵌等实现
4. 内存管理
    1. GC
    2. 变量逃逸
