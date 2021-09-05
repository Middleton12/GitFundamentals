# git commit

The command `git commit` will take all changes (items added with [git add](./Add.md)) and packge them up in what is called a commit.

Commits come with commits messages that are required for each commit. You add a message to a commit command by using the `-m` flag follwed by a message in quotes.

A commit message _can_ be anyhting, but best practice dictates that you should use that message to indicate the changes included in the commit.

For example, if we have an application we're working on we just built out the ability to register new accounts, then might have some variation of the following.

```
git add .
git commit -m "Added register funvtionality"
```

Then when viewing the history of a git repostory, you can pinponit where the registation functionality was added.

## Resources 

- [Git Commit Documentaion](http:/git-scm.com/docs/git-commit)

----
[Back to home](../README.md)

