# git commit
The command `git commit` will take all tracked changes (items added with [git add](./Add.md)) and package them up in what is called a commit.
Commits come with commit messages that are required for each commit. You add a message to a commit by using the the `-m` flag followed by a message in quotes .
A commit message _can_ be anything, but best practice dictates that you should use that message to indicate the changes included in the commit. 

For example, if we have an application we're working on where we just built out the abilitiy to register new accounts, then you might have some variation of the following:
'''
git add .
git commit -m "Added register functionality"
'''

Then when viewing the history of a git repository, you can pinpoint where the regisration functionality was added. 

## Resources
-[Git Commit Documentation](https://git-scm.com/docs/git-config)
---
[Back to home](../README.md)