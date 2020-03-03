# 一本糊涂账
------
基于各种JavaSe知识的图形桌面小应用


# 目录
- [功能](#功能)
- [项目开发流程](#项目开发流程)
- [软件设计思想](#软件设计思想)
- [总结](#总结)

## 功能
- 消费一览：
- ![image](https://github.com/CoolDownnll/projects/blob/master/ImgsFolderForReadMe/1.BootStrap.PNG)
## 项目开发流程
- 表结构设计：
分析应用功能可知，消费一览来自于记一笔以及设置里的预算，记一笔中的分类来自于消费分类，月消费报表来自于记一笔，备份和恢复来自于设置里的Mysql安装目录。所以综合起来本应用设计三张表，分别为：消费记录表Record、设置表Config、消费分类表Category。
- 原型设计：
为了方便监听器获取组件，需要将面板类设置为单例的
- 实体类与DAO的设计
- 功能开发
## 软件设计思想
## 总结
