# Git Commands Used 
2. git checkout main 
mkdir Task1
echo "# Task1" > Task1/README.md 
git add Task1/README.md
git commit -m "Add Task1/README.md"
git push origin master

3.git checkout -b dev
echo "This is a test file." > test_file.txt
git add test_file.txt
git commit -m "Add test file to dev branch"
git push origin dev

4.git checkout -b Aymenaqil01-new_feature
git push origin Aymenaqil01-new_feature

5.git add README.md
git commit -m "Add README.md to Aymenaqil01-new_feature"
git push origin Aymenaqil01-new_feature

6.git status

7. echo ".*" > .gitignore
git add -f .gitignore
git commit -m "Add .gitignore to ignore files starting with ."
git push origin Aymenaqil01-new_feature

8.git add .
git commit -m "Added .gitignore to ignore files starting with a '.' "
git push origin Aymenaqil01-new_feature

9. pull request manuellement dans GitHub

10.git checkout dev
git merge Aymenaqil01-new_feature
git push origin dev / 
git checkout main
git merge dev
git push origin main

11.git checkout Aymenaqil01-new_feature
echo "New changes in README.md" >> README.md
git add README.md
git commit -m "Update README.md"
git revert HEAD
git push origin Aymenaqil01-new_feature

12.git checkout main
git log > log.txt
git add log.txt
git commit -m "Save git log output to log.txt"
git push origin main

13.git worktree list
git checkout dev
git branch -D Aymenaqil01-new_feature

14.git checkout dev
nano git_commands.md
