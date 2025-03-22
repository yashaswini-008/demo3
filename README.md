echo "# demo3" >> README.md
git init
git add README.md
git commit -n "first commit"
git branch -H main
git remote add orgin https://github.com/gptcs/demo3.git
git push -u origin main
