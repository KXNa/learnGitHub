Git is a version control system.
Git is free software.
Git is a distributed version control system.
Git is free software.


ssh-keygen -t rsa -C "350054244@qq.com"

证书
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/Nana/.ssh/id_rsa):
Created directory '/c/Users/Nana/.ssh'.
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/Nana/.ssh/id_rsa.
Your public key has been saved in /c/Users/Nana/.ssh/id_rsa.pub.
The key fingerprint is:
SHA256:A5UWUTkRVv8wsocVt0Vs8A9OOs3EgqWxdOt8gUh7szg 350054244@qq.com
The key's randomart image is:
+---[RSA 3072]----+
|        +=O=+ o++|
|       .o+oX = +=|
|      ..  *.B @o.|
|       .   = / *.|
|        S E O * o|
|         . . +   |
|                 |
|                 |
|                 |
+----[SHA256]-----+



Creating a new branch is quick.

查看分支：git branch

创建分支：git branch <name>

切换分支：git checkout <name>

创建+切换分支：git checkout -b <name>

合并某分支到当前分支：git merge <name>

删除分支：git branch -d <name>