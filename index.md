---
title: Home
layout: home
nav_order: 1
permalink: /
---

# Git & GitHub Documentation Wiki
## Group 01 - Riley, Alex, Nova, Traigen, and Gus!

Welcome to our Git & GitHub documentation wiki!

This website serves as a quick-reference guide for game development programmers and artists looking to learn about Git, GitHub, and version control.

Our documentation covers Git fundamentals, common commands, branching, merging, and collaborative workflows, with practical examples relevant to game development.

## The Role of Version Control in Software Development

Version control, also known as revision control or source control, is the management of changes to documents such as computer programs.

In software development, it helps developers manage different versions of a project, collaborate with others, recover older versions, and safely test new features.

Unlike simply using `Ctrl + Z`, version control allows developers to undo changes made weeks ago, restore older versions of files, and manage changes made by other team members.

### Pros of Version Control

Version control provides developers with much more than just the ability to undo changes.

- Tracks changes made to a project over time.
- Makes it easy to restore older versions of files.
- Allows developers to work on new features while fixing bugs in older versions.
- Helps multiple developers collaborate without overwriting each other's work.
- Allows distributed teams to work together on projects from anywhere in the world.
- Makes testing new features safer.
- Helps identify when bugs were introduced.

Version control is useful for both individual developers and teams, providing a safety net throughout the development process.

### Types of Version Control

#### Local Version Control

Stores different versions of files on one computer. It is simple, but not ideal for team projects.

#### Centralized Version Control

Stores the main project on a central server. Developers connect to the server to access and update files.

Examples include:

- Perforce Helix Core
- Subversion (SVN)
- CVS

#### Distributed Version Control

Each developer has a full copy of the project and its history. Developers can work independently and synchronize their changes.

Examples include:

- Git
- Mercurial

### Version Control in Game Development

Version control is especially useful in game development, where programmers and artists often work on the same project.

For example, in a Unity project:

- Programmers can track changes to scripts and game mechanics.
- Artists can manage changes to textures, models, and other assets.
- Team members can work on different features without directly overwriting each other's work.
- Developers can restore earlier versions if a new feature introduces problems.

Different version control systems are commonly used in game development:

- **Git:** A free, open-source distributed version control system commonly used in software development and game projects.
- **Unity Version Control:** A version control solution designed for game development teams, including programmers and artists.
- **Perforce Helix Core:** A centralized version control system widely used by larger game development studios.
- **Subversion (SVN):** A centralized version control system that can be used by smaller development teams.

## What Is Git?

Git is a free, open-source distributed version control system used to track and manage changes to files throughout a project's development.

Git allows developers to save different versions of their projects, restore previous changes, and collaborate with others.

When combined with hosting platforms like GitHub or GitLab, Git also allows developers to share their work with teams remotely.

### How Does Git Work?

Git tracks changes through repositories, which contain a project's files and their version history.

When developers make changes, they can create a **commit**, which acts as a save point for the project.

Each commit records a snapshot of the project at that point in time, allowing developers to review previous versions and recover earlier work.

Git also supports **branches**, allowing developers to work on new features or bug fixes independently before merging their changes into the main project.

Because Git is distributed, developers can work offline and synchronize their changes with remote repositories when connected.

### Pros of Git

- **Free and Open Source:** Git is available without purchasing a license.
- **Version History:** Developers can create commits and return to previous versions of their projects.
- **Offline Development:** Developers can commit changes and review project history without an internet connection.
- **Branching and Merging:** Developers can experiment with new features without directly affecting the main project.
- **Fast Operations:** Most Git operations are performed locally.
- **Collaboration:** Multiple developers can work on the same project and combine their changes.

### Cons of Git

- **Learning Curve:** Git commands and workflows can be difficult for beginners and non-programmers to understand.
- **Large File Handling:** Git is not optimized for frequently changing large binary assets, although Git LFS can help.
- **Binary File Conflicts:** Files such as textures, models, and audio cannot always be merged automatically.
- **File Locking:** Git does not include built-in file locking, although Git LFS provides locking functionality.
- **Repository Size:** Large projects with extensive file histories can require significant storage space.

### Git in Game Development

Git is useful in game development because programmers and artists often need to collaborate on the same project.

For example, in a Unity project:

- Programmers can track changes to C# scripts and game mechanics.
- Team members can create branches to develop new features independently.
- Developers can restore earlier versions if a new feature introduces bugs.
- Artists can manage textures, models, and audio files, although large assets may benefit from Git LFS.

Git is especially useful for managing code, but game development teams should consider how they will handle large binary files and merge conflicts.

### Git vs. GitHub

Although Git and GitHub are often used together, they serve different purposes.

- **Git:** A version control system that tracks and manages changes to files.
- **GitHub:** An online platform that hosts Git repositories and provides additional tools for collaboration.

Git can be used entirely on a local computer without GitHub.

GitHub provides features such as pull requests, code reviews, and remote repository hosting that make collaborating with others easier.

## Additional Resources

- [Pro Git - About Version Control](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)
- [Pro Git - What Is Git?](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F)
- [GitHub Docs - About Git](https://docs.github.com/en/get-started/using-git/about-git)
- [Pro Git - A Short History of Git](https://git-scm.com/book/en/v2/Getting-Started-A-Short-History-of-Git)
- [GitHub Docs - About Git Large File Storage](https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-git-large-file-storage)
- [Unity Documentation - Unity Version Control](https://docs.unity.com/en-us/unity-version-control)
- [Perforce - Helix Core](https://www.perforce.com/products/helix-core)

## Team Member Biographies

<!--
Each team member must add their own short paragraph biography
to this section through a separate feature branch and pull request.

Add biographies below this comment.
-->
