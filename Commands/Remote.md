# Git Remote

When working with git, a **remote** is any git repository that is not on the maching you are working on(not local). the counterpart to this is **[local]**, or the maching that is being developed on.

Take Github for example. WHile git is the technology that allows you to create local repositories, Github is the site that will host remote repositories. Once stored remotely, you can bring that repository back down to local or share it with others.

**Note** While the repositories (local and remote) are related and track the same project, they can have different states if changes are not shared between the two.

## Adding a remote

A remote can be added with the `git remote add` command, followed by name and location of the remote.

The name is a local name, meaning it's your local and does not impact the actual remote server.
```
git remote add origin https://github.ElevenfiftyAcademy/GitFundamentals.git

```
### Removing a remote

A remote can be removed with the `git remote remove` command, followed by the name of the remote.
```
git remove remote origin
```
## Resources

- [Git Remote Documentation](https://git-scm.com/docs/git-remote)
---
[back to home](../README.md)