# **Task 2**

## Version Control

Version control (also known as source control) is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time. They are especially useful for DevOps teams since they help them to reduce development time and increase successful deployments. Version control software keeps track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members. For almost all software projects, the source code is like a precious asset whose value must be protected. Version control protects source code from both catastrophe and the casual degradation of human error and unintended consequences.

In summary, version control is a software practice that helps software teams manage changes to source code over time. It is especially useful for DevOps teams since it helps them to reduce development time and increase successful deployments.

## Difference Between Git and GitHub

Git and GitHub are two distinct tools used in software development. Git is a **distributed version control system** that helps developers track changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files. Its goals include speed, data integrity, and support for distributed, non-linear workflows. On the other hand, GitHub is a **web-based Git repository hosting service** that offers all of the distributed revision control and source code management (SCM) functionality of Git as well as adding its own features. It provides a graphical user interface to manage Git repositories, which makes it easier to use for beginners. GitHub is focused on centralized source code hosting and includes a built-in user management feature. It is maintained by Microsoft and includes a free-tier and pay-for-use tier.

Here is a table of differences between Git and GitHub:

| **S.No.** | **Git** | **GitHub** |
|-------|---------|-----------|
| 1.    | Git is a software. | GitHub is a service. |
| 2.    | Git is a command-line tool. | GitHub is a graphical user interface. |
| 3.    | Git is installed locally on the system. | GitHub is hosted on the web. |
| 4.    | Git is maintained by Linux. | GitHub is maintained by Microsoft. |
| 5.    | Git is focused on version control and code sharing. | GitHub is focused on centralized source code hosting. |
| 6.    | Git is a version control system to manage source code history. | GitHub is a hosting service for Git repositories. |
| 7.    | Git has no user management feature. | GitHub has a built-in user management feature. |
| 8.    | Git is open-source licensed. | GitHub includes a free-tier and pay-for-use tier. |
| 9.    | Git has minimal external tool configuration. | GitHub has an active marketplace for tool integration. |
| 10.   | Git provides a Desktop interface named Git Gui. | GitHub provides a Desktop interface named GitHub Desktop. |
| 11.   | Git competes with CVS, Azure DevOps Server, Subversion, Mercurial, etc. | GitHub competes with GitLab, Bit Bucket, AWS Code Commit, etc. |

## Alteraternatives to GitHub

There are several alternatives to GitHub that you can use which are:

1. Bitbucket - A Git and Mercurial code management and collaboration platform developed by Jesper Noehr in 2008 (now owned by Atlassian).
2. GitLab - An open-source Git-based platform developed by Dmitriy Zaporozhets and Sytse Sijbrandij in 2014.
3. Gitea - This is a community managed fork of Gogs, lightweight code hosting solution written in Go and published under the MIT license.

## Difference between git fetch and git pull

The difference between `git fetch` and `git pull` lies in their functionality. The `git fetch` commad retrieves the latest data from a remote repository and updates your remote-tracking branches without merging them. This operation is safe to run at any time since it never changes any of your local branches. On the other hand, `git pull` fetches the latest data from a remote repository and merges it with your local branch. It brings a local branch up-to-date with its remote version, while also updating your other remote-tracking branches.

In summary, `git fetch` is a safe operation that only updates your remote-tracking branches, while `git pull` updates your local branch by merging the latest data from a remote repository with your local branch.

## Git Rebase

The `git rebase` is a command that helps integrate changes from one branch onto another branch by reapplying a sequence of commits on top of a new base commit. This can compress all the changes into a single patch or update an existing branch to a new base. Rebase creates new commits that are different and independent from the old ones, which are not destroyed.

The command for git rebase is `git rebase`. You can use it with various options to customize the behavior of the command. For example, you can use `git rebase -i` to interactively edit the commits being rebased, or `git rebase --onto <newbase> <upstream>` to rebase a branch onto a new base commit.

## Git Cherry-pick

**Git cherry-pick** is a command that allows you to apply the changes introduced by some existing commits to another branch. This is useful for incorporating bug fixes, feature enhancements, or commits from experimental branches into your main codebase. Unlike merge or rebase, git cherry-pick enables granular integration of changes without merging the entire branch.

The command for git cherry-pick is `git cherry-pick <commit>`. You can use it to apply the changes introduced by one or more existing commits to your current branch. For example, `git cherry-pick abc123` applies the changes introduced by the commit with hash `abc123` to your current branch.
