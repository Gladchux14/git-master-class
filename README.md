# git-master-class

### Version Control

Version control also known as Source control is the practice of tracking and managing changes to files. <br/> version control are systems that record changes to a file or a set of files over time so that you can record specific versions of it.

### Difference between Git and Github

- Git is a version control system that runs o byour local machihne to keep track of your changes, enable you have a historical back-up as well as collaboration.

-Github is Hosted GIT ie it runs the version control system on the web.Github provides a comprehensive ecosystem of online development tools that are built around Git, it also enhances continous integration.

### 3 other Github Alternatives

- Gitlab
- BitBucket
- Launchpad

### Difference between git fetch and git pull

- Git pull: brings the files from the remote repository to your local repository and directory to to your working directory. <br/> it is a straightforward process of calling up files from your remote repository.

- Git fetch: this brings files down to your local repository from the remote repository but it does not merge them, if you want it available in your working directory you have to merge using the command ' $ git merge' .

### Git rebase

Git rebase places changes from a particular branch ontop of a different branch ie at the tip of the current branch in order. the command for it is ' $ git rebase '.

### Git cherry-pick

git cherry pick allows you bring changes from a specific commit into your branch, you can get change(s) made from another branch onto yoour current branch. you simply check into the branch you want to get the specific commit from and do  '$ git log' <br/> this gives you series of commit made on that branch then you check for the id of the one you want to bring. check back to your current branch and use '$ git cherry pick (the id of the commit)' as a commanda and commit it. voila! you will have that particular change added to your current branch.