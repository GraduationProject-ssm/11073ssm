# [首页查询更多项目](https://github.com/GraduationProject-ssm) 包安装运行


# 11073ssm医院挂号系统

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1Kp48e9EtU?p=115)


﻿



**　　　　


**毕业设计**



|**题    目：**|**医院挂号系统**|
| - | :-: |
|||
|**作    者：**||
|**学   号：**||
|**所属学院：**||
|**专业年级：**||
|**学校导师：**||**职  称：**||
|**班级导师：**||**职  务：**||
|**完成时间：**||

目    录

[摘  要	I](#_Toc55328682)

[**Abstract**	II](#_Toc55328683)

[第1章  前  言	3](#_Toc55328684)

[1.1  研究背景	3](#_Toc55328685)

[1.2  研究现状	3](#_Toc55328686)

[1.3  系统开发目标	3](#_Toc55328687)

[第2章  系统开发环境	5](#_Toc55328688)

[2.1 java技术	5](#_Toc55328689)

[2.2 Mysql数据库	6](#_Toc55328690)

[2.3 B/S结构	7](#_Toc55328691)

[2.4 JSP技术介绍	7](#_Toc55328691)

[2.5 ECLIPSE 开发环境	7](#_Toc55328691)

[第3章  需求分析	9](#_Toc55328693)

[3.1  需求分析	9](#_Toc55328694)

[3.2  系统可行性分析	9](#_Toc55328695)

[3.3  项目设计目标与原则	9](#_Toc55328696)

[3.4  系统流程分析	10](#_Toc55328697)

[第4章  架构设计	12](#_Toc55328698)

[4.1  系统体系结构	12](#_Toc55328699)

[4.2  数据库实体设计	13](#_Toc55328700)

[4.3  数据库表设计	15](#_Toc55328701)

[第5章  系统实现	17](#_Toc55328702)

[5.1  登陆	17](#_Toc55328703)

[5.1  管理员功能模块	17](#_Toc55328703)

[5.2  医生功能模块	19](#_Toc55328704)

[5.3 用户前后台功能模块  	19](#_Toc55328704)

[第6章  系统测试	23](#_Toc55328705)

[6.1  测试目的	23](#_Toc55328706)

[6.2  测试方法	23](#_Toc55328707)

[6.3  功能测试	24](#_Toc55328708)

[6.4  测试结论	25](#_Toc55328709)

[第7章 结  论	26](#_Toc55328710)

[参考文献	27](#_Toc55328711)

[致  谢	28](#_Toc55328712)



摘  要

在网络发展的时代，国家对人们的健康越来越重视，医院的医疗设备更加先进，医生的医术、服务水平也不断在提高，给用户带来了很大的选择余地，而且人们越来越追求更个性的需求。在这种时代背景下，医院只能以用户为导向。

本系统采用了jsp技术，将所有业务模块采用以浏览器交互的模式，选择MySQL作为系统的数据库，开发工具选择My eclipse来进行系统的设计。基本实现了系统应有的主要功能模块，本系统有管理员、医生和用户，管理员：个人中心、公告信息管理、用户管理、科室信息管理、医生管理、预约时间段管理、出诊信息管理、在线预约管理、上班打卡管理、留言板管理、系统管理，用户：个人中心、在线预约管理、我的收藏管理。医生：个人中心、出诊信息管理、在线预约管理、上班打卡管理。前台首页：首页、公告信息、科室信息、出诊信息、留言反馈、我的、跳转到后台等操作。

对系统进行测试后，改善了程序逻辑和代码。同时确保系统中所有的程序都能正常运行，所有的功能都能操作，并且该系统有很好的操作体验，实现了对于系统和医院双赢。

关键词：医院挂号系统；jsp;Mysql； 





**Abstract**

In the era of network development, the state pays more and more attention to people's health, the medical equipment of the hospital is more advanced, the medical skills and service level of doctors are also constantly improving, which brings users a lot of choice, and people are more and more pursuing more personalized needs. In this context, the hospital can only be user-oriented

This system uses JSP technology, all business modules use browser interaction mode, choose MySQL as the database of the system, development tools choose my eclipse to design the system. The system has administrator, doctor and user, administrator: personal center, announcement information management, user management, department information management, doctor management, appointment period management, visiting information management, online appointment management, clock in management, message board management, system management, user: personal center, online appointment Management, my collection management. Doctor: personal center, visiting information management, online appointment management, clock in management. Front page: front page, announcement information, department information, visiting information, message feedback, my, jump to the background and other operations.

After testing the system, the program logic and code are improved. At the same time to ensure that all the programs in the system can run normally, all the functions can be operated, and the system has a good operating experience, to achieve a win-win situation for the system and the hospital.

Key words: hospital registration system; JSP; MySQL;

**				
8


第1章  前  言

1.1  研究背景

传统的医院挂号方式是在线下实体进行的，用户需要到线下进行实际的预约挂号，而随着医院科室类型的不断普及，其性能、医药费的透明化，越来越多的医院也开始出于各种各样的理由而热衷网上发展 ，传统的线下预约模式已经无法满足人们的需求了。

互联网的产生，带来了网络的再次高速发展，人们的生活得到了翻天覆地的变化。人们可以随时随地的享受互联网带来的方便快捷，在生活工作中的方方面面的需要都能在网络上实现，比如预约挂号、线上咨询等等。也就是说网络成了人们目前最直接、最方便、最轻松的接入口。

在当今世界，互联网快速发展的现在，如何利用互联网创造更简单高效的生活，这是我们首要讨论的。需要医院挂号信息管理相关网站，一方面使得管理员可以对医院挂号的信息进行及时更新和信息化的管理，可以较为容易的获取预约挂号信息、医生信息等等。另一方面用户可以利用互联网更直观的查看预约挂号的相关信息。与传统的预约方式相比，用户预约挂号的方式更加轻松，系统的操作更加的准确，这是一种潜在趋势，或许可以有效加快医院挂号的普及情况。

1.2  研究现状

经过调查，目前现代人的生活节奏加快，生活压力也在逐渐的增加，网络的发展给人们带来的便利，随着人们的网上预约挂号不断的增加，越来越多的人们开始加入了网上预约挂号的大潮中，但是我国对于网上系统信息管理效果低下，而且出错率也很高。因此大家都在寻找一款更加专业化的系统。

随着系统的不断出现，用户需求不断增多，系统也不断的得到壮大，本系统主要根据用户、医生和管理员的实际需要，方便用户利用互联网实现对系统的了解、对比，同时让管理者可以通过这个系统对用户实际需求以及各科室信息的所有了解和预约情况进行管理。设计该系统主要目的是为了方便用户可以有一个非常好的平台体验，管理员也可以通过该系统进行更加方便的管理操作，实现了之前指定好的计划。

1.3  系统开发目标

对于网站的设计，要保证主界面的整洁有序，能够抓住人的眼球，不会产生视觉疲劳，更重要的是，带给人容易操作的直观感受，这样才能留住用户去进行使用，增加三分热度的延续期。在系统的后台设计上，要采取非常简洁有效的技术，开发方便的同时，便于以后的维护。我们不但要确保所有的功能都能够满足用户的需求，用户还要能自己主动通过网站去实现想要的操作，而管理者的简单通过网站对用户的需求情况进行了解和管理。为达到这一目的，提出以下目标：

（1）用户可以实时查看最新的医生信息，以及相关资讯；

（2）用户可以对比各医生的信息，选择自己较为满意的医生；

（3）用户可以通过系统信息进行预约挂号；

（4）管理员可以在后台方便管理后台网页的各种信息；

（5）医生可以方便查询、用户预约的状态。

第2章  系统开发环境
## 2.1 JAVA简介
Java主要采用CORBA技术和安全模型，可以在互联网应用的数据保护。它还提供了对EJB（Enterprise JavaBeans）的全面支持，java servlet API，JSP（java server pages），和XML技术。JAVA语言是一种面向对象的语言，它通过提供最基本的方法来完成指定的任务，开发者只需要知道一些概念就能够编写出一些应用程序。Java程序相对较小，其代码能够在小机器上运行。Java是一种计算机编程语言，具有封装、继承和多态性三个主要特性，广泛应用于企业Web应用程序开发和移动应用程序开发。

Java语言和一般编译器以及直译的区别在于，Java首先将源代码转换为字节码，然后将其转换为JVM的可执行文件，JVM可以在各种不同的JVM上运行。因此，实现了它的跨平台特性。虽然这使得Java在早期非常缓慢，但是随着Java的开发，它已经得到了改进。
## 2.2 MySql数据库
Mysql的语言是非结构化的，用户可以在数据上进行工作。MySQL因为其速度、可靠性和适应性而备受关注。大多数人都认为在不需要[事务](https://baike.baidu.com/item/%E4%BA%8B%E5%8A%A1)化处理的情况下，MySQL是管理内容最好的选择。并且因为Mysql的语言和结构比较简单，但是功能和存储信息量很强大，所以得到了普遍的应用。

Mysql数据库在编程过程中的作用是很广泛的，为用户进行数据查询带来了的方便。Mysql数据库的应用因其灵活性强，功能强大，所以在实现某功能时只需要一小段代码，而不像其他程序需要编写大段代码。总体来说，Mysql数据库的语言相对要简洁很多。 

数据流程分析主要就是数据存储的储藏室，它是在计算机上进行的，而不是现实中的储藏室。数据的存放是按固定格式，而不是无序的，其定义就是：长期有固定格式，可以共享的存储在计算机存储器上。数据库管理主要是数据存储、修改和增加以及数据表的建立。为了保证系统数据的正常运行，一些有能力的处理者可以进行管理而不需要专业的人来处理。数据表的建立，可以对数据表中的数据进行调整，数据的重新组合及重新构造，保证数据的安全性。介于数据库的功能强大等特点，本系统的开发主要应用了Mysql进行对数据的管理。
#########
### 2.3  B/S架构 
B/S结构的特点也非常多，例如在很多浏览器中都可以做出信号请求。并且可以适当的减轻用户的工作量，通过对客户端安装或者是配置少量的运行软件就能够逐步减少用户的工作量，这些功能的操作主要是由服务器来进行控制的，由于该软件的技术不断成熟，最主要的特点就是与浏览器相互配合为软件开发带来了极大的便利，不仅能够减少开发成本，还能够不断加强系统的软件功能，层层相互独立和展现层是该B/S结构完成相互连接的主要特性。

## 2.4 JSP技术介绍
JSP技术本身是一种脚本语言，但它的功能是十分强大的，因为它可以使用所有的JAVA类。当它与JavaBeans 类进行结合时，它可以使显示逻辑和内容分开，这就极大的方便了用户的需求。JavaBeans 可以对JSP技术的程序进行扩展，从而形成新的应用程序，而且JavaBeans的代码可以重复使用，所以就便于对程序进行维护。JavaBean 组件有内部的接口，可以帮助不同的人对系统进行访问。1999年，Sun微系统公司正式推出了JSP技术，这是一种动态技术，是基于整个JAVA体系和JavaServlet提出的，是具有普遍适用性的WEB技术，也是本系统设计的核心技术之一。JSP技术能够极大的提高WEB网页的运行速度。这些内容会与脚本结合，并且由JavaBean和Servlet组件封装。所有的脚本均在服务器端运行，JSP引擎会针对客户端所 提交的申请进行解释，然后生成脚本程序和JSP标识，然后通过HTML/XML页面将结果反馈给浏览器。因此，开发人员亲自设计最终页面的格式和HTML/XML标识时，完全可以使用JSP技术。

所以结合系统的需求及功能模块的实现，使用JSP技术是最合适的，而且JSP的拓展性比较好，对于系统在后期使用过程中可以不断对系统功能进行拓展，是系统更完成，更方便的满足用户管理。
#########
## 2.5 ECLIPSE 开发环境
ECLIPSE 支持广泛、兼容性高并且功能强大，是一个Eclipse 插件集合，普遍适应于JAVA和J2EE的系统开发，支持 JDBC，Hibernate，AJAX，Struts，Java Servlet，Spring，EJB3等市面上存在的几乎所有数据库链接工具和主流Eclipse产品 开发工具。 

ECLIPSE 在业内是所熟知的开发工具，该平台在开发的过程中运用的就是该工具。ECLIPSE 又被称之为企业级的工作平台，它是以Eclipse IDE为基础的。ECLIPSE 可以帮助我们进行数据库的研发和J2EE的使用，除此之外，还可以提高系统的运营能力，这突出表现在服务器的整合过程中。ECLIPSE 的功能相当完备，能够为J2EE的集成提供必要的环境支持，从而完成编码、测试、调试及发布等功能。它可以支持JSP，HTML，SQL，Javascript，Struts， CSS等。



第3章  需求分析

3.1  需求分析

开发系统的过程中，去调查用户的功能诉求，对需要存在的功能进行需求分析是特别重要的，且对于系统的开发有着实际的意义，设计系统通过对用户的需求进行分析，结合实际情况进行开发研究，对用户的所有需求做出一个完整的基本的框架，然后一步一步的完成、实现。需求分析可以为系统的开发提供一个目标，只有按照这个目标进行开发设计，才能进行完整的开发，这样设计出的系统才有使用的意义，才能在竞争激烈的软件市场中生存，才能真正的帮助人们解决问题，提高实际的效率。

3.2  系统可行性分析

3.2.1 技术可行性

本系统采取的是目前应用最广泛的程序进行技术的支持，主要的技术支持是java语言，他作为一个相当成熟的语言程序，在众多的软件开发中起着很大作用。而且用java语言编辑出来程序可以直接运行，不需要借助其他的翻译器进行翻译。所以在技术方面是完全可以行的。

3.2.2 经济可行性

本项目开发的初衷就是为了节约，因为系统开发的所有过程都是我自己开发的，而且在开发过程使用到的技术也都是市面上常见的容易操作的，所以不需要请专业的人士花资金来进行系统的开发，而且在项目开发的过程中我也学到了更多的知识。开发的这个软件可以在网络中进行免费的下载，对计算机的软硬件没有很高的要求，因此这个项目是非常实惠的，在经济方面是完全可性的。

3.2.3 操作可行性

操作可行性也就是系统的可用性，一个系统的操作是否容易决定着这个系统的使用度，在系统的操作方面的设计我都是采取简洁易懂的方式，操作的整个菜单界面整齐有序，所有的功能都有序的排列，不会出现重叠或者需要转换的现象，用户想要哪方面的操作都可以直接进行操作，所以该系统任何人都可以进行操作，不需要有相关专业的技术这样用户在操作起来就容易很多。

3.3  项目设计目标与原则

1、关于系统的基本要求

（1）管理员功能要求：个人中心、公告信息管理、用户管理、科室信息管理、医生管理、预约时间段管理、出诊信息管理、在线预约管理、上班打卡管理、留言板管理、系统管理

医生：个人中心、出诊信息管理、在线预约管理、上班打卡管理，

用户：个人中心、在线预约管理、我的收藏管理




等功能模块。

（2）性能：因为医院挂号管理中有很多的信息需要存储，因此对于系统的存储量有很大的要求，需要有一个强大的数据库的支持才能确保所有的信息都能安全稳定的进行存储。

（3）安全与保密要求：用户都必须注册、登录才能进入系统。

（4）环境要求：支持Windows系列、Vista系统等多种操作系统使用。

2、设计原则

本系统采用JSP技术，Mysql数据库开发，充分保证了系统稳定性、完整性。 

（1）系统响应效率：由于是系统，因此就需要系统的响应效率是非常高的，并且可以支持很多人同时进行系统的使用。

（2）界面简洁清晰：系统界面要简单有序，所有的功能一目了然。

（3）储存性高：因为是系统，所以就会在数据库要求上比较严格，信息录入的比较多，而且丰富复杂， 这就需要一个强大的数据库来存放更多的数据和保证数据的时时性。

（4）易学性：系统的设计一定要简单，使得用户使用起来非常好的顺手。

（5）稳定性需求：该系统在使用过程中必须保持稳定，不要出现卡顿、模糊等情况。

（6）稳定性：由于是系统，因此系统运行必须要十分的稳定。

3.4  系统流程分析

用户需要拥有属于自己的账号和密码，且必须正确，这样才能顺利登录到系统中。进入网站后，用户可以自行查询预约情况，在自己满意的医生的详情页面的最后，可以直接选择预约挂号操作。具体流程如下图3-2所示：

![](/md/blog.001.png)

图3-2 用户操作流程图

为了保证系统的安全性，要使用本系统对系统信息进行管理，必须先登陆到系统中。其具体登录流程图如图3-3所示：

![](/md/blog.002.png)

图3-3 系统操作流程图

第4章  架构设计

4.1  系统体系结构

系统的结构图4-1所示：

网

络

管理员

服务器和程序

用户

医生

![](/md/blog.003.png)

图4-1 系统结构

登录系统结构图，如图4-2所示：

系统

用户登录

密码正确

管理员界面

用户界面

医生界面
![](/md/blog.004.png)

图4-2 登录结构图

系统结构图，如图4-3所示：

![](/md/blog.005.png)

图4-3 系统结构图

4.2  数据库实体设计

数据库的功能就是对系统中所有的数据进行存储和管理。所有的数据可以在数据库中产时间的进行存储，方便用户的使用。而且所有的数据库中的数据也应该具有一定的共享性，任何的系统可以对一些数据进行使用，同时还应该保持一定的独立性，每一个数据库中的数据都有很强的安全性，可以被很好的存放到数据库，没有进行身份的验证是不能对这些数据进行查看和使用的。数据库的设计需要明确每一个实体之间的联系，系统的E-R图如下图所示：：

管理员实体主要存储管理信息包括用户名、密码、角色。管理员信息属性图如图4-5所示。

![](/md/blog.006.png)

图4-5 管理员信息实体属性图

1、用户信息：用户名、密码、姓名、性别、头像、联系电话、身份证实体图如图4-6所示：

![](/md/blog.007.png)

图4-6用户信息实体图

2、医生信息：医生工号、密码、医生姓名、性别、照片、职称、科室、擅长、手机实体图如图4-7所示：

![](/md/blog.008.png)

图4-7医生信息实体图

4.3  数据库表设计

当系统在运行的时候，数据库要能确保自己的独立性，想要哪部分的数据就选择相应的设置选项，对应的数据就会以表格的形式展现出来。当对这一个功能进行设置，他就会与数据库进行连接，会在对话框中弹出相应的数据源。

表4-1chuzhenxinxi

出诊信息表

|字段名称|字段意义|字段类型|字段长度|键码|能否为空|
| :-: | :-: | :-: | :-: | :-: | :-: |
|did|主键编号|int|11|主键|否|
|yishenggonghao|医生工号|char|16||否|
|yishengxingming|医生姓名|char|16||否|
|zhaopian|照片|char|16||否|
|zhicheng|职称|int|11||否|
|keshi|科室|char|2||否|
|shanzhang|擅长|char|16||否|
|chuzhenshijian|出诊时间|char|16||否|
|keyuerenshu|可约人数|char|8||否|
|guahaofei|挂号费|varchar|255||否|

表4-2  abo管理员信息表

|字段名称|字段意义|字段类型|字段长度|键码|能否为空|
| :-: | :-: | :-: | :-: | :-: | :-: |
|account|账号|char|16||否|
|password|密码|char|16||否|
|name|姓名|char|16||否|

表4-3gonggaoxinxi

公告信息表

|字段名称|字段意义|字段类型|字段长度|键码|能否为空|
| :-: | :-: | :-: | :-: | :-: | :-: |
|pid|序号|int|11|主键|否|
|gonggaobiaoti|公告标题|char|16||否|
|leixing|类型|char|32||否|
|tupian|图片|char|32||否|
|neirong|内容|char|16|外键|否|
|faburiqi|发布日期|char|16|外键|否|


表4-yisheng

医生表

|字段名称|字段意义|字段类型|字段长度|键码|能否为空|
| :-: | :-: | :-: | :-: | :-: | :-: |
|pid|序号|int|11|主键|否|
|yishenggonghao|医生工号|char|16||否|
|mima|密码|char|32||否|
|yishengxingming|医生姓名|char|32||否|
|xingbie|性别|char|16|外键|否|
|zhaopian|照片|char|16|外键|否|
|zhicheng|职称|char|16|外键|否|
|keshi|科室|char|16|外键|否|
|shanzhang|擅长|char|16|外键|否|
|shouji|手机|char|16|外键|否|








第5章  系统实现
## **5.1 登录**
管理员输入个人的账号、密码登录系统，这时候系统的数据库就会在进行查找相关的信息，如果我们输入的账号、密码不正确，数据库就会提示出错误的信息提示，同时会提示管理员重新输入自己的账号、密码，直到账号密码输入成功后，会提登录成功的信息。网站管理员登录效果图如图5-1所示：

![](/md/blog.009.png)     
图5-1登录界面
## **5.2  管理员功能模块**
### **5.2.1个人中心**
管理员对个人中心进行操作填写原密码、新密码、确认密码并进行添加、删除、修改以及查看。程序成效图如下图5-2所示:

![](/md/blog.010.png)

图5-2个人中心界面图
### **5.2.2公告信息管理**
管理员对公告信息管理进行添加公告标题、类型、图片、内容、发布日期、查看、修改以及删除等操作。程序效果图如下图5-3所示：

![](/md/blog.011.png)

图5-3公告信息管理界面
### **5.2.3用户管理**
管理员对用户管理进行添加用户名、密码、姓名、性别、头像、联系电话、身份证、删除、修改以及查看等操作。程序效果图如下图5-4所示：

![](/md/blog.012.png)

图5-4用户管理界面

### **5.2.4医生管理**
管理员对医生信息进行添加医生工号、密码、医生姓名、性别、照片、职称、科室、擅长、手机进行删除、修改以及查看等操作。程序效果图如下图5-5所示：

![](/md/blog.013.png)
#########
######### 图5-5医生信息界面图
### **5.2.5出诊信息管理**
管理员对出诊信息管理进行添加医生工号、医生姓名、照片、职称、科室、擅长、出诊时间、可约人数、挂号费删除、修改以及查看等操作。程序效果图如下图5-6所示：

![](/md/blog.014.png)
######### 图5-6出诊信息管理界面图
### **5.2.6系统理**
系统管理:管理员通过系统管理页面查看轮播图进行上传图片进行添加、删除、修改以及查看并对整个系统进行维护等操作。程序效果图如下图5-7所示：

![](/md/blog.015.png)
######### 图5-7系统管理界面图





## **5.3 医生功能模块**

### **5.3.1登陆**

医生输入个人的医生工号、密码、角色登录系统，这时候系统的数据库就会在进行查找相关的信息，如果我们输入的医生工号、密码不正确，数据库就会提示出错误的信息提示，同时会提示管理员重新输入自己的医生工号、密码，直到账号密码输入成功后，会提登录成功的信息。医生登录效果图如图5-8所示：。

![](/md/blog.016.png)

图5-8医生登陆功能界面图
### **5.3.2出诊信息管理**
医生对出诊信息管理进行查看医生工号、医生姓名、照片、职称、科室、擅长、出诊时间、可约人数、挂号费查看等操作。程序效果图如下图5-9所示：

![](/md/blog.017.png)
######### 图5-9出诊信息界面图
### **5.3.3在线预约管理**
医生对在线预约管理进行查看审核、支付等操作。程序效果图如下图5-10所示：

![](/md/blog.018.png)
######### 图5-10在线预约界面图
## **5.4用户前后台功能模块** 
5.4.1用户注册/登陆

通过页面填写用户名、密码、姓名、性别、头像、联系电话、身份证等信息，信息无误选择登陆，输入完成后选择进入医院挂号系统，如图5-11所示。

![](/md/blog.019.png)

![](/md/blog.020.png)

图5-11用户注册/登陆界面图

5.4.2前台首页

用户前台首页浏览，通过内容列表可以获取网站首页、公告信息、科室信息、出诊信息、留言反馈、我的、跳转到后台等信息操作内容，如图5-12所示。

![](/md/blog.021.png)

图5-12用户前台浏览管理界面图
## `  `**5.4.3** 个人信息
## `  `用户进入到个人信息界面，通过界面查看用户个人信息，信息如下：用户名、密码、姓名、性别、头像、联系电话、身份证等信息，可以进行添加‘修改、删除等相对应操作，如图5-13所示。
![](/md/blog.022.png)

图5-13个人信息界面图



5.4.4  出诊信息管理

用户进入到出诊信息管理界面，通过界面进行搜索医生姓名、职称、科室进行查看医生工号、医生姓名、照片、职称、科室、擅长、出诊时间、可约人数、挂号费等信息可进行预约，，如图5-14所示。

![](/md/blog.023.png)


![](/md/blog.024.png)

图5-9图5-14出诊信息界面图

5.4.5 在线预约管理
## `    `用户进入到在线预约管理界面，通过界面查看用医生工号、医生姓名、职称、科室、挂号费、时间段、就诊描述、健康码、日期用户名、姓名身份证、是否适合、审核回复、是否支付等信息，可以进行查看、修改、删除、支付、查看审核等相对应操作，如图5-15所示。
![](/md/blog.025.png)


图5-15在线预约管理界面图

## 5.5.6 我的收藏管理 
## 在收藏管理页面可以查看用户id 收藏ID 表名 收藏名称、收藏图片等等内容，并进行添加，修改，删除或查看等操作，如图5-16所示。
![](/md/blog.026.png)

图5-16我的收藏管理界面图

第6章  系统测试

6.1  测试目的

随着互联网不断的发展，目前各大领域都利用互联网进行了信息的管理，质量问题是很重要的标准，也决定着是否有更多的人使用。所以软件的质量我们必须要把关，必须要把软件做好，做到位，少出不必要的问题，这样才能有更多的用户使用，并且得到更多的推广。所以，我们在开发完系统后，需要进行大量的测试，以确保系统的稳定性和可使用性，并要确定系统的质量能否做到满足不同人的需求。这是系统在开发设计中非常重要的环节，测试的结果直接关系到系统的好坏。

集成测试：在系统测试当中会出现很多的问题，我们要及时的进行标注并且在进行测试的时候要采取自动化的测试，这样即准确又快速，而且不会出现疲劳，手动的测试很容易出现疲劳期，而且测试的结果也有时候会出错，所以在测试的时候才去自动测试时最好的测试方法。

在测试的过程中及时的发现问题，并且进行问题的解决，这样设计出的系统可以正常稳定的运行，不会出现重大的问题。我所进行的软件测试参照以下三个步骤进行测试：

(1)模块测试：对系统中的每一项都进行针对的测试，发现并找到问题。

(2)系统测试：让系统长时间进行各种情况下的运行，反馈运行期间的稳定性问题并解决。

(3)验收测试：其他测试完成后，最后检测阶段，确保软件准备就绪。

6.2  测试方法

在对系统进行测试的时候我们主要应用到两种测试的方法，通过测试我们就能找出可能存在的问题保证系统成功运行。

从软件的内部构造和具体实施是否有关系的观点来看：黑盒测试和白盒测试。

1）黑盒测试：测试系统功能，当用户进行相应的操作时，系统是否能够及时且准确的反馈数据，并执行相应功能。需要对功能以及使用方法进行详细的测试，保证所有的操作信息都能够完整的输出输入。

2）白盒测试：主要是对系统的结构进行测试，了解系统在运行过程中是否可以正常的工作。

系统的测试也会从下面几方面进行：

(1)窗体测试：例如用户登录界面，在用户名和密码输入时，需要界面窗口弹出，给予用户反馈，我对窗口的设计进行了测试，确保每一个窗口在用户进行相应操作后，能够及时的弹出。

(2)数据跟踪：进行数据跟踪，我们就能知道系统功能是否在顺利的执行当中。将数据库中的相关的信息进行调动，弹出我们需要的相对应的数据信息。同时，在追踪过程中，我们也更容易的发现系统的问题所在，便于解决问题和维护系统。

(3)综合测试：完成上述测试后，需要对系统进行由内而外的重新检测，来宏观的发现系统中存在的问题，并且及时的进行解决，系统的设计要结合实际的使用情况有针对性的进行开发，可以满足不同人的需求。

6.3  功能测试

本系统设计基本达到我理想的开发状态，在各个功能的运行方面，表现较为良好，基本满足用户的使用需求，及时矫正了较多的错误信息。总体说来，软件通过了相应的测试。

表6-1：用户登录测试表

|模块名称|测试用例|预期结果|实际结果|是否通过|
| :-: | :- | :- | :- | :- |
|登录模块|用户名：abo   密码：123  |弹出错误提示，提示密码错误|弹出错误提示，提示密码错误|通过|
|登录模块|<p>用户名：123   </p><p>密码：abo   </p>|弹出错误提示，提示用户名错误|弹出错误提示，提示用户名错误|通过|
|登录模块|<p>用户名：abo   </p><p>密码：abo   </p>|管理员登录成功|管理员登录成功|通过|

表6-2：删除出诊信息测试表

|模块名称|测试用例|预期结果|实际结果|是否通过|
| :-: | :- | :- | :- | :- |
|删除出诊信息模块|出诊信息名：最新通知  |删除成功、页面自动跳转|删除成功、页面自动跳转|通过|

表6-3：修改密码测试表

|模块名称|测试用例|预期结果|实际结果|是否通过|
| :- | :- | :- | :- | :- |
|修改密码模块|<p>原密码：666</p><p>新密码：123</p><p>确认密码：123  </p>|弹出错误提示，提示原密码错误|弹出错误提示，提示原密码错误|通过|
|修改密码模块|<p>原密码：abo   新密码：123</p><p>确认密码：333  </p>|弹出错误提示，提示确认密码不一致|弹出错误提示，提示确认密码不一致|通过|
|修改密码模块|<p>原密码：abo   新密码：123</p><p>确认密码：123  </p>|密码修改成功|密码修改成功|通过|

6.4  测试结论

测试的过程要按照指定好的计划一步一步的实行，测试时候一定不要着急，并且将测试的结果进行详细的记录，我们在进行测试的时候做好选择自动化的测试，这样更加的准确也更快捷，如果采用人工测试的方法就不会这么的方便，很可能会出现一些问题，而且极其测试不会疲劳也不会出现问题。在测试的时候一定要非常专注，时刻关注着测试的结果，一旦发现异常及时进行修改，；最后，测试完之后的文档应该保存下来，方便以后测试时用到。

通过测试，我们也可以直观的感受到，在我们最开始进行系统设计的时候，先把思路理清楚，才能有机会把代码写好。有好的逻辑性的代码在后期的测试中才能避免出现问题，也可以给我们节省很多的时间和不必要的操作。

第7章 结  论

` `系统为用户提供了公平的、相互包容的、操作方便的使用系统，基本满足了用户的使用需要，以及我最初的开发目标和方向。Java语言、MySQL数据库等技术时是我开发的基础，这些技术都有各自的优点，学好这些技术，至关重要。通过这些优点设计出来的系统能够正常稳定的运行，并且可以满足人们的所有需求，在对系统的需求以及各个模块进行了详细的分析后，有针对性的进行设计，最后通过测试，系统能够正常的运行，该系统设计完成。

本次开发过程中使用的是Java技术，该技术具有代码编写简单方便，对平台没有要求对技术方面也没有要求，并且有很好的面像对象性，所以在技术方面是相当成熟的。利用java技术作为系统主要的技术支持可以使得系统能够正常的运行并且实现相应的功能。在这次的系统的设计过程中遇到了很多的困难，幸好有老师同学们的帮助，在他们的帮助下完成了这次系统的设计。

通过这次系统的开发，我参考了很多相关系统的例子，取长补短，吸取了其他系统的长处，逐步对该系统进行了完善，但是该系统还是有很多的不足之处，有待以后进一步学习。

实践证明，系统有着非常好的发展前景，经过测试运行，系统各项功能都十分完善，界面漂亮，使用方便，操作容易，在技术理论上已经成熟。
#########
参考文献

[1] 贝伊利 (Lynn Beighley),莫里森 (Michael Morrison),苏金国, 徐阳. Head First Java & MySQL(中文版)[M]. 中国电力出版社,2018,03.

[2] 潘凯华,刘中华, 等. Java开发实战1200例(第1卷)(附DVD-ROM光盘1张)[M].  清华大学出版社,2019,01.

[3] 帕蒂拉(Armando Padilla),霍金斯(Tim Hawkins),盛海艳,刘霞. 高性能Java应用开发[M]. 人们邮电出版社,2019,11.

[4] 陈益材,等. Java+MySQL+Dreamweaver动态网站建设从入门到精通(附多媒体语音教学光盘)[M]. 机械工业出版社,2019,06.

[5] 高洛峰,LAMP兄弟连. 细说Java(精要版)(附DVD光盘1张)[M]. 电子工业出版社,2018,06.

[6] Lorna Mitchell,等. Java精粹:编写高效Java代码[M]. 机械工业出版社,2018,10.

[7] 列旭松,陈文. Java核心技术与最佳实践[M]. 机械工业出版社,2018,07.

[8] Symfon,CakeJava,Zend Bartosz Porebski,Karol Przystalski,Leszek Nowak, 付勇. Java框架高级编程:应用[M]. 清华大学出版社,2017,02.

[9] 波诺赛克 (Boroncxyk.T.),Elizabeth Naramore,薛焱. Web开发入门经典:使用Java6、Apache和MySQL[M]. 清华大学出版社 ,2017,07.

[10] 辛洪郁,张鑫. Java项目开发全程实录(第3版)[M]. 清华大学出版社,2018,11.

[11] 杨宇,等. Java典型模块与项目实战大全(附DVD-ROM光盘1张)[M]. 清华大学出版社,2018,01.

[12] 贾素来．常见动态网页技术比较[J]．大众科技，2018,9.

[13] 西尔伯沙茨(Silberschatz.A.) . 计算机科学丛书：数据库系统概念(原书第6版)[M]. 机械工业出版社,2019,03．.                                                      

[14]萨师煊，王珊．数据库系统概论[M]．北京:高等教育出版社，2018：10-180．

[15]陈刚．Eclipse从入门到精通[M]．(第2版)．北京:清华大学出版社，2018：17-380． 

[16]孙卫琴．精通Struts:基于MVC的Java Web设计与开发[M]．北京:电子工业出版社，2017：19-421



致  谢

光阴似箭，一晃大学生活即将过去了。一直以严谨的态度和积极的热情投身于学习和工作中，虽然有竞争，也有泪水，但是通过我不断学习和奋斗不断的完善自己，不仅很好的完成了我的学业而且也让我的各方面得到了发展，取得了很大的进步。

大学的生活也即将结束，虽然也有许多的不舍，但是终究是要告别的。回想大学的学习生活，有泪水也有汗水。在此期间我严格要求自己，凭着对知识的强烈追求，刻苦钻研，勤奋好学，态度端正，目标明确，牢固的掌握了一些专业知识和技能，做到了理论联系实际。除了专业知识的学习外，我还不断的扩展我的知识面，从不同的领域以不同的方式来获得新的知识。争取成为一名各方面都很合格的大学生。

这次的毕业设计，是我独自完成周期最长，也是耗力最大的一个项目。值得庆幸的是，在我毕业设计完成的过程当中，有许多帮助我的同学和老师。在几个月的开发过程中，我遇到了大大小小无数个问题。是我的舍友和老师，不断地帮助鼓励。

我的指导老师，在自身工作十分繁忙的情况下，依然能做到及时恢复我们发去的问题邮件，并抽时间对我们进行线下的辅导。指出我们设计上的失误，逻辑错误以及学习规划问题，可以说没有导师的帮助，我的毕设会陷入死胡同，是导师为我指点了迷津，像迷雾中的路灯，为我指明方向！


41
![](/md/blog.027.png)










