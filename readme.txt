建立Git仓库两步：
1.使用Git add <file>命令，告诉Git将文件加入仓库
2.使用Git commit -m <message>，提交文件到仓库中，message是对文件改动的说明。

版本回退：
1.使用git log命令查看以往版本
2.使用git reset --hard HEAD^<numbers of version to back>回到n个版本前
3.使用git reflog记录每一次命令例如commit id，以便回到最新版本