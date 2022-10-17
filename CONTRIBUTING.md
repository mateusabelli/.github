<!-- omit in toc -->

# Contributing

First off, thanks for taking the time to contribute! ❤️

This file contains a set of guidelines for everyone who wishes to contribute to this repository. Feel free to ask questions and make sure you read the whole guidelines

> And if you like the project, but just don't have time to contribute, that's fine. There are other easy ways to support the project and show your appreciation, which we would also be very happy about:
>
> - Star the project
> - Tweet about it
> - Refer this project in your project's readme
> - Mention the project at local meetups and tell your friends/colleagues

## How to Contribute

- Take a look at the existing Issues or create a new issue!
- Fork the Repo. Then, create a branch for any issue that you are working on. Finally, commit your work.
- Create a **Pull Request** (_PR_), which will be promptly reviewed and given suggestions for improvements by the community.
- Add screenshots or screen captures to your Pull Request to help us understand the effects of the changes proposed in your PR.

---

## How to make a Pull Request

**1.** Start by making a Fork of the repository. Click on the <img src="https://i.imgur.com/G4z1kEe.png" height="16" width="16"> Fork symbol at the top right corner.

**2.** Clone your new fork of the repository in the terminal/CLI on your computer with the following command:

```bash
git clone https://github.com/<your-github-username>/<repository-name>
```

**3.** Navigate to the newly created project directory:

```bash
cd <repository-name>
```

**4.** Set upstream command:

```bash
git remote add upstream https://github.com/mateusabelli/<repository-name>.git
```

**5.** Create a new branch:

```bash
git checkout -b <your-branch-name>
```

**6.** Sync your fork or your local repository with the origin repository:

- In your forked repository, click on "Fetch upstream"
- Click "Fetch and merge"

### Alternatively, Git CLI way to Sync forked repository with origin repository:

```bash
git fetch upstream
```

```bash
git merge upstream/main
```

### [Github Docs](https://docs.github.com/en/github/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github) for Syncing

**7.** Make your changes to the source code.

**8.** Stage your changes and commit:

**Make sure** not to run the commands `git add .` or `git add *`. Instead, stage your changes for each file/folder

```bash
git add index.html
```

```bash
git commit -m "<your_commit_message>"
```

**9.** Push your local commits to the remote repository:

```bash
git push origin <your-branch-name> 
```

**10.** Create a [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)!

**11.** **Congratulations!** You've made your first contribution!

**_After this, the maintainers will review the PR and will merge it if it helps move the project forward. Otherwise, it will be given constructive feedback and suggestions for the changes needed to add the PR to the codebase._**

---

## Style Guide for Git Commit Messages

**How you can add more value to your contribution logs:**

- Use the present tense. (Example: "Add feature" instead of "Added feature")
- Use the imperative mood. (Example: "Move item to...", instead of "Moves item to...")
- Limit the first line (also called the Subject Line) to _50 characters or less_.
- Capitalize the Subject Line.
- Separate subject from body with a blank line.
- Do not end the subject line with a period.
- Wrap the body at _72 characters_.
- Use the body to explain the _what_, _why_, _vs_, and _how_.
- Reference Issues and Pull Requests liberally after the first line.

---

## Issues

In order to discuss changes, you are welcome to open an issue about what you would like to contribute. Enhancements are always encouraged and appreciated.
