<style>
body {font-family: Calibri, STXihei; line-height: 1.5em;}
a { text-decoration: none;}
p { margin: 0.5em 0;}
h1 {  border: none;}
h2 {  background-color: deepskyblue; padding: .3em;}
#项目经历 + ul > li > p:nth-child(1) {font-size: 120%}
 
</style>


<h1 style="text-align:center">张得群</h1>

手机: (+86)13070175160&emsp;&emsp;&emsp;邮箱: [dqzhangchn@gmail.com](mailto:dqzhangchn@gmail.com)&emsp;&emsp;&emsp; 博客: <https://blog.92qun.de>

## 教育背景
* **中国科学院地理科学与资源研究所&emsp;&emsp;硕士&emsp;&emsp;地图学与地理信息系统&emsp;&emsp;Top 10%&emsp;&emsp;&emsp;&emsp;**2014.09 - 2017.06

    研究方向：时空索引、分布式存储与计算

* **河南理工大学&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;本科&emsp;&emsp;地理信息系统&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Rank 1/48&nbsp;&emsp;&emsp;&emsp;&nbsp;**2010.09 - 2014.06

## 工作经历
* **武汉新视野风险管理科技有限公司&emsp;&emsp;高级研发工程师**&emsp;&emsp;&emsp;&emsp; 2018.04 - 2019.10

* **百度核心搜索部&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;机器学习研发工程师**&emsp;&emsp;&nbsp;2017.07 - 2018.03


## 项目经历

* **基于物联网及大数据的水产养殖防灾减灾系统设计与研发&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;负责人/开发&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2018.06 - 2019.06**

    使用物联网技术手段，监测养殖水体参数，结合鱼类生长状况、天气模型等数据，监控及预测短期内养殖风险，降低损失。

    个人职责：

    1. 项目**需求分析、方案调研及设计、软硬件系统架构设计、产品原型设计**；
    2. 开发物联网**上位机系统**（*Twisted*），完成 **下位机&hArr;上位机 消息解析、指令下发**, 实现数据分发、入库；
    4. 基于 *Redis* 消息中间件，打通 **后端&hArr;上位机** 通信，设计并实现下位机制任务排他锁；
    3. 基于 *Django & DRF* 开发服务后端系统，为前端提供 **REST接口**，打通下位机控制任务 **前端&hArr;后端** 部分（*Django Channels*）；
    5. 指导实习生分析天气-水质参数-养殖灾害的相关关系及建立数学模型。

    成果：

    1. 专利：一种基于物联网及大数据的水产养殖风险降低方法 (受理中）；
    2. 软著： 水产养殖保险保单管理系统、水产养殖保险风险监控业务系统、水产养殖物联网客户端系统、水产养殖物联网硬件出厂设置软件；
    3. 系统：水产养殖农户版系统、水产养殖保险公司版系统（多客户商业端，与农户联动）；
    4. 政府汇报：[中央农村工作领导小组副组长袁纯清带领工作组视察调研系统功能及应用](http://www.sohu.com/a/255487326_100165300)。


* **百度搜索热词优化&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;开发人员&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2017.08 - 2018.04**

    对百度搜索结果页、首页、WISE端搜索结果页等推荐热词进行优化，提高点击率及时效性，为大搜导流。

	个人职责：

    1. 爬取新闻站点标题，去重与合并；
    1. 优化 热点Query 排序，**提高热词时效性及点击率**；
    3. 维护升级[百度搜索风云榜](http://top.baidu.com)，对词条进行扩源、拓展出口，提高产品影响力；
    4. 配合PM完成其他产品优化升级推广, 如[百度Doodle页热词](https://m.baidu.com/s?word=今日新鲜事&from=1020853c&sa=ire_dl_gh_logo_ws)，[搜索热词阿拉丁卡片](https://m.baidu.com/from=1020853c/s?word=热点事件)。

    成果： 

    1. 搜索结果页右侧热词推荐点击率从0.6%提高至0.85%，相对提升约40%；
    2. [2017年百度沸点数据](http://top.baidu.com/2017)。


* **SendCats网站开发&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;联合创始人/前端开发&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2015.05 - 2016.07**

    创业项目，旨在大学生学习资料、经验的分享平台，并打造具有专长学生的自营销服务。

    个人职责：
    1. 前端开发（*AngularJS(v1.4) + Bootstrap*），确立了前端技术路线；
    2. 前端自动化测试（*Karma + Jasmine*）及自动部署（*Gulp*）；
    3. 文件上传/下载服务（七牛云）；
    4. Code Review、产品功能定位研讨等。


* **基于HBase的海量室内移动对象管理与分析&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;课题项目&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2016.01 - 2017.05**

	建立针对室内移动数据的**时空索引**，实现移动对象的语义轨迹查询与分析。

	个人职责:

    1. 在计算集群上**运维** *Hadoop, Hbase, Spark* 等系统环境；
    2. 设计支持语义查询的移动对象**时空索引**；
    3. 提供移动对象轨迹查询、面向语义单元的数据查询接口（Java)；
    4. 结合室内语义信息，进行**数据挖掘**，描述**用户画像**。

    成果：

    1. 硕士毕业论文；
    2. 张得群,谢传节,裴韬.基于 HBase 的面向语义单元的室内移动对象索引[J].地球信息科学学报,2017,19(3):307-316.


<!--
* HER系统数据抓取与入库 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 实习生 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2014.10 - 2015.03

    个人职责: a. 使用爬虫抓取可用数据源(Python实现); b. 设计和维护PostGIS数据库结构; c. 为业务人员提供 数据查询接口( Java 实现)。


* 基于百度地图API的河南理工大学校园地图设计与开发&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;大学生技能训练项目/小组长 &nbsp;&nbsp;&nbsp;&nbsp;2012.10 - 2013.01

    *项目介绍: 通过开放使用的网络地图API构建校园电子地图。*

    个人职责: a. 负责协调小组(6人)成员分工; b. 设计和开发系统， 服务器端采用ASP.NET开发，负责前端与地图操作相关的 JS 部分开发(基于百度地图JS­API); c. 建立和维护SQL Server数据库，使用XML格式存储线段数据。

    成果：
    1. 创业杯竞赛二等奖；
    2. 程钢,梁晓莉,张得群,蔡圣准.基于地图API的校园在线电子地图设计与实现[J].测绘工程,23(1):5-11.
-->



## 个人技能
  * 掌握常用**数据结构**和**算法**

  * 娴熟的 **Python** 开发能力，熟悉 **JupyterLab** 和相关科学运算库 *Numpy、Pandas* 等

  * 熟悉机器学习与深度学习，对 **Sci-kit、Pytorch** 等机器学习框架有一定使用经验

  * 熟练 **Python Web** 开发( Django, DRF, Channels )，一年的 **Angular + Bootstrap** 前端开发经验

  * 对 **Hadoop, HBase, Spark** 等分布式存储、MapReduce 分布式计算有良好的使用经验

  * 多年 Linux 环境下开发经验，熟练常用 **Shell** 命令，熟练掌握 **PostgreSQL**，有一定的 PostGIS 使用经验

## 实习、荣誉、其他

  * 北京市安澜尔雅科技有限公司 开发人员，负责爬虫开发、数据处理与存储 2014.10 - 2015.01

  * 河南理工大学矿山空间信息技术国家测绘地理信息局重点实验室 实习生 2012.10 - 2013.05

  * 国家励志奖学金， 一等奖学金(两次)，计算机等级考试四级数据库工程师，2012年大学生数据建模竞赛省三等奖，则泰杯测绘科技论文竞赛二等奖  2011 - 2013

  * 2015 北马， 博士合唱团， 自然资源学学会2015年会志愿者 2014 - 2015

  * 爱好：慢跑、游泳、户外 
