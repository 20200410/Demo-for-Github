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
- git commit -m'本次动作的理由'





##### Linux 命令

- mv #为文件或者目录改名，或者将文件或目录移入其他位置。
- **参数说明**：
    - **-b**: 当目标文件或目录存在时，在执行覆盖前，会为其创建一个备份。
    - **-i**: 如果指定移动的源目录或文件与目标的目录或文件同名，则会先询问是否覆盖旧文件，输入 y 表示直接覆盖，输入 n 表示取消该操作。
    - **-f**: 如果指定移动的源目录或文件与目标的目录或文件同名，不会询问，直接覆盖旧文件。
    - **-n**: 不要覆盖任何已存在的文件或目录。
    - **-u**：当源文件比目标文件新或者目标文件不存在时，才执行移动操作。

1. git mv #重新命名文件
2. git log #查看git的日志
3. git log --oneline ->简洁的方式呈现日志
4. git log -n2 --oneline # 查看最近2条日志
5. git log --all -graph #图形化的方式显示所有日志
6. git branch -v #查看本地有多少分支
7. git checkout -b temp # 创建新的分支temp
8. git checkout branchName #切换分支
9. pwd 查看当前路径
10. git reset --hard #清除暂存区和工作区的清理



### 本地仓库同步到Github

- git remote add github git@github.com:20200410/Demo-for-Github.git
    - git remote add 是用github替代后面的SSH协议地址

- git remote -v
    - 什么意思？

- git push github --all
    - 什么意思？

