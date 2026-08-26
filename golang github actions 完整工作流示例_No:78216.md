最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang github actions 完整工作流示例
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://book.2stzcr.asia/blog/288993.Doc

原标题：Hands‑on：简易熔断逻辑状态机原型实现
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://book.2stzcr.asia/blog/322527.Doc

原标题：业务错误码体系设计方案
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://book.2stzcr.asia/blog/874928.Doc

原标题：Hands‑on：本地模拟消息重复消费处理实践
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://book.2stzcr.asia/blog/851939.Doc

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.2stzcr.asia/blog/709512.Doc

原标题：Spring 事务传播机制配置生效
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://book.2stzcr.asia/blog/957221.Doc

原标题：大文件导出内存溢出防护
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://book.2stzcr.asia/blog/626380.Doc

原标题：golang 系统设计定时任务分布式锁
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://book.2stzcr.asia/blog/431887.Doc

原标题：设计思考：大促系统架构压测改造整体思路
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://book.2stzcr.asia/blog/876733.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://book.2stzcr.asia/blog/069441.Doc

原标题：项目实践：多环境配置管理组件设计与实现
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://book.2stzcr.asia/blog/483648.Doc

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://book.2stzcr.asia/blog/875119.Doc

原标题：GraphQL 接口查询优化实操
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://book.2stzcr.asia/blog/685708.Doc

原标题：golang kafka 批量发送消费优化
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://book.2stzcr.asia/blog/917094.Doc

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://book.2stzcr.asia/blog/153026.Doc

原标题：请求重试组件退避策略实现
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://book.2stzcr.asia/blog/763650.Doc

原标题：不必要字符转义关闭业务异常
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://book.2stzcr.asia/blog/396557.Doc

原标题：golang etcd watch 监听配置变更
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://book.2stzcr.asia/blog/278053.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://book.2stzcr.asia/blog/936094.Doc

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://book.2stzcr.asia/blog/723233.Doc

原标题：golang 系统设计线上日志快速检索技巧
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://book.2stzcr.asia/blog/161954.Doc

原标题：golang 系统设计 commit 提交规范约定
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://book.2stzcr.asia/blog/748236.Doc

原标题：golang kafka 监控指标简单梳理
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://book.2stzcr.asia/blog/510628.Doc

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://book.2stzcr.asia/blog/193714.Doc

原标题：golang 系统设计 http1.1 http2 核心差异讲解
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://book.2stzcr.asia/blog/740102.Doc

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://book.2stzcr.asia/blog/633068.Doc

原标题：入门实践：项目配置文件多环境管理方案
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://book.2stzcr.asia/blog/495982.Doc

原标题：golang mysql 事务回滚异常处理
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://book.2stzcr.asia/blog/841807.Doc

原标题：nestjs 拦截器过滤器管道实战
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://book.2stzcr.asia/blog/557685.Doc

原标题：golang docker 部署 mongodb 开发环境
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://book.2stzcr.asia/blog/306599.Doc

原标题：开源项目构建失败排查步骤
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://book.2stzcr.asia/blog/206021.Doc

原标题：设计思考：容器化业务应用架构改造要点
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://book.2stzcr.asia/blog/970919.Doc

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://book.2stzcr.asia/blog/948036.Doc

原标题：golang yaml 解析配置加载实操
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://book.2stzcr.asia/blog/494776.Doc

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://book.2stzcr.asia/blog/236583.Doc

原标题：方案对比：几种分布式限流算法架构适用性
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://book.2stzcr.asia/blog/780440.Doc

原标题：从零学习基础的接口请求与参数处理
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://book.2stzcr.asia/blog/637875.Doc

原标题：Architecture：日志、监控、告警整套可观测架构
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://book.2stzcr.asia/blog/574986.Doc

原标题：图片上传预览格式大小处理
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://book.2stzcr.asia/blog/439142.Doc

原标题：Performance：数据库大表优化，冷热数据分离
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://book.2stzcr.asia/blog/427436.Doc


二、踩坑排错｜Troubleshooting
原标题：调优方案：静态资源缓存头Cache‑Control优化
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://book.2stzcr.asia/blog/976461.Doc

原标题：实践：分布式事务本地模拟验证实践
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://book.2stzcr.asia/blog/381857.Doc

原标题：线上故障：慢查询拖垮整个数据库服务
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://book.2stzcr.asia/blog/900027.Doc

原标题：nodejs 多进程任务分发处理
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://book.2stzcr.asia/blog/223655.Doc

原标题：数据库分表存储大表优化方案
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://book.2stzcr.asia/blog/654878.Doc

原标题：效率笔记：调试网络请求curl命令高级用法
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://book.2stzcr.asia/blog/993436.Doc

原标题：部署实践：服务器防火墙安全组配置实践
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://book.2stzcr.asia/blog/132570.Doc

原标题：golang 系统设计网关 ssl 证书配置更新实操
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://book.2stzcr.asia/blog/971072.Doc

原标题：架构笔记：数据脱敏架构接入层与存储层方案
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://book.2stzcr.asia/blog/600986.Doc

原标题：静态资源 404 路径打包修复
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://book.2stzcr.asia/blog/602278.Doc

原标题：golang 系统设计日志级别业务使用原则梳理
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://book.2stzcr.asia/blog/630916.Doc

原标题：入门实践：实现简单文件读写功能
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://book.2stzcr.asia/blog/214786.Doc

原标题：性能笔记：数据库表字段设计影响查询性能
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://book.2stzcr.asia/blog/670161.Doc

原标题：方案设计：批量大数据导出系统架构拆解
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://book.2stzcr.asia/blog/203273.Doc

原标题：golang 令牌桶限流中间件 gin
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://book.2stzcr.asia/blog/248190.Doc

原标题：macOS 脚本执行权限开启
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://book.2stzcr.asia/blog/852582.Doc

原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://book.2stzcr.asia/blog/855409.Doc

原标题：golang 链路追踪简易实现方案
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://book.2stzcr.asia/blog/404180.Doc

原标题：golang 系统设计大事务拆分实战思路
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://book.2stzcr.asia/blog/907315.Doc

原标题：踩坑记录：文件描述符不足，上传功能随机失败
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://book.2stzcr.asia/blog/480970.Doc

原标题：入门实践：简单批量处理脚本编写
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://book.2stzcr.asia/blog/906615.Doc

原标题：实战：容器内执行调试排错完整实操流程
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://book.2stzcr.asia/blog/240029.Doc

原标题：架构笔记：海量日志处理架构选型与实践
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.2stzcr.asia/blog/345611.Doc

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://book.2stzcr.asia/blog/826289.Doc

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://book.2stzcr.asia/blog/773149.Doc

原标题：golang 系统设计大盘看板设计最佳实践汇总
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://book.2stzcr.asia/blog/663939.Doc

原标题：配置与镜像分离防止信息泄露
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://book.2stzcr.asia/blog/307041.Doc

原标题：Practice：实现请求ID透传全链路日志实践
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://book.2stzcr.asia/blog/997679.Doc

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://book.2stzcr.asia/blog/470997.Doc

原标题：Practice：实现请求ID透传全链路日志实践
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://book.2stzcr.asia/blog/711307.Doc

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://book.2stzcr.asia/blog/066101.Doc

原标题：操作系统内核版本适配服务
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://book.2stzcr.asia/blog/701658.Doc

原标题：golang 系统设计内存复用 sync.pool 使用
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://book.2stzcr.asia/blog/178930.Doc

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://book.2stzcr.asia/blog/151452.Doc

原标题：开发复盘：超时参数统一治理线上服务实践
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://book.2stzcr.asia/blog/205151.Doc

原标题：架构笔记：分库分表中间件选型业务约束
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://book.2stzcr.asia/blog/728852.Doc

原标题：新手向：npm/pip/maven依赖版本冲突入门排查
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://book.2stzcr.asia/blog/310776.Doc

原标题：golang 系统设计 rest 资源命名规范汇总
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://book.2stzcr.asia/blog/374090.Doc

原标题：Practice：实现多数据源动态切换组件实践
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://book.2stzcr.asia/blog/611116.Doc

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://book.2stzcr.asia/blog/609956.Doc

三、实战开发｜Practice
原标题：实战：WebSocket断线重连完整业务处理实践
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://book.2stzcr.asia/blog/506688.Doc

原标题：golang 系统设计会话共享多实例部署
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.2stzcr.asia/blog/633551.Doc

原标题：vue3 组合式 API 业务开发实战
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://book.2stzcr.asia/blog/888677.Doc

原标题：Git 代码冲突正确处理方式
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://book.2stzcr.asia/blog/083524.Doc

原标题：前端大文件分片上传完整方案
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://book.2stzcr.asia/blog/966899.Doc

原标题：安全实践：防止重放攻击接口签名方案
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://book.2stzcr.asia/blog/603310.Doc

原标题：golang 系统设计故障演练简单思路
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://book.2stzcr.asia/blog/852153.Doc

原标题：进程线程并发基础概念讲解
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://book.2stzcr.asia/blog/715279.Doc

原标题：开发生产环境资源路径统一
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://book.2stzcr.asia/blog/371997.Doc

原标题：CLI 批量处理工具文件操作开发
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://book.2stzcr.asia/blog/634535.Doc

原标题：golang prometheus metrics 埋点开发
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://book.2stzcr.asia/blog/070435.Doc

原标题：大文件导出内存溢出防护
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://book.2stzcr.asia/blog/082115.Doc

原标题：golang 分布式上下文传递方案
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://book.2stzcr.asia/blog/949495.Doc

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://book.2stzcr.asia/blog/387400.Doc

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://book.2stzcr.asia/blog/770291.Doc

原标题：golang 系统设计数据库慢请求排查流程
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://book.2stzcr.asia/blog/240499.Doc

原标题：踩坑记录：文件描述符不足，上传功能随机失败
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://book.2stzcr.asia/blog/187881.Doc

原标题：踩坑记录：端口被占用导致服务启动失败
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.2stzcr.asia/blog/911764.Doc

原标题：坑点：gitcherry‑pick引入不兼容代码
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://book.2stzcr.asia/blog/534326.Doc

原标题：golang 消息队列 kafka 消费开发
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://book.2stzcr.asia/blog/621635.Doc

原标题：golang 系统设计一致性哈希原理讲解
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://book.2stzcr.asia/blog/474285.Doc

原标题：异步异常捕获避免进程崩溃
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://book.2stzcr.asia/blog/144018.Doc

原标题：实践：大文件分片上传后端完整实现思路
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://book.2stzcr.asia/blog/269752.Doc

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://book.2stzcr.asia/blog/751929.Doc

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://book.2stzcr.asia/blog/728415.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://book.2stzcr.asia/blog/229750.Doc

原标题：HelloCI：理解持续集成基础工作流程
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://book.2stzcr.asia/blog/996532.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://book.2stzcr.asia/blog/833209.Doc

原标题：前后端会话登录状态持久化
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://book.2stzcr.asia/blog/384275.Doc

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://book.2stzcr.asia/blog/944176.Doc

原标题：golang 系统设计请求签名校验完整方案
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://book.2stzcr.asia/blog/606692.Doc

原标题：golang 日志 zap 结构化日志实践
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://book.2stzcr.asia/blog/082601.Doc

原标题：golang 系统设计缓存优化落地实操指南
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://book.2stzcr.asia/blog/829869.Doc

原标题：golang 系统设计线程协程泄露定位方法
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://book.2stzcr.asia/blog/829666.Doc

原标题：Hands‑on：代码生成器，一键生成CRUD模板
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://book.2stzcr.asia/blog/166646.Doc

原标题：坑点：gitcherry‑pick引入不兼容代码
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://book.2stzcr.asia/blog/299509.Doc

原标题：golang 链路 traceId 透传中间件
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://book.2stzcr.asia/blog/533234.Doc

原标题：golang 消息队列 kafka 消费开发
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://book.2stzcr.asia/blog/711652.Doc

原标题：golang 系统设计最小权限原则落地实践
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://book.2stzcr.asia/blog/903257.Doc

原标题：express 请求参数校验处理
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://book.2stzcr.asia/blog/300732.Doc

四、架构设计｜Architecture
原标题：golang 系统设计性能瓶颈定位完整方法论
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://book.2stzcr.asia/blog/963624.Doc

原标题：新手教程：gitrebase基础使用与风险提示
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://book.2stzcr.asia/blog/671922.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://book.2stzcr.asia/blog/463813.Doc

原标题：golang mysql 行锁表锁场景区分
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://book.2stzcr.asia/blog/788719.Doc

原标题：golang 系统设计监控大盘故障快速定位思路
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://book.2stzcr.asia/blog/618130.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://book.2stzcr.asia/blog/431625.Doc

原标题：安全实践：生产环境禁止开启debug调试模式
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://book.2stzcr.asia/blog/949931.Doc

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://book.2stzcr.asia/blog/741086.Doc

原标题：golang redis 发布订阅简单示例
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://book.2stzcr.asia/blog/851163.Doc

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://book.2stzcr.asia/blog/515295.Doc

原标题：nodejs 集成测试业务流程编写
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://book.2stzcr.asia/blog/647172.Doc

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://book.2stzcr.asia/blog/113103.Doc

原标题：golang docker 部署 mysql 注意事项
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://book.2stzcr.asia/blog/781240.Doc

原标题：eslint prettier 代码规范落地
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://book.2stzcr.asia/blog/314178.Doc

原标题：DevOps：WSL2生产环境使用风险提示
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://book.2stzcr.asia/blog/514865.Doc

原标题：踩坑记录：分页逻辑错误造成数据重复输出
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://book.2stzcr.asia/blog/202102.Doc

原标题：golang 系统设计 api 接口兼容性设计原则
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://book.2stzcr.asia/blog/398695.Doc

原标题：golang 系统设计 lru 缓存算法实现思路
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://book.2stzcr.asia/blog/430022.Doc

?
