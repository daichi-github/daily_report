## code
- mkdir git_pr
- git switch -c main
- git add .
- git commit  
On branch main  
Initial commit  
nothing to commit (create/copy files and use "git add" to track)  
- git switch -c sub
- git switch main  
  fatal: invalid reference: main
- git push -v origin main  
Pushing to https://github.com/daichi-github/git_pr.git  
error: src refspec main does not match any  
error: failed to push some refs to 'https://github.com/daichi-github/git_pr.git'  
- git remote add origin https://github.com/daichi-github/git_pr.git  
error: remote origin already exists.  
error: remote origin already exists.  
zsh: command not found: error:  

## まとめ
- branchを作成しても、保存されない。  
他のbranchに移動すれば、もともといたbranchがなくなる？
- pushしても、main branchが存在しないのかうまくできない。  
