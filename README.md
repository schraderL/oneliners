# oneliners

**Initiate new git.**
```
echo "# oneliners" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/schraderL/oneliners.git
git push -u origin master
```
**Loop over file in bash**
```
while read p; do
  echo "$p"
done < file
```
