
git的使用方法<br>
在刚下载安装时候需要使用基本语法来命名你的git<br>
git config --global user.name //用户名<br>
git config --global user.emaill //邮箱<br>
使用首先要初始化本地库<br>
基本语法<br>
git init //用来初始化本地库<br>
想要git使用你的电脑文件就需要初始化本地库，让git掌握文件夹库的权限<br>
创建后会出现隐藏的一个文件.git就让git本地库拿到权限<br>
查看本地库的状态基础命令git status<br>
新增文件基础命令vim hello.txt<br>
修改文件基础指令vim (文件名)<br>
yy是复制p是粘贴<br>
cat hello.txt是查看此文本内容<br>
<p color = "red">将本地仓库中东西放进预存区基础指令git add (跟你的文件名称)</p><br>
将暂存区里的文件删除进工作区git rm --cached (文件名)<br>
将文件放进暂存区还没放进本地库进行历史版本的运行<br>
提交本地库 git commit （"日志信息"） （文件名）<br>
查看版本历史信息指令git refolog<br>
查看历史版本信息更详细质令git log<br>
觉得当前代码写的不够好可以进行版本穿梭<br>
基础指令git reset --hard 版本号<br>
<img width="586" height="411" alt="QQ_1771152519993" src="https://github.com/user-attachments/assets/193c62e6-7f57-42e6-aa38-14373f2d228b" /><br>
什么是分支:在版本控制中,同时推进多个任务，为每个任务，我们可以创建每个任务的分支。使用分支意味着程序员可以把自己工作从主线分离开来，来开发自己分支时候，不会影响主线分支运行<br>
分支的操作:
<img width="596" height="200" alt="cc2b73d9d98bb3a2a165fe7336874595" src="https://github.com/user-attachments/assets/f6a57149-177e-439e-bc80-5ed843e93d49" /><br>
查看分支 git branch-v<br>
创建分支 git branch 分支名字<br>
切换分支 git checkout 分支名字<br>
合并分支需要先走到主分支上面，再去写想要合并的东西
合并分支 git merge “合并分支名字”  //合并
代码冲突：在同一文件和同一位置有了两套的不同意见修改。git无法帮我们决定用哪一个就必须人为修改
<img width="597" height="436" alt="QQ_1771159862576" src="https://github.com/user-attachments/assets/8086ed2a-2e39-4b59-be28-fe25a74c14f9" /><br>
图片后面的master|nerging的意思是二者文件正在合并中当前提交本地库不能带<文件名>因为git不知道是主分支修改文件,还是分支修改文件
文件提交后会回到master.



 









