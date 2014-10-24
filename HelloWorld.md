## This is a markdown file

It's in a text file called HelloWorld.md
in 2014-10-DataSciToolbox/gitRepos/datasciencecoursera/HelloWorld.md

git help init

git init
#x git push --dry-run --repo=datasciencecoursera  
#x git remote add [-t <branch>] [-m <master>] [-f] [--[no-]tags] [--mirror=<fetch|push>] <name> <url>
#x git remote add HelloWorld.md https://github.com/6511/datasciencecoursera.git

#******************************************************************************
#The general idea is to add, commit and push your files to the GitHub repo.
#******************************************************************************
git add HelloWorld.md
git status
# On branch master
#
# Initial commit
#
# Changes to be committed:
#   (use "git rm --cached <file>..." to unstage)
#
#	new file:   HelloWorld.md
#
git commit  -m 'HelloWorld.md'
#Finally, to push files.
git push --set-upstream https://github.com/6511/datasciencecoursera master
git push --dry-run  -u  --repo=https://github.com/6511/datasciencecoursera
git push --set-upstream https://github.com/6511/datasciencecoursera master

# Made further edits
git commit  -m 'Made further edits to HelloWorld.md'
# ********* Error # Changes not staged for commit:

git add HelloWorld.md
git status
# On branch master
# Changes to be committed:
#   (use "git reset HEAD <file>..." to unstage)
#
#	modified:   HelloWorld.md
#
git commit  -m 'Made further edits to HelloWorld.md'
# [master b63804c] Made further edits to HelloWorld.md
# 1 file changed, 28 insertions(+), 3 deletions(-)



GIT-PUSH(1)                                                 Git Manual                                                GIT-PUSH(1)

NAME
       git-push - Update remote refs along with associated objects

SYNOPSIS
       git push [--all | --mirror | --tags] [--follow-tags] [-n | --dry-run] [--receive-pack=<git-receive-pack>]
                  [--repo=<repository>] [-f | --force] [--prune] [-v | --verbose] [-u | --set-upstream]
                  [--force-with-lease[=<refname>[:<expect>]]]
                  [--no-verify] [<repository> [<refspec>...]]

DESCRIPTION
       Updates remote refs using local refs, while sending objects necessary to complete the given refs.


