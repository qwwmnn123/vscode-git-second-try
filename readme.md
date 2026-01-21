…or create a new repository on the command line
echo "# vscode-git-second-try" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:qwwmnn123/vscode-git-second-try.git
git push -u origin main


…or push an existing repository from the command line
git remote add origin git@github.com:qwwmnn123/vscode-git-second-try.git
git branch -M main
git push -u origin main