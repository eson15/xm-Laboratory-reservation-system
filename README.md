# 【原创项目】基于Springboot+Vue的实验室预约系统  
基于Springboot+Vue的【实验室预约系统】，系统代码全部原创，并提供带敲视频和笔记  
大家好，我是武哥，最近给大家手撸了一个基于Springboot+Vue的实验室预约系统，教室预约，自习室预约，机房预约等，可用于实习项目、毕业设计、课程设计等，系统全部原创，如有遇到网上抄袭站长的，欢迎联系博主~  

#### 项目在线体验地址  
体验地址：**（请电脑端浏览器访问）**：[http://111.229.67.228:84/](http://111.229.67.228:84/)  
系统管理员账号：**admin 123456**    
实验室管理员：**zhang 123456**  
学生账号：**zhangsan 123456**    
线上环境，部分基础数据不允许修改（例如系统公告、实验室相关数据、用户数据等等），可以体验实验室预约的核心业务功能。  

#### 项目技术栈  
> 前后端分离  
> 后端：Springboot2 + Mybatis  
> 前端：Vue2 + ElementUI  
> 数据库： MySQL  

#### 项目功能描述  

>**系统管理员**  
>登录、个人信息、修改密码、管理后台管理系统所有数据  
>**信息公告部分：**  
>1、**实验室分类管理**：管理员可以管理实验室分类，且不同实验室**会绑定一个实验室管理员账号**  
>2、**实验室管理**：管理员可以管理实验室信息，绑定具体的分类下面，实验室默认是空闲状态，如果有人预约会变成使用中，使用结束状态会回归到空闲。  
>3、**预约记录管理**：管理用户的预约记录，可以审核用户预约，审核通过后用户可以使用  
>4、**报修记录管理**：管理用户的报修记录，且可以**指定检修单位进行检修**  
>5、**检修记录管理**：管理所有实验室设备的检修记录  
>6、**系统公告管理**：管理平台系统公告  
>7、**管理员信息管理**：管理管理员的信息  
>8、**用户信息管理**：管理平台用户信息  
>####   
>**实验室管理员**  
>登录、个人信息、修改密码、管理自己实验室的数据  
>1、**实验室管理**：管理自己名下的实验室信息。  
>2、**预约记录管理**：审核用户预约自己管理的实验室，**用户使用结束后，可以释放实验室的状态为空闲**  
>3、**报修记录管理**：查看自己管理的实验室的报修记录信息  
>4、**检修记录管理**：查看自己实验室的检修记录  
>####   
>**学生**  
注册、登录、个人信息、修改密码、查看系统公告  
>1、**实验室查看**：查看当前所有可预约的实验室，卡片式展示  
>2、**实验室预约**：可以对空闲实验室进行预约操作，预约后，等待实验室管理员或者系统管理员审核，审核通过后可以使用  
>3、**实验室报修**：实验室使用结束后，如果实验室里有设备需要报修的话，可以给系统提交报修信息  
>4、**报修记录**：查看自己提交的报修记录  
>5、**检修记录**：查看实验室的检修记录  
>6、**班级管理**：查看班级的基本信息  
#### 创新点  
> 1、echarts统计图统计，使用柱状图和饼图统计实验室的使用和空闲状态数量  
> 2、整个过程实现一个完整的闭环，对实验室预约、报修、检修形成一套完整的闭环  
> 3、用户视角实验室预约页面进行卡片式设计，改变普通管理系统的死板  
> 4、巧妙的数据关联设计（实验室分类、实验室、实验室管理员、用户之间的多维度关联）  
#### 部分关键页面截图  
登陆页面:![请添加图片描述](https://img-blog.csdnimg.cn/direct/574cd3e20f6a47e99778ed41a3e6437a.png)
#### 管理系统页面  
系统首页：![请添加图片描述](https://img-blog.csdnimg.cn/direct/9f26cf9ea981424ea162f648a2913d1b.png)
实验室分类：![请添加图片描述](https://img-blog.csdnimg.cn/direct/5175223cd61f4fb58ac24de18a936798.png)实验室管理：![请添加图片描述](https://img-blog.csdnimg.cn/direct/48959effb63d4aa28585a783bf9de84e.png)
![请添加图片描述](https://img-blog.csdnimg.cn/direct/1aa75856d89d4f9792e905778a0788c4.png)实验室预约（学生视角）：![请添加图片描述](https://img-blog.csdnimg.cn/direct/c08c628392fa49b58f403f84345d8ba7.png)
预约记录：![请添加图片描述](https://img-blog.csdnimg.cn/direct/8b787a39478e4bd78d9295cdbf7711e6.png)报修管理：![请添加图片描述](https://img-blog.csdnimg.cn/direct/9237edd065264faa9c07a937057abd7b.png)
![请添加图片描述](https://img-blog.csdnimg.cn/direct/a1644d0a75aa4ad4a2e2aff445a1266b.png)检修记录：![请添加图片描述](https://img-blog.csdnimg.cn/direct/69c2b6e1c5c94e338c35342ecca161b1.png)用户管理：![请添加图片描述](https://img-blog.csdnimg.cn/direct/f08a47db25424df2aaae73159189c8ee.png)

资料获取方式：加入知识星球：【项目训练营】即可  
<img src="https://img-blog.csdnimg.cn/direct/44f688415c0c47cc81ad08a1f275e6a4.png" width="300px" />

**星球提供**：  

1. （**价值**）星球内部的所有实战项目均提供脚手架、详细的笔记和完整的带敲视频，可以跟着完整学习视频敲出来，学习过程中提供一对一答疑。  
2. 星球内部的实战项目会一直更新，星球成员可以学习所有项目，具体项目列表如下（长期更新）：[https://www.yuque.com/xiaqing-en2ii/skflxg/cayqu7tvpxrwt9tf](https://www.yuque.com/xiaqing-en2ii/skflxg/cayqu7tvpxrwt9tf)  
3. 星球内部会提供不同的专栏，其中除了上述实战项目外，还有学习资料，比如经典学习笔记、超全面试题等  
4. 星球内部会不定期分享学习经验，开发经验，工作经验，如果你有需要，也可以提供相应文档    
