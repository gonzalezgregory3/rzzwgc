最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Architecture：中小型后端服务整体架构设计复盘
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.etx3og.asia/arts/435399.Doc

原标题：设计思考：API网关和BFF职责边界划分
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.etx3og.asia/arts/913407.Doc

原标题：安全实践：生产环境禁止开启debug调试模式
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.etx3og.asia/arts/901581.Doc

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.etx3og.asia/arts/260396.Doc

原标题：项目实践：数据库慢日志采集分析落地实践
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://wiki.etx3og.asia/arts/713026.Doc

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.etx3og.asia/arts/410848.Doc

原标题：WSL 搭建 Windows Linux 开发环境
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.etx3og.asia/arts/792302.Doc

原标题：golang 系统设计 id 生成器选型对比
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://wiki.etx3og.asia/arts/306617.Doc

原标题：部署实践：服务器时间同步chrony配置
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://wiki.etx3og.asia/arts/125271.Doc

原标题：记一次限流组件误配置把正常用户拦截
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.etx3og.asia/arts/203040.Doc

原标题：golang 日志脱敏敏感字段过滤
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.etx3og.asia/arts/519625.Doc

原标题：站内邮件消息通知功能开发
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://wiki.etx3og.asia/arts/014425.Doc

原标题：golang 系统设计监控告警阈值设置思路
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://wiki.etx3og.asia/arts/344709.Doc

原标题：包管理器依赖缓存清理
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.etx3og.asia/arts/574596.Doc

原标题：golang 系统设计监控体系指标分类方法论梳理
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.etx3og.asia/arts/166760.Doc

原标题：AI实践：大模型生成代码后审查与重构实践
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.etx3og.asia/arts/606751.Doc

原标题：Hands‑on：简易连接池原型实现理解原理
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://wiki.etx3og.asia/arts/732618.Doc

原标题：实战项目：容器健康探针配置完整实践示例
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://wiki.etx3og.asia/arts/385485.Doc

原标题：Docker Compose 一键搭建本地栈
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.etx3og.asia/arts/110703.Doc

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.etx3og.asia/arts/976338.Doc

原标题：golang 系统设计数据库死锁分析规避
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.etx3og.asia/arts/947873.Doc

原标题：golang 系统设计 mq 消息积压解决方案
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://wiki.etx3og.asia/arts/974545.Doc

原标题：golang 配置热更新不重启服务
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://wiki.etx3og.asia/arts/486592.Doc

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.etx3og.asia/arts/054411.Doc

原标题：磁盘 inode 耗尽文件创建失败
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.etx3og.asia/arts/098658.Doc

原标题：golang 系统设计本地缓存更新失效方案实现
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://wiki.etx3og.asia/arts/393595.Doc

原标题：入门实践：简单数据脱敏处理示例
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.etx3og.asia/arts/484446.Doc

原标题：golang mysql 避免 select * 查询
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.etx3og.asia/arts/492899.Doc

原标题：golang 系统设计 cpu 瓶颈定位优化方案
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://wiki.etx3og.asia/arts/162000.Doc

原标题：golang 系统设计批量处理优化业务性能
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.etx3og.asia/arts/533713.Doc

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.etx3og.asia/arts/504771.Doc

原标题：golang k8s helm chart 简单编写
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.etx3og.asia/arts/543337.Doc

原标题：优化实践：分页查询性能优化解决offset问题
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.etx3og.asia/arts/911269.Doc

原标题：项目实践：Docker镜像安全扫描本地实操
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://wiki.etx3og.asia/arts/973107.Doc

原标题：golang 优雅停机服务关闭实现
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.etx3og.asia/arts/306991.Doc

原标题：入门实践：简单数据脱敏处理示例
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.etx3og.asia/arts/613844.Doc

原标题：线上故障：慢查询拖垮整个数据库服务
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.etx3og.asia/arts/607498.Doc

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://wiki.etx3og.asia/arts/637107.Doc

原标题：HelloWorld：快速上手新项目最小可运行示例
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.etx3og.asia/arts/496211.Doc

原标题：调优方案：Web服务内核socket参数调优
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://wiki.etx3og.asia/arts/423733.Doc


二、踩坑排错｜Troubleshooting
原标题：webpack chunk 分包策略详解
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://wiki.etx3og.asia/arts/931249.Doc

原标题：项目实践：消息队列消息确认机制业务实践
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://wiki.etx3og.asia/arts/351948.Doc

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.etx3og.asia/arts/933060.Doc

原标题：Hands‑on：简易速率限制中间件完整实现
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.etx3og.asia/arts/299295.Doc

原标题：golang 静态编译缩小镜像体积
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://wiki.etx3og.asia/arts/724928.Doc

原标题：开发代理服务网络限制解决
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://wiki.etx3og.asia/arts/526047.Doc

原标题：实战项目：实现分布式任务调度最小原型
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.etx3og.asia/arts/787115.Doc

原标题：Architecture：文件处理服务架构大文件内存规避
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.etx3og.asia/arts/059836.Doc

原标题：Redis 分布式锁高并发安全实现
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.etx3og.asia/arts/204621.Doc

原标题：golang rsa 非对称加密签名验签
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.etx3og.asia/arts/649606.Doc

原标题：golang 系统设计本地缓存与分布式缓存
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.etx3og.asia/arts/481087.Doc

原标题：API 大版本不兼容平滑迁移
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.etx3og.asia/arts/838480.Doc

原标题：golang consul 健康检查服务注册
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.etx3og.asia/arts/076995.Doc

原标题：复盘总结：数据库迁移升级风险评估清单
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.etx3og.asia/arts/209094.Doc

原标题：Architecture：配置中心架构，动态配置设计思路
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.etx3og.asia/arts/260523.Doc

原标题：golang 系统设计压测指标 qps rt 错误率讲解
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.etx3og.asia/arts/156560.Doc

原标题：线程调度优化减少上下文切换
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.etx3og.asia/arts/880704.Doc

原标题：Issue：操作系统最大打开文件数限制导致报错
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.etx3og.asia/arts/634486.Doc

原标题：踩坑：大事务引发数据库连接池耗尽
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.etx3og.asia/arts/909029.Doc

原标题：golang 系统设计数据库表设计通用规范模板
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://wiki.etx3og.asia/arts/814743.Doc

原标题：golang 系统设计配置本地缓存降级策略方案
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://wiki.etx3og.asia/arts/129339.Doc

原标题：Troubleshooting：数据库主从延迟带来查询数据不一致
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://wiki.etx3og.asia/arts/452224.Doc

原标题：golang consul 健康检查服务注册
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.etx3og.asia/arts/623072.Doc

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://wiki.etx3og.asia/arts/425953.Doc

原标题：部署实践：Nginx高可用配置方案实践
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.etx3og.asia/arts/014555.Doc

原标题：golang 系统设计第三方调用超时重试熔断
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://wiki.etx3og.asia/arts/640336.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://wiki.etx3og.asia/arts/452315.Doc

原标题：文件句柄耗尽资源泄露处理
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://wiki.etx3og.asia/arts/248288.Doc

原标题：从零搭建简单CLI命令行工具
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://wiki.etx3og.asia/arts/814644.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://wiki.etx3og.asia/arts/773962.Doc

原标题：记一次第三方SDK版本兼容引发线上故障
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.etx3og.asia/arts/818033.Doc

原标题：golang 雪花 id 重复问题排查
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://wiki.etx3og.asia/arts/354120.Doc

原标题：快速入门YAML配置文件语法与示例
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://wiki.etx3og.asia/arts/646333.Doc

原标题：golang kafka 同步异步消费对比
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://wiki.etx3og.asia/arts/538488.Doc

原标题：golang docker 网络模式桥接 host
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://wiki.etx3og.asia/arts/429377.Doc

原标题：部署复盘：服务启动顺序依赖处理方案
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.etx3og.asia/arts/858517.Doc

原标题：golang 系统设计配置敏感信息加密存储方案
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.etx3og.asia/arts/930062.Doc

原标题：golang defer panic 异常处理
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.etx3og.asia/arts/828741.Doc

原标题：设计思考：消息顺序性架构保证与业务妥协
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.etx3og.asia/arts/081858.Doc

原标题：批量操作分批处理防止 OOM
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.etx3og.asia/arts/155308.Doc

三、实战开发｜Practice
原标题：开发记录：接口请求日志记录完整中间件实现
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.etx3og.asia/arts/745443.Doc

原标题：golang 系统设计开源项目安全漏洞处理流程
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.etx3og.asia/arts/561452.Doc

原标题：golang 系统设计数据脱敏架构实现
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://wiki.etx3og.asia/arts/947441.Doc

原标题：Practice：实现数据库事务消息最终一致性demo
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://wiki.etx3og.asia/arts/787621.Doc

原标题：vite 插件开发自定义构建逻辑
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://wiki.etx3og.asia/arts/455380.Doc

原标题：git rebase 整理提交历史实操
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.etx3og.asia/arts/506153.Doc

原标题：Hands‑on：简易链路追踪原型开发实践
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://wiki.etx3og.asia/arts/506451.Doc

原标题：golang 系统设计本地缓存更新失效方案实现
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://wiki.etx3og.asia/arts/322048.Doc

原标题：golang es 聚合统计查询实现
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.etx3og.asia/arts/671079.Doc

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://wiki.etx3og.asia/arts/875049.Doc

原标题：坑点：版本号语义化理解错误依赖版本错乱
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.etx3og.asia/arts/712638.Doc

原标题：实战：数据库索引设计，复合索引最佳实践
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.etx3og.asia/arts/081256.Doc

原标题：新手指南：看懂开源项目的Issue与PR
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.etx3og.asia/arts/154488.Doc

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.etx3og.asia/arts/527964.Doc

原标题：Git 误提交撤销回退实操教程
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.etx3og.asia/arts/930149.Doc

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.etx3og.asia/arts/487226.Doc

原标题：DevOps：CI构建产物缓存复用加速编译
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://wiki.etx3og.asia/arts/306391.Doc

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://wiki.etx3og.asia/arts/960468.Doc

原标题：golang redis 过期策略内存淘汰
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.etx3og.asia/arts/660653.Doc

原标题：golang mysql 事务回滚异常处理
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://wiki.etx3og.asia/arts/892943.Doc

原标题：golang 系统设计服务优雅停机完整流程
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.etx3og.asia/arts/136014.Doc

原标题：项目实践：消息队列消息堆积模拟处理实践
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://wiki.etx3og.asia/arts/261554.Doc

原标题：golang k8s 持久化 pv pvc 使用实操
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://wiki.etx3og.asia/arts/592790.Doc

原标题：golang github actions 缓存依赖提速
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.etx3og.asia/arts/536392.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.etx3og.asia/arts/052183.Doc

原标题：安全复盘：定时任务权限过大风险管控
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.etx3og.asia/arts/604170.Doc

原标题：golang 系统设计 lru 缓存算法实现思路
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.etx3og.asia/arts/429705.Doc

原标题：Hands‑on：静态资源CDN缓存控制头配置实践
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://wiki.etx3og.asia/arts/303072.Doc

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://wiki.etx3og.asia/arts/218601.Doc

原标题：消息消费重试次数限制防爆炸
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.etx3og.asia/arts/250805.Doc

原标题：Performance：批量导入数据性能优化实践
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://wiki.etx3og.asia/arts/236314.Doc

原标题：golang github actions 缓存依赖提速
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.etx3og.asia/arts/644213.Doc

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://wiki.etx3og.asia/arts/579054.Doc

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://wiki.etx3og.asia/arts/381597.Doc

原标题：新手指南：本地多版本环境共存配置
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.etx3og.asia/arts/245364.Doc

原标题：golang url 参数编码处理方案
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.etx3og.asia/arts/259096.Doc

原标题：golang kafka offset 提交策略
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.etx3og.asia/arts/373952.Doc

原标题：golang excel 简单读写操作示例
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.etx3og.asia/arts/417604.Doc

原标题：golang 系统设计缓存预热缓存降级实现
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://wiki.etx3og.asia/arts/315906.Doc

原标题：golang 结构体 json 序列化坑点
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://wiki.etx3og.asia/arts/717140.Doc

四、架构设计｜Architecture
原标题：golang gin 静态资源访问配置
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://wiki.etx3og.asia/arts/975047.Doc

原标题：GitHub Markdown 文档语法汇总
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://wiki.etx3og.asia/arts/178029.Doc

原标题：快速入门ORM，实现简单数据库增删改查
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.etx3og.asia/arts/318570.Doc

原标题：golang 系统设计缓存一致性方案对比
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.etx3og.asia/arts/647303.Doc

原标题：新手教程：gitrebase基础使用与风险提示
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.etx3og.asia/arts/679337.Doc

原标题：nestjs 拦截器过滤器管道实战
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://wiki.etx3og.asia/arts/000616.Doc

原标题：golang 系统设计数据库连接池调优实践
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.etx3og.asia/arts/851557.Doc

原标题：OpenSource：开源项目许可证License选型指南
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.etx3og.asia/arts/966725.Doc

原标题：golang docker 基础命令实操汇总
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.etx3og.asia/arts/199182.Doc

原标题：golang git 提交信息规范校验
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.etx3og.asia/arts/903476.Doc

原标题：Nginx 缓冲区调优大文件上传
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://wiki.etx3og.asia/arts/936658.Doc

原标题：前端国际化多语言方案落地
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.etx3og.asia/arts/786410.Doc

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.etx3og.asia/arts/884151.Doc

原标题：golang 静态文件服务搭建教程
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.etx3og.asia/arts/201129.Doc

原标题：复盘总结：线上故障完整复盘报告模板示例
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.etx3og.asia/arts/540869.Doc

原标题：golang docker 部署 mongodb 开发环境
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://wiki.etx3og.asia/arts/077654.Doc

原标题：golang docker 部署 mysql 注意事项
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.etx3og.asia/arts/976048.Doc

原标题：golang 系统设计 mq 消息丢失完整防护
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://wiki.etx3og.asia/arts/117410.Doc

?
