# Create a new branch
	git checkout -b new-branch-name


# Go to another branch
	git checkout branch-name


# Update main
	git checkout main/master
	git pull origin main/master

Upload your changes and merge them into main:
git add .
git commit -m “description”
git checkout main/master
git pull origin main/master
git checkout your-branch
git merge main/master
If conflicts:
Solve conflicts
git add .
git commit -m “solve conflicts”
git push origin your-branch
Go to github, create a pull request, confirm it and merge it

If no conflicts:
	git add .
git commit -m “changes merged into main”
git push origin your-branch
Go to github, create a pull request, confirm it and merge it

Remove everything you did after your last commit
	git stash

Remove git from a folder
	rm -rf .git

