# 这是什么
这是一个用来记录大家学习情况的一个库。大家可以把目前自己正在了解的语言、正在做的事情、想要做的事情提交到这个库里面。基础相对薄弱也不用担心，也当作是记录自己的进步。

# 如何操作
这需要会使用**git**的一些功能。<br>

如果会用*Markdown*语法的话，就提交（上传）`.md`文件。<br>
如果不会的话，可以去了解一下*Markdown*语法，**非常简单**的。<br>
实在不行的话，可以提交`.txt`（文本文件）。

>以下的操作可以在自己喜欢的编辑器或IDE中完成，我个人用得比较多的是**visual studio code**

## 一、建立本地文件夹
在自己的电脑上建立一个全英文路径的文件夹。文件夹的名称可以是`Group_Project`

## 二、克隆远程仓库
1. 打开命令行程序（按下Windows + R键，然后在搜索狂内输入cmd）
2. 使用`cd`命令跳转到之前创建的文件夹中。<br>
   *X:/xx/Group_Project* 要换成自己文件夹所在的位置<br>
`cd -d X:/xx/Group_Project`
3. 使用命令将远程仓库克隆到本地<br>
`git clone https://github.com/0Night-to-Five0/MembersInfo.git`
4. 查看是否在当前文件夹内增加了一个*MembersInfo*文件夹
5. 若成功则使用cd命令进入MembersInfo文件夹<br>
   `cd ./Group_Project`

## 三、编写自己情况的文件
1. 创建自己的修改分支,把test修改为你喜欢的名字/代号<br>
   `git branch test`
2. 跳转到自己的修改分支当中<br>
   `git checkout test`
3. 创建一个编写自己信息的文件（自己的英文名.md/自己的英文名.txt)
4. 可以自由的编写自己的文件啦（*最好是能够使用 `Markdown`*）
5. 写完记得保存（一般的快捷键为Ctrl + S）
6. 提交该文件夹内所有文件到暂存区<br>
   `git add *`
7. 提交文件夹内所有文件到本地仓库<br>
   `git commit -m '里面填写你的提交日志，比如做了什么' *`

## 四、推送文件到远程仓库
1. 输入命令同步一下本地和远程仓库<br>
   `git pull https://github.com/0Night-to-Five0/MembersInfo.git`
2. 成功之后把自己的分支推送到远程仓库（test要换成自己设定的分支名）<br>
   `git push https://github.com/0Night-to-Five0/MembersInfo.git test`

## 五、等待管理员进行合并
也就是说成员提交的代码不会立刻同步到项目主干上的，需要仓库管理员进行合并。之后才会让大家的内容出现在主干上。

# 我能从中学到什么
- 慢慢熟练git的使用方法
- 初步了解使用git合作的流程
- 了解了Markdown的语法
- 对自己的现在做出计划
- 对自己的未来做出设想
- ……