# Learning Git and GitHub (Adapted from freeCodeCamp.com)
Git is a version control system. It is use to track changes of code. 

## Important Terminology
Directory: Folder\
Terminal or Command Line: Interface for Text Commands\
CLI: Command Line Interface\
Code Editor: Word Processor for Writing Code\
Repository: Project, or the folder where your project is kept in\
GitHub: A website to host git repositories online

## Git Commands 
git clone -> Bring a repository that is hosted somewhere like GitHub into a folder on your local machine\
git add -> track your files and changes in Git\
git commit -m [message] -m [description] -> save your files in Git\
git push origin master -> upload Git commits to a remote repository like GitHub\
git pull origin master -> download changes from a remote repository to your local machine, the opposite of push\
git status -> the status of the repository: any untracked files or modified files\
git init -> initialize Git on your folder\
git remote add origin [link] -> connecting your folder on your local machine to a repository on GitHub\
git remote -v -> list out all remote repositories connected to your folder\
git branch -> list all the branches (* representing the current branch)\
git checkout -b [name of the branch] -> create a new branch\
git checkout [name of the branch] -> switch branch\
git diff [name of the branch] -> show the differences\
git merge [name of the branch] -> merging the branches\
git commit -am [message] -> adding and commiting modified file (doesn't work on newly created file)\
git reset -> undoing staging\
git reset HEAD~1 -> undoing git commit\
git log -> log of all commits\
git reset --head [code in log] -> undoing git commit and unstage\














