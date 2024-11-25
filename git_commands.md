# Git Commands Used 
2. <h2>Create Task1 folder in the master branch. Create and push
 ./Task1/README.md file.</h2>
git checkout main 
mkdir Task1 /
echo "# Task1" > Task1/README.md /
git add Task1/README.md /
git commit -m "Add Task1/README.md" /
git push origin master 

3. <h2>Create new branch dev. Create and push any test file.</h2>
 git checkout -b dev /
echo "This is a test file." > test_file.txt /
git add test_file.txt /
git commit -m "Add test file to dev branch" /
git push origin dev 

4. <h2> Create new branch %USERNAME-new_feature.</h2>
git checkout -b Aymenaqil01-new_feature /
git push origin Aymenaqil01-new_feature 

5. <h2>Add README.md file to your %USERNAME-new_feature branch</h2>
git add README.md /
git commit -m "Add README.md to Aymenaqil01-new_feature" /
git push origin Aymenaqil01-new_feature 

6.<h2> Check the repository status</h2>
git status

7.<h2>Add .gitignore file to ignore all files whose name begins “.”</h2>
 echo ".*" > .gitignore /
git add -f .gitignore /
git commit -m "Add .gitignore to ignore files starting with ." /
git push origin Aymenaqil01-new_feature 

8.<h2>Commit and push changes to github repo.</h2>
git add . /
git commit -m "Added .gitignore to ignore files starting with a '.' " /
git push origin Aymenaqil01-new_feature 

9.<h2>Create Pull Request to the dev branch.</h2>
    pull request manuellement dans GitHub

10.<h2> Merge your branch with the dev branch and create Pull Request to
 the master branch. Merge dev with master.</h2>
git checkout dev /
git merge Aymenaqil01-new_feature /
git push origin dev / 
git checkout main / 
git merge dev /
git push origin main 

11.<h2>Checkout to %USERNAME-new_feature, make changes in
 README.md and commit them. Revert last commit in
 %USERNAME-new_feature branch.</h2>
git checkout Aymenaqil01-new_feature /
echo "New changes in README.md" >> README.md /
git add README.md /
git commit -m "Update README.md" /
git revert HEAD /
git push origin Aymenaqil01-new_feature 

12.<h2> Check your repo with git log command, create log.txt file in
 master branch and save “git log” output in it.</h2>
git checkout main /
git log > log.txt /
git add log.txt /
git commit -m "Save git log output to log.txt" /
git push origin main 

13.<h2>Delete local and remote branch %USERNAME-new_feature.</h2>
git worktree list /
git checkout dev /
git branch -D Aymenaqil01-new_feature 

14.<h2>Add all used command to the git_commands.md file in the dev
 branch.</h2>
git checkout dev /
nano git_commands.md 
<h2>Outputs</h2>
<a href="https://github.com/Aymenaqil01/Devops/tree/main/images" target="_blank">Go to GitHub Images Folder</a>
