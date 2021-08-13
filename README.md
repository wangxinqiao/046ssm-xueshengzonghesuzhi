#  046ssm学生综合素质评价系统
046ssm学生综合素质评价系统


#### 介绍
````
基于SSM的学生综合素质评价系统设计与实现，系统共分三种角色，包括管理员、教师、学生；
管理员主要功能包括：
权限中心：用户组权限控制、用户组信息管理；
系统设置：菜单管理、系统日志、成绩比例修改；
信息管理：教师信息管理、学生信息管理、课程信息管理、班级信息管理、学期信息管理、状态信息管理、用户账号管理；
教师主要功能包括：
活动管理：活动记录管理；
信息维护：个人信息修改、学生信息管理；
综合评测：综合成绩管理、学生异议处理、学生成绩分析；
成绩管理：学生成绩管理；
学生主要功能包括：
学生个人信息：个人信息修改；
信息查询：活动记录查询、成绩查询、综合成绩查询；
异议申报：学生异议申报；
````
源码获取：[ **点此获取** ](http://www.shuyue.fun/?type=productinfo&id=147)

#### 环境需要
```
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；
5.是否Maven项目: 是；查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目
6.数据库：MySql 5.7版本；
```

#### 技术栈
```
1. 后端：SSM(Spring SpringMVC MyBatis)
2. 前端：thymeleaf和layui
```

#### 使用说明
```
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
2. 将项目中db.properties配置文件中的数据库配置改为自己的配置
3. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;若为maven项目，导入成功后请执行maven clean;maven install命令，配置tomcat，然后运行；
4. 运行项目，输入localhost:8080/ 登录; 注意项目路径必须配置为/，否则会出错；
5. 管理员账号：chenxyu321  密码：123456
教师账号：113   密码：123456
学生账号：160839135  密码：123456
```

#### 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/110117_76adebd9_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/110025_32eeecba_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/110036_0b5ab652_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/110045_36872ccc_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/110055_1c4df8d0_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/110106_ac7859a8_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/110128_95978279_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/110139_56363edc_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/110149_55540ce0_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/110158_1bcf84c0_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/110207_70950100_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/110218_53dce0d5_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/110229_a213b2ad_863230.png "屏幕截图.png")
