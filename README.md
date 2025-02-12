# 基于Django+MySQL农业生产数据管理系统

本系统根据农业生产数据以及相关数据进行数据分析和可视化，主要针对农业数据

系统基于Django+MySQL，技术相对简单，适合学习。
系统集中致力于参考学习，不提供任何借用用途。下分享系统的构建说明与想法。


##### 编辑器

Visual Studio Code(https://code.visualstudio.com/下载最新版即可)

##### 前端技术

HTML+CSS

##### 后端技术

后端框架：Django==4.2.1

数据库：MySQL 8.0.15

Python版本：python 3.11.5

##### 本地运行

使用jetbrains工具Pycharm或者上述工具Vscode打开都可以

在目录文件下运行命令

```python
pip install -i requirements.txt
```

在项目终端命令行中输入

```python
python manage.py runserver 127.0.0.1:8000
```

登录页面：http://127.0.0.1:8000/login

主页：http://127.0.0.1:8000/

##### 注意

- 注意 Django 项目启动应该先切入`cd manage.py所在目录`。
- 系统中不存在后台管理员账号，可以**使用命令`python manage.py createsuperuser`创建**即可。
  启动后更改地址为127.0.0.1:8000/login/打开系统登陆页面，如图3-3所示。
 
图3-3 系统登录页面
输入用户名和密码后进入系统。
 
图3-4 项目系统主页展示
查看有效灌溉面积的可视化。
 
图3-5 有效灌溉面积可视化展示
查看近20年受灾面积的可视化。
 
图3-6 受灾面积可视化展示
查看全国各省农用化肥使用量。
 
图3-7 农用化肥使用量可视化。
