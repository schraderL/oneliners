# oneliners

##Initiate new git.
```
echo "# oneliners" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/schraderL/oneliners.git
git push -u origin master
```
##Loop over file in bash
```bash
while read p; do
  echo "$p"
done < file
```
##Loop over column in bash
```bash
for i in $(cut -f 3 file.tsv|sed 1d); do
  echo $i
done
```

##AWK tab out
```bash
 awk -v OFS='\t'
 ```

## Display tabs as proper columns
```bash
column -t
column -t -s $'\t'
 ```
