# Git

- Introduction to Git


After installing git config your user and email 
```bash
git config --global user.name "<YOUR_NAME>"
git config --global user.email "<GIT_EMAIL_ADDRESS>"
```

## Steps
1. `git init` (Initialize git into the folder)
2. `git add filename anotherfile.ext foldername/` (Add files to track or move changes to `staged`)
3. `git commit -m "YOUR MESSAGE"` (Committed changes to local)
4. `git log`
5. `git remote add <name> <remote-url>`
  ```bash
  git remote add origin https://github.com/zakeer/git-intro.git
  ```
6. `git remote -v` - it will return connected remote url
7. `git push -u <remote-name> <branch-name>`
  ```bash
  git push -u origin master
  ```