# My GitHub Cheatsheet


## Step 1 - Setting up the files

#### Create a new repo in GitHub and git remote add origin https://github.com/rjrobbie/git-practice.git
### git init - in the new directory I've made in the terminal

## Step 2 - Tracking files (doesn’t use past tense in commit message)

### git add (add the items to the parcel)
### Add all files / git add . or Add specific file / git add index.html
### git commit -m “a brief description of changes (add a label to the parcel)
### git push --set-upstream origin main (first time and then just git push origin main

## Step 3 - Create a new branch 

### git checkout -b “branch name” - name it inside quotations

## Step 4 - Committing branch changes 

### Repeat Step 1 to track changes
### Git push -u origin new-branch
### Go back to GitHub

## Step 5 - ‘Pull Requests’ 

### Go to the main repo and notice “ new-branch had recent pushes less than a minute ago” at the top of the page and ‘compare and new pull request’ 
### Add link to the ticket in the description
### Add more context about the job in the description
### Click on the big green button that says create pull request
### Click on the big green button that says ‘merge pull request’ when changes have been compared, followed by ‘confirm merge’ 
### Go ahead and delete the branch (might not always be the case)

## Step 6 - Updating the main branch

### Go back to the main branch
### git checkout main
### git pull origin main

## Step 7 - Add another branch (shows modified and not untracked branches)

### Repeat ‘Step 3’

## Bonus - Forking and cloning

### Visit the repo you want to use on GitHub and click the ‘fork’ button
### This should now be visible in your own profile as a repo
### Copy the url for your version of this repo, if you see your GitHub username in the link you’re doing fine
### Next, navigate to your Projects folder in the command line, or wherever you keep your coding projects
### Using the url we just copied, type ‘git clone whatever-your-url-is and we’re good to go
### Everything we need is now in our Projects folder, check with ls to see the new directory and then cd <nameofdirectory> to open it
### Nearly done, enter ‘code .’ in the terminal to see it in VS Code and now we can make changes to the code on our local machine
### Finally, commit your work at the end of your session as described in ‘step 2’. 


## Tips 

### git status - shows changes to be committed 
### git checkout (branch name) - switches between branches
### git branch - checks which branch I’m working on
### git stash - saves my work and puts branch on hold 
### git stash pop - brings back branch and brings back saved work
### Delete a branch - git branch -D branchName
### Clone a repo by clicking on the drop-down of the repo and clone
### Check where the branch needs to be merged with. ‘Base’ is where it needs to merge and ‘compare’ is the current branch
