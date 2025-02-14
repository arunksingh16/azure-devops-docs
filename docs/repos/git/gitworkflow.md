---
title: Azure Repos Git tutorial
titleSuffix: Azure Repos
description: Learn Git with the Azure DevOps Services/TFS Git tutorial.
ms.assetid: 0270b0fa-461b-4079-9703-cdcf53bdf39f
ms.technology: devops-code-git 
ms.topic: tutorial
ms.date: 09/28/2021
monikerRange: '<= azure-devops'
---

# Azure Repos Git tutorial

[!INCLUDE [temp](../includes/version-tfs-2015-cloud.md)]
[!INCLUDE [temp](../includes/version-vs-2015-vs-2019.md)]

Use version control to save your work and coordinate code changes across your team. Even if you're just a single developer, version control helps you stay organized as you fix bugs and develop new features. Version control keeps a history of your development so that you can review and even rollback to any version of your code with ease.

The steps in the following tutorials show how to perform common version controls tasks using the following version control workflow.

## Version control workflow

Version control has a general workflow that most developers use when writing code and sharing it with the team.

These steps are:

---
1. Get a local copy of code if they don't have one yet.
2. Make changes to code to fix bugs or add new features.
3. Once the code is ready, make it available for review by your team.
4. Once the code is reviewed, merge it into the team's shared codebase.

---

![The Git feature branch workflow](media/gitworkflow.png)

Git has a version of this workflow using terminology and commands unique to Git. Throughout this tutorial you'll learn about repositories, branches, commits, and pull requests. 
These terms might sound familiar if you've used a version control system like Team Foundation Version Control or Subversion, but they behave differently in Git.
 
##  Git workflow

---
1. [Create a branch](./create-branch.md) for the changes you plan to make and give it a name, such as `users/jamal/fix-bug-3214` or `cool-feature-x`. For more branching guidance, see [Adopt a Git branching strategy](git-branching-guidance.md)
2. [Commit changes](commits.md) to your branch. People often have multiple commits for a bug fix or feature.
3. [Push your branch](pushing.md) to the remote repository. 
4. [Create a pull request](pull-requests.md#create-a-new-pull-request) so other people can review your changes. To incorporate feedback, you might need to make more commits and push more changes.
5. [Complete your pull request](pull-requests.md#complete-the-pull-request) and resolve any merge conflicts from changes other people made after you created your branch.   

---

Use this workflow if you're new to Git. As your team gets more experienced and confident with Git, extend it to suit your team's needs.

## Next steps

> [!div class="nextstepaction"]
> [Create a new Git repository](creatingrepo.md)

> [!div class="nextstepaction"]
> [Clone an existing Git repository](clone.md)