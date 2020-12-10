# Task 17.2.7 npm

git init  
git remote add origin git@github.com:DevOps-SKF/t170207-npm.git  
git add README.md  
git commit -m "initial commit"  
git branch -M master  
git push -u origin master  

npm init  
cerate inde.js  
npm i jquery  
create .gitignore with node_modules/  
git add .  

git commit -m "v1.0.0"  
git push  

### 10.12.20202  
git config --global user.signingkey 537A8503  
git config --global commit.gpgSign true  
git config --global tag.gpgSign true  
git config --global gpg.program "C:\Prog\GnuPG\bin\gpg.exe"  

and new commit to check the GPG signature  
git commit -a -m "Signed commit"  
