## This is a markdown file

It's in a text file called HelloWorld.md
in 2014-10-DataSciToolbox/gitRepos/datasciencecoursera/HelloWorld.md

git init
git push --dry-run --repo=datasciencecoursera  HelloWorld.md

git remote add [-t <branch>] [-m <master>] [-f] [--[no-]tags] [--mirror=<fetch|push>] <name> <url>
git remote add HelloWorld.md https://github.com/6511/datasciencecoursera.git

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


