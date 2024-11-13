### Github repo setup

On github create a new repo called `fastapp`, do not add a readme, .gitignore, or any other files.

With these options you should see

> …or create a new repository on the command line

and the commands that are like

```bash
echo "# fastapp" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/<YOUR_USER_NAME>/fastapp.git
git push -u origin main
```

`$ cd fastapp` (what fastapi_template created)

Now run only these commands to push the code up. Don't forget to replace `<YOUR_USER_NAME>`

```bash
git init
git add -A
git commit -m "config 1"
git branch -M main
git remote add origin https://github.com/<YOUR_USER_NAME>/fastapp.git
git push -u origin main
```
