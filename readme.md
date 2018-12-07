### git权威指南 http://www.worldhello.net/gotgit/
### git教程廖雪峰
### 官方忽略文件 https://github.com/github/gitignore
#### git pull origin master --allow-unrelated-histories
### 查看历史
* 查看具体某个文件的具体修改历史信息
git log -p filename
![git log -p filename](/img/git_log_p_file.png)
 
* 两个tag之间文件差异
git diff tag1 tag2 --stat
![两个tag之间文件差异](/img/git_diff_tag_tag.png)
* 两个分支之间文件差异
git diff branch1 branch2 --stat
![两个分支之间文件差异](/img/git_diff_branch_branch.png)

* 根据commit-id查看某个提交
git show commit-id
![根据commit-id查看某个提交](/img/git_show_commit_id.png)

* 查看某个提交的文件变化
git show commit-id filename

* 查看新增、修改、删除的文件清单
git log --name-status
* 查看ASCII 图形表示的分支合并历史
git log --oneline --graph





 



