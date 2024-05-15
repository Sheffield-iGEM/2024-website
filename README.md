This is the Sheffield iGEM 2024 website if anyone wants to add this to their device for windows:

- use the command
```
winget install getzola.zola
```
- then in the specific directory you want to have the git repo and use the command
```
zola init
```
- put in any details you like for the URL and make sure to say yes

- next you want to get the git repo so use the commands * not sure how repeatable the results are!!!
```
git init
git remote add origin https://github.com/Sheffield-iGEM/2024-website.git
git branch -M main
git switch main
git branch --set-upstream-to=origin/main main
git rebase
git pull
```

- this should hopefully give you an upto date version of the website locally 
- in order to make changes can use the command
```
git push
```

The URL for the website which you can find online is: https://sheffield-igem.github.io/2024-wiki/
(it is also visible on the repo)
