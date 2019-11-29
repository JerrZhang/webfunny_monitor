   #### 健康提醒
   
   最近，高以翔突然离世消息沸沸扬扬，也想起身边有这样的突然离开的同事，不由得感慨生命之脆弱。
   
   最近发现有些小伙伴在凌晨1-5点访问我的网站，还有私信我的，我对你们的学习精神表示尊重，但是生命诚可贵，当你们看到这条提醒的时候，如果已经很晚了，希望你们关上电脑，好好睡一觉。这比什么都重要。
   
   
   ### 前言
   怎样定位前端线上问题，一直以来，都是很头疼的问题，因为它发生于用户的一系列操作之后。错误的原因可能源于机型，网络环境，复杂的操作行为等等，在我们想要去解决的时候很难复现出来，自然也就无法解决。 当然，这些问题并非不能克服，让我们来一起看看如何去监控并定位线上的问题吧。
   
   开发了这么久，也是颇有一番感慨。 一叹，前辈高人技艺之精湛；二叹，开源世界心胸之广阔；正是有这些无私奉献的大牛们，才让这技术的世界多姿多彩。
   
   
   
[【**📚 部署教程 📚**】](./Document.md) 一键部署，欢迎尝试。
   
   

---------------------------------------------------------

具体效果：[请移步线上监控系统](http://www.webfunny.cn/webfunny_multi/home.html)

### 主体功能
1. 监控JS报错、http接口报错、静态资源加载报错等；记录页面访问、点击事件、接口请求等行为日志；

2. 统计PV/UV数据、用户7天留存数据、版本号/机型/地域分布数据

3. 提供报错具体查找和定位功能、用户详细行为追踪与分析功能、用户网络环境评估功能

4. 提供额外上报接口，上报自定义日志


### 目录结构
         ./A-monitor-code/webmonitor.js   探针代码
         ./schema  数据库建表结构
         ./views/ 前端展示代码
         ./config  数据库配置目录
         ./logs  运行报错日志目录
         ./config.js 自动化配置文件

更新计划：[更新排期计划表](https://github.com/a597873885/webfunny_monitor/blob/master/UpdateList.md)

### 开源说明
本项目是开源的，除了部分属于业务代码，不便开源，但是并不影响对项目本身（原理）的理解，也不会影响你的部署。
带来不便，请予以理解和见谅。

### 贡献者支持
一颗star, 一份[关注](https://www.toutiao.com/c/user/105123468724/#mid=1651276811334670), 都将是我前进的动力  :)


![首页简介](https://github.com/a597873885/image_list/blob/master/home.gif)
