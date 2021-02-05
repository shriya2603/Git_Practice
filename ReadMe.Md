Create branch:
1.	Clone this repository:
git clone <REPOSITORY_URL>
2.	Navigate to the repository in your shell:
cd github-slideshow
3.	Create a branch, use whatever name you like. Here, my-slide is branch name.
git branch my-slide
4.	Push the branch to GitHub:
git push --set-upstream origin <BRANCH-NAME>

First Commit 
1.	Check out to your branch:
git checkout my-slide
2.	Create a new file named _posts/0000-01-02-shriya2603.md.
3.	Add the content to your file
4.	Stage your new file:
git add _posts/0000-01-02-shriya2603.md
5.	After adding the text, commit the change while providing a commit message. For guidelines on commit messages, check out the Commits 101 drop-down, just above these instructions:
git commit -m "<YOUR-MESSAGE>"
6.	Push your new commit to GitHub:
git push

Create a pull request
1.	Open a pull request using this shortcut or manually as follows:
o	From the "Pull requests" tab, click New pull request
o	In the "base:" drop-down menu, make sure the "master" branch is selected
o	In the "compare:" drop-down menu, select "my-slide"
2.	When you’ve selected your branch, enter a title for your pull request. For example Add shriya2603's file
3.	The next field helps you provide a description of the changes you made. Feel free to add a description of what you’ve accomplished so far. As a reminder, you have: created a branch, created a file and made a commit, and opened a pull request
4.	Click Create pull request

Merge the pull request
1.	Check out to the master branch:
git checkout master
2.	Merge your branch:
git merge my-slide
3.	Push the merged history to GitHub:
git push
4.	Delete your the branch locally:
git branch -d my-slide
5.	Once your branch has been merged, you don't need it anymore. Click Delete branch.

