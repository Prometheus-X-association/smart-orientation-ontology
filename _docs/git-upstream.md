# Update both sides

```
git checkout main 
## do git commit 
git push 
git checkout upmain
git merge main 
git push 
git checkout main 
```

# First time set-up :

* add the prometheus-x as `upstream` remote
```
git remote add upstream git@github.com:Prometheus-X-association/smart-orientation-ontology.git
```

* on github, rename the default upstream branch to upmain 

* on local : 
```
git fetch upstream
git switch -c upmain upstream/upmain
```

* for the first time push to remote: (add `--allow-unrelated-histories`): 
```
git checkout upmain
git merge main --allow-unrelated-histories
git push
```
