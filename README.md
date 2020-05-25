## git 命令

```bash
# 在现有的项目中初始化仓库
git init 

# 克隆仓库
git clone [url]

# 检查当前文件状态
git status
 # 简写
 git status -s

# 跟踪新文件
git add [file]

# 查看修改文件
 # 查看尚未暂存的文件更新了哪些部分
 git diff
 # 查看已经暂存起来的文件(staged)和上次提交时的快照之间(HEAD)的差异
 git diff --cached
 git diff --staged

# 提交更新
git commit
 # 提交更新时添加描述
 git commit -m "提交内容"
 # 跳过 git add 直接提交
 git commit -a -m "提交内容"

# 推送
git push

# 删除文件
git rm [file]

# 重命名文件
git mv [filr_from] [file_to]