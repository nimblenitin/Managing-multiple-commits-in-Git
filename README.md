# Managing-multiple-commits-in-Git

Steps-

```

1. Create a local git repo with file index.html and push it to a remote repository on Github.
$ vi index.html
$ git init
$ git add .
$ git commit -m "First commit"
$ git remote add origin <URL>
$ git push -u origin main

2. Edit the file on the remote repository. Add the following line of code in the index.html file: 
H2 { color: red; font-size: 150%} <!-- added at remote -->

3. Fetch the changes from remote repository
$ git fetch
$ git rebase origin/main

4. Check the logs for all the commits history
$ git log --oneline

```



