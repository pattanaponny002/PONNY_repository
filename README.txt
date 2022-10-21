

echo "# test_repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/pattanaponny002/test_repo.git
git push -u origin main

git remote add origin https://github.com/pattanaponny002/test_repo.git
git branch -M main
git push -u origin main
