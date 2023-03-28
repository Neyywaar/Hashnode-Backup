---
title: "Git & GitHub"
seoTitle: "Git & GitHub"
datePublished: Mon Mar 27 2023 10:22:58 GMT+0000 (Coordinated Universal Time)
cuid: clfqokprj000509l853qobt7l
slug: git-github
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1679679675403/77058251-bb88-4b6a-86d0-eef994797e8e.png
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1679912551209/2ef782d1-a108-48d0-8eca-fa69031a97c4.webp
tags: github, git, developer, gitlab, gitcommands

---

## Introduction

Git is a free and open-source tool that helps developers manage their code repositories. It is a distributed version control system that allows developers to work on their code locally and then upload it to a remote repository so others can access it and work on it too.

GitHub is a platform on the web where developers can store their code and work together on projects. It has many tools that help people work better together, like pull requests and issue tracking. With GitHub, developers can collaborate from anywhere in the world.

Using Git and GitHub makes it easier to keep track of changes made to the code and helps find and fix mistakes. It also helps people work together, even if they are far apart. Plus, there are lots of examples on GitHub that people can use to learn from and build their projects.

---

## Features

GitHub has many features that can help developers work together more easily. Some of these features include:

* **Pull Requests:** Developers can use pull requests to suggest changes to a code repository. Other users can then review and talk about these changes before they become a part of the main code.
    
* **Issues:** GitHub has tools that help with keeping track of issues and managing projects. For example, project boards and milestones can be used to stay organized and on top of things.
    
* **Collaboration:** With Git and GitHub, many people can work on the same code at the same time. This helps to prevent conflicts and ensures that everyone has the latest code.
    
* **Public Repositories:** GitHub has many public repositories that developers can use to learn from, contribute to, or build upon. This can help people to learn about different coding styles and best practices and also to show off their work.
    

---

## Getting Started

To start using GitHub, you need to first make an account. Once you have made an account, you can make a new repository by doing these things:

1. Sign in to your GitHub account
    
2. Click on the `"+"` sign and then select `"New repository"`
    
3. Type in your desired repository name and decide if you want it to be public or private
    
4. You can also add a description and license, but it is optional
    
5. Click on `"Create repository"` to make your new repository
    

After that, you can use the `git clone` command to copy the repository to your computer.

---

## Other basic Git Commands

Here are some of the basic Git commands that every beginner should know:

```bash
$ git init
```

This command **initializes a new Git repository** in the current directory. It creates a new hidden `.git` directory that will contain all the necessary Git metadata and configuration files.

---

```bash
$ git status
```

This command **shows the current status of the repository**. It lists any modified files that are not yet staged for commit, any files that are staged and ready to be committed, and any files that are untracked and not yet added to the repository.

---

```bash
$ git add "file_name"
```

This command **stages the specified file** for the next commit. When you add a file to the staging area, you're telling Git that you want to include the changes in the next commit.

---

```bash
$ git remote add origin "repo_url"
```

This command **adds a remote repository** named `origin` with the URL specified by `repo_url`. This allows you to push and pull changes to and from the **remote repository**.

---

```bash
$ git checkout "branch_name"
```

This command **switches to the specified branch**. If the branch doesn't exist yet, Git will create it for you.

---

```bash
$ git commit -m "commit_message"
```

This command **creates a new commit** with the changes you've staged in the previous step. The `-m` flag allows you to specify a commit message that briefly explains the changes you've made.

---

```bash
$ git push -u origin main
```

This command **pushes the new commit** to the `main` branch of the remote repository named `origin`. The `-u` flag sets the upstream branch for the current branch so that future git push commands will automatically push to the correct remote branch.

---

## Branching

One of the good things about using Git is that it lets people manage branches easily. This means that developers can work on different versions of the code at the same time. A branch is like a little arrow pointing to a certain version of the code. Normally, there is a master branch, which is the main one. However, developers can create new branches to work on different things without changing the main branch.

If you want to change the name of the `master` branch to `main`, you can just type this command:

```bash
$ git branch -m master main
```

---

## Merging

After you have worked on a branch and made some changes, you can combine those changes with the main branch. This is usually done by making a pull request. A pull request is like a suggestion for changes to a repository. Other people can look at the changes and talk about them before they get combined into the main branch.

To put one branch into another branch, use this command::

```bash
$ git merge "branch_name" -m "commit_message"
```

When merging branches, review changes and resolve conflicts if any. Keep committing messages descriptive to track history and help others understand changes

---

## Best Practices

Here are some best practices to follow when using Git and GitHub:

* **Commit Often:** You should commit your changes often so you can keep track of your progress and go back if you need to.
    
* **Write Descriptive Commit Messages:** When you commit your changes, you should write descriptions that tell what you did.
    
* **Use Branches:** Make new branches to work on new things so you don't mess up the main branch.
    
* **Review Pull Requests:** When reviewing pull requests, take the time to understand the changes and provide constructive feedback.
    

---

## Conclusion

In conclusion, Git and GitHub are powerful tools for managing code repositories and collaborating on projects. They provide several features that help developers work together more efficiently, such as pull requests, issue tracking, and project boards. It is important to follow best practices when using Git and GitHub, such as committing often, using descriptive commit messages, and using branches. By following these practices, developers can easily track their progress, collaborate effectively, and produce high-quality code. Whether you're a beginner or an experienced developer, Git and GitHub are essential tools to have in your toolkit.

---

## Find Me on:

* **GitHub** - [github.com/Neyywaar](https://github.com/Neyywaar)
    
* **Twitter** - [twitter.com/neyywaar](https://twitter.com/neyywaar)