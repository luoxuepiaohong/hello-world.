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
 # 从 git 仓库删除文件，且该文件保留在本地工作目录中（即不让 git 继续追踪）
 git rm --cached [file]

# 重命名文件
git mv [filr_from] [file_to]

# 查看提交历史
git log
 # 显示每次提交的内容差异
 git log -p
 # 显示每次提交的简略统计信息
 git log --stat
 # 显示最近两次统计信息
 git log -2
 # 显示最近两次提交的内容差异
 git log -p -2
 # 退出 git log
 q

 # 忽略文件
  - window 环境下新建 gitignore.txt 文件
  - 在项目根目录下面按住Shift键并右键，然后选择“在此处打开命令窗口”
  - 执行命令 ren gitignore.txt .gitignore
  - 把需要忽略的文件规则保存到 .gitignore 文件
    - 忽略规则： https://git-scm.com/docs/gitignore
```
