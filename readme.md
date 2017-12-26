﻿# 个人信息

- 李耿斌/男/1988年
- 学校：广东工业大学 (2007~2011)
- 专业：计算机科学与技术
- 学位：本科工学学士
- 工作年限：2011年至今
- 期望职位：后端高级工程师
- 期望城市：深圳/广州/珠海

---

# 联系方式

- Tel: 13250201567
- Email: kenbinglee@gmail.com
- QQ: 6904505
- Github: github.com/kenbing
- Blog: http://0xff00.com

---

# 工作经历


## Mobvista (2017-03-27 ~ 2017-11-28)

*声明：由于公司业务变更，与个人发展方向相违背，于 2017-11-28 号正式离职*

### 1. 基于Facebook开放平台构建的广告自投系统（FMP）

**FMP架构审查优化**

- FMP 用户数据访问权限安全优化
- FMP 登陆安全/链路安全 问题优化
- Adapi 架构图梳理及输出业务接口文档
- Adapi 白名单机器整理并推动IT部及运维部清理过期机器

**FMP业务需求开发**

- 广告创建/开闭业务异步化
- 修复广告统计SQL慢查并普及调优方案
- 修复批量接口500丢数据疑难问题

**流程优化**

- 协同改进组内gitflow
- 推动运维部门机器权责归属流程 


## 酷狗音乐 (2014-11-10 ~ 2016-07-25)

### 1. 酷狗直播

日常业务开发维护

- 送礼模块
- 关注系统
- 鉴黄系统
- 结算模块

营收活动开发

- 2015年酷音乐盛典
- 魏晨粉丝见面会等

### 2. 酷狗广告位接口

处理酷狗平台及客户端所有广告入口的请求，采用 Openresty 实现单机 (2*6core + 64G) 2W QPS，支持横向扩容的服务集群保证服务的稳定，引入 Redis 3.0 新集群特性解决原来单点问题及减少运维成本

### 3. 通用推拉流平台

酷狗流服务平台及繁星推拉流服务的一个中间件，同样采用 Openresty 提供异步服务，保证了繁星全平台产品的推拉流服务统一接入，隐藏流媒体具体的业务接入及变更


## 4399游戏/飞游网络/胡莱游戏 (2011-10-17 ~ 2014-06-20)

本人在4399所属部门（奥丁工作室）后期由于独立出来创业，本人所在团队在公司归属问题上经历了三个投资人，先后签署了三份合同，而实际工作负责的内容是一直持续进行的，固合并为一段经历，特此声明

- 2011-10 ~ 2012-02 广州爱游信息科技有限公司
- 2012-02 ~ 2012-07 广州飞游网络科技有限公司
- 2012-07 ~ 2014-06 广州互爱信息科技有限公司
(由于广州互爱是13年1月份才正式注册，所以合同是13年1月份开始签订，可直接找互爱人事行政主管黄永光证明 020-38350590)

### 1. 斩仙游戏

- 负责游戏礼包模块的开发
- 负责腾讯特权开通及相关所有运营营收活动

### 2. 游戏充值登录入口

负责游戏充值及登录业务的设计及实现，包括数据库设计及服务器架构的优化，这个项目最大的收获是在一周内学习并用 JSP 实现了功能，并在日后游戏访问量激增后优化了 Tomcat 连接数，并在一些访峰值访问量较大的平台通过两台 Tomcat + 前置 Nginx 做负载均衡，把并发峰值1000提高了一倍，保证游戏正常的登录及充值两大核心业务

### 3. 游戏运营管理后台

负责把各个游戏后台分冗余代码的模块化，实现标准管理后台的雏形，减少不同项目后台的差异从而减少后期维护的成本，并加入了 memcached，提高经常性访问数据的调用，减少DB层的压力

后期做为项目负责人，主要对架构优化调整，例如把 PHP 迁移至5.6，Memcache 更换为 Redis，view 层用 Bootstrap 重写，编写技术文档，培养新人及代码审核

### 4. 运维资产管理系统

负责报警模块的开发，调用服务器预警系统提供的报警短线API发送报警信息，并通过加入报警阀值减少多余报警的干预，并自学写一个 python 日志抓取程序，把数据间隔同步到本地，提高2倍数据加载的响应速度

---

# 技能清单

- 开发平台: LNMP/Openresy
- Linux: Archlinux/CentOS/Ubuntu
- RPC框架: Thrift/ProtoBuf
- 前端库: JQuery/Bootstrap/Highchart
- 数据库: Mysql
- 缓存: Memcache/Redis
- 虚拟化: Docker/VBox
- 消息队列: NSQ/Kafka
- 版本管理: Git/SVN
- 编辑器: Vim
- 日志相关: ELK

---

# 开源贡献

### [nsqphp](https://github.com/davegardnerisme/nsqphp '项目地址')

Pull request：https://github.com/davegardnerisme/nsqphp/pull/48

说明：为NSQ官方php客户端贡献过补丁，使其支持多字节字符的传输

---

# 自我评价 

工作上，关注分布式领域，擅长构建高并发高可用平台，善于表达，理解能力强，沟通有技巧，能妥当处理组内外的合作，英文流利，轻松阅读英文文档，善用 Google, StackOverFlow, Github, 活跃于部分开源社区。

生活中，热爱摇滚乐，玩过band，当过背包客。

---

# 其他经历

### 徒步滇藏线 (2014-07 ~ 2014-10)

从游戏公司离职当天定好机票，开始了我的背包客之旅，耗时二个月从大理途步至拉萨，后来坐青藏铁路经由格尔木，西宁，西安等城市一路回到广州。

### Gap Year (2016-08 ~ 2017-01)

计划了一趟为期半年的间隔年，分别在泰国，四川，杭州，上海生活了半年时间，其中以清迈停留时间最长，大抵一个半月，熟悉古城的每条小巷。
