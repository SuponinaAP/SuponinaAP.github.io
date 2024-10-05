---
title: Git — distributed version control system
summary: This article will provide a brief overview of the Git version control system, with a focus on the practical application of its main commands.
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

favorite: true
---

Welcome 👋

{{< toc mobile_only=true is_open=true >}}

## Purpose of the publication.

This article will provide a brief overview of the Git version control system, with a focus on the practical application of its main commands. Despite the abundance of information about Git on the web, beginners often find it difficult to get to grips with it, as the documentation can be difficult to understand. 
The purpose of this article is to provide a clear and concise description of some of the key Git commands. This will allow users to learn the system more quickly and avoid mindlessly applying commands without understanding their implications. It will also provide a short and concise introduction to the system for new users.


[//]: # ([![The template is mobile first with a responsive design to ensure that your site looks stunning on every device.]&#40;https://raw.githubusercontent.com/wowchemy/wowchemy-hugo-modules/main/starters/academic/preview.png&#41;]&#40;https://hugoblox.com&#41;)

## Subject area and basic terms

***A version control system is software for handling changing information that allows you to store multiple versions of a single document, revert to earlier versions, and determine who made the changes and when.***

- *Git — distributed version control system*
- *GitHub — service for use Git*

### **Basic Concepts Git**

- repository — repository of files and change references
- commit — tracking changes, keeping track of variances
- HEAD — symbolic link to the latest changes
- Status «Detached HEAD» — HEAD doesn't necessarily refer to commit
- HEAD can point to a branch or commit

### **Objects Git**

- Blob, Tree, Commit, References
- The branch is defined by the operating system and file system
- Learn more about Git objects in the documentation

### **Git services**

- Services that provide services for Git users
- HEAD — pointer to the current branch
- The working tree is usually derived from the tree state referenced by HEAD

### **Work areas and commands**

- working directory - working directory on the computer
- staging area - area of prepared files
- branch - a branch consists of a set of commits
- merge - merge branches
- pull - pull changes from the server
- push - push changes to the server

### **Symbols and commands**

- _#_ - comment symbol
- <> - angle brackets
- $ - terminal input prompt

### **Git application**

- Designed for distributed development team work
- Used by designers, writers, editors, planners, translators
- Often used by hr specialists and hr managers
- Economical, does not require sending a large number of files
- Allows you to return to previous states of the system
- Convenient for individual work, allows to correct errors and return to optimal versions



## Creation History

### Quote from Wiki:

Git (pronounced “git”[8]) is a distributed version control system. The project was created by Linus Torvalds to manage the development of the Linux kernel, with the first version released on April 7, 2005. To date, it is maintained by Junio Hamano.

## Theoretical part

### **History and license of Git**

- The project was created by Linus Torvalds to manage the development of the Linux kernel
- Git is distributed under the GNU GPL 2 license.

### **The main goal of a version control system**

- Simplify the handling of changing information streams
- Localization of each project developer's data

### **Data localization**

- Each developer has a local repository on their machine
- Changes are sent from the local repository to the remote repository
- Any developer can download new changes to continue their work

### **Standards and ethics**

- It is important to adhere to standards for code layout and working with the system
- Standards facilitate communication and understanding between developers
- Ethics and culture help to better understand each other

### **Types of version control systems**

- Centralized: code is stored on a server, all developers have access
- Cons: no local repository, difficult to access resource
- Decentralized: each developer has their own repository, quick recovery

### **Interoperability with other systems**

- CVS and Subversion support
- Standard import and export tool - archives of series of versioned files

### **Git concepts**

- Fork: a remote copy of the repository on the server
- Clone: a local copy of a remote repository
- Branch: a way to make changes and merge them with the rest of the code
- Work tree: a tree of source files to edit
- Index: a binary file with information about the files in the current branch
- HEAD pointer: a reference to the last commit in the current branchPractical Part

## Practical part

To use the git system you need to:
1. Install the git program on your system.
2. Configure the program and test its functionality locally
3. Register your account on GitHub
4. Create a local repository or copy the repository of an existing project
5. Write a README.MD file.
6. In case you are starting a project, create a remote repository
7. Commit changes locally
8. Submit changes to GitHub
9. Register developer accounts for your project
10. Give them a link to the project

There are many different commands that allow you to interact with the repository through the guide, below are a few schematics with different commands.

[The figure shows how to prepare a folder on the local computer for git.](ИндЛаб2.png)'



image:
  caption: 'Image credit: [get-started](ИндЛаб2.2.png)'

The diagram in Fig. 2 shows how the commands add, commit all, commit, reset, git reset head, git update index work.
The diagram below shows the difference between working with a local repository and a repository on GitHub.

image:
  caption: 'Image credit: [get-started](ИндЛаб2.3.png)'

1. The Hugo Blox website builder for Hugo, along with its starter templates, is designed for professional creators, educators, and teams/organizations - although it can be used to create any kind of site
2. The template can be modified and customised to suit your needs. It's a good platform for anyone looking to take control of their data and online identity whilst having the convenience to start off with a **no-code solution (write in Markdown and customize with YAML parameters)** and having **flexibility to later add even deeper personalization with HTML and CSS**
3. You can work with all your favourite tools and apps with hundreds of plugins and integrations to speed up your workflows, interact with your readers, and much more

[//]: # ([![The template is mobile first with a responsive design to ensure that your site looks stunning on every device.]&#40;https://raw.githubusercontent.com/wowchemy/wowchemy-hugo-modules/main/starters/academic/preview.png&#41;]&#40;https://hugoblox.com&#41;)

## Crowd-funded open-source software

To help us develop this template and software sustainably under the MIT license, we ask all individuals and businesses that use it to help support its ongoing maintenance and development via sponsorship.

### [❤️ Click here to become a sponsor and help support Hugo Blox's future ❤️](https://hugoblox.com/sponsor/)

As a token of appreciation for sponsoring, you can **unlock [these](https://hugoblox.com/sponsor/) awesome rewards and extra features 🦄✨**

## Ecosystem

- **[Bibtex To Markdown](https://github.com/GetRD/academic-file-converter):** Automatically import publications from BibTeX

## Inspiration

[Learn what other **creators**](https://hugoblox.com/creators/) are building with this template.

## Features

- **Page builder** - Create _anything_ with no-code [**blocks**](https://hugoblox.com/blocks/) and [**elements**](https://docs.hugoblox.com/reference/markdown/)
- **Edit any type of content** - Blog posts, publications, talks, slides, projects, and more!
- **Create content** in [**Markdown**](https://docs.hugoblox.com/reference/markdown/), [**Jupyter**](https://docs.hugoblox.com/getting-started/cms/), or [**RStudio**](https://docs.hugoblox.com/getting-started/cms/)
- **Plugin System** - Fully customizable [**color** and **font themes**](https://docs.hugoblox.com/getting-started/customize/)
- **Display Code and Math** - Code syntax highlighting and LaTeX math supported
- **Integrations** - [Google Analytics](https://analytics.google.com), [Disqus commenting](https://disqus.com), Maps, Contact Forms, and more!
- **Beautiful Site** - Simple and refreshing one-page design
- **Industry-Leading SEO** - Help get your website found on search engines and social media
- **Media Galleries** - Display your images and videos with captions in a customizable gallery
- **Mobile Friendly** - Look amazing on every screen with a mobile friendly version of your site
- **Multi-language** - 35+ language packs including English, 中文, and Português
- **Multi-user** - Each author gets their own profile page
- **Privacy Pack** - Assists with GDPR
- **Stand Out** - Bring your site to life with animation, parallax backgrounds, and scroll effects
- **One-Click Deployment** - No servers. No databases. Only files.

## Themes

Hugo Blox and its templates come with **automatic day (light) and night (dark) mode** built-in. Visitors can choose their preferred mode by clicking the sun/moon icon in the header.

[Choose a stunning **theme** and **font**](https://docs.hugoblox.com/getting-started/customize/) for your site. Themes are fully customizable.

## License

Copyright 2016-present [George Cushen](https://georgecushen.com).

Released under the [MIT](https://github.com/HugoBlox/hugo-blox-builder/blob/main/LICENSE.md) license.