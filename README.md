# git_howto
Notes on using git

Show

Display information about the origin

    git remote show origin
Ammend

If you need to re-do a commit. You can replace the last commit with "git commit --amend"
If the files did not change, the commit message will be the that of the last commit.
[--ammend](https://git-scm.com/book/en/v2/Git-Basics-Undoing-Things#_undoing)

    git commit --amend

Unstage

To remove a file that has been staged
git reset HEAD somefile
[reset](https://git-scm.com/book/en/v2/Git-Basics-Undoing-Things#Unstaging-a-Staged-File)

    git reset HEAD somefile

Alias

Git supports command aliases.  If you want to create a shorthand or new command. Use the following syntax.

    git config --global alias.unstage 'reset HEAD --'
[git-alias](https://git-scm.com/book/en/v2/Git-Basics-Git-Aliases)
