# Python Flask #
<a href = "https://dormousehole.readthedocs.io/en/latest/">FlaskDocument</a>

<a href = "https://www.youtube.com/watch?v=5fFeDagDl1A">how to install cirtualenvwrapper</a>

<a href = "https://www.bilibili.com/video/BV1nV411k79y?p=3">将虚拟环境放入一个文件夹(19:50)</a>

## 所有虚拟环境都设置在我的user里的<strong>myenv</strong>

* 需要python3版本 以及 virtualenvwrapper.sh

Terminal 找到相关路径
```bash
which virtualenvwrapper.sh
which python3.7.sh
```

若没有virtualenvwrapper.sh:
```bash
 sudo pip3 install virtualenvwrapper
 source virtualenvrapper.sh        
 mkvirtualenv safdas
 deactivate
 vi ~/.bash_profile

# Enter these
--------------------------
source virtualenvwrapper.sh

# 统一虚拟环境的文件夹
export WORKON_HOME=$HOME/myenv

# 使用python3版本
export WIRTUALEMVWRAPPER_PYTHON=/usr/local/bin/python3.7        
source /usr/local/bin/virtualenvwrapper.sh
# Enter :wq     (保存并退出)
-----------------------------

source ~/.bash_profile
```