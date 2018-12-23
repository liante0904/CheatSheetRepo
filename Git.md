# Git CheetSheetRepo

## Git install
### Brew install
[Check Brew CheetSheet]((https://github.com/liante0904/CheetSheetRepo/blob/master/Brew.md))

### Git install
``$ brew install git``

### setup PATH
``$ echo "export PATH=/usr/local/bin:$PATH" >> ~./bash_profile``  
``$ vi ~/.bash_profile``

> Copy & Paste below code
~~~
export PATH=/usr/local/bin:$PATH
~~~

### Check ver
``$ git --version``  

### Git config
``$ git config --global user.name "John Doe"``  
``$ git config --global user.email johndoe@example.com``  

### Git config check
``$ git config --list``  

## Git Command
``$ git remote add origin http://myRepoURL``  
``$ git init``  
``$ git add something.file``  
``$ git commit -m "commit message"``  
``$ git git push origin master``  
``$ git log``  





## Reference
<http://joshualog.com/MacOSX-Homebrew%EB%A5%BC-%EC%9D%B4%EC%9A%A9%ED%95%98%EC%97%AC-git-%EC%84%A4%EC%B9%98%ED%95%98%EA%B8%B0/>