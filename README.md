基于`Django-3.0.7, Adminlet-2.4.10` 构建的资产管理系统，针对服务器资产的自动数据收集、报告、接收、审批、更新和展示，搭建一个基础的面向运维的主机管理平台。

主要基于 https://www.liujiangblog.com/ 网站教程进行的复现，用于个人学习

## 简单的使用方法：

* 创建虚拟环境
* 使用pip安装第三方依赖
* 修改settings.example.py文件为settings.py
* 运行migrate命令，创建数据库和数据表
* 运行python manage.py runserver启动服务器
