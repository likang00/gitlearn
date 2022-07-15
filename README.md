## gitlearn 

#### git init 

```
Quick setup — if you’ve done this kind of thing before
or	
https://github.com/likang00/gitlearn.git
Get started by creating a new file or uploading an existing file. We recommend every repository include a README, LICENSE, and .gitignore.

…or create a new repository on the command line
echo "# gitlearn" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/likang00/gitlearn.git
git push -u origin main

…or push an existing repository from the command line
git remote add origin https://github.com/likang00/gitlearn.git
git branch -M main
git push -u origin main

…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
```


#### 生成SSH key

```
ssh-keygen -t rsa

Generating public/private rsa key pair.
Enter file in which to save the key (/Users/likang/.ssh/id_rsa): 
Created directory '/Users/likang/.ssh'.
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in /Users/likang/.ssh/id_rsa
Your public key has been saved in /Users/likang/.ssh/id_rsa.pub
```