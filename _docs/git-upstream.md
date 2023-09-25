
# Update upstream

* for the first time add `--allow-unrelated-histories`, after test without: 
```
git checkout upmain
git merge main --allow-unrelated-histories
git push
```

# set-up

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


