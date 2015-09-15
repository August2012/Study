1.  ssh: connect to host github.com port 22: Connection refused
`[fulinux@ubuntu learngit]$ git push -u origin master      
ssh: connect to host github.com port 22: Connection refused  
fatal: Could not read from remote repository.  
  
  
Please make sure you have the correct access rights  
and the repository exists. `

可以采用如下方法：
`[fulinux@ubuntu ~]$ vim .ssh/config  
  
Host github.com  
User fulinux@sina.com  
Hostname ssh.github.com  
PreferredAuthentications publickey  
IdentityFile ~/.ssh/id_rsa  
Port 443  `

测试：ssh -T git@github.com  
推送：git push -u origin master  