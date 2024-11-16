---
title: Git - a distributed version control system
summary: This article will give a brief overview of the Git version control system with a focus on practical applications of its main commands.
date: 2024-10-05

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](Git.webp)'

author:
  - admin

tags:
  - Git
  - Markdown

---

Добро пожаловать 👋

{{< toc mobile_only=true is_open=true >}}

## Publication Objective.

This article will give a brief overview of the Git version control system, with a focus on practical application of its basic commands. Despite the abundance of information about Git on the Internet, it can often be difficult for beginners to get to grips with it, as the documentation can be difficult to understand. 
The purpose of this article is to provide a clear and concise description of some of the key Git commands. This will allow users to get to grips with the system more quickly and avoid mindlessly applying commands without understanding their implications. It will also provide a short and concise introduction to the system for new users.


[//]: # ([![The template is mobile first with a responsive design to ensure that your site looks stunning on every device.]&#40;https://raw.githubusercontent.com/wowchemy/wowchemy-hugo-modules/main/starters/academic/preview.png&#41;]&#40;https://hugoblox.com&#41;)

## Subject area and key terms

***A version control system is software for handling changing information that allows you to store multiple versions of a single document, revert to earlier versions, and determine who made changes and when.

- *Git is a distributed version control system.
- *GitHub is a service for using Git.

### **Main concepts of Git**

- repository - repository of files and references to changes
- commit - track changes, keep track of deviations
- HEAD - symbolic link to recent changes
- Status ‘Detached HEAD’ - HEAD does not necessarily refer to a commit
- HEAD can point to a branch or commit.

### **Git Objects**

- Branch, tree, commit, links
- A branch is defined by the operating system and file system
- Learn more about Git objects in the documentation

### **Git Services**

- Services that provide services for Git users
- HEAD is a pointer to the current branch
- A working tree is usually formed from the tree state referenced by HEAD

### **Working Zones and Commands**

- working directory - working directory on the computer
- staging area - an area of prepared files
- branch - a branch consists of a set of commits
- merge - merge branches
- pull - pull changes from the server
- push - push changes to the server

### **Symbols and commands**

- _#_ - comment symbol
- <> - angle brackets
- $ - terminal input prompt

### **Application Git**

- Designed for distributed development team work
- Used by designers, writers, editors, planners, translators
- Often used by human resources and personnel managers
- Economical, does not require sending a large number of files
- Allows you to return to previous states of the system
- Convenient for individual work, allows to correct errors and return to optimal versions.



### History of creation

### Quote from Wiki:

Git (pronounced ‘git’[8]) is a distributed version control system. The project was created by Linus Torvalds to manage the development of the Linux kernel, with the first version released on 7 April 2005. It is currently maintained by Junio Hamano.

### Theoretical part

### **History and licence of Git**

- The project was created by Linus Torvalds to manage the development of the Linux kernel.
- Git is distributed under the GNU GPL 2 licence.

### **The main purpose of a version control system**.

- Simplify the handling of changing streams of information
- Localisation of each project developer's data

### **Data localisation**.

- Each developer has a local repository on their machine.
- Changes are sent from the local repository to the remote repository
- Any developer can download new changes to continue their work

### **Standards and Ethics**

- It is important to adhere to standards for code design and working with the system
- Standards promote communication and understanding between developers
- Ethics and culture help to better understand each other

### **Types of version control systems**

- Centralised: code is stored on a server, all developers have access.
- Cons: no local repository, difficult to access resource
- Decentralised: each developer has their own repository, fast recovery

### **Interoperability with other systems**.

- CVS and Subversion support
- Standard import and export tool - archives of series of versioned files

### **Git Concepts**

- Fork: a remote copy of the repository on the server
- Clone: a local copy of a remote repository
- Branch: a way to make changes and merge them with the rest of the code
- Working tree: tree of source files to edit
- Index: binary file with information about the files in the current branch
- HEAD pointer: reference to the last commit in the current branchPractical part

## Practice

To use the git system, you need to:
1. Install the git software on your system.
2. Configure the programme and test it locally.
3. Register your account on GitHub
4. Create a local repository or copy the repository of an existing project
5. Write a README.MD file.
6. If you are starting a project, create a remote repository.
7. Commit the changes locally
8. Submit the changes to GitHub
9. Register developer accounts for your project
10. Give them a link to the project

There are many different commands that allow you to interact with the repository through the guide, below are some diagrams with different commands.


[The diagram shows how to prepare a folder on your local computer to work with git.](ИндЛаб2.png)

[The diagram in Figure 2 shows how the commands add, commit all, commit, reset, git reset head, git update index work.](ИндЛаб2.2.png)

[The diagram below shows the difference between working with a local repository and a GitHub repository.](ИндЛаб2.3.png)