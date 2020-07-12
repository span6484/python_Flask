# Day2
* reference：
<a href ="https://www.bilibili.com/video/BV1nV411k79y?p=4">1.4 flask请求与响应</a>

## 删除隐藏文件和编译bash小技巧

1. 从go里面去recent file找到位置
2. 按住shift+command+> 显示出hidden files
3. terminal 输入open .bash_profile 

## 404 error
上网时看见的404 报错是web serve没有该内容

## 整个流程
<img src="pic/day2_1.png" width = "50%" />

```py
## 在虚拟环境中的app.py
from flask import Flask

app = Flask(__name__)

# 装饰器
@app.route('/')     #路由     http://127.0.0.1:5000/ (python3 app.py)
def hello_world():      #视图函数       即mtv： view视图

    return 'Hello World!'           #打印在浏览器上


if __name__ == '__main__':
    app.run(port=8000)           # 默认端口号5000        按住control键点击run
    #app.run(port=8000)     #设置成端口号8000     --> http://127.0.0.1:8000/
    #app.run(host='0.0.0.0', port=8000)         默认本机访问，如果想外网访问，则需要加上host’0.0.0.0‘


```
run(host='ip 地址'， port=‘端口号’)， 一个端口号对应一个程序