# 1.5 tracking changes
## Release 5: Reflect

**How does tracking and adding changes make developers' lives easier?**
Tracking and adding changes lets developers keep track of projects. you can make changes without instantly updating the master. This is a safe place to make mistakes.

**What is a commit?**
A commit is like a savepoint you can revert back to if your project ends up having a bug.

**What are the best practices for commit messages?**
the first line of commit messages should contain a short description with verbs and imperative present tense because it will tell someone what the commit does.

**What does the HEAD^ argument mean?**
HEAD^ will go back to the last commit.  

**What are the 3 stages of a git change and how do you move a file from one stage to the other?**
You should always work in a feature branch when making changes to a file.
when you create a new file git has no idea it exsists untill you add it (git add)
you can confirm this by running git status. untracked files font will be red in git bash.
once you add the file you can commit and decribe your changes (git commit -m "")

work on the file (in a feature branch) > add it (git add .) > commit changes (git commit -m "")

**Write a handy cheatsheet of the commands you need to commit your changes?**
edit > save > git status > add > commit -m

**What is a pull request and how do you create and merge one?**
A pull request merges code from a feature branch into the master.

you can create a pull request after pushing your changes to github. 
you should now see a red bar in your repo on this gibhub website. 

To the right is a green button that says *Compare & pull request* 

After clicking the button fill out the pull request and click the green button on the bottom right *Create pull request*

if there are no conflicts you should be able to click the green *Merge pull request* button that has appeared. 

Confirm the merge and delete the branch to keep your branches clean.

The Master on github should now be updated!


**Why are pull requests preferred when working with teams?**
Pull requests are preferred among teams because they merge code from other branches rather than the master. This keeps things clean and when working with multiple people will result in less conflicts rather than uploading into the master right away.