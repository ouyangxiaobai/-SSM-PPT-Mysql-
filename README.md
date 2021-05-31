​
摘  要

 

下载地址：http://ym.maptoface.com/2021/05/31/%e5%9f%ba%e4%ba%8essm%e7%9a%84%e4%ba%ba%e6%89%8d%e6%8b%9b%e8%81%98%e7%bd%91%e7%ab%99%e7%9a%84%e7%a0%94%e7%a9%b6%e4%b8%8e%e5%ae%9e%e7%8e%b0%e6%af%95%e4%b8%9a%e8%ae%ba%e6%96%87%e4%bb%bb%e5%8a%a1/

 

本课题主要介绍人才招聘网站设计以及功能构建的实现。首先详细地叙述了人才招聘网站产生和发展的背景及意义，其次描述人才招聘网站的功能需求，整体系统结构的设计、数据库表的设计，最后完成人才招聘网站功能的实现。优点：网站整体风格简约大方，页面布局合理、网站操作方便，解决传统招聘本身地理位置限制问题、信息传递不便问题，为求职者和企业双方构建相互交流的网络平台。

本课题主要以SSM框架做为开发技术，同时采用MySQL作为后台数据库来实现人才招聘网站。其主要的功能是：普通用户投递职位信息和收藏职位信息；企业用户发布职位和查看投递者信息；管理员对普通用户和企业用户进行管理与维护。

关键词： 招聘网站； SSM； MySQL数据库；

 

Research and Realization of Recruitment Website

ABSTRACT

This topic mainly introduces the website design and the realization of the function construction. Firstly, it describes the background and significance of the emergence and development of the recruitment website. Secondly, it describes the functional requirements of the recruitment website, the design of the whole system structure, the design of the database table, and finally the realization of the function of the recruitment website. Advantages: the overall style of the site simple and generous, reasonable layout of the page, the site easy to operate, to solve the traditional recruitment of their own geographical location restrictions, the problem of inconvenience to information for job seekers and enterprises to build mutual exchange of network platform.

This topic mainly uses the SSM framework as the development technology, simultaneously uses the MySQL as the backstage database to realize the talent recruitment website. Its main function is: ordinary users to post job information and collection of job information; business users to post and view the poster information; administrators of ordinary users and business users to manage and maintain.

Keywords：Recruitment site； SSM； MySQL Database；


目   录

摘  要 i

Research and Realization of Recruitment Website ii

目   录 iii

第一章  绪  论 1

1.1 课题背景 1

1.2 国内外研究概况 1

1.3 研究意义 2

第二章 系统分析 3

2.1 系统总体分析 3

2.2 技术选择分析 5

第三章 系统设计 6

3.1 系统总体设计 6

3.2 数据库介绍 6

3.3 数据库表设计 6

3.3.1 用户信息表 7

3.3.2 企业信息表 7

3.3.3 职位表 7

3.3.4 收藏表 8

3.3.5 申请职位表 8

3.3.6 系统管理员表 8

第四章 系统实现 9

4.2 前台设计 9

4.2.1 网站首页设计 9

4.2.2 用户注册和登录模块 10

4.2.3 搜索模块 11

4.2.4 企业详细信息展示 12

4.2.5 职位投递 13

4.2.6 职位收藏 14

4.2.7 职位收藏夹 14

4.2.8 职位投递记录 14

4.2.9 职位新闻 15

4.3 后台设计 15

4.3.1 企业用户后台注册、登录 15

4.3.2 企业后台主页 17

4.3.3 企业信箱和发布职位 17

4.3.4 后台用户管理以及企业管理 18

第五章 系统测试 20

5.1 系统测试 20

5.2测试用例 20

5.2.1 登录测试 20

5.2.2 职位投递和收藏测试 20

5.2.3 个人简历修改测试 21

结束语 22

致谢 23

参考文献 24

                 

摘  要

本课题主要介绍人才招聘网站设计以及功能构建的实现。首先详细地叙述了人才招聘网站产生和发展的背景及意义，其次描述人才招聘网站的功能需求，整体系统结构的设计、数据库表的设计，最后完成人才招聘网站功能的实现。优点：网站整体风格简约大方，页面布局合理、网站操作方便，解决传统招聘本身地理位置限制问题、信息传递不便问题，为求职者和企业双方构建相互交流的网络平台。

本课题主要以SSM框架做为开发技术，同时采用MySQL作为后台数据库来实现人才招聘网站。其主要的功能是：普通用户投递职位信息和收藏职位信息；企业用户发布职位和查看投递者信息；管理员对普通用户和企业用户进行管理与维护。

关键词： 招聘网站； SSM； MySQL数据库；

 

Research and Realization of Recruitment Website

ABSTRACT

This topic mainly introduces the website design and the realization of the function construction. Firstly, it describes the background and significance of the emergence and development of the recruitment website. Secondly, it describes the functional requirements of the recruitment website, the design of the whole system structure, the design of the database table, and finally the realization of the function of the recruitment website. Advantages: the overall style of the site simple and generous, reasonable layout of the page, the site easy to operate, to solve the traditional recruitment of their own geographical location restrictions, the problem of inconvenience to information for job seekers and enterprises to build mutual exchange of network platform.

This topic mainly uses the SSM framework as the development technology, simultaneously uses the MySQL as the backstage database to realize the talent recruitment website. Its main function is: ordinary users to post job information and collection of job information; business users to post and view the poster information; administrators of ordinary users and business users to manage and maintain.

Keywords：Recruitment site； SSM； MySQL Database；


目   录

摘  要 i

Research and Realization of Recruitment Website ii

目   录 iii

第一章  绪  论 1

1.1 课题背景 1

1.2 国内外研究概况 1

1.3 研究意义 2

第二章 系统分析 3

2.1 系统总体分析 3

2.2 技术选择分析 5

第三章 系统设计 6

3.1 系统总体设计 6

3.2 数据库介绍 6

3.3 数据库表设计 6

3.3.1 用户信息表 7

3.3.2 企业信息表 7

3.3.3 职位表 7

3.3.4 收藏表 8

3.3.5 申请职位表 8

3.3.6 系统管理员表 8

第四章 系统实现 9

4.2 前台设计 9

4.2.1 网站首页设计 9

4.2.2 用户注册和登录模块 10

4.2.3 搜索模块 11

4.2.4 企业详细信息展示 12

4.2.5 职位投递 13

4.2.6 职位收藏 14

4.2.7 职位收藏夹 14

4.2.8 职位投递记录 14

4.2.9 职位新闻 15

4.3 后台设计 15

4.3.1 企业用户后台注册、登录 15

4.3.2 企业后台主页 17

4.3.3 企业信箱和发布职位 17

4.3.4 后台用户管理以及企业管理 18

第五章 系统测试 20

5.1 系统测试 20

5.2测试用例 20

5.2.1 登录测试 20

5.2.2 职位投递和收藏测试 20

5.2.3 个人简历修改测试 21

结束语 22

致谢 23

参考文献 24

转存失败重新上传取消 转存失败重新上传取消  转存失败重新上传取消 转存失败重新上传取消  转存失败重新上传取消 转存失败重新上传取消 转存失败重新上传取消 转存失败重新上传取消 转存失败重新上传取消 转存失败重新上传取消  转存失败重新上传取消  转存失败重新上传取消  转存失败重新上传取消

​
