Git Please move or remove them before you can merge. error solution

git clean  -d  -fx ""

Among them 
X - delete ignore file has not identified for git files
D -- deletion was not added to the git in the path of the file
F - forced operation


<h2>Managing Remotes / Adding a remote</h2>
Adding a remote

To add a new remote, use the git remote add command on the terminal, in the directory your repository is stored at.

The git remote add command takes two arguments:

    A remote name, for example, origin
    A remote URL, for example, https://github.com/user/repo.git

For example:

git remote add origin https://github.com/user/repo.git
Set a new remote

git remote -v
Verify new remote

<h2>Removing Remotes</h2>

If you want to remove a remote for some reason – you’ve moved the server or are no longer using a particular mirror, or perhaps a contributor isn’t contributing anymore – you can either use git remote remove or git remote rm:

$ git remote remove paul</br>
$ git remote
origin

Once you delete the reference to a remote this way, all remote-tracking branches and configuration settings associated with that remote are also deleted.

git pull origin master

<h2>How to remove a directory from git repository?</h2

git rm -rf folder_name </br>
git commit -m "your commit" </br>
git push origin master

<h2>return to commit</h2>
git log
git reset --hard ABCDE
git push origin master



