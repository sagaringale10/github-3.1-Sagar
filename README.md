# github-3.1-Sagar
for assignment 3.1
git add                                       =Stage the all the file for commit to your local repository by the following command.
git commit -m "Create changes on README file" =Commit the file that you’ve staged in your local repository.
git push origin main                          =Push the changes in your local repository to GitHub.
git clone”                                    =is used for just downloading exactly what is currently on the remote repository and saving it in your machine's folder where that project is placed. (Only one time)
“git fetch”                                   =is the command that tells the local repository that there are changes available in the remote repository without bringing the changes into the local repository.
“git pull”                                    =downloads the changes and merges them into your current branch. (Can be multiple time if there is new changes on the branch in the repo).
“git log”                                     = for checking history of git commands
“git config"                                  = Get and set repository or global options



Create new branch on GitHub
git branch
git branch feature2                           =create new branch
git checkout feature2                         =Change to the new branch 
git checkout -b <new-branch-name>             =create new branch and change to the branch
git checkout                                  =swicth between braches or swicth to new branch



for creating the changes on local file
git add .
git commit -m “Comment of the changes”
git push --set-upstream origin <new-branch-name>
git push
