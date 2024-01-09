HTML Smuggling example 

PoC by Sofiane Hamlaoui (offensive-security/defense-evasion/file-smuggling-with-html-and-javascript.md)

Modified to execute script automatically


echo "# htmlSmuggling-noclick" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/paulsery/htmlSmuggling-noclick.git
git push -u origin main
# htmlSmuggling-noclick
