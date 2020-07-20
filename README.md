# hello
在上传文件到远程仓库时遇到了fatal: Could not read from remote repository. Please make sure you have the correct access rights and the repository exists.的问题：

廖老师是通过 git@github.com:michaelliao/learngit.git 关联的，如果已经用git@关联，则可以在.git目录下的config文件中，把 url = 后面的内容改为https类型的即可。
https类型的格式为：  url = https://github.com/xiexiexiekuan/hello.git
原格式为：           url = git@github.com:xiexieixekuan/hello.git
然后再上传即可，按要求输入密码登录。
