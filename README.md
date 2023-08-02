#Automate all kinds of repository related process & actions
This file is online
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


CI/CD Process: Continuous Integration and Continuous Deployment
CI: Code changes are automatically built, tested and merged
CD: Publishing new version of code after merger

Github: A cloud git repository (project managed in Git) | push, pull
	      Code management & collaborative development
	      Github actions, to automate code

Git: A free version control system
1. Create snapshots of code (‘Commits’)
2. Work with alternative branch versions
3. Move between branches & commits
With git you can roll back to older code or develop new features without breaking the production code

Git Commands:
1. Git init: Creates hidden .git folder that contains the metadata 
2. Git add <files>: Staging process | Stages changes for next commit
    1. Git add .
    2. Git add file_name_1 file_name_2
    3. Git add /subfolder/file
    4. After git add, files will be stages
3. Git commit -m “commit message”
4. Git status: to check snapshot
5. Git log: All the commits you have, in chronological order
6. Git checkout <id>: Move between commits
7. Git checkout main: Go back to ahead of all the past commits
8. Git revert <id> | :q! To quit after putting in message, Git revert creates a new checkpoint
9. Git reset —hard <id> | deletes all the commits happened before

Git Branch:
1. Git branch <branch name> | Creates new branch
2. Git checkout <branch name> | To work on a branch
3. Git branch -D <branch name> | To delete a branch
4. Git checkout -b <branch name> | To create and move to a new branch
5. Git merge <branch to merge with current branch>

Github: Puts git functionalities on cloud. Code storage bucket.
1. Git remote add origin <repository url>: To establish a connection with remote
2. Git remote set-url origin https://<username>@github.com…..
3. Git push origin main | It will create main branch in remote branch
4. Git pull origin | To download files from GitHub
