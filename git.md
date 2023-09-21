# Welcome to git: essentials guide

## Commands to use and what they do
1. git init - create local repository
2. git add (file) - see that the letter U is changed to an A (next to the file name on the left), that means the file is added and is being tracked

P.S. git add. - with the dot at the end - will automatically add all files to be tracked

3. git commit -m "Commit: what changed?" - save changes + message (detailing the changes - can be viewed in log)
OR
Save changes by pressing control + s
OR
At the top press file => auto save (make sure there is a галочка)

P.S. git commit -am "New commit message" - save commits without adding the file and changes first. Much quicker and more efficient.

4. git log - see my commits and the time they were made

P.S. press q to quit

5. git status - check if there are any unsaved changes or modifications from previous save

6. git checkout 
- first 4 symbols of a commit version in the log you want to transfer to - your previous versions (like if you messed up or want to change the stuff you did to create a better version)
- git checkout main - to get back to the most recent version (FYI for the professors it is master, not main)

7. git diff 
- 4b16 (first 4 symbols) - to see the changes made from the commit which symbols you typoed and latest version
- 4b16 188e (first 4 symbols of one commit and first 4 symbols of the other to compare the version - used when comparing not with the latest version in the log)

8. git branch - see all your branches and see which one you are in
- git branch name - create a new branch
- git checkout name - go to that branch
- git merge (merge 2 branches - to merge with main branch - checkout to main first)