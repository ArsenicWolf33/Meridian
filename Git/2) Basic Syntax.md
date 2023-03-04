

1. init: Initialise

2. git config -h: Help

3. clear: To clear

4.  git status: Show which branch and tracked/untracked files

5. git add: Start tracking a file

6. git rm --cached<filename>: To remove a file from being tracked

7. git add --all || git add -A ||  git add .: To start tracking files

8. git commit -m "insert message": To comming along with a message

9. git diff: To see what changes have been made after commiting

10. git add index.htm: To add changes after editing

11. git restore --staged index.htm: Remove a file from staging, not yet ready to commit

12. git rm "secret recepie.htm": To delete a file from git

13. git restore --staged "secret recipe.htm": To remove the deletion from the stageing

14. git restore "secret recipe.htm": To recover a deleted file

15. git mv "KCC Logo.png" "Primary Logo.png": To 'move' a file from an old name to a new name

16. git log || git log --oneline: See all commits 

17. git commit -m "correct spelling" --amend: To change a previous commit message

18. git reset *52225*: To revert branch to previous commit 
     (number in asterix is the yellow identifier number, type without asterix)

19. git rebase -i --root: To change complete log (text editor)
20. :x : Exit text editor

21. git branch FixTemp: To create new branch called FixTemp

22. git branch: To see all branches

23. git switch FixTemp: To switch to FixTemp branch

24. git checkout main: To check main, then do `git branch FixTemp` to copy the branch into FixTemp, other wise it creates an empty branch

25. git branch --delete FixTemp: To delete a branch

26. git branch -m "FixTemp": To rename current branch to FixTemp

27. git merge -m "Merging FixTemp with main" FixTemp: To merge changes of fixtemp with main

28.  git fetch: To get changes made on the online version of the repository




# Pushing online 

1. git remote add origin https://github.com/ArsenicWolf33/arsenicwolf33.github.io.git

2. change made online, first fetch and log (git fetch)

	1. git push -u origin main