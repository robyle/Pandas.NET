# 环境安装

## Windows10安装pip

pip是一个很方便的python包管理工具，这里简短记录一下win10安装pip的过程。准备工作：

1、python环境

2、pip安装文件，官网网址：<https://pypi.org/project/pip/#files>

可以看到有一个.py文件，待会儿直接运行这个文件即可。win+r 运行cmd，进入这个.py文件的目录下，运行：

python setup.py install

等待安装完成，接下来要为pip添加环境变量，我这里python环境是anaconda配置的，所以pip安装到了anaconda的scripts目录下（各位这步要根据自己的安装路径来配置）。

pip就安装完成了，进入cmd在任意位置输入

pip list

检验是否成功安装