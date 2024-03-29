@[TOC](多媒体播放器)

# 一、引言


 《音乐播放器APP说明书》是为音乐播放器APP的设计而编写的文档。为此我们对现在的音乐播放器以及大家对音乐播放器的需求进行了全面以及认真的调查。编写说明书，是为了说明本项目的详细需求、进度安排、组织项目开发并测试等信息，而项目功能、项目性能要求、数据描述等要求则会详细分析，以作为项目开发工作的基础和依据以及确认测试和验收的依据。
## 分工
 | | 名字|工作  
-------- | -----|------|
组长  | 马心如|需求分析|
组员  | 齐童|需求分析、git搭建|
|  | 廖凯茵|报告需求分析 |
|  | 廖妤芳|需求分析|
|  | 黄婉玲|需求分析|
|  | 雷书梦|需求分析PPT制作|
# 二、总体描述

## 项目背景
音乐的魅力在生活中是极大的，不同的国家、不同语言的人，可以从音乐中体会到相同的情感，可以加强人与人之间的联系，它也可以让身体放轻松，纾解压力。为了使人们能够通过手机等设备在任何时候都欣赏到音乐，因此我们希望能设计出一个基于Android系统的音乐播放器APP。

## 项目目标
本项目的目的是开发一个可以播放主流的音乐文本格式的播放器。设计的主要功能是播放MP3格式的音乐文件，并且能控制播放，暂停，停止，音量控制，选择上一曲，选择下一曲，更改皮肤，歌曲列表文件的管理操作，在线播放，读取存储卡播放等多种播放控制，界面简洁明了，操作简单清晰。软件系统检测到错误行为时，报告错误，并提示处理操作。
##  典型用户场景及需求
### 情景一
#### 背景
典型用户:某大学本科生李华 男 20岁
#### 典型用户的需求/迫切需要解决的问题
a.	李华想要对自己收藏或是播放的歌单分类
b.	李华很喜欢某歌手/歌曲，想要搜索该歌手/歌曲
c.	李华喜欢边听歌边唱歌，但经常忘记歌词
d.	李华想要将整个界面调整为自己喜欢的风格
#### 假设
a.	首页已经完成;
b.	播放界面已经完成;
c.	首页左侧导航已经完成;
d.	歌单详情界面已经完成;
e.	通知栏界面已经完成
f.	搜索界面已经完成
g.	李华有条件和能力使用该平台.
#### 场景
李华可以在播放界面或是歌单详情界面，选择收藏/取消收藏、添加到歌单/从歌单中移除等功能，并且查看歌单详情、在首页中查看我的收藏，以及所创建的歌单；
李华能够在搜索栏中选择从全部歌曲中搜素货值从特定歌曲搜索自己喜欢的歌手/歌曲；
李华可以通过播放界面，查看歌词，歌词滚动的设置还能使李华得知歌曲播放到哪，同时还能切换播放模式、选择上/下首切换、播放/暂停。
李华能够通过设置，更改界面的风格以及可以改变颜色模式。
### 情景二
#### 背景
典型用户:上班族思琪 女 30岁
#### 典型用户的需求/迫切需要解决的问题
a.	思琪会定期回顾自己近期最常听的歌曲
b.	思琪想要建立每段时间自己最常听的歌曲的歌单
c.	思琪想要把用户界面调整为夜间模式
#### 假设
a.	首页已经完成;
b.	播放界面已经完成;
c.	首页左侧导航已经完成;
d.	界面颜色模式已经完成;
e.	历史最多播放功能已经完成;
f.	歌单详情界面已经完成;
g.	思琪有条件和能力使用该平台.
#### 场景
思琪能够在使用APP时透过设置，将界面调整为夜间模式；思琪可以将历史最多播放清单中的歌曲添加到新创建的歌单，并且查看歌单详情；思琪可以在首页中看到已创建的歌单。
## 运行环境
Android 手机/平板基于Windows操作系统
# 三、假定和约束
1）开发时限的约束：由2019年10月到12月约两个月的时间完成。
2）人员限制：在小组6人的合作以及老师的指导下共同完成。
3）数据安全性和稳定性的约束：所有信息保存在主服务器的数据库中，能够防止信息被窃取和篡改。
4）系统稳定性的约束：系统能够长时间稳定运行。
# 四、类图
![类图](https://img-blog.csdnimg.cn/20191122205821459.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80Mzc4NDg0OA==,size_16,color_FFFFFF,t_70)
# 五、界面原型设计
界面结构如下：
![界面结构](https://img-blog.csdnimg.cn/20191122205908389.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80Mzc4NDg0OA==,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20191122210021505.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80Mzc4NDg0OA==,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20191122210040356.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80Mzc4NDg0OA==,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20191122210046936.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80Mzc4NDg0OA==,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20191122210105644.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80Mzc4NDg0OA==,size_16,color_FFFFFF,t_70)
# 六、功能描述
应用首页
历史最多播放：播放次数最多10首歌曲
主歌曲：所有歌曲、最近播放、我的收藏
创建的歌单：新建/编辑歌单、删除歌单
底部播放导航：播放/暂停、播放列表操作

搜索：全部歌曲中搜索/特定歌曲中搜索

播放界面
基本播放控制：播放进度调整、播放/暂停、上/下首切换
歌曲操作：收藏/取消收藏、查看歌曲详情、添加至播放列表、删除歌曲
播放列表操作：播放模式调整、定位歌曲、移除歌曲

首页左侧导航
定时停止播放
播放界面风格：遮罩、渐变、虚化
主题色定制：标题栏颜色、图标颜色
颜色模式：白天、夜间
用户指南
设置
退出

歌单详情界面
删除歌曲：添加到歌单/从歌单中移除
收藏/取消收藏：查看歌曲详情
播放所有歌曲：编辑歌单信息
# 七、系统功能描述验收标准
1. 按钮
	除首页外的每个界面均有一个返回上级界面按钮，以及搜索按钮。
2. 首页界面
    首页提供三个按钮：“历史最多播放”、“主歌单”、“创建的歌单”，点击相应的按钮可以跳转对应的界面，同时在首页底部提供播放导航，能够选择播放/暂停歌曲，以及播放列表的操作，例如播放模式调整和定位歌曲等。
3. 历史最多播放界面
显示播放次数最多的10次歌曲
4. 主歌单界面
显示所有歌曲，最近播放，我的收藏

5. 创建歌单界面
能够新建/创建歌单，或是删除歌单
6. 播放界面
显示正在播放的歌曲，歌曲播放进度以及歌词，能够进行基本播放控制，例如播放进度调整、播放/暂停、上/下曲切换；歌曲操作，如收藏/取消收藏、查看歌曲详情、添加至播放列表、删除歌曲；播放列表操作，如播放模式调整、定位歌曲、移除歌曲。
7. 首页左侧导航
首页左侧导航提供界面风格以及颜色等的设置按钮，例如定时停止播放功能、播放界面风格、主题色定制、颜色模式、用户指南、设置、退出。
8. 歌单详情界面
歌单详情界面提供“收藏/取消收藏”、“删除歌曲”、“播放所有歌曲”三个按钮，可从“删除歌曲”按钮中选择添加到歌单/从歌单中移除，或是“收藏/取消收藏”按钮中查看歌曲详情，“播放所有歌曲”按钮中编辑歌单信息。
9. 通知栏界面
显示正在播放歌曲，可选择播放/暂停、收藏/取消收藏、上/下首切换功能。
10. 搜索界面
搜索歌曲时可选择在全部歌曲中搜索或是特定歌曲中搜索。

