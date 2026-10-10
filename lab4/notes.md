1 --global saves our name and email everywhere so we dont have to type it every time we make a repo if we skip it git only remembers it for that single folder

2 using -a shows hidden stuff like .git .venv and .gitignore which are hidden by default inside .git it keeps all the history and config info

3 git wanted to track a ton of files including auto generated ones in .venv and cache folders that i definitely didnt write myself

4 once we added .venv to .gitignore all those venv files completely vanished from the untracked list in git status

5 .gitignore needs to be committed so anyone else cloning the repo gets those rules too otherwise only my computer ignores those files

6 README.md moved from untracked files to changes to be committed in the 3 places model it moved from working directory to staging area with git add

7 git printed out the commit message branch name hash and stats showing 3 files changed with 36 insertions

8 the first 7 characters are called the commit hash and it acts like a unique id for that snapshot of code

9 the 4 steps of the git loop are edit files stage them git add commit them git commit and push them git push

10 README.md gets a special name and spot because github automatically looks for it to display as the main front page of the repo

11 gh auth login connects our terminal to github and saves a token so we dont have to type our password every single time we push

12 the repo front page shows the rendered README.md because github automatically picks it up to display project info

13 no running git push doesnt change our local history at all it just uploads a copy of our commits to github

14 a private repo means code is safely stored online but locked so only invited collaborators see it while a non existent repo has no online backup at all
