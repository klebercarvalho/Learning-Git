# Learning-Git
Learning Git


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
