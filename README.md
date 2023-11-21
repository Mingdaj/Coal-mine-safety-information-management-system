# Coal-mine-safety-information-management-system
基于 Spring Boot + Vue 的煤矿安全信息管理系统（前后端分离）

![image](https://github.com/Mingdaj/Coal-mine-safety-information-management-system/assets/130920375/036598ef-ffce-4109-8602-eb5553094473)

针对中小型煤矿安全管理模式不完善，信息化水平较低，运用软件工程开发规范，设计开发基于Spring Boot+Vue前后端分离开发的煤矿安全信息管理系统。

系统采用B/S架构，用Java语言和Spring Boot框架技术编码实现系统的各功能模块的业务处理；用Vue渐进式框架实现系统各功能模块的前端页面；用Axios实现前后端异步通信及页面的局部刷新；用MySQL数据库存储与管理系统数据；用MyBatis-Plus实现对数据库的访问。主要功能模块包括登录模块、用户信息管理模块、法规标准管理模块、新闻公告管理模块、安全考勤管理模块、井下设备管理模块、安全隐患管理模块、风险统计模块等。

为了验证系统是否可行并且有效，对其进行了测试。通过设计测试用例进行了关键模块的黑盒测试，对系统响应速度和数据处理能力进行分析和比较。结果表明，该系统能够提高煤矿安全信息管理的效率和数据的准确性，减少管理人员的工作量和时间，同时也为煤矿的安全生产管理提供了稳定可靠的信息支持。

技术栈：SpringBoot + Vue + DFA敏感词匹配算法

系统管理员用例图：

![image](https://github.com/Mingdaj/Coal-mine-safety-information-management-system/assets/130920375/7ea2d45e-0bf0-4519-8dac-64a3f028d5c1)


系统设计类图：

![image](https://github.com/Mingdaj/Coal-mine-safety-information-management-system/assets/130920375/a0ddefbf-f3fd-4191-ab2f-54bbd1ae3adf)

E-R图：

![image](https://github.com/Mingdaj/Coal-mine-safety-information-management-system/assets/130920375/953a69a2-fe7a-45bd-af31-c560762b67b3)

环境搭建：jdk8 + maven3.6.1 + mysql5.7 + node-v16.7.0

项目目录：

![image](https://github.com/Mingdaj/Coal-mine-safety-information-management-system/assets/130920375/0f1fc811-07b9-49bf-a824-67e488a98ee0)

后端部署步骤：

1. 创建colliery数据库，并执行sql脚本

2. 修改配置文件（数据库连接信息）

![image](https://github.com/Mingdaj/Coal-mine-safety-information-management-system/assets/130920375/d2abe48c-e223-48e3-9567-bd7b61428f89)

前端部署步骤：

1. 进入 煤矿安全信息管理系统\client_admin 前端目录，在文件路径中输入cmd回车将进入命令行

![image](https://github.com/Mingdaj/Coal-mine-safety-information-management-system/assets/130920375/cdeb3c10-27bc-4b7f-8852-b6cbdbb103e6)

2. npm install

3. npm run dev，即可

管理员界面：

![image](https://github.com/Mingdaj/Coal-mine-safety-information-management-system/assets/130920375/ba077748-59ca-432c-ad31-8b8e334960a5)

![image](https://github.com/Mingdaj/Coal-mine-safety-information-management-system/assets/130920375/404a974f-b877-40d3-bd44-19840c3fccf6)

普通用户界面：

![image](https://github.com/Mingdaj/Coal-mine-safety-information-management-system/assets/130920375/c5463690-d7f5-4c9c-9ce3-77349eea1d7c)

![image](https://github.com/Mingdaj/Coal-mine-safety-information-management-system/assets/130920375/62fe02d7-dfe8-48cc-b351-da8a44bcd74d)

**有偿分享，非诚勿扰.**

天下没有免费的午餐，前后端代码+部署调试搞活动，详情加QQ咨询。前10名购买半价，另外有一些学习问题也可以一起交流，买到就是赚到！

QQ：*2790810983*

助理QQ：*3539048933*
