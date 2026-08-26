最新前沿技术资讯

一、入门教程｜Getting Started
原标题：记一次GC频繁，服务CPU持续高负载排查
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.bl1u1s.asia/arts/392233.Doc

原标题：Hands‑on：简易熔断逻辑状态机原型实现
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://wiki.bl1u1s.asia/arts/058629.Doc

原标题：DNS 解析异常第三方调用故障
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.bl1u1s.asia/arts/592081.Doc

原标题：Debug：并发场景下数据覆盖丢失问题定位
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://wiki.bl1u1s.asia/arts/741561.Doc

原标题：TCP 心跳检测清理僵死连接
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.bl1u1s.asia/arts/959285.Doc

原标题：ServiceWorker 缓存页面更新清理
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.bl1u1s.asia/arts/670763.Doc

原标题：多套环境灵活切换配置方案
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://wiki.bl1u1s.asia/arts/663356.Doc

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://wiki.bl1u1s.asia/arts/523993.Doc

原标题：DevOps：CI构建产物缓存复用加速编译
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.bl1u1s.asia/arts/757943.Doc

原标题：5分钟快速搭建个人技术文档站点
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.bl1u1s.asia/arts/080185.Doc

原标题：golang 系统设计故障演练简单落地思路方法论
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.bl1u1s.asia/arts/797723.Doc

原标题：golang 系统设计分表分页排序业务实现难点
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://wiki.bl1u1s.asia/arts/683935.Doc

原标题：记一次升级操作系统内核引发服务不稳定
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.bl1u1s.asia/arts/481752.Doc

原标题：快速上手搭建简易内网测试服务
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.bl1u1s.asia/arts/789648.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.bl1u1s.asia/arts/424409.Doc

原标题：golang 系统设计监控大盘故障快速定位思路
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.bl1u1s.asia/arts/802583.Doc

原标题：新手指南：本地防火墙端口访问失败排查
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.bl1u1s.asia/arts/079357.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://wiki.bl1u1s.asia/arts/966358.Doc

原标题：开发记录：跨域中间件完整配置与边界处理
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.bl1u1s.asia/arts/965905.Doc

原标题：golang 系统设计链路追踪架构简单讲解
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://wiki.bl1u1s.asia/arts/425516.Doc

原标题：坑点：限流计数器重置时机错误，绕过限流规则
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://wiki.bl1u1s.asia/arts/404681.Doc

原标题：TCP 长连接参数优化 TIME_WAIT
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.bl1u1s.asia/arts/539069.Doc

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.bl1u1s.asia/arts/190655.Doc

原标题：Git 误提交撤销回退实操教程
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://wiki.bl1u1s.asia/arts/638217.Doc

原标题：实践：消息队列死信处理业务落地实践
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://wiki.bl1u1s.asia/arts/554336.Doc

原标题：golang 系统设计时间字段选型 datetime timestamp
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://wiki.bl1u1s.asia/arts/109848.Doc

原标题：golang 系统设计网关缓存静态资源实现思路
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.bl1u1s.asia/arts/522384.Doc

原标题：golang 系统设计敏感数据加密存储方案
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.bl1u1s.asia/arts/660077.Doc

原标题：golang redis 位图用户签到统计
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.bl1u1s.asia/arts/369839.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.bl1u1s.asia/arts/757344.Doc

原标题：架构笔记：多数据源架构设计事务处理难点
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.bl1u1s.asia/arts/316818.Doc

原标题：golang 系统设计网关限流熔断降级配置思路
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.bl1u1s.asia/arts/644145.Doc

原标题：golang es 查询语句 DSL 实操
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://wiki.bl1u1s.asia/arts/108982.Doc

原标题：操作系统内核版本适配服务
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.bl1u1s.asia/arts/081295.Doc

原标题：空指针异常判空容错处理
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://wiki.bl1u1s.asia/arts/971514.Doc

原标题：磁盘占满服务不可用清理方案
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://wiki.bl1u1s.asia/arts/113098.Doc

原标题：Practice：实现请求大小限制中间件防护大报文
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://wiki.bl1u1s.asia/arts/635880.Doc

原标题：文件句柄耗尽资源泄露处理
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://wiki.bl1u1s.asia/arts/031745.Doc

原标题：vite 项目配置与构建提速技巧
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.bl1u1s.asia/arts/699945.Doc

原标题：Practice：实现业务唯一流水号生成组件实践
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.bl1u1s.asia/arts/717133.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 项目 makefile 脚本编写
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://wiki.bl1u1s.asia/arts/199484.Doc

原标题：golang grafana 面板变量模板制作
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://wiki.bl1u1s.asia/arts/336995.Doc

原标题：开发记录：容器日志标准输出采集实践方案
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.bl1u1s.asia/arts/853692.Doc

原标题：踩坑记录：分页逻辑错误造成数据重复输出
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://wiki.bl1u1s.asia/arts/032483.Doc

原标题：golang 系统设计开源 pr 评审合并流程实操
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://wiki.bl1u1s.asia/arts/877470.Doc

原标题：golang 系统设计序列化性能选型对比
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.bl1u1s.asia/arts/008288.Doc

原标题：Architecture：事件溯源架构模式适用业务场景
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://wiki.bl1u1s.asia/arts/792152.Doc

原标题：坑点：缓存过期策略不当引发业务异常
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://wiki.bl1u1s.asia/arts/554663.Doc

原标题：golang 系统设计内部服务 mock 集成测试方案
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://wiki.bl1u1s.asia/arts/940053.Doc

原标题：golang k8s 节点污点容忍度配置
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://wiki.bl1u1s.asia/arts/059555.Doc

原标题：快速上手单元测试，写出第一个测试用例
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.bl1u1s.asia/arts/479543.Doc

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.bl1u1s.asia/arts/060764.Doc

原标题：Hands‑on：简易导出PDF后端生成demo实践
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.bl1u1s.asia/arts/655974.Doc

原标题：golang 系统设计告警规则阈值设置方法论
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://wiki.bl1u1s.asia/arts/108119.Doc

原标题：golang 系统设计密钥轮换安全实践思路
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.bl1u1s.asia/arts/244481.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.bl1u1s.asia/arts/706933.Doc

原标题：golang 系统设计本地缓存 redis 缓存多级组合
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://wiki.bl1u1s.asia/arts/038733.Doc

原标题：golang 系统设计分库分表 id 全局生成策略
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.bl1u1s.asia/arts/765572.Doc

原标题：快速入门日志打印与日志分级基础用法
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://wiki.bl1u1s.asia/arts/325870.Doc

原标题：golang 系统设计日志级别业务使用原则梳理
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.bl1u1s.asia/arts/191838.Doc

原标题：golang 配置文件多环境加载
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://wiki.bl1u1s.asia/arts/872648.Doc

原标题：golang 系统设计代码仓库权限管理方案
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://wiki.bl1u1s.asia/arts/059979.Doc

原标题：大事务拆分回滚日志暴涨解决
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://wiki.bl1u1s.asia/arts/482070.Doc

原标题：golang rate‑limiter 限流组件
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://wiki.bl1u1s.asia/arts/115307.Doc

原标题：新手指南：读懂项目构建脚本作用
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.bl1u1s.asia/arts/239185.Doc

原标题：数据库分表存储大表优化方案
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.bl1u1s.asia/arts/693428.Doc

原标题：前端水印防信息泄露实现
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://wiki.bl1u1s.asia/arts/184557.Doc

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.bl1u1s.asia/arts/205590.Doc

原标题：新手向：配置项目eslint/prettier代码格式化
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://wiki.bl1u1s.asia/arts/333734.Doc

原标题：golang 系统设计缓存故障降级处理方案
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://wiki.bl1u1s.asia/arts/596418.Doc

原标题：新手向：开源项目fork与同步上游代码
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.bl1u1s.asia/arts/700245.Doc

原标题：golang 系统设计缓存预热脚本编写实操
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://wiki.bl1u1s.asia/arts/254872.Doc

原标题：golang 系统设计容器健康检查设计思路
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.bl1u1s.asia/arts/778482.Doc

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://wiki.bl1u1s.asia/arts/617565.Doc

原标题：ICMP 放通网络丢包问题修复
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://wiki.bl1u1s.asia/arts/375859.Doc

原标题：重复提交幂等防护再次讲解
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://wiki.bl1u1s.asia/arts/191936.Doc

原标题：golang 系统设计服务优雅停机完整流程
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.bl1u1s.asia/arts/867358.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.bl1u1s.asia/arts/939036.Doc

原标题：设计思考：系统容量评估架构前期估算思路
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.bl1u1s.asia/arts/555268.Doc

原标题：git rebase 整理提交历史实操
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://wiki.bl1u1s.asia/arts/125371.Doc

三、实战开发｜Practice
原标题：golang 结构体深拷贝几种实现
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://wiki.bl1u1s.asia/arts/993348.Doc

原标题：零基础理解缓存基础原理与简单使用
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://wiki.bl1u1s.asia/arts/490740.Doc

原标题：golang 系统设计开源 issue 处理回复沟通技巧
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://wiki.bl1u1s.asia/arts/419946.Doc

原标题：nestjs 权限守卫鉴权实现方案
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.bl1u1s.asia/arts/560625.Doc

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://wiki.bl1u1s.asia/arts/505474.Doc

原标题：分布式 ID 生成器高并发实现
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.bl1u1s.asia/arts/209486.Doc

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.bl1u1s.asia/arts/605309.Doc

原标题：时间精度统一业务判断修复
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.bl1u1s.asia/arts/568548.Doc

原标题：Performance：批量导入数据性能优化实践
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.bl1u1s.asia/arts/167322.Doc

原标题：golang 系统设计限流算法原理代码实现
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.bl1u1s.asia/arts/849504.Doc

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.bl1u1s.asia/arts/323739.Doc

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://wiki.bl1u1s.asia/arts/572078.Doc

原标题：golang 系统设计 mq 消息丢失完整防护
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://wiki.bl1u1s.asia/arts/906233.Doc

原标题：性能笔记：磁盘IO过高业务优化手段
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://wiki.bl1u1s.asia/arts/568099.Doc

原标题：容器软链接文件权限修复
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://wiki.bl1u1s.asia/arts/243054.Doc

原标题：开发代理服务网络限制解决
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.bl1u1s.asia/arts/241389.Doc

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://wiki.bl1u1s.asia/arts/800058.Doc

原标题：nodejs 多进程任务分发处理
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://wiki.bl1u1s.asia/arts/494104.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.bl1u1s.asia/arts/783230.Doc

原标题：OpenSource：大型仓库Git历史清理瘦身实操
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.bl1u1s.asia/arts/186894.Doc

原标题：Nginx 丢失请求头配置修正
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.bl1u1s.asia/arts/906144.Doc

原标题：动态定时任务业务调度实现
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.bl1u1s.asia/arts/800338.Doc

原标题：golang 数据库批量更新性能优化
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.bl1u1s.asia/arts/950060.Doc

原标题：网关超时时间调优后端等待
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://wiki.bl1u1s.asia/arts/690311.Doc

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.bl1u1s.asia/arts/677952.Doc

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://wiki.bl1u1s.asia/arts/799900.Doc

原标题：golang 系统设计回调签名校验防伪造实现
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.bl1u1s.asia/arts/712932.Doc

原标题：nodejs redis 缓存业务实战
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.bl1u1s.asia/arts/449794.Doc

原标题：代码模块化组件化拆分思路
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://wiki.bl1u1s.asia/arts/684770.Doc

原标题：golang docker 部署 prometheus 整套
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://wiki.bl1u1s.asia/arts/028073.Doc

原标题：golang 系统设计 changelog 变更日志维护
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://wiki.bl1u1s.asia/arts/775835.Doc

原标题：golang 系统设计技术债务识别登记治理思路
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.bl1u1s.asia/arts/344206.Doc

原标题：golang 系统设计大文件上传架构
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://wiki.bl1u1s.asia/arts/480213.Doc

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.bl1u1s.asia/arts/290055.Doc

原标题：记一次限流组件误配置把正常用户拦截
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://wiki.bl1u1s.asia/arts/640394.Doc

原标题：架构复盘：容器资源隔离架构CPU内存限制设计
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.bl1u1s.asia/arts/679895.Doc

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.bl1u1s.asia/arts/260462.Doc

原标题：优化实践：业务定时任务错开高峰避免资源争抢
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.bl1u1s.asia/arts/915663.Doc

原标题：CI 构建缓存加速编译速度
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://wiki.bl1u1s.asia/arts/077458.Doc

原标题：golang kafka 消息顺序性保证方案
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://wiki.bl1u1s.asia/arts/552933.Doc

四、架构设计｜Architecture
原标题：golang k8s service 服务暴露几种类型
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.bl1u1s.asia/arts/727721.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.bl1u1s.asia/arts/569955.Doc

原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://wiki.bl1u1s.asia/arts/830155.Doc

原标题：Docker 容器入门镜像实操教程
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.bl1u1s.asia/arts/256521.Doc

原标题：golang 空接口 interface 使用技巧
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.bl1u1s.asia/arts/175870.Doc

原标题：后端分页查询逻辑代码实现
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.bl1u1s.asia/arts/568896.Doc

原标题：Git 分支切换合并删除完整操作
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://wiki.bl1u1s.asia/arts/234112.Doc

原标题：golang 系统设计分库分表本地测试调试技巧
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://wiki.bl1u1s.asia/arts/317428.Doc

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.bl1u1s.asia/arts/147433.Doc

原标题：开发复盘：超时参数统一治理线上服务实践
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://wiki.bl1u1s.asia/arts/824974.Doc

原标题：性能复盘：消息队列大量小消息性能问题优化
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://wiki.bl1u1s.asia/arts/446706.Doc

原标题：eslint prettier 代码规范落地
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.bl1u1s.asia/arts/944917.Doc

原标题：实践：OpenAPI自动生成接口文档完整实践
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.bl1u1s.asia/arts/201157.Doc

原标题：开源实践：给开源项目写单元测试贡献代码
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://wiki.bl1u1s.asia/arts/923391.Doc

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.bl1u1s.asia/arts/261523.Doc

原标题：开发环境变量配置全平台教程
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.bl1u1s.asia/arts/949335.Doc

原标题：golang 系统设计本地消息表可靠消息最终一致性
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.bl1u1s.asia/arts/404887.Doc

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://wiki.bl1u1s.asia/arts/957890.Doc

?
