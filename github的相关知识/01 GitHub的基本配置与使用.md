## Github基本安装与配置
* 配置账户信息
* 配置 SSH Key
## 建立代码仓库 repository
1. 建立git仓库，也就是建立一个目录 控制台命令，cd到你的本地项目根目录下，执行git命令： git init
2. 将项目的所有文件添加到仓库中 git add . 如果要单独添加某一文件，将 点号. 替换成相应的文件名
3. 将文件提交到本地仓库 git commit -m "注释语句内容"
4. 【应可省略，待使用官网推荐的方法验证下】在github上建立对应的仓库，在建立完成页面地址栏中拷贝URL，
5. 将本地仓库关联到远端github上
	执行命令：git remote add origin https://github.com/用户名/仓库名
6. pull 一下 远程master与当前分支进行合并
	git pull origin master
	
7. 上传github远端代码库
	git push -u origin master