"hi"echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Fredmanzi/test.git
git push -u origin main