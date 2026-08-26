最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://book.13tfn9.asia/blog/756074.Doc

原标题：golang websocket 消息广播实现
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://book.13tfn9.asia/blog/523685.Doc

原标题：设计思考：分布式会话架构选型对比
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://book.13tfn9.asia/blog/721754.Doc

原标题：Nginx 反向代理路由配置实战
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://book.13tfn9.asia/blog/283204.Doc

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.13tfn9.asia/blog/177970.Doc

原标题：DevOps：CI构建产物缓存复用加速编译
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://book.13tfn9.asia/blog/523044.Doc

原标题：架构笔记：缓存雪崩缓存击穿架构防护方案
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://book.13tfn9.asia/blog/075408.Doc

原标题：实践：数据库备份脚本自动化编写实践
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://book.13tfn9.asia/blog/210255.Doc

原标题：Redis 内存淘汰策略数据防丢失
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://book.13tfn9.asia/blog/241040.Doc

原标题：端口占用释放资源重启服务
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://book.13tfn9.asia/blog/840428.Doc

原标题：golang mysql innodb 事务隔离级别
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://book.13tfn9.asia/blog/227115.Doc

原标题：JWT 工具封装令牌刷新过期
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://book.13tfn9.asia/blog/876752.Doc

原标题：设计思考：大促系统架构压测改造整体思路
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://book.13tfn9.asia/blog/477497.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://book.13tfn9.asia/blog/530595.Doc

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://book.13tfn9.asia/blog/467038.Doc

原标题：golang docker volume 数据持久化
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://book.13tfn9.asia/blog/420778.Doc

原标题：零基础理解JSON、XML数据格式处理
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://book.13tfn9.asia/blog/219691.Doc

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://book.13tfn9.asia/blog/059772.Doc

原标题：无用对象回收抑制内存上涨
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://book.13tfn9.asia/blog/310147.Doc

原标题：golang 系统设计熔断算法 hystrix 思路
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://book.13tfn9.asia/blog/692405.Doc

原标题：golang 配置热更新不重启服务
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://book.13tfn9.asia/blog/930690.Doc

原标题：Issue：本地可以访问，容器内部网络不通
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://book.13tfn9.asia/blog/085394.Doc

原标题：架构复盘：供应链安全架构依赖包风险治理
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://book.13tfn9.asia/blog/292786.Doc

原标题：golang 系统设计 csrf 接口防护实现
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://book.13tfn9.asia/blog/411772.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://book.13tfn9.asia/blog/729297.Doc

原标题：性能笔记：磁盘IO过高业务优化手段
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://book.13tfn9.asia/blog/784838.Doc

原标题：golang 系统设计分布式锁不同场景选型对比
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://book.13tfn9.asia/blog/577233.Doc

原标题：golang 系统设计日志级别业务使用原则梳理
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://book.13tfn9.asia/blog/567862.Doc

原标题：golang k8s 日志收集 efk 简单架构
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://book.13tfn9.asia/blog/295667.Doc

原标题：golang validator 自定义校验规则
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://book.13tfn9.asia/blog/101722.Doc

原标题：golang redis 发布订阅简单示例
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://book.13tfn9.asia/blog/227351.Doc

原标题：golang goroutine 池任务调度
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://book.13tfn9.asia/blog/550561.Doc

原标题：golang 系统设计防重复提交实现
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.13tfn9.asia/blog/921298.Doc

原标题：golang 系统设计内网外网服务隔离方案
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://book.13tfn9.asia/blog/540374.Doc

原标题：快速上手简单性能监控指标查看
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://book.13tfn9.asia/blog/532770.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://book.13tfn9.asia/blog/827144.Doc

原标题：部署复盘：服务启动顺序依赖处理方案
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://book.13tfn9.asia/blog/712346.Doc

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://book.13tfn9.asia/blog/438873.Doc

原标题：开发复盘：数据库批量更新优化性能实践
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://book.13tfn9.asia/blog/486959.Doc

原标题：golang 系统设计压测工具 vegeta 使用示例
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://book.13tfn9.asia/blog/936000.Doc


二、踩坑排错｜Troubleshooting
原标题：避坑：请求未设置read超时无限挂起连接
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://book.13tfn9.asia/blog/365812.Doc

原标题：golang 系统设计 changelog 变更日志维护
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://book.13tfn9.asia/blog/538432.Doc

原标题：消息队列生产消费模型入门
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://book.13tfn9.asia/blog/726186.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://book.13tfn9.asia/blog/714019.Doc

原标题：依赖安装失败全方位排错
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://book.13tfn9.asia/blog/533229.Doc

原标题：架构复盘：慢查询治理架构层面优化手段
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://book.13tfn9.asia/blog/465115.Doc

原标题：快速上手阅读开源项目源码的入门思路
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://book.13tfn9.asia/blog/086251.Doc

原标题：HTTPS 证书过期更新操作
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://book.13tfn9.asia/blog/500435.Doc

原标题：快速入门GraphQL基础查询语法示例
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://book.13tfn9.asia/blog/490403.Doc

原标题：架构复盘：消息死信处理架构避免消息丢失
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://book.13tfn9.asia/blog/518949.Doc

原标题：从零搭建简单CLI命令行工具
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://book.13tfn9.asia/blog/234061.Doc

原标题：从零学习简单分布式ID生成思路
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://book.13tfn9.asia/blog/309739.Doc

原标题：排错：CI流水线构建失败，日志无明确报错
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.13tfn9.asia/blog/900303.Doc

原标题：golang 系统设计缓存预热脚本编写实操
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://book.13tfn9.asia/blog/311668.Doc

原标题：golang 系统设计代码安全审计简单思路
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://book.13tfn9.asia/blog/199253.Doc

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://book.13tfn9.asia/blog/311267.Doc

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://book.13tfn9.asia/blog/863921.Doc

原标题：golang 数据库批量更新性能优化
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://book.13tfn9.asia/blog/675221.Doc

原标题：golang k8s 基础概念 pod deployment
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://book.13tfn9.asia/blog/943107.Doc

原标题：运维笔记：服务器Swap分区调优生产实践
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://book.13tfn9.asia/blog/429403.Doc

原标题：golang 系统设计分布式锁看门狗续期原理理解
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://book.13tfn9.asia/blog/561928.Doc

原标题：消息队列生产消费模型入门
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://book.13tfn9.asia/blog/781899.Doc

原标题：项目实践：消息队列消息堆积模拟处理实践
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://book.13tfn9.asia/blog/469357.Doc

原标题：golang es 查询语句 DSL 实操
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://book.13tfn9.asia/blog/205580.Doc

原标题：实践：大文件分片上传后端完整实现思路
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://book.13tfn9.asia/blog/539915.Doc

原标题：RPC 报文大小上限调优大请求
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://book.13tfn9.asia/blog/125090.Doc

原标题：安全实践：防止JSON解析漏洞恶意payload
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://book.13tfn9.asia/blog/769539.Doc

原标题：部署实践：HTTPS证书自动续期配置实践
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://book.13tfn9.asia/blog/489066.Doc

原标题：Architecture：对象存储接入业务整体架构
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://book.13tfn9.asia/blog/539433.Doc

原标题：golang 协程泄露问题排查方法
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://book.13tfn9.asia/blog/054249.Doc

原标题：部署实践：告警收敛避免告警风暴配置
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://book.13tfn9.asia/blog/109394.Doc

原标题：限流组件计数器令牌桶模式实现
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://book.13tfn9.asia/blog/209383.Doc

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://book.13tfn9.asia/blog/490911.Doc

原标题：多套环境灵活切换配置方案
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://book.13tfn9.asia/blog/424913.Doc

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://book.13tfn9.asia/blog/487218.Doc

原标题：golang 系统设计版本号语义化规范讲解
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://book.13tfn9.asia/blog/148148.Doc

原标题：Issue：开源项目升级大版本后API不兼容踩坑
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://book.13tfn9.asia/blog/132194.Doc

原标题：快速上手简易网关转发逻辑模拟
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://book.13tfn9.asia/blog/152358.Doc

原标题：golang 系统设计错误码体系完整设计
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://book.13tfn9.asia/blog/857665.Doc

原标题：nodejs 信号处理优雅关闭服务
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://book.13tfn9.asia/blog/609632.Doc

三、实战开发｜Practice
原标题：Security：服务器最小权限账号运维实践
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://book.13tfn9.asia/blog/969654.Doc

原标题：golang mongodb 分页性能优化技巧
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://book.13tfn9.asia/blog/599692.Doc

原标题：特殊输入字符过滤解析防护
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://book.13tfn9.asia/blog/674515.Doc

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://book.13tfn9.asia/blog/633326.Doc

原标题：DevOps：GitLabCI完整流水线配置示例
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://book.13tfn9.asia/blog/504814.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://book.13tfn9.asia/blog/425446.Doc

原标题：实践：代码提交前自动格式化校验配置实践
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://book.13tfn9.asia/blog/370347.Doc

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://book.13tfn9.asia/blog/915329.Doc

原标题：方案设计：批量大数据导出系统架构拆解
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://book.13tfn9.asia/blog/562002.Doc

原标题：golang 系统设计分库分表扩容平滑迁移
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://book.13tfn9.asia/blog/314472.Doc

原标题：入门实践：简单错误码设计与使用规范
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://book.13tfn9.asia/blog/425094.Doc

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://book.13tfn9.asia/blog/815924.Doc

原标题：后端登录鉴权模块完整开发
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://book.13tfn9.asia/blog/910343.Doc

原标题：业务错误码体系设计方案
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://book.13tfn9.asia/blog/829688.Doc

原标题：开源源码阅读拆解学习思路
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://book.13tfn9.asia/blog/040288.Doc

原标题：golang k8s ingress 路由域名转发
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://book.13tfn9.asia/blog/538710.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://book.13tfn9.asia/blog/600840.Doc

原标题：golang 信号捕获程序退出处理
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://book.13tfn9.asia/blog/792033.Doc

原标题：golang 系统设计集成测试环境准备清理实操
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://book.13tfn9.asia/blog/162548.Doc

原标题：JWT 工具封装令牌刷新过期
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://book.13tfn9.asia/blog/768527.Doc

原标题：monorepo 项目多包管理最佳实践
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://book.13tfn9.asia/blog/757369.Doc

原标题：手写简易 RPC 服务通信原型
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.13tfn9.asia/blog/902847.Doc

原标题：golang 系统设计 api 网关核心能力梳理
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://book.13tfn9.asia/blog/120965.Doc

原标题：实践：接口参数自动校验业务落地实践
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://book.13tfn9.asia/blog/638032.Doc

原标题：不必要字符转义关闭业务异常
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://book.13tfn9.asia/blog/438903.Doc

原标题：Practice：实现防爬虫简单拦截中间件实践
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://book.13tfn9.asia/blog/863037.Doc

原标题：Docker 容器时区错误修复方案
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://book.13tfn9.asia/blog/486231.Doc

原标题：排错：前端缓存304异常更新不及时
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://book.13tfn9.asia/blog/932313.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://book.13tfn9.asia/blog/017727.Doc

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://book.13tfn9.asia/blog/159393.Doc

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://book.13tfn9.asia/blog/128299.Doc

原标题：golang 系统设计架构图绘制规范简单建议
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://book.13tfn9.asia/blog/261703.Doc

原标题：golang redis hyperloglog 基数统计
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://book.13tfn9.asia/blog/459342.Doc

原标题：golang es 分页深分页性能优化
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://book.13tfn9.asia/blog/382148.Doc

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://book.13tfn9.asia/blog/502394.Doc

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://book.13tfn9.asia/blog/789766.Doc

原标题：golang 系统设计自动化测试 ci 流水线集成实操
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://book.13tfn9.asia/blog/205387.Doc

原标题：golang gorm ORM 数据库操作
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://book.13tfn9.asia/blog/292586.Doc

原标题：golang 系统设计依赖漏洞扫描修复流程
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://book.13tfn9.asia/blog/370744.Doc

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://book.13tfn9.asia/blog/787883.Doc

四、架构设计｜Architecture
原标题：golang 系统设计 api 文档 swagger redoc 落地
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://book.13tfn9.asia/blog/906642.Doc

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.13tfn9.asia/blog/716216.Doc

原标题：golang redis 批量 pipeline 实践
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://book.13tfn9.asia/blog/188191.Doc

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://book.13tfn9.asia/blog/805316.Doc

原标题：Performance：缓存策略优化，降低数据库压力
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://book.13tfn9.asia/blog/057648.Doc

原标题：golang 系统设计缓存与数据库一致性权衡
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://book.13tfn9.asia/blog/917822.Doc

原标题：Dockerfile 编写容器打包实战
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://book.13tfn9.asia/blog/052566.Doc

原标题：Practice：实现请求body重复读取中间件实践
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://book.13tfn9.asia/blog/309914.Doc

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://book.13tfn9.asia/blog/425039.Doc

原标题：本地运行正常线上报错排查
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://book.13tfn9.asia/blog/702594.Doc

原标题：golang 系统设计日志规范结构化日志落地
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.13tfn9.asia/blog/534197.Doc

原标题：nodejs 集成测试业务流程编写
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://book.13tfn9.asia/blog/947875.Doc

原标题：golang toml 配置文件解析教程
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://book.13tfn9.asia/blog/249946.Doc

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://book.13tfn9.asia/blog/933675.Doc

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://book.13tfn9.asia/blog/155739.Doc

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://book.13tfn9.asia/blog/122348.Doc

原标题：入门实践：搭建简单的热更新开发环境
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://book.13tfn9.asia/blog/828304.Doc

原标题：零基础理解缓存基础原理与简单使用
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://book.13tfn9.asia/blog/602362.Doc

?
