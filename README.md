# Description
My personal blog need show some pictures, I try to store the pictures in this repository. 



## Useful command for me to use

### 1. Create New Folder Locally

If we create new local folder  and want to upload it into remote repository. We should cd into the local folder and type 

```bash
git init
```

This will let the local folder prepared to be a github folder. Then connect this folder to the remote folder

```bash
git remote add origin <https://gitxxxx.com/xxxxx/xxxxx.git>
```

The content in the "<>" should be replaced with your own git account link.  Then add all files

```bash
git add .
```

 add description

```bash
git commit -m "<some description here>"
```

Be careful that that `"<>"` double quotation marks are needed. Then  type 

```bash
git push -u origin master
```

When prompted to update the remote repository locally, proceed with the following command

```bash
git pull   
```

Prompt "git pull remote" and so on, continue with the following command

```bash
git pull origin master
```

If history related errors are prompted, continue with the following command

```bash
 git pull origin master --allow-unrelated-histories
```

Then you can push the local folder by typing 

```bash
git push origin master 
```



### 2. Update Changes

If the repository has been create in the remote and the local folder has push history. You can fetch changes from remote repository.

```bash
git pull
```

add new files to remote repository

```bash
git add .
git commmit -m "changes"
git push origin master
```

This is a simple version of the command. 




