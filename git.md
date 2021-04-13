git是由linxu开发的，用c写的
咱们先说一些Linux常见的dos命令
1.找到文件加路径，在文件资源位置输入cmd,然后回车，打开dos窗口
2.window+R: 快速打开dos窗口
3.在桌面左下角搜索框中输入cmd,然后回车，打开dos窗口

cd + 文件夹名：打开对应的文件夹，改文件夹必须在改文件下，否则系统早不到该目录
cd ../ 返回上一级
cd / 返回根路径
dir 查看当前目录下的文件
mkdir +文件名 创建一个文件夹
copy con 文件名 --> 编辑 -->ctrl+z 编辑完成
rd +文件名 软删除
rd /s+文件名 硬删除
cls  清空目录
shutdown -s -t 60 定时关机（单位s）
shutdown -r -t 60 定时重启（单位s）
shutdown -a 取消


git 操作步骤：
1. git init -->初始化git 仓库
2. git status -->查看状态的
    --红色代表工作区内容还没提交到暂存区
    --绿色代表工作区内容已经提交到暂存区，还没提交到历史区
3. git add 文件名
   -- git add . :把所有的文件(抛去删除的)从暂存区提交到历史区
   -- git add A :（包含删除的）

4. git commit -m"注释的内容"：把暂存区的内容提交到历史区

5. git log / git reflog：打印历史版本

6.git rm --cached 文件名 ： 删除暂存区的内容

git 远程仓库的配置：
 + git config --global --list:查看全局配置信息
 + git config --global user.name'github登录的姓名'
 + git config --global user.email 'github登录的邮箱'

 