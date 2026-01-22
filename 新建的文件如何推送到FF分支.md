# 1) 确保在 FF 分支
git checkout FF

# 2) 查看文件状态
git status

# 3) 添加新文件到暂存区
git add "提交冲突是的处理.md"

# 4) 提交（注意用 -m 不是 -t）
git commit -m "Add 提交冲突是的处理.md"

# 5) 推送到 FF 分支
git push -u origin FF

//上面这些不行之后，可以在vscode图形化的界面上操作