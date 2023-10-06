# How to contribute 

Here is a quick-start guide on how to contribute to the wagtail/outreachy repository. This guide is also helpful for other Wagtail repositories.

Either this is your first time using git or you need to quickly recap your previous knowledge on git, you will find this helpful.

## Steps

Take the following steps to make your contribution:

1. Fork the wagtail/outreachy repository:
    * Go to the [wagtail/outreachy repo](https://github.com/wagtail/outreachy).
    * Click the **Fork** to make your own copy of the repository. Github creates a copy at `https://github.com/<your-github-username>/wagtail-outreachy`.


2. Open your command window on your local machine.


3. Clone your forked repository, to copy the files right into your local machine. Here, we have the `outreachy` directory.

For example, 
```
mkdir waggy-tail
cd waggy-tail/
git clone https://github.com/<your-username>/wagtail-outreachy
cd wagtail-outreachy
```


4. Add the upstream repository as a git remote repository:

```
git remote add upstream https://github.com/wagtail/outreachy
git remote set-url --push upstream no_push
```


5. Check your remotes:

`git remote -v`

You should have 2 remote repositories:
    - `origin` - your own forked repo with your username
    - `upstream` - the actual wagtail/outreachy repo


6. Create a branch.  It is advisable that you name the branch based on the details of the changes made.

`git checkout -b doc-updates`

You can create a separate branch for each contribution. To do this, ensure you have made commit your current branch, checkout to `main` before creating a new branch
`git checkout main` checkout to the main branch

7. Check that you are in the right branch

`git branch`

The branch with the mark `*` is the current branch you are working on

8. Make your contribution by editing or creating new files in the directory. Add your changes using 
`git add .` or `git add <file/folder name>`

9. Save your contribution by making a commit with a commit message 
`git commit -m "this is what I did"` as an example. 

10. Push from your branch to the remote branch using `git push`

11. Once your contribution is ready for review, create a pull request **in the branch** on your **fork** on the GitHub UI. The PR is automatically sent to the upstream repo - the repo you forked from (wagtail/outreachy)

12. If you will like to update your branch with the` main` branch on the `wagtail/outreachy` repo:

`git checkout main`
`git pull https://github.com/wagtail/outreachy main`
