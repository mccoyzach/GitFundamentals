# git push
When you have a [remote](./remote.md) set up you'll need to begin to move [commits](./commit.md) to the remote. This can be done with the commang 'git push'.

You can attach a name and branch name to your ccommand to specify where you're pushing to.

'''
git push origin main
'''

This command will push the **main** branch to the remote called **origin**.
This means any commits that are in your local eill be **pushed** to the remote.

### Upstream Tracking

Instead of including the name og the remote and the branch uou're in every time, you can set local branches to track an upstream branch.
This means you can tell the branch to push to ots assigned austream remote branch by using the commaand 'git push'.

'''
git push -u origin main
'''

After this command is used, uou can just use 'git push' and it function the same way.

## Resources

- [git Push Documentation](https://git-scm.com/docs/git-push)

---

[Back to home](../README.md)