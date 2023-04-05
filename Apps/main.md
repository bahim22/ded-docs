# Main docs

```sh
# If you have a local clone, you can update it by running the following commands.
git branch -m dev prod
git fetch origin
git branch -u origin/prod prod
git remote set-head origin -a

# create new repo
echo "# ded-docs" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M dev
git remote add origin git@github.com:bahim22/ded-docs.git
git push -u origin dev
```
