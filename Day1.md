# Day1  虚拟环境与pycharm创建

## 虚拟环境

* 在原来的公共环境下建一个房子， 需要的工具不同，放在不同虚拟环境里，互相不影响

ex: (house4)://.../pip install pymysql

* 每新建一个app就新建一个环境, 步骤：
1. pip install virtualenv       创建虚拟环境
2. 进入scripts文件夹 输入激活  activate </br> 
   （xxx）..
3. pip install django==2.0          // django==2.0 是举例的安装django2.0版本
4. deactivate           //退出

* 常见虚拟环境命令
0. 虚拟环境名字 mkvirtualenv
1. 进入环境     workon 环境名
2. 退出         deactivate
3. 删除         rmvirtualenv   环境名
4. 列出环境     lsvirtualenv
5. 进入环境目录     cdvirtualenv    环境名

## pip3 list         

* 在pycharm create project后 用pip3 list 查看有哪些
* pip install flask==1.0    (可选择卸载原来版本， 安装所需要的)

## 结构：
### 项目结构 
    |--static
    |--templates    模板
    |--app.py       启动

### web项目
    |--mvc
    |--model    
    |--view       启动
    |--controller   
### python:
    |--mtv
    |--model    模型
    |--template    -》html
    |--view     视图      -》》  控制作业

