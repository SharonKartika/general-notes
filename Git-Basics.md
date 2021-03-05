# Git basics

The following clones a github repo into a directory. 

```bash
git clone git@github.com:USER-NAME/REPOSITORY-NAME.git
#or
git clone https://github.com/user-name/repository-name.git
```

```bash
git add .
git commit -m "the commit message"
git push origin main
```

```bash
git status
git log
```

### Github repo from a local git repo

1. Go to github and create a new repo with the same name as the local repo. Copy the clone link of the new repo.

2. Move to the local repo (make sure it is initialised), open terminal and type, 

   ```bash
   git remote add origin <git clone link>
   ```

All set!