# create_repo_steps
a cheetsheet to create a repo with commands

1. create an online repo
2. create a local directory
3. in the directory, ```git init```
4. ```git remote add origin <link copy from ssh>```
5. ```git pull origin master --rebase```
6. ```git branch --set-upstream-to=origin/master master```


alternative approach:

1. create an online repo
2. ```git clone <link copy from ssh>```

# how to push

1. do coding as usual
2. ```git status``` (the step is not required)
3. ```git add .```
4. ```git commit -m "<commit message>"```
5. ```git push ```
