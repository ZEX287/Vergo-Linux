# Vergo-Linux
## It's a test of upload makrdown file to github
### Git command for pull differnetial:
<style>
    .large-text{
        font-size: 20px;
         }
    .middle-text{
        font-size: 18px;
    }
</style>

<p class="large-text">
echo "# Vergo-Linux" >> README.md： 这行命令会将字符串 # Vergo-Linux 写入一个名为 README.md 的文件中。如果文件不存在，它会创建该文件；如果文件已经存在，它会在文件末尾追加该字符串。<br>
git init： 这行命令会在当前目录中初始化一个新的 Git 仓库。它会创建一个 .git 目录，用于存储所有的 Git 元数据和对象。

git add README.md： 这行命令会将 README.md 文件添加到暂存区（staging area）。暂存区是一个临时区域，用于保存你想要在下一次提交中包含的更改。<br>

git commit -m "first commit"： 这行命令会将暂存区中的更改提交到本地仓库，并附带提交信息 "first commit"。提交信息应该简洁明了，描述本次提交的内容。<br>
</p>
git branch -M main： 这行命令会将当前分支重命名为 main。-M 选项表示强制重命名，即使目标分支已经存在。

<p class="middle-text">
git remote add origin git@github.com:ZEX287/Vergo-Linux.git： 这行命令会将远程仓库的地址添加到本地仓库中，并命名为 origin。这样你就可以将本地仓库的更改推送到这个远程仓库。

git push -u origin main： 这行命令会将本地 main 分支的更改推送到远程仓库的 main 分支。-u 选项会将本地分支与远程分支关联起来，以便将来可以简化推送和拉取操作。

在你第一次使用 git push -u origin main 命令之后，-u 选项会将本地分支与远程分支关联起来12。这意味着你只需要在第一次推送时使用 -u 选项，以后每次同步变动到 GitHub 时，只需使用 git push 或 git pull 命令即可，无需再加 -u **选项**

push：这个命令用于将本地仓库中的更改推送到远程仓库。具体来说，它会将本地分支的提交上传到远程分支，从而使远程仓库中的代码与本地仓库保持一致。通常在你完成了一些更改并希望将这些更改分享给其他人时使用12.

git pull：这个命令用于从远程仓库获取最新的更改并将其合并到本地分支。它实际上是 git fetch 和 git merge 的组合，先从远程仓库获取最新的提交，然后将这些提交合并到当前分支。通常在你开始新的工作之前，确保你的本地仓库是最新的.

在 Git 中，git push -u origin main 命令用于将本地分支的更改推送到远程仓库的 main 分支，并设置上游（upstream）分支. 具体来说，这个命令有两个主要作用：

推送本地更改：将本地 main 分支的所有提交推送到远程仓库的 main 分支。这意味着远程仓库中的 main 分支将与本地分支保持同步.

设置上游分支：-u 选项（或 --set-upstream）会将本地分支与远程分支关联起来。这样，以后你在执行 git push 或 git pull 命令时，不需要再指定远程仓库名称和分支名称，Git 会默认使用这个关联关系12.
例如，第一次使用 git push -u origin main 后，以后你只需使用 git push 或 git pull 命令即可同步本地和远程仓库的更改，而不需要每次都指定 origin main.# Vergo-Linux
</p>