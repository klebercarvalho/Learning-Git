# Learning-Git
Learning Git

###### Create & Clone

Creare new respository
```sh
$ git init
```

Clone local respository
```sh
$ git git clone /path/to/repository
```

Clone remote respository
```sh
$ git clone username@host:/path/to/repository

```
###### Add & Remove

Add changes to INDEX
```sh
$ git add <filename>
```

Add all changes to INDEX
```sh
$ git add *
```

Remove/Delete
```sh
$ git rm <filename>
```

Remove files from the staging area. if unwanted files were added to the staging area, but not yet committed, then a simple reset will do the job
```sh
$ git reset HEAD file
# Or everything
$ git reset HEAD .
# Single file
$ git reset <filename>
```

###### Commit & Synchronize

Commit changes
```sh
$ git commit -m "Commit message"
```

Push changes to remote respository
```sh
$ git push origin master
$ git push -u origin master
```

Connect local repository to remote respository
```sh
$ git remote add origin <server>
```

Update local respository with remote changes
```sh
$ git remote add origin <server>
```

Get latest from Git branch
```sh
$ git pull origin <server>
```

###### Branches

Create new branchs
```sh
$ git checkout -b <branch>
# e.g.
$ git checkout -b feature_x
```

Switch to master branch
```sh
$ git checkout master
```

Delete branch
```sh
$ git branch -d <branch>
```

Push branch to remote repository
```sh
$ git push origin <branch>
```

###### Merge

Merge changes from another branch
```sh
$ git merge <branch>
```

View changes between two branches
```sh
$ git merge <branch>
```

###### Tagging

Create tag
```sh
$ git tag <tag> <commit ID)
# e.g.
$git tag 1.0.0 1b2e1d63ff
```

Get commit ID
```sh
$ git log
```

Show the working tree status
```sh
$ git status
```

###### Restore

Replace working copy with lastes form HEAD
```sh
$ git checkout --<filenames>
```
Resources

* http://rogerdudler.github.io/git-guide/
