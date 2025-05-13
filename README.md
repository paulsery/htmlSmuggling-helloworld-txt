HTML Smuggling example 

Borrowed PoC by Sofiane Hamlaoui https://github.com/SofianeHamlaoui/Pentest-Notes/blob/master/offensive-security/defense-evasion/file-smuggling-with-html-and-javascript.md

Compile payload:
  gcc -o helloworld helloworld.c

Encode executable as base64
  base64 helloworld > payload.txt


Modified to execute script automatically


echo "# htmlSmuggling-noclick" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/paulsery/htmlSmuggling-noclick.git
git push -u origin main
# htmlSmuggling-noclick
