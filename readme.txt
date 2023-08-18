Hello,this is my first git test.
Just like Linux os, we use Git by Git Bash.

mkdir name: create a directory.
cd name/name/...: enter a directory.
pwd: show the present directory.
cat filename: check the file.
touch filename: create a new file.
rm filename: delete the file.

git init: initialize empty Git repository in the present directory.
git add filename: submit the file to Index.
git commit -m "annotation": submit the file to Repository.
git status: check if another file hasn't been submitted.
git diff filename: check the difference between the present file with last one.
git log: check the history of submitting.
git log -pretty=oneline: just like "git log" but only one line.
git reset --hard HEAD^: return to the last version.
git reset --hard HEAD^^: return to the the version before last.
...
git reset --hard HEAD~100: return to the version 100 versions before.
git reset --hard versionNum: return to the version with versionNum.
git reflog: check all the versionNum.
git restore filename: revoke the change of the file:
                      1.before add:
		        return to the version as Repository.
		      2.after add:
		        return to the first version after add.
git checkout -- filename: restore the file after deleted in the workspace.
git push origin main: submit the newest main to Github.


