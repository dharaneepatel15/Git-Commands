# Git-Commands

#### Remote
`git remote origin show` --> Show all branches on remote repositiry \
`git remote -v` --> List all remote-urls that set up in local repository \
`git remote add origin url` --> Add remote's url \
`git remote set-url origin url` --> Changes remote's url

#### Initialize git to folder
1. `git init`
2. `git add`
3. `git commit`
4. `git remote add origin url`
5. `git push origin`

#### Fetch
`git fetch origin` --> Fetch all brnaches and changes from remote to local 

#### Git Pull keepig all local changes

1. `git statsh`  - # Stash all local changes
2. `git pull origin` - # Fetch changes from remote 
3. `git stash pop` - # Get all local stashed changes back (May have merge conflits)

#### Remove files that commited by mistake from commit before push

1. `git reset --soft HEAD~1` - # Remove the last commit but preserve changes
2. `git reset HEAD path/to/unwanted_file`- #To remove unneeded file from staging area
3. `git commit -c ORIG_HEAD` - If want to commit again with same message 


#### Add all files to commit except single file/folder

1. `git add -u` - # Add only updated files, not add new ones.
2. `git reset -- path/to/excepted_file_or_folder`- # To exclude file/folders from staging area


### Resources
- https://www.atlassian.com/git/tutorials
- https://git-scm.com/book/en/v2
- https://github.community/t/what-are-main-differences-between-git-github-and-bitbucket-resp-gitkraken-and-also-git-and-mercuri/1580 
