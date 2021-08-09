# git commit

The command 'git commit' will take all tracked changes (items added with [git add](./Add.md)) and package them op in what is called a commit.

Commits come with comit messages that are required for each commit.  You add a message to a coommit command by ising the '-m' flag followed by a message in quotes.

A commit message _can_ be anything, but best practice dictates that you should use that message to indicate the changes included in the commit.

For example, if we have an application we're working on where we just built out the ablilty to register new accounts, then you might have some variation of the following:

...
git add .
git commit -m "Added register functionality"
...

Then when viewing the history of a git repository, you can pinpoint where the registration functionaly was added.

## Resources

-[Git Commit Documentation](https://git-scm.com/docs/git-commit)