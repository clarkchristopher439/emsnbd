最新前沿技术资讯

一、入门教程｜Getting Started
原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.bzh0c2.asia/arts/319874.Doc

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.bzh0c2.asia/arts/198286.Doc

原标题：从零搭建简单的健康检查接口示例
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.bzh0c2.asia/arts/057724.Doc

原标题：golang 系统设计容量评估简单方法论
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.bzh0c2.asia/arts/603106.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://wiki.bzh0c2.asia/arts/747191.Doc

原标题：实践：数据库慢查询分析与索引优化实战演练
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.bzh0c2.asia/arts/573273.Doc

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://wiki.bzh0c2.asia/arts/889657.Doc

原标题：运维笔记：服务器日志轮转logrotate配置
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://wiki.bzh0c2.asia/arts/744848.Doc

原标题：golang jwt 过期刷新 token 实现
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.bzh0c2.asia/arts/196447.Doc

原标题：接口压测定位系统性能瓶颈
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.bzh0c2.asia/arts/184305.Doc

原标题：golang 系统设计短链接服务实现思路
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.bzh0c2.asia/arts/167510.Doc

原标题：golang mysql 分表 id 路由逻辑
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.bzh0c2.asia/arts/820834.Doc

原标题：入门实践：使用模板快速生成项目脚手架
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.bzh0c2.asia/arts/617596.Doc

原标题：nodejs 内存溢出问题排查修复
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://wiki.bzh0c2.asia/arts/382795.Doc

原标题：Practice：模拟热点key，验证缓存防护策略
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.bzh0c2.asia/arts/250718.Doc

原标题：实战：搭建日志收集分析简易完整演示环境
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.bzh0c2.asia/arts/478446.Doc

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.bzh0c2.asia/arts/490311.Doc

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.bzh0c2.asia/arts/842500.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.bzh0c2.asia/arts/226913.Doc

原标题：安全复盘：Redis未授权访问漏洞防护
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://wiki.bzh0c2.asia/arts/938446.Doc

原标题：实战：Redis过期回调实现业务事件通知实践
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.bzh0c2.asia/arts/622063.Doc

原标题：排错：macOS权限保护导致脚本执行被拦截
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.bzh0c2.asia/arts/188762.Doc

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://wiki.bzh0c2.asia/arts/475802.Doc

原标题：记一次本地运行正常，线上环境报错诡异问题
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.bzh0c2.asia/arts/250568.Doc

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.bzh0c2.asia/arts/019027.Doc

原标题：限流组件计数器令牌桶模式实现
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://wiki.bzh0c2.asia/arts/042693.Doc

原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://wiki.bzh0c2.asia/arts/196054.Doc

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://wiki.bzh0c2.asia/arts/018519.Doc

原标题：前端错误监控上报系统搭建
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://wiki.bzh0c2.asia/arts/194430.Doc

原标题：Security：Web常见安全漏洞原理与修复清单
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.bzh0c2.asia/arts/296267.Doc

原标题：golang redis 五种数据结构实战
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.bzh0c2.asia/arts/701035.Doc

原标题：eslint prettier 代码规范落地
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.bzh0c2.asia/arts/798433.Doc

原标题：golang 系统设计降级策略开关配置方案
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://wiki.bzh0c2.asia/arts/530131.Doc

原标题：实战：单元测试+集成测试完整项目落地实践
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.bzh0c2.asia/arts/936736.Doc

原标题：golang docker 基础命令实操汇总
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://wiki.bzh0c2.asia/arts/077778.Doc

原标题：golang 系统设计布隆过滤器原理与落地
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.bzh0c2.asia/arts/643083.Doc

原标题：实战：单元测试+集成测试完整项目落地实践
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.bzh0c2.asia/arts/751031.Doc

原标题：golang 系统设计读写分离延迟业务兼容
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://wiki.bzh0c2.asia/arts/492845.Doc

原标题：golang mysql json 字段查询使用
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://wiki.bzh0c2.asia/arts/821461.Doc

原标题：记一次限流组件误配置把正常用户拦截
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://wiki.bzh0c2.asia/arts/747873.Doc


二、踩坑排错｜Troubleshooting
原标题：限流规则误拦截正常请求修复
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.bzh0c2.asia/arts/932911.Doc

原标题：设计思考：业务系统中什么时候不要用微服务
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://wiki.bzh0c2.asia/arts/830762.Doc

原标题：golang k8s cronjob 定时任务配置
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.bzh0c2.asia/arts/796463.Doc

原标题：golang 系统设计内存高占用排查思路
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.bzh0c2.asia/arts/851545.Doc

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.bzh0c2.asia/arts/374556.Doc

原标题：golang github actions 缓存依赖提速
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://wiki.bzh0c2.asia/arts/380233.Doc

原标题：开发记录：批量接口请求并发控制实践
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.bzh0c2.asia/arts/828179.Doc

原标题：nodejs 跨域中间件配置细节
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.bzh0c2.asia/arts/455449.Doc

原标题：快速入门简单签名校验实现思路
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://wiki.bzh0c2.asia/arts/771819.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://wiki.bzh0c2.asia/arts/707454.Doc

原标题：快速启动：本地运行开源项目排障清单
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://wiki.bzh0c2.asia/arts/774572.Doc

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://wiki.bzh0c2.asia/arts/618990.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://wiki.bzh0c2.asia/arts/482672.Doc

原标题：golang 消息队列 kafka 消费开发
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://wiki.bzh0c2.asia/arts/134053.Doc

原标题：新手参与开源社区贡献指南
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.bzh0c2.asia/arts/347834.Doc

原标题：实战项目：GitSubmodule管理多仓库实践
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.bzh0c2.asia/arts/796328.Doc

原标题：golang 信号捕获程序退出处理
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://wiki.bzh0c2.asia/arts/545933.Doc

原标题：架构笔记：多数据源架构设计事务处理难点
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.bzh0c2.asia/arts/399991.Doc

原标题：AI实践：大模型生成代码后审查与重构实践
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.bzh0c2.asia/arts/031327.Doc

原标题：部署实践：HTTPS证书自动续期配置实践
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.bzh0c2.asia/arts/070998.Doc

原标题：实战：Docker资源监控查看容器状态实操
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.bzh0c2.asia/arts/546097.Doc

原标题：坑点：gitsubmodule子模块更新失败踩坑
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.bzh0c2.asia/arts/646706.Doc

原标题：快速入门ORM，实现简单数据库增删改查
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://wiki.bzh0c2.asia/arts/596078.Doc

原标题：vite 插件开发自定义构建逻辑
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.bzh0c2.asia/arts/255226.Doc

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.bzh0c2.asia/arts/932722.Doc

原标题：前后端交互跨域问题完整处理
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.bzh0c2.asia/arts/132771.Doc

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://wiki.bzh0c2.asia/arts/924036.Doc

原标题：golang 系统设计内部服务链路 trace 传递实现
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://wiki.bzh0c2.asia/arts/278798.Doc

原标题：WebSocket 聊天室实时通讯开发
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.bzh0c2.asia/arts/533137.Doc

原标题：golang 系统设计数据库慢请求排查流程
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.bzh0c2.asia/arts/644367.Doc

原标题：实战项目：前端资源打包体积优化完整实操
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://wiki.bzh0c2.asia/arts/318460.Doc

原标题：golang redis 缓存更新策略讲解
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://wiki.bzh0c2.asia/arts/890414.Doc

原标题：实战：数据库索引设计，复合索引最佳实践
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.bzh0c2.asia/arts/562606.Doc

原标题：代码模块化组件化拆分思路
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.bzh0c2.asia/arts/422226.Doc

原标题：全平台系统环境变量配置
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.bzh0c2.asia/arts/984189.Doc

原标题：设计思考：分布式ID系统架构选型对比
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.bzh0c2.asia/arts/338600.Doc

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.bzh0c2.asia/arts/665039.Doc

原标题：快速入门OpenAPI文档生成基础实践
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.bzh0c2.asia/arts/887953.Doc

原标题：内网 DNS 不稳定随机报错排查
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.bzh0c2.asia/arts/044036.Doc

原标题：golang kafka 重试机制配置实操
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://wiki.bzh0c2.asia/arts/246406.Doc

三、实战开发｜Practice
原标题：golang redis 地理位置 geo 使用
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.bzh0c2.asia/arts/578161.Doc

原标题：开发记录：跨域中间件完整配置与边界处理
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.bzh0c2.asia/arts/116582.Doc

原标题：开源项目本地运行排错完整清单
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://wiki.bzh0c2.asia/arts/429826.Doc

原标题：文件读写与异常捕获代码示例
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://wiki.bzh0c2.asia/arts/660938.Doc

原标题：golang docker 部署 mongodb 开发环境
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://wiki.bzh0c2.asia/arts/344498.Doc

原标题：前端下载导出文件功能实现
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.bzh0c2.asia/arts/715687.Doc

原标题：nodejs 内存溢出问题排查修复
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.bzh0c2.asia/arts/023544.Doc

原标题：快速入门简单签名校验实现思路
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.bzh0c2.asia/arts/159924.Doc

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.bzh0c2.asia/arts/865252.Doc

原标题：golang 系统设计开源项目 release 发布流程
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.bzh0c2.asia/arts/034249.Doc

原标题：部署复盘：静态站点部署CDN完整流程
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://wiki.bzh0c2.asia/arts/638692.Doc

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://wiki.bzh0c2.asia/arts/115755.Doc

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://wiki.bzh0c2.asia/arts/420320.Doc

原标题：golang 系统设计大流量削峰处理方案
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.bzh0c2.asia/arts/782219.Doc

原标题：安全笔记：HTTPSTLS配置安全加固实践
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.bzh0c2.asia/arts/125642.Doc

原标题：新手向：Mac/Windows开发环境差异踩坑
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://wiki.bzh0c2.asia/arts/473108.Doc

原标题：记一次限流组件误配置把正常用户拦截
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.bzh0c2.asia/arts/581297.Doc

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.bzh0c2.asia/arts/937965.Doc

原标题：图片上传预览格式大小处理
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.bzh0c2.asia/arts/690435.Doc

原标题：上传接口跨域配置特殊适配
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://wiki.bzh0c2.asia/arts/815795.Doc

原标题：线上故障：慢查询拖垮整个数据库服务
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.bzh0c2.asia/arts/148417.Doc

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://wiki.bzh0c2.asia/arts/671875.Doc

原标题：架构复盘：热点数据防护架构防止节点过载
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.bzh0c2.asia/arts/703987.Doc

原标题：运维笔记：服务器日志轮转logrotate配置
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.bzh0c2.asia/arts/988516.Doc

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.bzh0c2.asia/arts/485598.Doc

原标题：新手向：开源项目fork与同步上游代码
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://wiki.bzh0c2.asia/arts/437021.Doc

原标题：正则表达式优化 CPU 占满问题
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.bzh0c2.asia/arts/409077.Doc

原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.bzh0c2.asia/arts/337658.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.bzh0c2.asia/arts/199886.Doc

原标题：百万数据 Excel 导出内存优化
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.bzh0c2.asia/arts/828883.Doc

原标题：Practice：实现接口幂等性多种方案对比实践
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.bzh0c2.asia/arts/723009.Doc

原标题：配置与镜像分离防止信息泄露
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://wiki.bzh0c2.asia/arts/196726.Doc

原标题：坑点：软链接权限问题容器读取文件失败
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://wiki.bzh0c2.asia/arts/155943.Doc

原标题：Practice：实现接口防重提交组件实践
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.bzh0c2.asia/arts/377736.Doc

原标题：golang toml 配置文件解析教程
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://wiki.bzh0c2.asia/arts/526320.Doc

原标题：golang 系统设计最小权限原则落地实践
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.bzh0c2.asia/arts/199755.Doc

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.bzh0c2.asia/arts/208543.Doc

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://wiki.bzh0c2.asia/arts/405400.Doc

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://wiki.bzh0c2.asia/arts/307527.Doc

原标题：golang docker 部署 es 本地开发
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.bzh0c2.asia/arts/448817.Doc

四、架构设计｜Architecture
原标题：部署实践：Nginx高可用配置方案实践
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.bzh0c2.asia/arts/325423.Doc

原标题：Git 混乱提交历史清理方法
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://wiki.bzh0c2.asia/arts/190706.Doc

原标题：优化实践：接口批量合并减少网络请求次数
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.bzh0c2.asia/arts/156884.Doc

原标题：Performance：长连接管理优化减少连接重建开销
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://wiki.bzh0c2.asia/arts/044224.Doc

原标题：端口占用访问失败排查方案
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.bzh0c2.asia/arts/236685.Doc

原标题：nestjs 权限守卫鉴权实现方案
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.bzh0c2.asia/arts/787335.Doc

原标题：golang alertmanager 钉钉告警推送
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://wiki.bzh0c2.asia/arts/223555.Doc

原标题：实践：灰度流量切分简易实现方案
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.bzh0c2.asia/arts/594440.Doc

原标题：golang 接口返回统一封装工具
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.bzh0c2.asia/arts/261340.Doc

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.bzh0c2.asia/arts/012558.Doc

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.bzh0c2.asia/arts/072559.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.bzh0c2.asia/arts/742814.Doc

原标题：golang 系统设计 mq 故障降级业务策略
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.bzh0c2.asia/arts/270615.Doc

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://wiki.bzh0c2.asia/arts/157137.Doc

原标题：HTTPS 证书过期更新操作
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.bzh0c2.asia/arts/347566.Doc

原标题：golang 系统设计告警规则阈值设置方法论
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://wiki.bzh0c2.asia/arts/439208.Doc

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.bzh0c2.asia/arts/599017.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.bzh0c2.asia/arts/603706.Doc

?
