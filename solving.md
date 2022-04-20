git fetch origin
git checkout -b add-theme origin/add-theme
git merge main

git checkout main
git merge --no-ff add-theme
git push origin main
