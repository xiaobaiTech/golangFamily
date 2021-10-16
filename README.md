# golangFamily
【超全golang面试题合集+golang学习指南+golang知识图谱+成长路线】 一份涵盖大部分golang程序员所需要掌握的核心知识。


<p align="center">
  <a href="#公众号"><img src="https://img.shields.io/badge/%E5%85%AC%E4%BC%97%E5%8F%B7-%E5%B0%8F%E7%99%BDdebug-blue" alt="公众号"></a>
  <a href="https://juejin.cn/user/4001878057422087"><img src="https://img.shields.io/badge/%E6%8E%98%E9%87%91-%E5%B0%8F%E7%99%BDdebug-yellow" alt="公众号"></a>
  <a href="https://www.zhihu.com/people/jin-ji-de-ren-shan-ren"><img src="https://img.shields.io/badge/%E7%9F%A5%E4%B9%8E-%E5%B0%8F%E7%99%BDdebug-yellowgreen" alt="投稿"></a>
  <a href="https://blog.csdn.net/ilini"><img src="https://img.shields.io/badge/csdn-CSDN-red.svg" alt="投稿"></a>
  <a href="https://xiaobaidebug.top/"><img src="https://img.shields.io/badge/%E5%8D%9A%E5%AE%A2-%E5%B0%8F%E7%99%BDdebug-brightgreen" alt="博客"></a>
  

</p>


![](https://cdn.jsdelivr.net/gh/zhaolunallen/picture/2021-1-8/1610113159235-GO%E6%88%90%E9%95%BF%E8%B7%AF%E7%BA%BF.jpg)



[脑图持续不断更新中，在线查看地址](https://www.processon.com/view/link/5ff500aa1e08531de81e1288)  
后续文章和内容会不断更新到 [github项目](https://github.com/xiaobaiTech/golangFamily) 中，欢迎关注。



<img src="https://cdn.jsdelivr.net/gh/xiaobaiTech/image/%E5%B0%8F%E7%99%BDdebug%E5%8A%A8%E5%9B%BE%E4%BA%8C%E7%BB%B4%E7%A0%81.gif" width="500px" />

# 目录(善用Ctrl+F)

- 基础入门
  - 新手
    - [Golang开发新手常犯的50个错误](https://blog.csdn.net/gezhonglei2007/article/details/52237582)
  - 数据类型
    - [连nil切片和空切片一不一样都不清楚？那BAT面试官只好让你回去等通知了。](https://mp.weixin.qq.com/s/sW4PD1MiaunURNDIU4BbQQ) 
    - [golang面试题：字符串转成byte数组，会发生内存拷贝吗？](https://mp.weixin.qq.com/s/qmlPuGVISx8NYp2b9LrqnA)  
    - [golang面试题：翻转含有中文、数字、英文字母的字符串](https://mp.weixin.qq.com/s/ssinnUM22PHPWRug8EzAkg)  
    - [golang面试题：拷贝大切片一定比小切片代价大吗？](https://mp.weixin.qq.com/s/8Dp2eCYzDdBbxAG5-jNevQ) 
    - map不初始化使用会怎么样
    - map不初始化长度和初始化长度的区别
    - map承载多大，大了怎么办
    - map的iterator是否安全？能不能一边delete一边遍历？
    - 字符串不能改，那转成数组能改吗，怎么改
    - 怎么判断一个数组是否已经排序
    - 普通map如何不用锁解决协程安全问题
    - array和slice的区别
    - [golang面试题：json包变量不加tag会怎么样？](https://mp.weixin.qq.com/s/bZlKV_BWSqc-qCa4DrsCbg) 
    - [golang面试题：reflect（反射包）如何获取字段tag？为什么json包不能导出私有变量的tag？](https://mp.weixin.qq.com/s/P7TEx2mInwEktXTEE6JDWQ)
    - 零切片、空切片、nil切片是什么
    - slice深拷贝和浅拷贝
    - map触发扩容的时机，满足什么条件时扩容？
    - map扩容策略是什么
    - 自定义类型切片转字节切片和字节切片转回自动以类型切片
    - make和new什么区别
    - slice ，map，chanel创建的时候的几个参数什么含义
    - slice，len，cap，共享，扩容
    - 线程安全的map怎么实现
    - go slice 和 array 区别
    - go struct能不能比较？
    - map如何顺序读取？
    - go中怎么实现set
    - map 的扩容机制是什么？
    - 使用值为 nil 的 sice、map 会发生什么？ 
    - Golang 有没有 this 指针？
    - Golang 语言中局部变量和全局变量的缺省值是什么
    - Golang 中的引用类型包含哪些?
    - 使用range 迭代 map 是有序的吗?
    - slice 的扩容机制是什么？
    - Golang 中指针运算有哪些?
    - 类型的值可以修改吗？  
    - 解析 JSON 数据时，默认将数值当做哪种类型
    - array 类型的值作为函数参数是引用传递还是值传递？

       
    
  - 流程控制
    - [昨天那个在for循环里append元素的同事，今天还在么？](https://mp.weixin.qq.com/s/SHxcspmiKyPwPBbhfVxsGA) 
    - [golang面试官：for select时，如果通道已经关闭会怎么样？如果只有一个case呢？](https://mp.weixin.qq.com/s/Oa3eExufo2Req_9IrDys-g) 
    - go defer（for defer）
    - select可以用于什么？
    - context包的用途？  
    - select 可以用于实现哪些功能？
    - 在循杯内执行 defer 语句会发生什么?
    - switch 中如何强制执行下一个 case 代码块?
    - 如何从 panic 中恢复?

- 进阶
  - 包管理  
    [学go mod就够了！](https://studygolang.com/articles/27293)
    
  - 优化
    - [golang面试题：怎么避免内存逃逸？](https://mp.weixin.qq.com/s/VzRTHz1JaDUvNRVB_yJa1A) 
    - [golang面试题：简单聊聊内存逃逸？](https://mp.weixin.qq.com/s/wJmztRMB1ZAAIItyMcS0tw) 
    - [给大家丢脸了，用了三年golang，我还是没答对这道内存泄漏题](https://mp.weixin.qq.com/s/-agtdhlW7Yj7S88a0z7KHg)
    - 内存碎片化问题
    - chan相关的goroutine泄露的问题
    - string相关的goroutine泄露的问题
    - [你一定会遇到的内存回收策略导致的疑似内存泄漏的问题](https://colobu.com/2019/08/28/go-memory-leak-i-dont-think-so/)
    - sync.Pool的适用场景
    - go1.13sync.Pool对比go1.12版本优化点
    
    
  - 并发编程
    - [golang面试题：对已经关闭的的chan进行读写，会怎么样？为什么？](https://mp.weixin.qq.com/s/izbZ3JRqX6jI6Wn7bV6xNQ) 
    - [golang面试题：对未初始化的的chan进行读写，会怎么样？为什么？](https://mp.weixin.qq.com/s/ixJu0wrGXsCcGzveCqnr6A)  
    - sync.map 的优缺点和使用场景
    - sync.Map的优化点
    - 主协程如何等其余协程完再操作
    - 有缓存的channel和没有缓存的channel区别是什么？
    - 协程通信方式有哪些？
    - channel底层实现
    - 读写锁底层是怎么实现的？
    - 请你说说golang的CSP思想
    - channel 是怎么保证线程安全？
 
    
  - 高级特性
    - [golang面试题：能说说uintptr和unsafe.Pointer的区别吗？](https://mp.weixin.qq.com/s/PSkz0zj-vqKzmIKa_b-xAA)
    - [golang 面试题：reflect（反射包）如何获取字段 tag？为什么 json 包不能导出私有变量的 tag？](https://mp.weixin.qq.com/s/WK9StkC3Jfy-o1dUqlo7Dg)
    - 协程和线程的差别
    - 垃圾回收的过程是怎么样的？
    - 什么是写屏障、混合写屏障，如何实现？
    - 开源库里会有一些类似下面这种奇怪的用法：`var _ io.Writer = (*myWriter)(nil)`，是为什么？
    - [GMP模型](https://zboya.github.io/post/go_scheduler/?hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io)
    - [动图图解，GMP里为什么要有P](https://mp.weixin.qq.com/s/SEE2TUeZQZ7W1BKkmnelAA)
    - 协程之间是怎么调度的
    - gc的stw是怎么回事
    - 利用golang特性，设计一个QPS为500的服务器
    - 为什么gc会让程序变慢
    - 开多个线程和开多个协程会有什么区别
    - 两个interface{} 能不能比较
    - 必须要手动对齐内存的情况
    - [go栈扩容和栈缩容，连续栈的缺点](https://segmentfault.com/a/1190000019570427)
    - golang怎么做代码优化
    - [golang隐藏技能:怎么访问私有成员](https://www.jianshu.com/p/7b3638b47845)
    - 协程可以自己主动让出 CPU 吗？
    - 断言时会发生拷贝吗
    - 接口是怎么实现的？
    - 协程与进程，线程的区别是什么？协程有什么优势？
    - 为什么小对象多了会造成 gc 压力?
    - 一个协程能保证绑定在一个内核线程上吗？
    - 闭包怎么实现的,闭包的主要应用场景
    - 两次 GC 周期重叠会引发什么问题，GC 触发机制是什么样的？
    - Goroutinue 什么时候会被挂起？
    - Data Race 问题怎么检测？怎么解决? 
    - Golang 触发异常的场景有哪些?
    - net/http包中client如何实现长连接？
    - net/http怎么做连接池和长链接？
    
  - 问题排查
    - [trace](https://mp.weixin.qq.com/s?__biz=MzA4ODg0NDkzOA==&mid=2247487157&idx=1&sn=cbf1c87efe98433e07a2e58ee6e9899e&source=41#wechat_redirect) 
    - [pprof](https://mp.weixin.qq.com/s/d0olIiZgZNyZsO-OZDiEoA) 
    - 什么是 goroutine 泄漏?
    - 当go服务部署到线上了，发现有内存泄露，该怎么处理
  
  - 源码阅读
    - [sync.map](https://qcrao.com/2020/05/06/dive-into-go-sync-map/)
    - net/http 
      - [i/o timeout ， 希望你不要踩到这个net/http包的坑](https://mp.weixin.qq.com/s/7Fl5MuCl-G6wIQQiAqLAKA) 
    - [mutex](https://mp.weixin.qq.com/s/MntwgIJ2ynOAdwnypWUjZw)
    - [channel](https://draveness.me/golang/docs/part3-runtime/ch06-concurrency/golang-channel/?hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io)
    - [context](https://draveness.me/golang/docs/part3-runtime/ch06-concurrency/golang-context/)
    - [select实现原理](https://mp.weixin.qq.com/s/9-eLJqYZrOpNLoiTGpBrKA)
    - main函数背后的启动过程
    - [内存管理](https://mp.weixin.qq.com/s?__biz=Mzg2MDU1Mjc3MQ==&mid=2247489860&idx=1&sn=2d3fa235f6768ad5a0c820b6241b9e99&source=41#wechat_redirect)
    - [GC垃圾回收](https://segmentfault.com/a/1190000020086769)
    - [timer](https://pengrl.com/p/62835/)
  - 汇编 
    - [汇编入门](https://juejin.cn/post/6844903929713524744)
    
    
  - [推荐书籍](#推荐书籍) 
  - [视频教程](#视频教程)
  - 实践常用工具   
    - [mysql建表语句转golang struct](https://marketplace.visualstudio.com/items?itemName=wandecilenio-martins.ddl-2-go-struct)
    - [json转golang struct](https://oktools.net/json2go)
    - [toml转golang struct](https://xuri.me/toml-to-go/)
    - [yaml转golang struct](https://yaml.to-go.online/)
    
- 图解网络基础   
  - [漫画图解HTTP知识点+面试题](https://mp.weixin.qq.com/s/wNRoDoW_VEqiq8JelePj2g) 
  - [TCP粘包 数据包：我只是犯了每个数据包都会犯的错](https://mp.weixin.qq.com/s/0-YBxU1cSbDdzcZEZjmQYA) 
  - [30张图带你搞懂！路由器，集线器，交换机，网桥，光猫有啥区别？](https://mp.weixin.qq.com/s/6eQ00Wzss61XUTO8xeL3iA) 
  - [既然IP层会分片，为什么TCP层也还要分段？](https://mp.weixin.qq.com/s/YpQGsRyyrGNDu1cOuMy83w)
  - [断网了，还能ping通 127.0.0.1 吗？为什么？](https://mp.weixin.qq.com/s/Gml_xxvGjq224L7zCoXm5w) 
  - [连接一个 IP 不存在的主机时，握手过程是怎样的？](https://mp.weixin.qq.com/s/Czv0CxDKqr2QNItO4aNZMA) 
  - [动图图解！代码执行send成功后，数据就发出去了吗？](https://mp.weixin.qq.com/s/87BZzLmcntA1snJIIhUR0w)
  - [活久见！TCP两次挥手，你见过吗？那四次握手呢？](https://mp.weixin.qq.com/s/Z0EqSihRaRbMscrZJl-zxQ)
  - [动图图解！收到RST，就一定会断开TCP连接吗？](https://mp.weixin.qq.com/s/Fr6o6gRiIUIspV9-jR9snw)
  - [动图图解！没有accept，能建立TCP连接吗？](https://mp.weixin.qq.com/s/n17NjGRab1u5eXkOCro1gg)
  - [来了来了！小白图解网络电子书和博客都来啦！](https://mp.weixin.qq.com/s/yZPorh6js8cq0_6FjfnGZA)
  - HTTP 是无状态的吗？需要保持状态的场景应该怎么做？
  - 粘包如何解决
  - RestFul 是什么？RestFul 请求的 URL 有什么特点？
  - 一次url访问会经历哪些过程
  - TCP 三次握手以及四次挥手的流程。为什么需要三次握手以及四次挥手？
  - TCP的拥塞控制具体是怎么实现的？UDP有拥塞控制吗？
  - 是否了解中间人劫持原理
  - TCP 与 UDP 在网络协议中的哪一层，他们之间有什么区别？
  - HTTP 与 HTTPS 有哪些区别？
  - select和epoll区别
  - TCP 如何实现数据有序性？
  - TCP长连接和短连接有那么不同的使用场景？
  - TIME_WAIT时长，为什么？
  - 什么是零拷贝？
  - HTTP 简述 HTTP 的 keepalive 的原理和使用场景
  - Cookie 和 Session 的关系和区别是什么？
  - DNS 查询服务器的基本流程是什么？DNS 劫持是什么？
  - libevent结构，内部实现
  - 简述对称与非对称加密的概念
  - epoll中的ET和LT模式
  - JWT 的原理和校验机制
  - TCP 怎么保证可靠传输？
  - 介绍下proactor和reactor
  - Accept发生在三次握手哪个阶段
  - RPC 的调用过程
  - tcp的可靠性体现在哪里
  - 如何解决 TCP 传输丢包问题？
  - 什么是 ARP 协议？简述其使用场景
  - http和https区别
  - DDOS 攻击原理，如何防范它？
  - 如何防止传输内容被篡改？
  - 介绍下滑动窗口
  - 三次握手四次握手详细过程，越详细越好
  - 什么是中间人攻击？如何防止攻击？
  - TCP 半连接发生场景
  - reactor的组成
  - udp包长度
  - IP为什么要分片
  - OSI 七层模型，TCP，IP 属于哪一层？
  - 数据包乱序会处理？
  - 什么是 SYN flood，如何防止这类攻击？
  - WebSocket 是如何进行传输的
  - 为什么需要序列化？有什么序列化的方式？
  - 有chunked的时候contentlength是什么样子
  - 如何设计一个可靠的udp
  - TCP 中常见的拥塞控制算法有哪些？
  - 如何设置非阻塞
  - 什么是跨域，什么情况下会发生跨域请求？
  - Udp的接收缓冲区和发送缓冲区和tcp的区别
  - 什么时候需要TCP四次挥手？
  - traceroute 有什么作用？
  - HTTP 的方法有哪些？
  - TIME_WAIT危害
  - select什么情况返回0
  - 半连接在哪个阶段
  - TCP 的 keepalive 了解吗？说一说它和 HTTP 的 keepalive 的区别？
  - 简述常见的 HTTP 状态码的含义（30从系统层面上，UDP 如何保证尽量可靠？
  - 指针与引用的区别
  - iPv4 和 iPv6 的区别
  - 项目中说用到线程池，开多大，为什么运用线程池？
  - 如何设计 API 接口使其实现幂等性？
  - TCP 的 TIME_WAIT 和 CLOSE_WAIT
  - HTTP 报文头部的组成结构
  - RestFul 与 RPC 的区别是什么？RestFul 的优点在哪里？
  - 从输入 URL 到展现页面的全过程
  - 什么是 TCP 粘包和拆包？
  - HTTP 中 GET 和 POST 区别
  - 讲一下拥塞控制和流量控制
  - TCP 协议的延迟 ACK 和累计应答
  - TCP 挥手时出现大量 CLOSE_WAIT 或 TIME_WAIT 怎么解决？
  - ARP协议工作流程
  - tcp与udp的区别以及应用场景
  - HTTPS 的加密与认证过程
  - TCP 中 SYN 攻击是什么？如何防止？
  - HTTP 短链接与长链接的区别
  - TCP 的报文头部结构
  - http长连接与短连接的区别
  - TCP 滑动窗口以及重传机制
  - seq为1000，发送了1000个数据，下一个seq是多少?
  - chunked块了解？介绍下
  - BGP 协议和 OSPF 协议的区别
  - 简述在四层和七层网络协议中负载均衡的原理
  - http协议格式，几种方法，功能是什么
  - syn如果丢了，重传多少次
  - epoll可读情况有哪些



- 操作系统
  - 创建线程有多少种方式？
  - 如何调试服务器内存占用过高的问题？
  - 简述操作系统如何进行内存管理
  - 简述创建进程的流程
  - 简述操作系统中 malloc 的实现原理
  - 简述僵尸进程和孤儿进程及其危害和处理
  - 两个线程交替打印一个共享变量
  - 进程通信中的管道实现原理是什么？
  - 简述同步与异步的区别，阻塞与非阻塞的区别
  - malloc 创建的对象在堆还是栈中？
  - 死锁产生的条件、死锁避免方法
  - 进程的三状态模型、五状态模型、七状态模型
  - 什么情况下，进程会进行切换？
  - Linux 系统态与用户态，什么时候会进入系统态？
  - Linux 下如何查看端口被哪个进程占用？
  - 共享内存是如何实现的？
  - 进程有多少种状态？
  - 线程间有哪些通信方式？
  - Linux 下如何排查 CPU 以及 内存占用过多？
  - 操作系统中，虚拟地址与物理地址之间如何映射？
  - CPU L1, L2缓存是什么
  - 信号量是如何实现的？
  - 什么时候会由用户态陷入内核态？
  - Linux 如何查看实时的滚动日志？
  - Linux 进程调度的算法
  - 简述分页与分段，分页与分段的区别
  - Linux 虚拟内存的页面置换算法
  - Linux 中虚拟内存和物理内存有什么区别？有什么优点？
  - traceroute 命令的原理
  - 操作系统是通过什么机制触发系统调用的？
  - Linux 零拷贝的原理
  - 系统调用的过程是怎样的？
  - Linux 的 IO模型有哪些
  - 简述自旋锁与互斥锁的使用场景
  - 多线程和多进程的区别是什么？
  - 简述几个常用的 Linux 命令以及他们的功能
  - 进程空间从高位到低位都有些什么？
  - 简述缓冲区溢出及其危害
  - mmap 的使用场景以及原理
  - BIO、NIO 有什么区别？怎么判断写文件时 Buffer 已经写满？
  - 线程有多少种状态，状态之间如何转换
  - 简述操作系统中的缺页中断
  - Linux 下如何查看 CPU 荷载，正在运行的进程，某个端口对应的进程？
  - 进程和线程之间有什么区别？
  - 进程间有哪些通信方式？
  - 为什么进程切换慢，线程切换快？
  - 线程从进程继承了哪些资源？线程独享哪些资源？
  - Linux 页大小是多少？
  - select, poll, epoll 的使用场景以及区别，epoll 中水平触发以及边缘触发有什么不同？
 
- 数据库
  - 数据库三大范式是什么
  - mysql有关权限的表都有哪几个
  - MySQL的binlog有有几种录入格式？分别有什么区别？
  - mysql有哪些数据类型
  - MySQL存储引擎MyISAM与InnoDB区别
  - MyISAM索引与InnoDB索引的区别？
  - InnoDB引擎的4大特性
  - 存储引擎选择
  - 什么是索引？
  - 索引有哪些优缺点？
  - 索引使用场景（重点）
  - 索引有哪几种类型？
  - 索引的数据结构（b树，hash）
  - 索引的基本原理
  - 索引算法有哪些？
  - 索引设计的原则？
  - 创建索引的原则
  - 创建索引的三种方式，删除索引
  - 创建索引时需要注意什么？
  - 使用索引查询一定能提高查询的性能吗？为什么
  - 百万级别或以上的数据如何删除
  - 前缀索引
  - 什么是最左前缀原则？什么是最左匹配原则
  - B树和B+树的区别
  - 使用B树的好处
  - 使用B+树的好处
  - Hash索引和B+树所有有什么区别或者说优劣呢?
  - 数据库为什么使用B+树而不是B树
  - B+树在满足聚簇索引和覆盖索引的时候不需要回表查询数据，
  - 什么是聚簇索引？何时使用聚簇索引与非聚簇索引
  - 非聚簇索引一定会回表查询吗？
  - 联合索引是什么？为什么需要注意联合索引中的顺序？
  - 什么是数据库事务？
  - 事物的四大特性(ACID)介绍一下?
  - 什么是脏读？幻读？不可重复读？
  - 什么是事务的隔离级别？MySQL的默认隔离级别是什么？
  - 对MySQL的锁了解吗
  - 隔离级别与锁的关系
  - 按照锁的粒度分数据库锁有哪些？锁机制与InnoDB锁算法
  - 从锁的类别上分MySQL都有哪些锁呢？像上面那样子进行锁定岂不是有点阻碍并发效率了
  - MySQL中InnoDB引擎的行锁是怎么实现的？
  - InnoDB存储引擎的锁的算法有三种
  - 什么是死锁？怎么解决？
  - 数据库的乐观锁和悲观锁是什么？怎么实现的？
  - 为什么要使用视图？什么是视图？
  - 视图有哪些特点？
  - 视图的使用场景有哪些？
  - 视图的优点
  - 视图的缺点
  - 什么是游标？
  - 存储过程与函数
  - 什么是存储过程？有哪些优缺点？
  - 什么是触发器？触发器的使用场景有哪些？
  - MySQL中都有哪些触发器？
  - 常用SQL语句
  - SQL语句主要分为哪几类
  - 超键、候选键、主键、外键分别是什么？
  - SQL 约束有哪几种？
  - 六种关联查询
  - 什么是子查询
  - 子查询的三种情况
  - mysql中 in 和 exists 区别
  - varchar与char的区别
  - varchar(50)中50的涵义
  - int(20)中20的涵义
  - mysql为什么这么设计
  - mysql中int(10)和char(10)以及varchar(10)的区别
  - FLOAT和DOUBLE的区别是什么？
  - drop、delete与truncate的区别
  - UNION与UNION ALL的区别？
  - 如何定位及优化SQL语句的性能问题？创建的索引有没有被使用到?或者说怎么才可以知道这条语句运行很慢的原因？
  - SQL的生命周期？
  - 大表数据查询，怎么优化
  - 超大分页怎么处理？
  - mysql 分页怎么实现
  - 慢查询日志怎么看
  - 关心过业务系统里面的sql耗时吗？统计过慢查询吗？对慢查询都怎么优化过？
  - 为什么要尽量设定一个主键？
  - 主键使用自增ID还是UUID？
  - 字段为什么要求定义为not null？
  - 如果要存储用户的密码散列，应该使用什么字段进行存储？
  - 优化查询过程中的数据访问
  - 优化长难的查询语句
  - 优化特定类型的查询语句
  - 优化关联查询
  - 优化子查询
  - 优化LIMIT分页
  - 优化UNION查询
  - 优化WHERE子句
  - 数据库优化
  - 为什么要优化
  - 数据库结构优化
  - MySQL数据库cpu飙升到500%的话他怎么处理？
  - 大表怎么优化？某个表有近千万数据，CRUD比较慢，如何优化？分库分表了是怎么做的？分表分库了有什么问题？有用到中间件么？他们的原理知道么？
  - 垂直分表适用场景
  - 水平分表适用场景
  - 水平切分的缺点
  - MySQL的复制原理以及流程
  - 读写分离有哪些解决方案？
  - 备份计划，mysqldump以及xtranbackup的实现原理
  - 数据表损坏的修复方式有哪些？ 
 
- 骚话连篇  
  - [程序员防猝死指南](https://mp.weixin.qq.com/s/PP80aD-GQp7VtgyfHj392g) 
  - [妙啊！程序猿的第一本互联网黑话指南](https://mp.weixin.qq.com/s/lpmCHabbFarXwR1ZJwJ_kg) 
  - [我感觉，我可能要拿图灵奖了。。。](https://mp.weixin.qq.com/s/K9a_TTYRmw5vQzCsCQTQrw)
  - [爷青回！最近很火的朋友圈怀旧小电视源码来啦！看到最后一个视频我大呼好家伙！](https://mp.weixin.qq.com/s/9_Au8hb-_5fNDiN4s0tNHw)
  - [我要开留言啦！](https://mp.weixin.qq.com/s/xawnze8S1SGmtK6rQ6bkMQ)  
    
 
- 包
  - [常用官方包说明](#常用包)
  - [常用第三方包说明](#三方包)
  - [常用框架](#框架)
  - [完整标准库列表](#完整包)
  - [优秀的第三方库](#优秀的开源库)
     - [音频和音乐](#音频和音乐)
     - [数据结构:Go中的通用数据结构和算法](#数据结构)
     - [分布式系统:Go中的通用数据结构和算法](#分布式系统)
     - [电子邮件:实现电子邮件创建和发送的库和工具](#电子邮件)
     - [嵌入式脚本语言:在go代码中嵌入其他语言](#嵌入式脚本语言)
     - [错误处理](#错误处理)
     - [处理文件和文件系统的库](#文件)
     - [金融:会计和财务软件包](#金融)
     - [游戏开发:游戏开发相关库](#游戏开发)
     - [地理位置:地理相关的位置信息和工具库](#地理位置)
     - [编译器相关:转到其他语言](#编译器)
     - [Goroutines:用于管理和使用Goroutines的工具](#Goroutines)
     - [图形界面:用于构建GUI应用程序的库](#图形界面)
     - [图片:用于处理图像的库](#图片)
     - [物联网:物联网设备编程库](#物联网)
     - [JSON格式:用于处理JSON的库](#JSON格式)
     - [机器学习:常用机器学习库](#机器学习)
     - [微软办公软件](#微软办公软件)
     - [自然语言处理](#自然语言处理)
     - [网络:与网络各层配合使用的库](#网络)
     - [视频:用于处理视频的库](#视频)
  
    
 


    
<br> </br> 
- 其他
1. 常用包    
<a name="常用包"></a>  <a name="常用包"></a>      

|    常用包  |   说明  |  
|:---------:|:------:| 
| fmt | 实现格式化的输入输出操作，其中的fmt.Printf()和fmt.Println()是开发者使用最为频繁的函数。   |  
| io | 实现了一系列非平台相关的IO相关接口和实现，比如提供了对os中系统相关的IO功能的封装。我们在进行流式读写（比如读写文件）时，通常会用到该包。   |  
| bufio | 它在io的基础上提供了缓存功能。在具备了缓存功能后， bufio可以比较方便地提供ReadLine之类的操作。   |  
| strconv | 提供字符串与基本数据类型互转的能力。   |  
| os | 本包提供了对操作系统功能的非平台相关访问接口。接口为Unix风格。提供的功能包括文件操作、进程管理、信号和用户账号等。   |  
| sync | 它提供了基本的同步原语。在多个goroutine访问共享资源的时候，需要使用sync中提供的锁机制。   |  
| flag | 它提供命令行参数的规则定义和传入参数解析的功能。绝大部分的命令行程序都需要用到这个包。   |  
| encoding/json | JSON目前广泛用做网络程序中的通信格式。本包提供了对JSON的基本支持，比如从一个对象序列化为JSON字符串，或者从JSON字符串反序列化出一个具体的对象等。   |  
| http | 通过http包，只需要数行代码，即可实现一个爬虫或者一个Web服务器，这在传统语言中是无法想象的。   |  



<br> </br> 
<a name="三方包"></a>  <a name="三方包"></a> 
2. 常用第三方包
|    包  |   地址  | 
|:---------:|:------:|
|数据库操作   |  [github.com/jinzhu/gorm](https://github.com/jinzhu/gorm) </br>     [github.com/go-xorm/xorm](https://github.com/go-xorm/xorm) |
|搜索es   |  [github.com/olivere/elastic](https://github.com/olivere/elastic)  |
|rocketmq操作   |  [github.com/apache/rocketmq-client-go/v2](https://github.com/apache/rocketmq-client-go/v2)  |
|rabbitmq 操作   |  [github.com/streadway/amqp](https://github.com/streadway/amqp)  |
|redis 操作   |  [github.com/go-redis/redis](https://github.com/go-redis/redis)  |
|etcd 操作   |  [github.com/coreos/etcd/clientv3](https://pkg.go.dev/go.etcd.io/etcd/clientv3)  |
|kafka|  [https://github.com/Shopify/sarama](https://github.com/Shopify/sarama)      [https://github.com/bsm/sarama-cluster](https://github.com/bsm/sarama-cluster)  |
|excel 操作   |  [github.com/360EntSecGroup-Skylar/excelize](https://github.com/360EntSecGroup-Skylar/excelize)  |
|ppt 操作   |  [golang.org/x/tools/cmd/present](https://golang.org/x/tools/cmd/present)  |
|go-svg 操作   |  [https://github.com/ajstarks/svgo](https://github.com/ajstarks/svgo)  |
|go 布隆过滤器实现  |  [https://github.com/AndreasBriese/bbloom](https://github.com/AndreasBriese/bbloom)  |
|json相关  |  [https://github.com/bitly/go-simplejson](https://github.com/bitly/go-simplejson)  |
|LRU Cache实现  |  [https://github.com/bluele/gcache  ](https://github.com/bluele/gcache  )    [https://github.com/hashicorp/golang-lru  ](https://github.com/hashicorp/golang-lru  )  |
|go运行时函数替换  |  [https://github.com/bouk/monkey  ](https://github.com/bouk/monkey  )  |
|toml  |  [https://github.com/toml-lang/toml  ](https://github.com/toml-lang/toml  )  [https://github.com/naoina/toml   ](https://github.com/naoina/toml   )  |
|yaml  |  [https://github.com/go-yaml/yaml  ](https://github.com/go-yaml/yaml  )  |
|viper  |  [https://github.com/spf13/viper  ](https://github.com/spf13/viper  )  |
|go key/value存储  |  [https://github.com/etcd-io/bbolt  ](https://github.com/etcd-io/bbolt  )  |
|基于ringbuffer的无锁golang workpool  |  [https://github.com/Dai0522/workpool  ](https://github.com/Dai0522/workpool  )  |
|轻量级的协程池  |  [https://github.com/ivpusic/grpool  ](https://github.com/ivpusic/grpool  )  |
|打印go的详细数据结构  |  [https://github.com/davecgh/go-spew  ](https://github.com/davecgh/go-spew  )  |
|基于ringbuffer实现的队列  |  [https://github.com/eapache/queue  ](https://github.com/eapache/queue  )  |
|拼音  |  [https://github.com/go-ego/gpy  ](https://github.com/go-ego/gpy  )  |
|分词  |  [https://github.com/go-ego/gse  ](https://github.com/go-ego/gse  )  |
|搜索  |  [https://github.com/go-ego/riot  ](https://github.com/go-ego/riot  )  |
|windows COM  |  [https://github.com/go-ego/cedar  ](https://github.com/go-ego/cedar  )  |
|session  |  [https://github.com/gorilla/sessions  ](https://github.com/gorilla/sessions  )  |
|路由  |  [https://github.com/gorilla/mux  ](https://github.com/gorilla/mux  )  |
|websocket  |  [https://github.com/gorilla/websocket  ](https://github.com/gorilla/websocket  )  |
|Action handler  |  [https://github.com/gorilla/handlers  ](https://github.com/gorilla/handlers  )  |
|csrf  |  [https://github.com/gorilla/csrf  ](https://github.com/gorilla/csrf  )  |
|context  |  [https://github.com/gorilla/context  ](https://github.com/gorilla/context  )  |
|过滤html标签  |  [https://github.com/grokify/html-strip-tags-go  ](https://github.com/grokify/html-strip-tags-go  )  |
|可配置的HTML标签过滤  |  [https://github.com/microcosm-cc/bluemonday  ](https://github.com/microcosm-cc/bluemonday  )  |
|根据IP获取地理位置信息  |  [https://github.com/ipipdotnet/ipdb-go  ](https://github.com/ipipdotnet/ipdb-go  )  |
|html转markdown  |  [https://github.com/jaytaylor/html2text  ](https://github.com/jaytaylor/html2text  )  |
|goroutine 本地存储  |  [https://github.com/jtolds/gls  ](https://github.com/jtolds/gls  )  |
|彩色输出|  [https://github.com/mgutz/ansi](https://github.com/mgutz/ansi)  |
|表格打印|  [https://github.com/olekukonko/tablewriter](https://github.com/olekukonko/tablewriter)  |
|reflect 更高效的反射API|  [https://github.com/modern-go/reflect2](https://github.com/modern-go/reflect2)  |
|msgfmt (格式化字符串，将%更换为变量名)|  [https://github.com/modern-go/msgfmt](https://github.com/modern-go/msgfmt)  |
|可取消的goroutine|  [https://github.com/modern-go/concurrent](https://github.com/modern-go/concurrent)  |
|深度拷贝|  [https://github.com/mohae/deepcopy](https://github.com/mohae/deepcopy)  |
|安全的类型转换包|  [https://github.com/spf13/cast](https://github.com/spf13/cast)  |
|从文本中提取链接|  [https://github.com/mvdan/xurls](https://github.com/mvdan/xurls)  |
|字符串格式处理（驼峰转换）|  [https://godoc.org/github.com/naoina/go-stringutil](https://godoc.org/github.com/naoina/go-stringutil)  |
|文本diff实现|  [https://github.com/pmezard/go-difflib](https://github.com/pmezard/go-difflib)  |
|uuid相关 |  [https://github.com/satori/go.uuid](https://github.com/satori/go.uuid)    [https://github.com/snluu/uuid](https://github.com/snluu/uuid)  |
|去除UTF编码中的BOM|  [https://github.com/ssor/bom](https://github.com/ssor/bom)  |
|图片缩放|  [https://github.com/nfnt/resize](https://github.com/nfnt/resize)  |
|生成 mock server|  [https://github.com/otokaze/mock](https://github.com/otokaze/mock)  |
|go 性能上报到influxdb|  [https://github.com/rcrowley/go-metrics](https://github.com/rcrowley/go-metrics)  |
|go zookeeper客户端|  [https://github.com/samuel/go-zookeeper](https://github.com/samuel/go-zookeeper)  |
|go thrift |  [https://github.com/samuel/go-thrift](https://github.com/samuel/go-thrift)  |
|MQTT 客户端  |  [https://github.com/shirou/mqttcli](https://github.com/shirou/mqttcli)  |
|hbase|  [https://github.com/tsuna/gohbase](https://github.com/tsuna/gohbase)  |
|go 性能上报到influxdb|  [https://github.com/rcrowley/go-metrics](https://github.com/rcrowley/go-metrics)  |
|go 性能上报到prometheus|  [https://github.com/deathowl/go-metrics-prometheus](https://github.com/deathowl/go-metrics-prometheus)  |
|ps utils|  [https://github.com/shirou/gopsutil](https://github.com/shirou/gopsutil)  |
|小数处理|  [https://github.com/shopspring/decimal](https://github.com/shopspring/decimal)  |
| 结构化日志处理(json)|  [https://github.com/sirupsen/logrus](https://github.com/sirupsen/logrus)  |
| 命令行程序框架 cli |  [https://github.com/urfave/cli](https://github.com/urfave/cli)  |
| 命令行程序框架  cobra|  [https://github.com/spf13/cobra](https://github.com/spf13/cobra)  |




<br> </br> 
<a name="框架"></a>  <a name="框架"></a> 
3. 必看项目
|    项目  |   地址  | 说明| 
|:---------:|:------:|:------:|
|gin |  [github.com/gin-gonic/gin](https://github.com/gin-gonic/gin)  | 轻量级web框架，很多公司都是基于它进行魔改 |
|beego   |  [github.com/beego/beego](https://github.com/beego/beego)  | 也是web框架，比较全能 | 
|kratos   |  [github.com/go-kratos/kratos](https://github.com/go-kratos/kratos)  | bilibili开源的微服务框架，b站出品必属于精品 | 
|TiDB   |  [github.com/pingcap/tidb](https://github.com/pingcap/tidb)  | 见识过mysql性能瓶颈之后你会想要选择的一款数据库 |

<br> </br> 
<a name="完整包"></a>  <a name="完整包"></a> 
4. 完整标准库列表 
|    包  |   子包  |   说明  |  
|:---------:|:------:|:------: |   
|  bufio   | bytes | 提供了对字节切片操作的函数 |  
|     | crypto | 收集了常见的加密常数 |  
|     | errors | 实现了操作错误的函数 |  
|     | Expvar | 为公共变量提供了一个标准的接口，如服务器中的运算计数器 |  
|     | flag | 实现了命令行标记解析 |  
|     | fmt | 实现了格式化输入输出 |  
|     | hash | 提供了哈希函数接口 |  
|     | html | 实现了一个HTML5兼容的分词器和解析器 |  
|     | image | 实现了一个基本的二维图像库 |  
|     | io | 提供了对I/O原语的基本接口 |  
|     | log | 它是一个简单的记录包，提供最基本的日志功能 |  
|     | math | 提供了一些基本的常量和数学函数 |  
|     | mine | 实现了部分的MIME规范 |  
|     | net | 提供了一个对UNIX网络套接字的可移植接口，包括TCP/IP、 UDP域名解析和UNIX域套接字 |  
|     | os | 为操作系统功能实现了一个平台无关的接口 |  
|     | path | 实现了对斜线分割的文件名路径的操作 |  
|     | reflect | 实现了运行时反射，允许一个程序以任意类型操作对象 |  
|     | regexp | 实现了一个简单的正则表达式库 |  
|     | runtime | 包含与Go运行时系统交互的操作，如控制goroutine的函数 |  
|     | sort | 提供对集合排序的基础函数集 |  
|     | strconv | 实现了在基本数据类型和字符串之间的转换 |  
|     | strings | 实现了操作字符串的简单函数 |  
|     | sync | 提供了基本的同步机制，如互斥锁 |  
|     | syscall | 包含一个低级的操作系统原语的接口 |  
|     | testing | 提供对自动测试Go包的支持 |  
|     | time | 提供测量和显示时间的功能 |  
|     | unicode | Unicode编码相关的基础函数 |  
| archive | tar | 实现对tar压缩文档的访问 |  
|     | zip | 提供对ZIP压缩文档的读和写支持 |  
| compress | bzip2  |  实现了bzip2解压缩
|     | flate | 实现了RFC 1951中所定义的DEFLATE压缩数据格式 |  
|     | gzip | 实现了RFC 1951中所定义的gzip格式压缩文件的读和写 |  
|     | lzw | 实现了 Lempel-Ziv-Welch编码格式的压缩的数据格式 |  
|     | zlib | 实现了RFC 1950中所定义的zlib格式压缩数据的读和写 |  
| container | heap | 提供了实现heap.Interface接口的任何类型的堆操作 |  
|     | lsit | 实现了一个双链表 |  
|     | ring | 实现了对循环链表的操作 |  
| crypto | aes | 实现了AES加密（以前的Rijndael） |  
|     | cipher | 实现了标准的密码块模式，该模式可包装进低级的块加密实现中 |  
|     | des | 实现了数据加密标准（ Data Encryption Standard，DES）和三重数据加密算法（ TripleData Encryption Algorithm， TDEA） |  
|     | dsa | 实现了FIPS 186-3所定义的数据签名算法（ Digital Signature Algorithm） |  
|     | ecdsa | 实现了FIPS 186-3所定义的椭圆曲线数据签名算法（ Elliptic Curve Digital SignatureAlgorithm） |  
|     | elliptic | 实现了素数域上几个标准的椭圆曲线 |  
|     | hmac | 实现了键控哈希消息身份验证码（ Keyed-Hash Message Authentication Code，HMAC） |  
|     | md5 | 实现了RFC 1321中所定义的MD5哈希算法 |  
|     | rand | 实现了一个加密安全的伪随机数生成器 |  
|     | rc4  | 实现了RC4加密，其定义见Bruce Schneier的应用密码学（ Applied  Cryptography） |  
|     | rsa | 实现了PKCS#1中所定义的RSA加密 |  
|     | sha1 | 实现了RFC 3174中所定义的SHA1哈希算法 |  
|     | sha256  | 实现了FIPS 180-2中所定义的SHA224和SHA256哈希算法 |  
|     | sha512  | 实现了FIPS  180-2中所定义的SHA384和SHA512哈希算法 |  
|     | subtle | 实现了一些有用的加密函数，但需要仔细考虑以便正确应用它们 |  
|     | tls | 部分实现了RFC  4346所定义的TLS 1.1协议 |  
|     | x509  |  可解析X.509编码的键值和证书
|     | x509/pkix | 包含用于对X.509证书、 CRL和OCSP的ASN.1解析和序列化的共享的、低级的结构 |  
| database | sql | 围绕SQL提供了一个通用的接口 |  
|     | sql/driver | 定义了数据库驱动所需实现的接口，同sql包的使用方式 |  
| debug | dwarf | 提供了对从可执行文件加载的DWARF调试信息的访问，这个包对于实现Go语言的调试器非常有价值 |  
|     | elf | 实现了对ELF对象文件的访问。 ELF是一种常见的二进制可执行文件和共享库的文件格式。 Linux采用了ELF格式 |  
|     | gosym | 访问Go语言二进制程序中的调试信息。对于可视化调试很有价值 |  
|     | macho | 实现了对[Mach-O对象文件](http://developer.apple.com/mac/library/documentation/DeveloperTools/Conceptual/MachORuntime/Reference/reference.html)的访问 |  
|     | pe | 实现了对PE（ Microsoft Windows Portable Executable）文件的访问 |  
| encoding | ascii85 | 实现了ascii85数据编码，用于btoa工具和Adobe’s PostScript以及PDF文档格式 |  
|     | asn1 | 实现了解析DER编码的ASN.1数据结构，其定义见ITU-T Rec X.690 |  
|     | base32 | 实现了RFC 4648中所定义的base32编码 |  
|     | base64 | 实现了RFC 4648中所定义的base64编码 |  
|     | binary | 实现了在无符号整数值和字节串之间的转化，以及对固定尺寸值的读和写 |  
|     | csv | 可读和写由逗号分割的数值（ csv）文件 |  
|     | gob | 管理gob流——在编码器（发送者）和解码器（接收者）之间进行二进制值交换 |  
|     | hex | 实现了十六进制的编码和解码 |  
|     | json | 实现了定义于RFC 4627中的JSON对象的编码和解码 |  
|     | pem | 实现了PEM（ Privacy Enhanced Mail）数据编码 |  
|     | xml | 实现了一个简单的可理解XML名字空间的XML 1.0解析器 |  
| go | ast | 声明了用于展示Go包中的语法树类型 |  
|     | build | 提供了构建Go包的工具 |  
|     | doc | 从一个Go AST（抽象语法树）中提取源代码文档 |  
|     | parser | 实现了一个Go源文件解析器 |  
|     | printer | 实现了对AST（抽象语法树）的打印 |  
|     | scanner | 实现了一个Go源代码文本的扫描器 |  
|     | token | 定义了代表Go编程语言中词法标记以及基本操作标记（ printing、 predicates）的常量 |  
| hash | adler32  | 实现了Adler-32校验和 |  
|     | crc32  | 实现了32位的循环冗余校验或CRC-32校验和 |  
|     | crc64  | 实现了64位的循环冗余校验或CRC-64校验和 |  
|     | fnv | 实现了Glenn Fowler、 Landon Curt Noll和Phong Vo所创建的FNV-1和FNV-1a未加密哈希函数 |  
| html | template | 它自动构建HTML输出，并可防止代码注入 |  
| image | color | 实现了一个基本的颜色库 |  
|     | draw | 提供一些做图函数 |  
|     | gif | 实现了一个GIF图像解码器 |  
|     | jpeg | 实现了一个JPEG图像解码器和编码器 |  
|     | png | 实现了一个PNG图像解码器和编码器 |  
| index | suffixarray | 通过构建内存索引实现的高速字符串匹配查找算法 |  
| io | ioutil | 实现了一些实用的I/O函数 |  
| log | syslog | 提供了对系统日志服务的简单接口 |  
| math | big | 实现了多精度的算术运算（大数） |  
|     | cmplx | 为复数提供了基本的常量和数学函数 |  
|     | rand | 实现了伪随机数生成器 |  
| mime | multipart | 实现了在RFC 2046中定义的MIME多个部分的解析 |  
| net | http | 提供了HTTP客户端和服务器的实现 |  
|     | mail | 实现了对邮件消息的解析 |  
|     | rpc | 提供了对一个来自网络或其他I/O连接的对象可导出的方法的访问 |  
|     | smtp | 实现了定义于RFC 5321中的简单邮件传输协议（ Simple Mail Transfer Protocol) |  
|     | textproto | 实现了在HTTP、 NNTP和SMTP中基于文本的通用的请求/响应协议 |  
|     | url | 解析URL并实现查询转义 |  
|     | http/cgi | 实现了定义于RFC 3875中的CGI（通用网关接口） |  
|     | http/fcgi | 实现了FastCGI协议 |  
|     | http/httptest | 提供了一些HTTP测试应用 |  
|     | http/httputil | 提供了一些HTTP应用函数，这些是对net/http包中的东西的补充，只不过相对不太常用 |  
|     | http/pprof | 通过其HTTP服务器运行时提供性能测试数据，该数据的格式正是pprof可视化工具需要的 |  
|     | rpc/jsonrpc | 为rpc包实现了一个JSON-RPC ClientCodec和ServerCodec |  
| os | exec | 可运行外部命令 |  
|     | user | 通过名称和id进行用户账户检查 |  
| path | filepath | 实现了以与目标操作系统定义文件路径相兼容的方式处理文件名路径 |  
| regexp | syntax | 将正则表达式解析为语法树 |  
| runtime | debug | 包含当程序在运行时调试其自身的功能 |  
|     | pprof | 以pprof可视化工具需要的格式写运行时性能测试数据 |  
| sync | atomic | 提供了低级的用于实现同步算法的原子级的内存机制 |  
| testing | iotest | 提供一系列测试目的的类型，实现了Reader和Writer标准接口 |  
|     | quick | 实现了用于黑箱测试的实用函数 |  
|     | script | 帮助测试使用通道的代码 |  
| text | scanner | 为UTF-8文本提供了一个扫描器和分词器 |  
|     | tabwriter | 实现了一个写筛选器（ tabwriter.Writer），它可将一个输入的tab分割的列翻译为适当对齐的文本 |  
|     | template | 数据驱动的模板引擎，用于生成类似HTML的文本输出格式 |  
|     | template/parse | 为template构建解析树 |  
|     | unicode/utf16| 实现了UTF-16序列的的编码和解码 |  
|     | unicode/utf8| 实现了支持以UTF-8编码的文本的函数和常数 |  







<br> </br> 
<a name="优秀的开源库"></a>  <a name="优秀的开源库"></a> 
5. 其他优秀的开源工具分类
- 音频和音乐
<a name="音频和音乐"></a>  <a name="音频和音乐"></a> 

|    包  |   说明  |   
|:---------:|:------:|  
|   [EasyMIDI](https://github.com/algoGuy/EasyMIDI) |  EasyMidi是一个简单可靠的库，用于处理标准Midi文件（SMF）。| 
|   [flac](https://github.com/mewkiz/flac) |  支持FLAC流的Native Go FLAC编码器/解码器。| 
|   [gaad](https://github.com/Comcast/gaad) |  本机Go AAC比特流解析器。| 
|   [go-sox](https://github.com/krig/go-sox) |  用于go的libsox绑定。| 
|   [go_mediainfo](https://github.com/zhulik/go_mediainfo) |  用于go的libmediainfo绑定。| 
|   [gosamplerate](https://github.com/dh1tw/gosamplerate) |  用于go的libsamplerate绑定。| 
|   [id3v2](https://github.com/bogem/id3v2) |  用于Go的快速，稳定的ID3解析和编写库。| 
|   [malgo](https://github.com/gen2brain/malgo) |  迷你音频库。| 
|   [minimp3](https://github.com/tosone/minimp3) |  轻量级MP3解码器库。| 
|   [mix](https://github.com/go-mix/mix) |  为音乐应用程序基于序列转到本地音频混合器。| 
|   [mp3](https://github.com/tcolgate/mp3) |  Native Go MP3解码器。| 
|   [music-theory](https://github.com/go-music-theory/music-theory) |  Go中的音乐理论模型。| 
|   [Oto](https://github.com/hajimehoshi/oto) |  在多个平台上播放声音的低级库。| 
|   [PortAudio](https://github.com/gordonklaus/portaudio) |  用于PortAudio音频I / O库的绑定。| 
|   [portmidi](https://github.com/rakyll/portmidi) |  绑定PortMidi。| 
|   [taglib](https://github.com/wtolson/go-taglib) |  为taglib绑定。| 
|   [vorbis](https://github.com/mccoyst/vorbis) |  “本机” Go Vorbis解码器（使用CGO，但没有依赖项）。| 
|   [waveform](https://github.com/mdlayher/waveform) |  Go程序包，能够从音频流生成波形图像。| 


- 数据结构
<a name="数据结构"></a>  <a name="数据结构"></a> 

|    包  |   说明  | 
|:---------:|:------:|
|   [algorithms](https://github.com/shady831213/algorithms) |  算法和数据结构。CLRS研究。| 
|   [binpacker](https://github.com/zhuangsirui/binpacker) |  二进制打包程序和解包程序可帮助用户构建自定义二进制流。| 
|   [bit](https://github.com/yourbasic/bit) |  具有额外的位旋转功能的Golang设置数据结构。| 
|   [bitset](https://github.com/willf/bitset) |  实现位集的Go包。| 
|   [bloom](https://github.com/zhenjl/bloom) |  在Go中实现的Bloom过滤器。| 
|   [bloom](https://github.com/yourbasic/bloom) |  Golang Bloom过滤器实现。| 
|   [boomfilters](https://github.com/tylertreat/BoomFilters) |  用于处理连续无界流的概率数据结构。| 
|   [concurrent-writer](https://github.com/free/concurrent-writer) |高并发直接替换bufio.Writer。| 
|   [conjungo](https://github.com/InVisionApp/conjungo) |  一个小型，强大而灵活的合并库。| 
|   [count-min-log](https://github.com/seiflotfy/count-min-log) |  执行Count-Min-Log草图：使用近似计数器进行近似计数（类似于Count-Min草图，但使用较少的内存）。| 
|   [crunch](https://github.com/superwhiskers/crunch) |  Go包实现了用于轻松处理各种数据类型的缓冲区。| 
|   [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) |  Cuckoo过滤器：是Go中实现的计数布隆过滤器的很好替代。| 
|   [deque](https://github.com/edwingeng/deque) |  高度优化的双端队列。| 
|   [deque](https://github.com/gammazero/deque) |  快速的环形缓冲区双端队列（双端队列）。| 
|   [dict](https://github.com/srfrog/dict) |  Go的类似Python的字典（dict）。| 
|   [encoding](https://github.com/zhenjl/encoding) |  Go的整数压缩库。| 
|   [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) |  自适应基数树的 Go实现。| 
|   [go-datastructures](https://github.com/Workiva/go-datastructures) |  有用，高性能和线程安全的数据结构的集合。| 
|   [go-ef](https://github.com/amallia/go-ef) |  Elias-Fano编码的Go实现。| 
|   [go-geoindex](https://github.com/hailocab/go-geoindex) |  内存中的地理索引。| 
|   [go-mcache](https://github.com/OrlovEvgeny/go-mcache) |  快速内存键：值存储/缓存库。指针缓存。| 
|   [go-rquad](https://github.com/aurelien-rainone/go-rquad) |  具有有效点定位和邻居发现功能的区域四叉树。| 
|   [gocache](https://github.com/eko/gocache) |  具有多个存储（内存，memcache，redis等），可链接，可加载，指标缓存等的完整Go缓存库。| 
|   [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) |  并发FIFO队列。| 
|   [gods](https://github.com/emirpasic/gods) |  数据结构。容器，集合，列表，堆栈，地图，BidiMap，树，HashSet等。| 
|   [gofal](https://github.com/xxjwxc/gofal) |  Go的小数api。| 
|   [golang-set](https://github.com/deckarep/golang-set) |  Go的线程安全和非线程安全高性能集。| 
|   [goset](https://github.com/zoumo/goset) |  Go的有用的Set集合实现。| 
|   [goskiplist](https://github.com/ryszard/goskiplist) |  Go中的跳过列表实现。| 
|   [gota](https://github.com/kniren/gota) |  Go的数据框，序列和数据整理方法的实现。| 
|   [hide](https://github.com/emvi/hide) |  ID类型，将其编组进/出哈希以防止将ID发送给客户端。| 
|   [hilbert](https://github.com/google/hilbert) |  Go程序包，用于在空间填充曲线（例如Hilbert和Peano曲线）之间映射值。| 
|   [hyperloglog](https://github.com/axiomhq/hyperloglog) |  HyperLogLog实施，具有稀疏，LogLog-Beta偏差校正和TailCut空间减少功能。| 
|   [iter](https://github.com/disksing/iter) |  C ++ STL迭代器和算法的实现。| 
|   [levenshtein](https://github.com/agext/levenshtein) |  Levenshtein距离和相似性度量标准，具有可自定义的编辑费用和通用前缀的类似于Winkler的奖金。| 
|   [levenshtein](https://github.com/agnivade/levenshtein) |  在Go中计算levenshtein距离的实现。| 
|   [mafsa](https://github.com/smartystreets/mafsa) |  具有最小完美散列的MA-FSA实现。| 
|   [merkletree](https://github.com/cbergoon/merkletree) |  merkle树的实现，可对数据结构的内容进行有效且安全的验证。| 
|   [mspm](https://github.com/BlackRabbitt/mspm) |  用于信息检索的多字符串模式匹配算法。| 
|   [null](https://github.com/emvi/null) |  可空转到类型，可以被编组/解组到/从JSON。| 
|   [parsefields](https://github.com/MonaxGT/parsefields) |  用于解析类似JSON的日志的工具，以收集唯一的字段和事件。| 
|   [pipeline](https://github.com/hyfather/pipeline) |  具有扇入和扇出的管线的实现。| 
|   [ptrie](https://github.com/viant/ptrie) |  前缀树的实现。| 
|   [remember-go](https://github.com/rocketlaunchr/remember-go) |  缓存慢速数据库查询的通用接口（由redis，memcached，ristretto或内存支持）。| 
|   [ring](https://github.com/TheTannerRyan/ring) |  围棋实现了高性能，线程安全的布隆过滤器。| 
|   [roaring](https://github.com/RoaringBitmap/roaring) |  实施压缩位集的软件包。| 
|   [set](https://github.com/StudioSol/set) |  使用LinkedHashMap的围棋设置简单的数据结构实现。| 
|   [skiplist](https://github.com/MauriceGit/skiplist) |  非常快的Go Skiplist实施。| 
|   [skiplist](https://github.com/gansidui/skiplist) |  Go中的跳过列表实现。| 
|   [timedmap](https://github.com/zekroTJA/timedmap) |  具有过期的键/值对的地图。| 
|   [treap](https://github.com/perdata/treap) |  使用树堆的持久快速排序的地图。| 
|   [trie](https://github.com/derekparker/trie) |  Go中的Trie实现。| 
|   [ttlcache](https://github.com/diegobernardes/ttlcache) |  内存中的LRU字符串接口{}映射，其中包含golang的到期时间。| 
|   [typ](https://github.com/gurukami/typ) |  空类型，安全的原始类型转换和从复杂结构中获取值。| 
|   [willf/bloom](https://github.com/willf/bloom) |  Go包实现Bloom过滤器。| 
 
- 分布式系统
<a name="分布式系统"></a>  <a name="分布式系统"></a> 

|    包  |   说明  | 
|:---------:|:------:|
|   [celeriac](https://github.com/svcavallar/celeriac.v1) |  用于在Go中添加支持以交互和监视Celery工作者，任务和事件的库。| 
|   [consistent](https://github.com/buraksezer/consistent) |  具有受限负载的一致哈希| 
|   [dht](https://github.com/anacrolix/dht) |  BitTorrent Kademlia DHT实施。| 
|   [digota](https://github.com/digota/digota) |  grpc电子商务微服务。| 
|   [dot](https://github.com/dotchain/dot/) |  使用操作转换/ OT进行分布式同步。| 
|   [doublejump](https://github.com/edwingeng/doublejump) |  改进后的Google的跳转一致性哈希。| 
|   [dragonboat](https://github.com/lni/dragonboat) |  Go中功能齐全的高性能多组Raft库。| 
|   [drmaa](https://github.com/dgruber/drmaa) |  基于DRMAA标准的集群调度程序的作业提交库。| 
|   [dynamolock](https://cirello.io/dynamolock) |  DynamoDB支持的分布式锁定实现。| 
|   [dynatomic](https://github.com/tylfin/dynatomic) |  将DynamoDB用作原子计数器的库。| 
|   [emitter-io](https://github.com/emitter-io/emitter) |  使用MQTT，Websockets和love构建的高性能，分布式，安全和低延迟的发布-订阅平台。| 
|   [flowgraph](https://github.com/vectaport/flowgraph) |  基于流的编程包。| 
|   [gleam](https://github.com/chrislusf/gleam) |  用纯围棋和Luajit快速和可扩展的分布式的map / reduce系统，具有Luajit的高性能结合Go的高并发，单独运行或分发。| 
|   [glow](https://github.com/chrislusf/glow) |  易于使用的可扩展的分布式大数据处理，Map-Reduce，DAG执行，全部在纯Go中进行。| 
|   [go-health](https://github.com/InVisionApp/go-health) |  health-用于在服务中启用异步依赖项运行状况检查的库。| 
|   [go-jump](https://github.com/dgryski/go-jump) |  Google的“ Jump”一致性哈希函数的端口。| 
|   [go-kit](https://github.com/go-kit/kit) | 支持服务发现，负载平衡，可插拔传输，请求跟踪等的微服务工具包| 
|   [go-sundheit](https://github.com/AppsFlyer/go-sundheit) |  建立用于支持为golang服务定义异步服务运行状况检查的库。| 
|   [gorpc](https://github.com/valyala/gorpc) |  简单，快速和可扩展的RPC库，可实现高负载。| 
|   [grpc-go](https://github.com/grpc/grpc-go) |  gRPC的Go语言实现。基于HTTP / 2的RPC。| 
|   [hprose](https://github.com/hprose/hprose-golang) |  十分新颖的RPC库，现在支持25种以上的语言。| 
|   [jsonrpc](https://github.com/osamingo/jsonrpc) |  jsonrpc软件包可帮助实现JSON-RPC 2.0。| 
|   [jsonrpc](https://github.com/ybbus/jsonrpc) |  JSON-RPC 2.0 HTTP客户端实现。| 
|   [KrakenD](https://github.com/devopsfaith/krakend) |  具有中间件的超高性能API网关框架。| 
|   [liftbridge](https://github.com/liftbridge-io/liftbridge) |  NATS的轻量级，容错消息流。| 
|   [micro](https://github.com/micro/micro) |  可插拔的microService工具箱和分布式系统平台。| 
|   [NATS](https://github.com/nats-io/gnatsd) |  用于微服务，IoT和云本机系统的轻量级高性能消息传递系统。| 
|   [outboxer](https://github.com/italolelis/outboxer) |  Outboxer是一个实现库模式的go库。| 
|   [pglock](https://cirello.io/pglock) |  PostgreSQL支持的分布式锁定实现。| 
|   [raft](https://github.com/hashicorp/raft) |  HashiCorp的Raft共识协议的Golang实现。| 
|   [raft](https://github.com/coreos/etcd/tree/master/raft) |  ETCD中实现的Raft协议。| 
|   [rain](https://github.com/cenkalti/rain) |  BitTorrent客户端和库。| 
|   [redis-lock](https://github.com/bsm/redislock) |  使用Redis的简化分布式锁定实现。| 
|   [resgate](https://resgate.io/) |  用于构建REST，实时和RPC API的实时API网关，其中所有客户端都可以无缝同步。| 
|   [ringpop-go](https://github.com/uber/ringpop-go) |  Go应用程序的可扩展，容错应用程序层分片。| 
|   [rpcx](https://github.com/smallnest/rpcx) |  分布式可插拔RPC服务框架，例如阿里巴巴Dubbo。| 
|   [sleuth](https://github.com/ursiform/sleuth) |  用于在HTTP服务之间进行无主p2p自动发现和RPC的库（[ZeroMQ](https://github.com/zeromq/libzmq)）。| 
|   [tendermint](https://github.com/tendermint/tendermint) |  高性能中间件，用于使用Tendermint共识和区块链协议将以任何编程语言编写的状态机转换为拜占庭容错复制状态机。| 
|   [torrent](https://github.com/anacrolix/torrent) |  BitTorrent客户端软件包。| 

- 电子邮件
<a name="电子邮件"></a>  <a name="电子邮件"></a> 

|    包  |   说明  | 
|:---------:|:------:|
|   [chasquid](https://blitiri.com.ar/p/chasquid) |  用Go编写的SMTP服务器。| 
|   [douceur](https://github.com/aymerick/douceur) |  CSS内衬为您的HTML电子邮件。| 
|   [email](https://github.com/jordan-wright/email) |  用于Go的强大而灵活的电子邮件库。| 
|   [go-dkim](https://github.com/toorop/go-dkim) |  DKIM库，用于签名和验证电子邮件。| 
|   [go-imap](https://github.com/emersion/go-imap) |  用于客户端和服务器的IMAP库。| 
|   [go-message](https://github.com/emersion/go-message) |  Internet消息格式和邮件消息的流库。| 
|   [go-premailer](https://github.com/vanng822/go-premailer) |  Go中HTML邮件的内联样式。| 
|   [go-simple-mail](https://github.com/xhit/go-simple-mail) |  使用SMTP保持活动状态和两个超时发送电子邮件的非常简单的程序包：连接和发送。| 
|   [Hectane](https://github.com/hectane/hectane) |  提供HTTP API的轻型SMTP客户端。| 
|   [hermes](https://github.com/matcornic/hermes) |  Golang软件包，可生成干净的响应式HTML电子邮件。| 
|   [mailchain](https://github.com/mailchain/mailchain) |  将加密的电子邮件发送到用Go编写的区块链地址。| 
|   [mailgun-go](https://github.com/mailgun/mailgun-go) |  Go库，用于使用Mailgun API发送邮件。| 
|   [MailHog](https://github.com/mailhog/MailHog) |  通过Web和API界面进行电子邮件和SMTP测试。| 
|   [SendGrid](https://github.com/sendgrid/sendgrid-go) |  SendGrid的Go库，用于发送电子邮件。| 
|   [smtp](https://github.com/mailhog/smtp) |  SMTP服务器协议状态机。| 

- 嵌入式脚本语言
<a name="嵌入式脚本语言"></a>  <a name="嵌入式脚本语言"></a> 

|    包  |   说明  | 
|:---------:|:------:|
|   [anko](https://github.com/mattn/anko) |  用Go语言编写的可编写脚本的解释器。| 
|   [binder](https://github.com/alexeyco/binder) |  转到基于[gopher-lua](https://github.com/yuin/gopher-lua)的 Lua绑定库。| 
|   [cel-go](https://github.com/google/cel-go) |  具有渐进式输入功能的快速，便携式，非图灵完整表达评估。| 
|   [expr](https://github.com/antonmedv/expr) |  可以评估表达式的引擎。| 
|   [gentee](https://github.com/gentee/gentee) |  可嵌入的脚本编程语言。| 
|   [gisp](https://github.com/jcla1/gisp) |  Go中的简单LISP。| 
|   [go-duktape](https://github.com/olebedev/go-duktape) |  Go的Duktape JavaScript引擎绑定。| 
|   [go-lua](https://github.com/Shopify/go-lua) |  Lua 5.2 VM到纯Go的端口。| 
|   [go-php](https://github.com/deuill/go-php) |  Go的PHP绑定。| 
|   [go-python](https://github.com/sbinet/go-python) |  与CPython C-API的幼稚go绑定。| 
|   [golua](https://github.com/aarzilli/golua) |  Lua C API的绑定。| 
|   [gopher-lua](https://github.com/yuin/gopher-lua) |  用Go编写的Lua 5.1 VM和编译器。| 
|   [gval](https://github.com/PaesslerAG/gval) |  用Go编写的高度可定制的表达语言。| 
|   [ngaro](https://github.com/db47h/ngaro) |  可嵌入的Ngaro VM实现，支持在Retro中编写脚本。| 
|   [otto](https://github.com/robertkrimen/otto) |  用Go编写的JavaScript解释器。| 
|   [purl](https://github.com/ian-kent/purl) |  Go中嵌入的Perl 5.18.2。| 
|   [tengo](https://github.com/d5/tengo) |  用于Go的字节码编译脚本语言。| 


- 错误处理
<a name="错误处理"></a>  <a name="错误处理"></a> 

|    包  |   说明  | 
|:---------:|:------:|
|   [emperror](https://github.com/emperror/emperror) |  Go库和应用程序的错误处理工具和最佳实践。| 
|   [errlog](https://github.com/snwfdhmp/errlog) |  可破解的软件包，用于确定错误的负责任的源代码（以及其他一些快速调试功能）。可插入任何现成的记录器。| 
|   [errors](https://github.com/emperror/errors) |  下拉更换为标准库的错误包和github.com/pkg/errors。提供各种错误处理原语。| 
|   [errors](https://github.com/pkg/errors) |  提供简单错误处理原语的软件包。| 
|   [errors](https://github.com/neuronlabs/errors) |  简单golang错误处理与分类元。| 
|   [errorx](https://github.com/joomcode/errorx) |  具有堆栈跟踪，错误组成等的功能丰富的错误包。| 
|   [Falcon](https://github.com/SonicRoshan/falcon) |  一个简单但功能强大的错误处理软件包。| 
|   [go-multierror](https://github.com/hashicorp/go-multierror) |  Go（golang）软件包，用于将错误列表表示为单个错误。| 
|   [tracerr](https://github.com/ztrue/tracerr) |  带有堆栈跟踪和源代码片段的Golang错误。| 
|   [werr](https://github.com/txgruppi/werr) |  错误包装程序为Go中的错误类型创建了一个包装程序，该包装程序捕获了调用它的文件，行和堆栈。| 


- 文件
<a name="文件"></a>  <a name="文件"></a> 

|    包  |   说明  | 
|:---------:|:------:|
|   [afero](https://github.com/spf13/afero) |  Go的文件系统抽象系统。| 
|   [afs](https://github.com/viant/afs) |  Go的抽象文件存储（mem，scp，zip，tar，云：s3，gs）。| 
|   [bigfile](https://github.com/bigfile/bigfile) |  文件传输系统，支持使用http api，rpc调用和ftp客户端管理文件。| 
|   [checksum](https://github.com/codingsince1985/checksum) |  计算大型文件的消息摘要，例如MD5和SHA256。| 
|   [flop](https://github.com/homedepot/flop) |  文件操作库，旨在与[GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html)镜像功能奇偶校验。| 
|   [go-csv-tag](https://github.com/artonge/go-csv-tag) |  tag-使用标签加载csv文件。| 
|   [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) |  复制human文件。| 
|   [go-exiftool](https://github.com/barasher/go-exiftool) |  ExifTool的Go绑定，这是众所周知的库，用于从文件（图片，PDF，office，...）提取尽可能多的元数据（EXIF，IPTC等）。| 
|   [go-gtfs](https://github.com/artonge/go-gtfs) |  在go中加载gtfs文件。| 
|   [notify](https://github.com/rjeczalik/notify) |  具有简单API的文件系统事件通知库，类似于os / signal。| 
|   [opc](https://github.com/qmuntal/opc) |  为Go加载Open Packaging Conventions（OPC）文件。| 
|   [parquet](https://github.com/parsyl/parquet) |  读取和写入 [parquet](https://parquet.apache.org/)文件。| 
|   [pdfcpu](https://github.com/hhrutter/pdfcpu) |  PDF 处理器。| 
|   [skywalker](https://github.com/dixonwille/skywalker) |  一种软件包，允许一个人轻松地同时通过文件系统。| 
|   [stl](https://gitlab.com/russoj88/stl) |  读取和写入STL（立体光刻）文件的模块。并发读取算法。| 
|   [tarfs](https://github.com/posener/tarfs) |  tar文件[`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem)接口的实现。| 
|   [vfs](https://github.com/C2FO/vfs) |  跨多种文件系统类型（例如os，S3和GCS）的Go的一组可插拔，可扩展且自以为是的文件系统功能。| 
 
- 金融
<a name="金融"></a>  <a name="金融"></a> 

|    包  |   说明  | 
|:---------:|:------:|
|   [accounting](https://github.com/leekchan/accounting) |  golang的货币和货币格式。| 
|   [currency](https://github.com/bnkamalesh/currency) |  高性能和准确的货币计算包。| 
|   [decimal](https://github.com/shopspring/decimal) |  任意精度定点十进制数字。| 
|   [go-finance](https://github.com/FlashBoys/go-finance) |  Go中的综合金融市场数据。| 
|   [go-finance](https://github.com/alpeb/go-finance) |  金融功能库，用于货币时间价值（年金），现金流量，利率转换，债券和折旧计算。| 
|   [go-finance](https://github.com/pieterclaerhout/go-finance) |  获取汇率，通过VIES检查增值税号和检查IBAN银行帐号的模块。| 
|   [go-money](https://github.com/rhymond/go-money) |  Fowler的Money模式的实现。| 
|   [ofxgo](https://github.com/aclindsa/ofxgo) |  查询OFX服务器和/或解析响应（使用示例命令行客户端）。| 
|   [orderbook](https://github.com/i25959341/orderbook) |  匹配引擎的限价订单在Golang。| 
|   [techan](https://github.com/sdcoffey/techan) |  具有高级市场分析和交易策略的技术分析库。| 
|   [transaction](https://github.com/claygod/transaction) |  以多线程模式运行的嵌入式帐户嵌入式事务数据库。| 
|   [vat](https://github.com/dannyvankooten/vat) |  增值税号验证和欧盟增值税率。| 

- 游戏开发
<a name="游戏开发"></a>  <a name="游戏开发"></a> 

|    包  |   说明  | 
|:---------:|:------:|
|   [Azul3D](https://github.com/azul3d/engine) |  用Go语言编写的3D游戏引擎。| 
|   [Ebiten](https://github.com/hajimehoshi/ebiten) |  Go中死的简单2D游戏库。| 
|   [engo](https://github.com/EngoEngine/engo) |  Engo是用Go语言编写的开源2D游戏引擎。它遵循实体组件系统范式。| 
|   [g3n](https://github.com/g3n/engine) |  Go 3D游戏引擎。| 
|   [GarageEngine](https://github.com/vova616/GarageEngine) |  用Go语言编写的2D游戏引擎，可在OpenGL上使用。| 
|   [glop](https://github.com/runningwild/glop) |  Glop（权力游戏库）是一个相当简单的跨平台游戏库。| 
|   [go-astar](https://github.com/beefsack/go-astar) |  A 路径查找算法的Go实现。| 
|   [go-collada](https://github.com/GlenKelley/go-collada) |  Go包，用于Collada文件格式。| 
|   [go-sdl2](https://github.com/veandco/go-sdl2) | [Simple DirectMedia Layer](https://www.libsdl.org/)的 Go绑定。| 
|   [go3d](https://github.com/ungerik/go3d) |  用于Go的面向性能的2D/3D数学软件包。| 
|   [gonet](https://github.com/xtaci/gonet) |  使用golang实现的游戏服务器框架。| 
|   [goworld](https://github.com/xiaonanln/goworld) |可扩展的游戏服务器引擎，具有空间实体框架和热插拔功能。| 
|   [Leaf](https://github.com/name5566/leaf) |  轻量级游戏服务器框架。| 
|   [nano](https://github.com/lonng/nano) |  重量轻，设备，高性能的基于golang游戏服务器架构。| 
|   [Oak](https://github.com/oakmound/oak) |  Pure Go游戏引擎。| 
|   [Pitaya](https://github.com/topfreegames/pitaya) |  可扩展的游戏服务器框架，具有群集支持和通过C SDK的iOS，Android，Unity等客户端库。| 
|   [Pixel](https://github.com/faiface/pixel) |  Go中的手工制作2D游戏库。| 
|   [raylib-go](https://github.com/gen2brain/raylib-go) |  去绑定raylib，简单和易于使用的库，以了解电子游戏编程。| 
|   [termloop](https://github.com/JoelOtter/termloop) |  Go的基于终端的游戏引擎，建立在Termbox之上。| 

- 地理位置
<a name="地理位置"></a>  <a name="地理位置"></a> 

|    包  |   说明  | 
|:---------:|:------:|
|   [geocache](https://github.com/melihmucuk/geocache) |  适用于基于地理位置的应用程序的内存中缓存。| 
|   [geoserver](https://github.com/hishamkaram/geoserver) |  geoserver是Go软件包，用于通过GeoServer REST API操纵GeoServer实例。| 
|   [gismanager](https://github.com/hishamkaram/gismanager) |  将 GIS数据（矢量数据）发布到PostGIS和Geoserver。| 
|   [osm](https://github.com/paulmach/osm) |  用于读取，编写和使用OpenStreetMap数据和API的库。| 
|   [pbf](https://github.com/maguro/pbf) |  OpenStreetMap PBF golang编码器/解码器。| 
|   [S2 geometry](https://github.com/golang/geo) |  Go中的S2几何库。| 
|   [Tile38](https://github.com/tidwall/tile38) |  具有空间索引和实时地理围栏的地理位置数据库。| 
|   [WGS84](https://github.com/wroge/wgs84) |  库坐标转换和变换（ETRS89，OSGB36，NAD83，RGF93，网络墨卡托UTM）。| 

- 编译器
<a name="编译器"></a>  <a name="金编译器融"></a> 

|    包  |   说明  | 
|:---------:|:------:|
|   [c4go](https://github.com/Konstantin8105/c4go) |  将C代码转换为Go代码。| 
|   [f4go](https://github.com/Konstantin8105/f4go) |  将FORTRAN 77代码转换为Go代码。| 
|   [gopherjs](https://github.com/gopherjs/gopherjs) |  从Go到JavaScript的编译器。| 
|   [llgo](https://github.com/go-llvm/llgo) |  Go的基于LLVM的编译器。| 
|   [tardisgo](https://github.com/tardisgo/tardisgo) |  Golang转换为CPP / CSharp / Java / JavaScript转译器。| 

- Goroutines
<a name="Goroutines"></a>  <a name="Goroutines"></a> 

|    包  |   说明  | 
|:---------:|:------:|
|   [ants](https://github.com/panjf2000/ants) |  用于golang的高性能goroutine池。| 
|   [artifex](https://github.com/borderstech/artifex) |  Golang使用基于工作程序的分派的简单内存中作业队列。| 
|   [async](https://github.com/studiosol/async) |  一种异步执行功能的安全方法，以防万一。| 
|   [breaker](https://github.com/kamilsk/breaker) |  使执行流程可中断的灵活机制。| 
|   [cyclicbarrier](https://github.com/marusama/cyclicbarrier) |  用于golang的CyclicBarrier。| 
|   [go-floc](https://github.com/workanator/go-floc) |轻松编排goroutine。| 
|   [go-flow](https://github.com/kamildrazkiewicz/go-flow) |  控制goroutine的执行顺序。| 
|   [go-tools/multithreading](https://github.com/nikhilsaraf/go-tools) |  使用带有简单API的轻量级库管理goroutine池。| 
|   [go-trylock](https://github.com/subchen/go-trylock) |  支持Golang的读写锁的TryLock。| 
|   [go-waitgroup](https://github.com/pieterclaerhout/go-waitgroup) |sync.WaitGroup与错误处理和并发控制类似。| 
|   [gohive](https://github.com/loveleshsharma/gohive) |  Go的高性能和易于使用的Goroutine池。| 
|   [gollback](https://github.com/vardius/gollback) |  异步简单函数实用程序，用于管理闭包和回调的执行。| 
|   [GoSlaves](https://github.com/themester/GoSlaves) |  简单和异步Goroutine池库。| 
|   [goworker](https://github.com/benmanns/goworker) |  goworker是基于Go的后台工作者。| 
|   [gowp](https://github.com/xxjwxc/gowp) |  gowp是并发限制goroutine池。| 
|   [gpool](https://github.com/Sherifabdlnaby/gpool) |  管理可调整大小的上下文感知goroutine池以绑定并发。| 
|   [grpool](https://github.com/ivpusic/grpool) |  轻巧的Goroutine池。| 
|   [Hunch](https://github.com/AaronJan/Hunch) |  预感提供功能，如：All，First，Retry，Waterfall等等，这使得异步流控制更加直观。| 
|   [oversight](https://cirello.io/oversight) |  监督是Erlang监督树的完整实现。| 
|   [parallel-fn](https://github.com/rafaeljesus/parallel-fn) |  并行运行功能。| 
|   [pool](https://github.com/go-playground/pool) |  有限的消费者goroutine池或无限制的goroutine池，以便更轻松地处理和取消goroutine。| 
|   [queue](https://github.com/AnikHasibul/queue) |  为您提供sync.WaitGroup类似的队列组可访问性。帮助您节流和限制goroutine，等待所有goroutine结束等等。| 
|   [routine](https://github.com/x-mod/routine) |  具有上下文和支持的例程控制：Main，Go，Pool和一些有用的Executors。| 
|   [semaphore](https://github.com/kamilsk/semaphore) |  基于通道和上下文的具有锁定/解锁操作超时的信号量模式实现。| 
|   [semaphore](https://github.com/marusama/semaphore) |  基于CAS的快速可调整大小的信号量实现（比基于通道的信号量实现更快）。| 
|   [stl](https://github.com/ssgreg/stl) |  基于软件交易内存（STM）并发控制机制的软件交易锁。| 
|   [threadpool](https://github.com/shettyh/threadpool) |  Golang线程池实现。| 
|   [tunny](https://github.com/Jeffail/tunny) |  线程池golang。| 
|   [worker-pool](https://github.com/vardius/worker-pool) |  goworker是一个简单的Go异步工作池。| 
|   [workerpool](https://github.com/gammazero/workerpool) |  Goroutine池，它限制了任务执行的并发性，而不是排队的任务数。| 

- 图形界面
<a name="图形界面"></a>  <a name="图形界面"></a> 

|    包  |   说明  | 
|:---------:|:------:|
|   [app](https://github.com/murlokswarm/app) |  打包以使用GO，HTML和CSS创建应用的程序。支持：MacOS，Windows正在开发中。| 
|   [fyne](https://github.com/fyne-io/fyne) |  为Go设计的跨平台本机GUI，使用EFL呈现。支持：Linux，macOS，Windows。| 
|   [go-astilectron](https://github.com/asticode/go-astilectron) |  使用GO和HTML / JS / CSS（由Electron支持）构建跨平台GUI应用。| 
|   [go-gtk](http://mattn.github.io/go-gtk/) |  GTK的绑定。| 
|   [go-sciter](https://github.com/sciter-sdk/go-sciter) |  Go绑定：用于现代桌面UI开发的可嵌入HTML / CSS / script引擎。跨平台。| 
|   [gotk3](https://github.com/gotk3/gotk3) |  GTK3的绑定。| 
|   [gowd](https://github.com/dtylman/gowd) |  使用GO，HTML，CSS和NW.js进行快速简单的桌面UI开发。跨平台。| 
|   [qt](https://github.com/therecipe/qt) |  Go的Qt绑定（支持Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi）。| 
|   [ui](https://github.com/andlabs/ui) |  Go的平台本地GUI库。跨平台。| 
|   [Wails](https://wails.app/) |  使用内置OS HTML渲染器的HTML UI的Mac，Windows，Linux桌面应用程序。| 
|   [walk](https://github.com/lxn/walk) |  Go的Windows应用程序库工具包。| 
|   [webview](https://github.com/zserge/webview) |  具有简单双向JavaScript绑定的跨平台Webview窗口（Windows / macOS / Linux）。| 
|   [go-appindicator](https://github.com/dawidd6/go-appindicator) |  libappindicator3 C库的Go绑定。| 
|   [gosx-notifier](https://github.com/deckarep/gosx-notifier) |  Go的OSX桌面通知库。| 
|   [mac-activity-tracker](https://github.com/prashantgupta24/activity-tracker) |  OSX库，用于通知计算机上的任何（可插入）活动。| 
|   [mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier) |  golang中的OSX睡眠/唤醒通知。| 
|   [robotgo](https://github.com/go-vgo/robotgo) |  Go本机跨平台GUI系统自动化。控制鼠标，键盘等。| 
|   [systray](https://github.com/getlantern/systray) |  跨平台的Go库，用于在通知区域中放置图标和菜单。| 
|   [trayhost](https://github.com/shurcooL/trayhost) |  跨平台的Go库，用于在主机操作系统的任务栏中放置一个图标。| 

- 图片
<a name="图片"></a>  <a name="图片"></a> 

|    包  |   说明  | 
|:---------:|:------:|
|   [bild](https://github.com/anthonynsimon/bild) |  纯Go中图像处理算法的集合。| 
|   [bimg](https://github.com/h2non/bimg) |  使用libvips进行快速有效的图像处理的小包装。| 
|   [cameron](https://github.com/aofei/cameron) |  Go的头像生成器。| 
|   [canvas](https://github.com/tdewolff/canvas) |  将矢量图形转换为PDF，SVG或光栅图像。| 
|   [darkroom](https://github.com/gojek/darkroom) |  具有可变存储后端的图像代理和侧重于速度和弹性的图像处理引擎。| 
|   [geopattern](https://github.com/pravj/geopattern) |  从字符串创建漂亮的生成图像图案。| 
|   [gg](https://github.com/fogleman/gg) |  纯Go中的2D渲染。| 
|   [gift](https://github.com/disintegration/gift) |  图像处理过滤器的包装。| 
|   [gltf](https://github.com/qmuntal/gltf) |  高效，强大的glTF 2.0读取器，写入器和验证器。| 
|   [go-cairo](https://github.com/ungerik/go-cairo) |  用于cairo图形库的绑定。| 
|   [go-gd](https://github.com/bolknote/go-gd) |  GD库的Go绑定。| 
|   [go-nude](https://github.com/koyachi/go-nude) |  Go的裸露检测。| 
|   [go-opencv](https://github.com/lazywei/go-opencv) |  用于OpenCV的绑定。| 
|   [go-webcolors](https://github.com/jyotiska/go-webcolors) |  webcolors库的端口，从Python到Go。| 
|   [gocv](https://github.com/hybridgroup/gocv) |  使用OpenCV 3.3+进行计算机视觉的Go软件包。| 
|   [goimagehash](https://github.com/corona10/goimagehash) |  Go感知图像哈希包。| 
|   [goimghdr](https://github.com/corona10/goimghdr) |  imghdr模块确定Go文件中包含的图像类型。| 
|   [govatar](https://github.com/o1egl/govatar) |  用于生成有趣头像的库和CMD工具。| 
|   [image2ascii](https://github.com/qeesung/image2ascii) |  将图像转换为ASCII。| 
|   [imagick](https://github.com/gographics/imagick) |  绑定到ImageMagick的MagickWand C API。| 
|   [imaginary](https://github.com/h2non/imaginary) |  用于图像大小调整的快速，简单的HTTP微服务。| 
|   [imaging](https://github.com/disintegration/imaging) |  简单的Go图像处理包。| 
|   [img](https://github.com/hawx/img) |  选择图像处理工具。| 
|   [ln](https://github.com/fogleman/ln) |  Go中的3D线条艺术渲染。| 
|   [mergi](https://github.com/noelyahan/mergi) |  用于图像处理（合并，裁切，调整大小，水印，动画）的Tool＆Go库。| 
|   [mort](https://github.com/aldor007/mort) |  用Go编写的存储和图像处理服务器。| 
|   [mpo](https://github.com/donatj/mpo) |  用于MPO 3D照片的解码器和转换工具。| 
|   [picfit](https://github.com/thoas/picfit) |  用Go编写的图像大小调整服务器。| 
|   [pt](https://github.com/fogleman/pt) |  用Go语言编写的路径跟踪引擎。| 
|   [resize](https://github.com/nfnt/resize) |  使用常见的插值方法为Go 调整图像大小。| 
|   [rez](https://github.com/bamiaux/rez) |  在纯Go和SIMD中调整图像大小。| 
|   [smartcrop](https://github.com/muesli/smartcrop) |  查找适合任何图像和尺寸的优质作物。| 
|   [steganography](https://github.com/auyer/steganography) |  用于LSB隐写术的Pure Go库。| 
|   [stegify](https://github.com/DimitarPetrov/stegify) |  用于LSB隐写术的Go工具，能够隐藏图像中的任何文件。| 
|   [svgo](https://github.com/ajstarks/svgo) |  用于SVG生成的Go语言库。| 
|   [tga](https://github.com/ftrvxmtrx/tga) |  软件包tga是TARGA图像格式的解码器/编码器。| 

- 物联网
<a name="物联网"></a>  <a name="物联网"></a> 

|    包  |   说明  | 
|:---------:|:------:|
|   [connectordb](https://github.com/connectordb/connectordb) |  量化自我和物联网的开源平台。| 
|   [devices](https://github.com/goiot/devices) |  IoT设备库套件，针对x / exp / io进行实验。| 
|   [eywa](https://github.com/xcodersun/eywa) |  Project Eywa本质上是一个连接管理器，用于跟踪连接的设备。| 
|   [flogo](https://github.com/tibcosoftware/flogo) |  Project Flogo是一个用于IoT Edge应用和集成的开源框架。| 
|   [gatt](https://github.com/paypal/gatt) |  盖特是一个围棋包构建低功耗蓝牙外设。| 
|   [gobot](https://github.com/hybridgroup/gobot/) |  Gobot是机器人技术，物理计算和物联网的框架。| 
|   [huego](https://github.com/amimof/huego) |  适用于Go的飞利浦Hue扩展客户端库。| 
|   [iot](https://github.com/vaelen/iot/) |  IoT是用于实现Google IoT Core设备的简单框架。| 
|   [mainflux](https://github.com/Mainflux/mainflux) |  工业物联网消息和设备管理服务器。| 
|   [periph](https://periph.io/) |  外设I / O与低级别的主板设备接口。| 
|   [sensorbee](https://github.com/sensorbee/sensorbee) |  用于物联网的轻量级流处理引擎。| 

- JSON格式
<a name="JSON格式"></a>  <a name="JSON格式"></a> 

|    包  |   说明  | 
|:---------:|:------:|
|   [ajson](https://github.com/spyzhov/ajson) |  具有JSONPath支持的golang的抽象JSON。| 
|   [gjo](https://github.com/skanehira/gjo) |  用于创建JSON对象的小型实用程序。| 
|   [GJSON](https://github.com/tidwall/gjson) |  使用一行代码获取JSON值。| 
|   [go-jsonerror](https://github.com/ddymko/go-jsonerror) |  Go-JsonError可让我们轻松创建遵循JsonApi规范的json响应错误。| 
|   [go-respond](https://github.com/nicklaw5/go-respond) |  Go包，用于处理常见的HTTP JSON响应。| 
|   [gojq](https://github.com/elgs/gojq) |  Golang中的 JSON查询。| 
|   [gojson](https://github.com/ChimeraCoder/gojson) |  从示例JSON自动生成Go（golang）结构定义。| 
|   [JayDiff](https://github.com/yazgazan/jaydiff) |  用Go编写的JSON diff实用程序。| 
|   [jettison](https://github.com/wI2L/jettison) |  用于Go的高性能，无反射JSON编码器。| 
|   [JSON-to-Go](https://mholt.github.io/json-to-go/) |  将JSON转换为Go结构。| 
|   [json2go](https://github.com/m-zajac/json2go) |  高级JSON到Go结构转换。提供可以解析多个JSON文档并创建适合所有JSON的结构的包。| 
|   [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) |根据JSON API错误参考进行绑定。| 
|   [jsonf](https://github.com/miolini/jsonf) |  突出显示格式和获取JSON的结构查询的控制台工具。| 
|   [jsongo](https://github.com/ricardolonga/jsongo) |Fluent API，可以更轻松地创建Json对象。| 
|   [jsonhal](https://github.com/RichardKnop/jsonhal) |  简单的Go包，用于将自定义结构编组为HAL兼容的JSON响应。| 
|   [kazaam](https://github.com/Qntfy/kazaam) |  用于JSON文档的任意转换的API。| 
|   [mp](https://github.com/sanbornm/mp) |  简单的cli电子邮件解析器。当前，它使用标准输入并输出JSON。| 

- 机器学习
<a name="机器学习"></a>  <a name="机器学习"></a> 

|    包  |   说明  | 
|:---------:|:------:|
|   [bayesian](https://github.com/jbrukh/bayesian) |  贝叶斯分类为Golang天真。| 
|   [CloudForest](https://github.com/ryanbressler/CloudForest) |  快速，灵活，多线程的决策树集合，用于纯Go中的机器学习。| 
|   [eaopt](https://github.com/MaxHalford/eaopt) |  进化优化库。| 
|   [evoli](https://github.com/khezen/evoli) |  遗传算法和粒子群优化库。| 
|   [fonet](https://github.com/Fontinalis/fonet) |  用Go编写的深度神经网络库。| 
|   [go-cluster](https://github.com/e-XpertSolutions/go-cluster) |  k模式和k-原型聚类算法的Go实现。| 
|   [go-deep](https://github.com/patrikeh/go-deep) |  Go中功能丰富的神经网络库| 
|   [go-fann](https://github.com/white-pony/go-fann) |  快速人工神经网络（FANN）库的Go绑定。| 
|   [go-galib](https://github.com/thoj/go-galib) |  用Go / golang编写的遗传算法库。| 
|   [go-pr](https://github.com/daviddengcn/go-pr) |  Go lang中的模式识别包。| 
|   [gobrain](https://github.com/goml/gobrain) |  用go语言编写的神经网络| 
|   [godist](https://github.com/e-dard/godist) |  各种概率分布及相关方法。| 
|   [goga](https://github.com/tomcraven/goga) |  Go的遗传算法库。| 
|   [GoLearn](https://github.com/sjwhitworth/golearn) |用于Go的通用机器学习库。| 
|   [golinear](https://github.com/danieldk/golinear) |  Go的liblinear绑定。| 
|   [GoMind](https://github.com/surenderthakran/gomind) |  Go中的简单神经网络库。| 
|   [goml](https://github.com/cdipaolo/goml) |  Go中的在线机器学习。| 
|   [Goptuna](https://github.com/c-bata/goptuna) |  用于Go语言编写的黑盒函数的贝叶斯优化框架。一切都会被优化。| 
|   [goRecommend](https://github.com/timkaye11/goRecommend) |  用Go编写的推荐算法库。| 
|   [gorgonia](https://github.com/gorgonia/gorgonia) |  基于图形的计算库，例如Theano for Go，它提供了用于构建各种机器学习和神经网络算法的原语。| 
|   [gorse](https://github.com/zhenghaoz/gorse) |  基于Go编写的协作过滤的离线推荐系统后端。| 
|   [goscore](https://github.com/asafschers/goscore) |  用于PMML的Go Scoring API。| 
|   [gosseract](https://github.com/otiai10/gosseract) |  使用Tesseract C ++库的OCR（光学字符识别）软件包。| 
|   [libsvm](https://github.com/datastream/libsvm) |  基于LIBSVM 3.14 libsvm的golang版本衍生作品。| 
|   [neat](https://github.com/jinyeom/neat) |  用于增强拓扑神经演化（NEAT）的即插即用，并行Go框架。| 
|   [neural-go](https://github.com/schuyler/neural-go) |  go-在Go中实现的多层感知器网络，通过反向传播进行训练。| 
|   [ocrserver](https://github.com/otiai10/ocrserver) |  一个简单的OCR API服务器，非常容易被Docker和Heroku部署。| 
|   [onnx-go](https://github.com/owulveryck/onnx-go) |  转到开放神经网络交换（ONNX）的接口。| 
|   [probab](https://github.com/ThePaw/probab) |  概率分布函数。贝叶斯推断。用纯Go语言编写。| 
|   [regommend](https://github.com/muesli/regommend) |  建议和协作过滤引擎。| 
|   [shield](https://github.com/eaigner/shield) |  贝叶斯文本分类器，具有灵活的标记器和Go的存储后端。| 
|   [tfgo](https://github.com/galeone/tfgo) |  易于使用的Tensorflow绑定：简化了官方Tensorflow Go绑定的使用。在Go中定义计算图，加载并执行经过Python训练的模型。| 
|   [Varis](https://github.com/Xamber/Varis) |  Golang神经网络。| 

- 金融
<a name="微软办公软件"></a>  <a name="微软办公软件"></a> 

|    包  |   说明  | 
|:---------:|:------:|
|   [unioffice](https://github.com/unidoc/unioffice) |  Pure Go库，用于创建和处理Office Word（.docx），Excel（.xlsx）和Powerpoint（.pptx）文档。| 
|   [excelize](https://github.com/360EntSecGroup-Skylar/excelize) |  Golang库用于读取和写入Microsoft Excel™（XLSX）文件。| 
|   [go-excel](https://github.com/szyhf/go-excel) |  一个简单而轻便的阅读器，可以将类似于related-db的excel读取为表格。| 
|   [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) |  libxlsxwriter的Golang绑定，用于编写XLSX（Microsoft Excel）文件。| 
|   [xlsx](https://github.com/tealeg/xlsx) |  用于简化在Go程序中读取Microsoft Excel最新版本使用的XML格式的库。| 
|   [xlsx](https://github.com/plandem/xlsx) |  在Go程序中快速/安全地读取/更新您现有的Microsoft Excel文件的方法。| 

- 自然语言处理
<a name="自然语言处理"></a>  <a name="自然语言处理"></a> 

|    包  |   说明  | 
|:---------:|:------:|
|   [getlang](https://github.com/rylans/getlang) |  快速自然语言检测程序包。| 
|   [go-i18n](https://github.com/nicksnyder/go-i18n/) |  用于处理本地化文本的软件包和一个随附工具。| 
|   [go-mystem](https://github.com/dveselov/mystem) |  CGo与Yandex.Mystem的绑定-俄罗斯形态分析仪。| 
|   [go-nlp](https://github.com/nuance/go-nlp) |  用于处理离散概率分布的实用程序和其他可用于执行NLP工作的工具。| 
|   [go-pinyin](https://github.com/mozillazg/go-pinyin) |  CN Hanzi至Hanyu拼音转换器。| 
|   [go-stem](https://github.com/agonopol/go-stem) |  搬运程序阻止算法的实现。| 
|   [go-unidecode](https://github.com/mozillazg/go-unidecode) |  Unicode文本的ASCII音译。| 
|   [go2vec](https://github.com/danieldk/go2vec) |  用于word2vec嵌入的阅读器和实用程序功能。| 
|   [gojieba](https://github.com/yanyiwu/gojieba) |  这是一个围棋实施解霸其中中国分词算法。| 
|   [golibstemmer](https://github.com/rjohnsondev/golibstemmer) |  雪球库libstemmer库的绑定，包括porter 2。| 
|   [gotokenizer](https://github.com/xujiajun/gotokenizer) |  基于字典和Goram语言的Bigram语言模型的标记器。（现在仅支持中文细分）| 
|   [gounidecode](https://github.com/fiam/gounidecode) |  Go的Unicode音译器（也称为unidecode）。| 
|   [gse](https://github.com/go-ego/gse) |  进行有效的文本分割；支持英语，中文，日语等。| 
|   [icu](https://github.com/goodsign/icu) |  CGO结合为ICU4C C库检测和转换功能。保证与版本50.1兼容。| 
|   [kagome](https://github.com/ikawaha/kagome) |  用纯Go语言编写的JP形态分析仪。| 
|   [libtextcat](https://github.com/goodsign/libtextcat) |  libtextcat C库的Cgo绑定。保证与2.2版兼容。| 
|   [MMSEGO](https://github.com/awsong/MMSEGO) |  这是MMSEG的GO实现，它是中文分词算法。| 
|   [nlp](https://github.com/Shixzie/nlp) |  从字符串中提取值，并用nlp填充您的结构。| 
|   [nlp](https://github.com/james-bowman/nlp) |  支持LSA（潜在语义分析）的自然语言处理库。| 
|   [paicehusk](https://github.com/rookii/paicehusk) |  Paice / Husk提取算法的Golang实现。| 
|   [petrovich](https://github.com/striker2000/petrovich) |  彼得罗维奇（Petrovich）是库，在给定的语法情况下使用俄语名称。| 
|   [porter](https://github.com/a2800276/porter) |  这是Martin Porter的Porter干算法的C实现的相当简单的移植。| 
|   [porter2](https://github.com/zhenjl/porter2) |  非常快的Porter 2 提取器。| 
|   [prose](https://github.com/jdkato/prose) |  用于文本处理的库，支持标记化，词性标记，命名实体提取等。仅限英语。| 
|   [RAKE.go](https://github.com/Obaied/RAKE.go) |  快速自动关键字提取算法（RAKE）的Go端口。| 
|   [segment](https://github.com/blevesearch/segment) |  用于执行Unicode标准附件＃29中所述的Unicode文本分段的Go库| 
|   [sentences](https://github.com/neurosnap/sentences) |  句子标记器：将文本转换为句子列表。| 
|   [shamoji](https://github.com/osamingo/shamoji) |  shamoji是用Go编写的单词过滤程序包。| 
|   [snowball](https://github.com/goodsign/snowball) |  Go的雪球茎端口（cgo包装器）。提供单词词干提取功能Snowball本机。| 
|   [stemmer](https://github.com/dchest/stemmer) |  用于Go编程语言的Stemmer软件包。包括英语和德语词干。| 
|   [textcat](https://github.com/pebbe/textcat) |Go软件包，用于基于n-gram的文本分类，并支持utf-8和原始文本。| 
|   [whatlanggo](https://github.com/abadojack/whatlanggo) |  Go的自然语言检测程序包。支持84种语言和24种脚本（书写系统，例如拉丁语，西里尔字母等）。| 
|   [when](https://github.com/olebedev/when) |  自然EN和RU语言日期/时间分析器具有可插拔的规则。| 
 
- 网络  
<a name="网络"></a>  <a name="网络"></a>  

|    包  |   说明  |  
|:---------:|:------:|  
|   [arp](https://github.com/mdlayher/arp) |包arp实现ARP协议，如RFC 826中所述。| 
|   [buffstreams](https://github.com/stabbycutyou/buffstreams) |  通过TCP流化协议缓冲区数据变得容易。| 
|   [canopus](https://github.com/zubairhamed/canopus) |  CoAP客户端/服务器实施（RFC 7252）。| 
|   [cidranger](https://github.com/yl2chen/cidranger) |  Go的快速IP到CIDR查找。| 
|   [dhcp6](https://github.com/mdlayher/dhcp6) |  软件包dhcp6实现了DHCPv6服务器，如RFC 3315中所述。| 
|   [dns](https://github.com/miekg/dns) |  使用DNS的Go库。| 
|   [ether](https://github.com/songgao/ether) |  用于发送和接收以太网帧的跨平台Go软件包。| 
|   [ethernet](https://github.com/mdlayher/ethernet) |  程序包ethernet实施IEEE 802.3以太网II帧和IEEE 802.1Q VLAN标签的封送处理。| 
|   [fasthttp](https://github.com/valyala/fasthttp) |  软件包fasthttp是Go的一种快速HTTP实现，比net / http快10倍。| 
|   [fortio](https://github.com/fortio/fortio) |  负载测试库和命令行工具，高级回显服务器和Web UI。允许指定设置的每秒查询负载，并记录延迟直方图和其他有用的统计数据并对其进行图形化。Tcp，Http，gRPC。| 
|   [ftp](https://github.com/jlaffaye/ftp) | 程序包ftp实现RFC 959中所述的FTP客户端。| 
|   [gev](https://github.com/Allenxuxu/gev) |  gev是基于Reactor模式的轻量级，快速，无阻塞的TCP网络库。| 
|   [gmqtt](https://github.com/DrmagicE/gmqtt) |  Gmqtt是一个灵活的高性能MQTT代理库，它完全实现了MQTT协议V3.1.1。| 
|   [gnet](https://github.com/panjf2000/gnet) |  gnet是一个高性能的，用纯围棋轻便，非阻塞，事件循环网络库。| 
|   [gNxI](https://github.com/google/gnxi) |  使用gNMI和gNOI协议的网络管理工具的集合。| 
|   [go-getter](https://github.com/hashicorp/go-getter) |  Go库，用于使用URL从各种来源下载文件或目录。| 
|   [go-powerdns](https://github.com/joeig/go-powerdns) |  Golang的 PowerDNS API绑定。| 
|   [go-stun](https://github.com/ccding/go-stun) |  STUN客户端的Go实现（RFC 3489和RFC 5389）。| 
|   [gobgp](https://github.com/osrg/gobgp) |  使用Go编程语言实现的BGP。| 
|   [golibwireshark](https://github.com/sunwxg/golibwireshark) |  软件包golibwireshark使用libwireshark库来解码pcap文件并分析解剖数据。| 
|   [gopacket](https://github.com/google/gopacket) |  Go库，用于使用libpcap绑定进行数据包处理。| 
|   [gopcap](https://github.com/akrennmair/gopcap) |  libpcap的包装器。| 
|   [goshark](https://github.com/sunwxg/goshark) |  软件包goshark使用tshark解码IP数据包并创建数据结构以分析数据包。| 
|   [gosnmp](https://github.com/soniah/gosnmp) |  用于执行SNMP操作的本机Go库。| 
|   [gosocsvr](https://github.com/rakeki/gosocsvr) |  套接字服务器变得简单。| 
|   [gotcp](https://github.com/gansidui/gotcp) |  用于快速编写tcp应用程序的Go软件包。| 
|   [grab](https://github.com/cavaliercoder/grab) |  用于管理文件下载的软件包。| 
|   [graval](https://github.com/koofr/graval) |  实验性FTP服务器框架。| 
|   [HTTPLab](https://github.com/gchaincl/httplab) |  HTTPLabs可让您检查HTTP请求并伪造响应。| 
|   [iplib](https://github.com/c-robinson/iplib) |  受python ipaddress和ruby ipaddr启发而使用IP地址（net.IP，net.IPNet）的库| 
|   [jazigo](https://github.com/udhos/jazigo) |  Jazigo是用Go语言编写的工具，用于检索多个网络设备的配置。| 
|   [kcp-go](https://github.com/xtaci/kcp-go) |  KCP-快速可靠的ARQ协议。| 
|   [kcptun](https://github.com/xtaci/kcptun) |  基于KCP协议的极其简单和快速的udp隧道。| 
|   [lhttp](https://github.com/fanux/lhttp) |  强大的websocket框架，可更轻松地构建IM服务器。| 
|   [linkio](https://github.com/ian-kent/linkio) |  用于读取器/写入器接口的网络链接速度模拟。| 
|   [llb](https://github.com/kirillDanshin/llb) |  这是代理服务器的非常简单但快速的后端。对于零内存分配和快速响应的快速重定向到预定义域很有用。| 
|   [mdns](https://github.com/hashicorp/mdns) |  Golang中的简单mDNS（多播DNS）客户端/服务器库。| 
|   [mqttPaho](https://eclipse.org/paho/clients/golang/) |  Paho Go客户端提供了一个MQTT客户端库，用于通过TCP，TLS或WebSockets连接到MQTT代理。| 
|   [NFF-Go](https://github.com/intel-go/nff-go) |  用于快速开发云和裸机（以前的YANFF）的高性能网络功能的框架。| 
|   [packet](https://github.com/aerogo/packet) |  通过TCP和UDP发送数据包。如果需要，它可以缓冲消息和热交换连接。| 
|   [peerdiscovery](https://github.com/schollz/peerdiscovery) |  Pure Go库，用于使用UDP多播的跨平台本地对等发现。| 
|   [portproxy](https://github.com/aybabtme/portproxy) |  简单的TCP代理，它将不支持它的API添加到CORS支持中。| 
|   [publicip](https://github.com/polera/publicip) |  软件包publicip返回您的面向公众的IPv4地址（互联网出口）。| 
|   [quic-go](https://github.com/lucas-clemente/quic-go) |在纯Go中实现QUIC协议。| 
|   [raw](https://github.com/mdlayher/raw) |  包raw允许在设备驱动程序级别为网络接口读取和写入数据。| 
|   [sftp](https://github.com/pkg/sftp) |  程序包sftp实现SSH文件传输协议，如[https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt](https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt)| 
|   [ssh](https://github.com/gliderlabs/ssh) |  用于构建SSH服务器的高级API（包装crypto / ssh）。| 
|   [sslb](https://github.com/eduardonunesp/sslb) |  这是一个超级简单的负载均衡器，只是一个实现某种性能的小项目。| 
|   [stun](https://github.com/go-rtc/stun) |  实施RFC 5389 STUN协议。| 
|   [tcp_server](https://github.com/firstrow/tcp_server) |  用于更快地构建tcp服务器的Go库。| 
|   [tspool](https://github.com/two/tspool) |  TCP库使用工作池来提高性能并保护您的服务器。| 
|   [utp](https://github.com/anacrolix/utp) |  围棋UTP微传输协议的实现。| 
|   [water](https://github.com/songgao/water) |  简单的TUN / TAP库。| 
|   [webrtc](https://github.com/pions/webrtc) |  WebRTC API的纯Go实现。| 
|   [winrm](https://github.com/masterzen/winrm) |  进入WinRM客户端以在Windows计算机上远程执行命令。| 
|   [xtcp](https://github.com/xfxdev/xtcp) |  具有同步全双工通信，安全关闭，自定义协议的TCP Server Framework。| 




- 视频
<a name="视频"></a>  <a name="视频"></a> 

|    包  |   说明  |  
|:---------:|:------:|  
|   [go-astisub](https://github.com/asticode/go-astisub) |  在GO中处理字幕（.srt，.stl，.ttml，.webvtt，.ssa / .ass，图文电视，.smi等）。| 
|   [go-astits](https://github.com/asticode/go-astits) |  在GO中本地解析和解复用MPEG传输流（.ts）。| 
|   [go-m3u8](https://github.com/quangngotan95/go-m3u8) |  Apple m3u8播放列表的解析器和生成器库。| 
|   [goav](https://github.com/giorgisio/goav) |  FFmpeg的综合Go绑定。| 
|   [gst](https://github.com/ziutek/gst) |  GStreamer的绑定。| 
|   [libgosubs](https://github.com/wargarblgarbl/libgosubs) |  go的字幕格式支持。支持.srt，.ttml和.ass。| 
|   [libvlc-go](https://github.com/adrg/libvlc-go) |  libvlc 2.X / 3.X / 4.X的绑定（由VLC媒体播放器使用）。| 
|   [m3u8](https://github.com/grafov/m3u8) |  Apple HLS的M3U8播放列表的解析器和生成器库。| 
|   [v4l](https://github.com/korandiz/v4l) |  用Go编写的Linux视频捕获库。|









<br> </br> 
<a name="推荐书籍"></a>  <a name="推荐书籍"></a> 

## 六、开源书籍
|    书籍名    | 推荐理由 |
|:---------:|:------:|
| [Go palyground](https://play.golang.org/) |不用搭建本地 Go 环境，在线就编写 Go 的代码|
|  [Go实战开发](https://github.com/astaxie/go-best-practice) | 作者是著名的 Go 开源项目 beego 的作者，他的最佳实践非常值得阅读|
|  [Go Web 编程](https://github.com/astaxie/build-web-application-with-golang/blob/master/zh/preface.md)  | 跟前面一本书作者是同一位，讲的是web开发|
|   [Go语言标准库](https://books.studygolang.com/The-Golang-Standard-Library-by-Example) | 对标准库的介绍|
|    [Go入门指南](https://github.com/Unknwon/the-way-to-go_ZH_CN/blob/master/eBook/directory.md) | 比较适合新手，内容相对基础一些 |
| [Go语言圣经](http://shouce.jb51.net/gopl-zh/ch1/ch1-01.html)  | 书如其名 |
| [Go语言中文网](https://studygolang.com/topics) | 找对圈子，学的更快|
| [菜鸟教程](https://www.runoob.com/go/go-environment.html) | 这个网站非常适合快速上手某门语言|
| [Go语言高级编程](https://chai2010.cn/advanced-go-programming-book) | 内容适合进阶|
| [go语言原本](https://golang.design/under-the-hood/) | 欧神出品，虽然号称进度只有9.9%/100%，但不妨碍它的优秀，值得一看|
| [golang设计模式](https://github.com/senghoo/golang-design-pattern) | 设计模式 Golang实现，《研磨设计模式》的golang实现|
| [Go语言四十二章经](https://github.com/ffhelicopter/Go42) | 可以对比查漏补缺|



<a name="视频教程"></a>  <a name="视频教程"></a> 

## 六、视频网课
  关注[公众号](#公众号) 回复【教程】即可在知识的海洋里呛水。


<br />
<br />
<br />




<a name="公众号"></a>  <a name="公众号"></a>

欢迎关注公众号:【小白debug】
![](https://cdn.jsdelivr.net/gh/xiaobaiTech/image/%E5%B0%8F%E7%99%BDdebug%E5%8A%A8%E5%9B%BE%E4%BA%8C%E7%BB%B4%E7%A0%81.gif)

![](https://cdn.jsdelivr.net/gh/zhaolunallen/picture/2021-1-10/1610269930614-640.png)




