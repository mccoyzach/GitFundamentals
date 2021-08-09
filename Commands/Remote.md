# git remote

When working with git, a **remote** is any git repository that is not on the machine you're working on. The counterpart to this is **local**, or the machine  that is being developed on.

Take GitHub for example. While git is the technology that allows you to create lacal repositories, GitHub is the site that will host your remote repositories. Once stored remotely, you can bring that repository back sown or share it with others.

**Note**: While the repositories (lacal and remote) are related and tracl the some project, they can have states if changes are not shared between the two.

### Adding a remote

A remote can be added with the 'git remote add' command, followed by the name and location of the remote.

The name is a local name, meaning it's your lable and soes not impact the actual remote whatsoever.

...
git remote add origin https:githubElevenFiftyAcademy/GitFundimentals.git
...

### Removing a remote

A remote can be removed with the 'git remote remove' command, followed by the name f the remote.

...
git remote remove origin
...

## Resources

-[Git Remote Documentation](https://git-scm.com/docs/gti-remote)

---

[Back to home](../README.md)