# github-3.1-pohleng
## _Assignment for 3.1-introduction-to-git-i_

> ✨You have learned on how to create new repository and create the changes on it. For the assignment, create new repository named "github-3.1-your-name" or other professional naming that you want.
> Update the Readme file to contain all github command you have learned and explain what are the usage of them.
> Create your ReadMe.md file as professional and beautifull as possible. (https://dillinger.io/)
> Push the changes you made to your repository.✨

## git add, git commit, git push

git add .
 - Stage the all the file for commit to your local repository by the following command.

git commit -m "Create changes on README file"
 - Commit the file that you’ve staged in your local repository.

git push origin main
 - Push the changes in your local repository to GitHub.

## Create new branch on GitHub
```
create new branch => git branch feature2
Change to the new branch => git checkout feature2
create new branch and change to the branch => git checkout -b <new-branch-name>
create the changes on local file
git add .
git commit -m “Comment of the changes”
git push --set-upstream origin <new-branch-name>
git push
```


