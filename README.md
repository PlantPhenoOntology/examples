# examples
A repo just for Plant Pheno Ontology examples  

Testing Commits
Here are some simple instructions to get started with Git from the Commandline.  This assumes you have the commandline git installed on your computer.  You can put test commits into the test directory

Clone repo into named directory (Get the HTTPS address from the Repo)
```
cd {some directory one level up from where you want this directory located}
git clone https://github.com/PlantPhenoOntology/examples.git examples
```

depth = 1means fetch only the latest version of the repo -- 
this is useful when checking out the PPO repo and you want to exclude the history
```git clone --depth=1 https://github.com/PlantPhenoOntology/PPO.git PPO```

Set your email globally (must be added to git repo first)
```
git config --global user.email "your_email@example.com"
```
show me the global email
```
git config --global user.email
```

Set your email for a repo
```
cd my_repo
git config user.email "your_email@example.com"
```

get status
```
git status
```

Add to local repo just updated files (NOT any untracked files)
```
git add -u
```

commit to local repository
```
git commit -m "Some message about this particular commit"
```

push to server
```
git push
```
  
