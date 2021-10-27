# Django

## 建立虚拟环境

新建文件夹learning_log, 下面的命令创建虚拟环境

------

learning_log$ **python -m venv 11_env**

learning_log$

------

## 安装virtualenv

如果无法安装virtualenv，并提示pip不是内部命令。**解决方法：**将安装目录下的pip.exe的路径添加到本地的**环境变量**中，然后重新运行下面的命令即可。

-----

$ pip install --user virtualenv

-----

![image-20211023202314450](C:\Users\HON\AppData\Roaming\Typora\typora-user-images\image-20211023202314450.png)

**安装过程提示有错误** ，如上图所示。

**解决方法：** 添加路径到***环境变量*** 中。

## 激活虚拟环境

Windows系统，使用命令11_env\Scripts\activate激活这个虚拟环境。

如果需要停止虚拟环境，可以执行deactivate:

------

learning_log$ deactivate

------

