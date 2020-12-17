# gitflow-demo 1.0.2

- `git flow init` - Create a new Project
- `git branch` -v - Check the avalable branch
-  echo "# gitflow-demo" >> README.md - add a file to project
- `git add` .
- `git commit` -m "first commit"
- create a git repo in github and copy the ssh link
- `git remote` add origin git@github.com:Satyakm/gitflow-demo.git
- `git remote` -v  -verify if the origin link is establised
- `git push` origin --all -push the changes to remort repo
- `git checkout` develop

## Create feature branch and merge it to devlopment branch
- `git flow feature start `<feature-id> -add a feature branch when we start the devlopment work flow.
- `git flow feature finish` feature-001 -This will auto merge the feature branch with development branch and delete the devlopment branch
- `git push` --set-upstream origin develop -push the latest changes to upstream

## Merge to master branch
- `git flow release start` 1.0.1
- `git add` .
- `git commit` -m "version added"
- `git flow release finish` '1.0.1' This will auto merge the devlopemnt branch with master branch
- `git checkout` master
- `git push` origin --all --follow-tags

https://github.com/nvie/gitflow
https://www.youtube.com/watch?v=BYrt6luynCI
