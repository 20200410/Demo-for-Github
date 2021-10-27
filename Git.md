## Git 常用命令

### 配置user信息

**配置 user.name和user.email**

$ git config --global user.name 'your_name'

$git config --global user.email 'your_email@domain.com'

缺省等同于local

#### 三个作用域

$git config --local  <- local只对某个仓库有效

$git config --global <-global对当前用户仓库有效

$git config --system <-system对系统所有登录的用户有效

### 显示config的配置，加 --list

$git config --list --local

$git config --list --global

$git config --list --system

### 建Git仓库

1. 将已有项目代码纳入Git管理

    $cd 项目代码所在的文件夹

    $git init

2. 新建的项目直接用Git管理

    $cd 某个文件夹

    $git init your_project  #会在当前路径下创建和项目名称同名的文件夹

    $cd your_project

### 往仓库里添加文件

- git add files -- 添加工作目录到**暂存区**
- git commit -- 暂存区到git版本历史



1. git mv ->重新命名文件
2. git log -> 查看git的日志
3. git log--oneline ->简洁的方式呈现日志
4. pwd 查看当前路径

