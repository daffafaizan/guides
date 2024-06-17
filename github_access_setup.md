## Setting Up GitHub On Your New Computer

1. Generate an SSH Key pair using `ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
`
2. Add the SSH Key to the SSH Agent
```
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa
```
3. Copy the contents of id_rsa.pub
4. Under the "Access" tab, go to "SSH and GPG" keys
5. Click "New SSH Key" and add! 
