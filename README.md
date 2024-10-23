xp 3
git clone https://github.com/SanchitDongre1/MV1
cd MV1
git branch
git checkout -b newly
git add .
git commit -m "Improved documentation for Docker getting started"
git push origin newly
git checkout main
git merge newly 
