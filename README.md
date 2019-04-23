### 关于我

- 姓名：李卫
- 专业：计算机网络
- 职业：后端开发
- Email: phper_lee@foxmail.com

### 工作经历
> 2018/05 - 至今 武汉智汇互动信息科技有限公司 **后端开发**

- 工作内容
    - 自媒体数据平台相关功能开发
    - 各类自媒体数据平台数据抓取，爬虫开发 
    - 工具类小程序项目功能开发
    - 内部小工具开发
- 参与项目
    - [快传播数据平台](http://data.711.cn)
    - [快传播编辑器](http://edit.711.cn)
    - 快传播第三方平台数据采集爬虫
    - 快传播后台管理小程序

> 2017/05 - 2018/04 悦云软件科技(北京)有限公司 **后端开发**

- 工作内容
  - 负责小程序门店和后台系统项目搭建及功能开发
  - 负责微商城项目功能开发及优化
  - 参与PC端门店系统后台功能开发
- 参与项目
  - 悦云智慧门店-小程序 && 智慧后台-小程序
  - 悦云智慧门店web端

> 2015/05 - 2017/5  客客信息技术有限公司 **后端开发**

- 工作内容
  - 负责公司自由产品[官网](http://www.kppw.cn)、[任务易](http://www.renwuyi.com)日常bug处理及新专题上线技术支持;
  - 带领开发小组完成公司[开源威客系统](http://demo.kppw.cn)功能开发及版本迭代;
  - 对售后反馈bug进行及时修复，并安排开发人员处理售后工单;
  - 利用公司开源项目完成各类客户二次开发任务需求完成项目交付;
- 参与项目
  - [新版KPPW威客系统](http://demo.kppw.cn)
  - [杭州科技局海螺邦](https://www.solosea.com/)
  - 立木项目
  - 点谷科技
  - [KEE协同工具](http://www.kee.im)
  - [KEKE官网](http://www.kppw.cn)


### 项目经验

##### 快传播数据平台
- 项目需求
   针对站内微信、微博、小红书、直播、短视频类媒体资源，搭建数据平台，实现平台内资源检索及榜单排名。同时实现各类API接口，配合内部其他应用功能实现。
    
- 责任描述
    - 基于项目需求进行后端开发
    - 第三方平台资源采集爬虫
    - 分配视图开发任务，并协调前端完成功能

- 技术栈
    - 基于laravel 5.5搭建项目，使用redis实现queue和cache
    - 使用elastic search实现库内资源检索及分词提取
    - 基于scrapy 实现部分爬虫采集功能，配合scrapyd-web等工具实现爬虫可视化管理
    - selenium、charles实现中间人采集方式的爬虫及xpath实现dom渲染内容提取
    - 使用mongodb 进行非重要数据的采集提取计算

##### 快传播编辑器
- 项目需求
  满足平台内客户内容发布编辑，搭建站内富文本资源编辑器。
  
- 责任描述
    - 实现编辑器资源编辑功能
    - 抓取第三方站点模板，填充编辑器内资源模板
    - 实现微信授权登录

- 技术栈
    - laravel 5.5搭建项目结构
    - 基于baidu富文本编辑器实现editor组件
    - python、php爬虫采集第三方资源站点

##### 快传播后台管理小程序
- 项目需求
  满足公司内部员工在非合法网段内的后台管理需求，实现移动端后台功能操作。
  
- 责任描述
    - 搭建小程序基础项目结构
    - 封装业务service及功能交互
    - 协调前端视图部分开发

- 技术栈
    - mpvue 搭建基础项目结构
    - axios 封装项目业务xhr请求

##### 悦云智慧门店、中控系统
- 项目需求
  基于微信小程序平台，实现门店系统小程序端管理，实现移动端收银、补货、报表、蓝牙打印等功能

- 责任描述
  - 搭建小程序端客户端项目，满足产品快速开发及后期拓展
  - 参与后端业务API开发和客户端js交互流程

- 技术栈
  - 基于[tencent/wepy](https://github.com/Tencent/wepy)搭建小程序客户端，便于npm引入第三方package，加速客户端开发
  - 基于git版本控制工具，使用git flow工作流协同开发
  - 基于jenkins自动化构建测试、预发布及生产环境
  - 后端基于自建框架，通过composer引入第三方package，提供业务API支撑

##### 悦云智慧门店系统-web端
- 项目需求
  打造垂直零售行业门店管理SAAS系统，实现门店收银、会员管理、订单管理、财务对账等管理功能

- 责任描述
  - 基于现有项目拓展业务需求，实现采购补货、毛利分析等功能
  - 优化现有代码业务层及模型层，提高代码复用度

- 技术栈
  - 基于自建框架MVC架构，服务端渲染视图，实现业务处理及ajax响应
  - 服务端采用redis缓存配置数据、DB采用读写分离提高查询效率
  - 前端采用HUI、jQuery实现页面交互

##### 新版KPPW威客系统
- 项目需求
  解决旧版系统拓展耗时较长、开发成本高等问题，使用第三方主流``` Laravel ``` 框架重构系统基础核心功能。
  
- 责任描述
  - 基于`Laravel 5.1`设计新版威客系统代码结构，便于后期版本迭代;
  - 设计新版系统数据库表结构，用户模块、任务模块、认证模块、财务模块、订单模块、日志模块、IM模块、wechat公众号模块、RESTful api等模块的数据表初步设计;
  - 开发用户模块、认证模块、财务模块、订单模块、IM模块、公众号模块的功能开发，实现用户注册登录及密码找回、企业个人资质认证、第三方支付宝、微信支付，基于php_swoole扩展实现IM聊天，为众包平台提供wechat公众号营销提供解决方案，接入第三方阿里大于、云通讯等短信服务商以及开发邮件配置发送实现消息通知。
  - 开发开源系统安装引导程序，实现用户配置安装使用。
  - 开发系统升级接口，便于后期在线升级功能拓展。

- 技术栈
  - 服务端基于主流php webframework  `Laravel 5.1 LTS`版本重构旧版威客系统：
    使用内置调度功能实现任务自动结算；
    使用auth middleware实现用户认证及权限验证；
    基于easywechat实现微信公众号功能；
    使用php `swoole`扩展实现基本IM通讯功能；
    使用ominipay实现第三方支付，同时提供APP业务API支付；
    使用laravel sms接入阿里、云片等主流短信服务商实现短信推送功能；
    使用laravel 内置SMTP邮件发送实现站内事件邮件通知；
    基于laravel 迁移`migration`和填充`dbseed`结合`artisan`控制台实现系统安装及更新。
  - 客户端使用laravel blade模版结合jQuery实现页面交互，同时引入第三方theme package实现多主题切换

##### 杭州科技局海螺邦
- 项目需求
基于KPPW开源威客系统，针对自媒体、设计类、文案类等网络兼职人员打造需求服务交易平台。

- 责任描述
  - 开发用户认证系统，实现用户注册、登录及密码找回；
  - 邮件管理及发送，实现后台邮件模板可配及消息通知；
  - 第三方短信运营商接入。

- 技术栈
  - 基于自主开发MVC框架实现用户认证功能模块、拓展邮件发送及站内信功能
  - 接入第三方短信SDK实现短信，实现短信模板可配及短信推送

##### 立木项目
- 项目需求
基于KPPW开源威客系统，打造基于地理位置的同城派单接单服务众包平台。

- 责任描述
  - 负责用户认证系统开发，注册、登录及找回；
  - baidu地图接入，实现雇主定位发布任务及威客定位查找附近服务商派单流程。

- 技术栈
  - 基于自主MVC框架实现用户认证功能
  - 接入百度地图SDK，实现威客任务基于地理位置发布任务派单和威客web端查询附近任务接单

##### 点谷科技
- 项目需求
基于KPPW开源威客系统，打造同城雇主威客任务服务交易众包平台。

- 责任描述
  - 负责任务同城发布及基于地理位置进入分站派单接单业务功能;
  - 基于地理位置进行任务筛选及本地任务接单限制。

- 技术栈
  - 基于现有系统拓展同城任务功能，调用第三方IP定位服务实现同城服务

##### 旧版KPPW威客系统迭代
- 项目需求
针对系统前一版本的反馈bug进行修复，并拓展系统多主题切换功能、七牛云储存的接入以及新主题的开发。

- 责任描述
  - 修复客户反馈bug推出补丁;
  - 接入七牛云存储，实现后台可切换文件上传本地或上传云存储功能;
  - 修改现有代码结构，实现模版文件目录切换加载，实现多主题配置功能。

- 技术栈
  - 基于现有系统接入七牛云存储，实现用户上传附近云存储节省服务器空间

##### 创业武汉通
- 项目需求
基于一期项目功能进行拓展，实现众创空间的地理位置发布及公众号地理位置寻径，实现自定义问卷上线及公众号用户推送。

- 责任描述
  - 负责后台众创空间基于地理位置发布及管理功能，基于百度地图api实现;
  - 实现问卷自定义题目预览发布;
  - 开发问卷推送功能及微信端问卷数据收集功能

- 技术栈
  - 基于微信公众号SDK开发微信端众创空间平台
  - 接入百度地图服务实现地域众创空间查询导航

##### kee协同工具 
- 项目需求
为项目众包协同工作提供一套完善的管理工具，实现项目分阶段验收，为雇主提供更清晰的项目进度信息。

- 责任描述
  - 参与后端API认证功能连调

##### KEKE官网
- 项目需求
开发新版官网，新增售卖功能，提升官网形象，整合官网后台到总后台统一管理。
- 责任描述
  - 设计授权套餐及产品模型满足业务需求;
  - 开发授权套餐管理及前台购买流程;
  - 解决总后台接入官网后台管理功能，实现总后台Oauth授权认证管理。
- 技术栈
  - 实现Oauth认证，实现总后台调用官网后台资源


