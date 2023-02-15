# Welcome

Welcome to the official website of the "Introduction to Git" VU workshop organized by *MSc Mentor Program (2023)*!
:wink:

This tutorial contains a series of lessons that will teach you the basics of Git. It is intended for beginners who have never used Git before, but it can also serve as a refresher course for those who have used it in the past.

Hopefully, you landed on this page after opening the link given to you on the day of the event, or as one of the pre-session reviewers, if you stumbled upon this page by accident please bare in mind this website was designed to go hand-in-hand with a physical workshop and isn't meant to be used as a standalone resource. 

Find the slides for the workshop at [this google drive link](https://docs.google.com/presentation/d/19a3nwVZPFIR5HiEy42X1cYcuCPnH8ggN3B_XZ61tvss/edit?usp=sharing).

## :octicons-git-merge-16: What is Git?

[Git](https://git-scm.com/) stands for "Global Information Tracker", which is a free and open-source distributed **version** control system** that allows you to track changes to files and collaborate with other people on projects, both large and small. 
It's a formidable tool, that is used by many developers and researchers to manage their code and data. In this tutorial, we will be covering the fundamentals of Git, and how to use it to manage your projects.

### Why Is Git Useful?

The benefits of Git can be summarised as follows:

* **Version Control**: Git allows you to track changes to files and revert to previous versions if needed.
* **Collaboration**: Git allows you to collaborate with others on projects.
* **Backup**: Git allows you to back up your files to a remote server.
* **Access Anywhere**: Git allows you to access your files from any computer with an internet connection.

#### What We **WILL** Be Covering In This Workshop

In this workshop we will be learning the basics of Git, such as how to:

* Create a GitHub repository
* Initialize a repository
* Add files to the staging area
* Commit changes
* Push changes to a remote repository
* Pull changes from a remote repository
* Resolve merge conflicts
* How to undo changes to a file to a previous commit


#### What We **WON'T** Be Covering In This Workshop

Git is a very complex piece of software, with many features which are used by professional developers for managing large, multi-person projects.
Many of these features are beyond the scope of this workshop, and will not be covered. These features include:

* **Branching**: a very powerful feature of Git, which allows you to create multiple versions of your project (it's also the inspiration for the Git logo). While this would be commonly used for small projects as well as large ones, it is not fundamental and is more easily tackled once you have a good understanding of the basics of Git. 

* **Collaboration**: multi-developer codebases, where various developers can update the same code simultaneously, are essential for industry and research. It is also the reason why Git was created and is so widely used. However, this requires a more complex workflow, which is beyond the scope of this workshop. Having a solid understanding of the basics of Git is a prerequisite for learning how to collaborate with others on projects.

## :octicons-mark-github-16: What is GitHub?

[GitHub](https://github.com/) is a website that hosts Git repositories. It is a very popular website that is used by many developers and researchers to host their code and data. You can think of it as a Dropbox, Google Photos or iCloud but for code. In this workshop, we will be using GitHub to host our repository.

!!! warning "Not Mass Storage!"
    GitHub isn't a mass storage solution, GitHub will reject any file larger than `100 `MB, and if the size of the repository exceeds `1 GB` GitHub will reject the repository or stop accepting updates.
    For code, this is usually not a problem (this equates to millions of lines of code), but if you are planning on using GitHub to host large files (e.g. images, videos, etc.) you should consider using a different service.



## What Will We Be Doing?

In this workshop, we will be using Git and GitHub to manage a project. Git is designed to work on projects of any size, from a simple website to a large software project. As such, the best way to learn Git is to use it on a project.

We crafted three possible projects, which we (hopefully) will get to after the pizza break :pizza:.

### The Three Choices Are:

!!! easy "Easy &emsp; [MNIST Classifier](project/mnist/)"
    Coding a basic [MNIST](https://en.wikipedia.org/wiki/MNIST_database) classifier using [Pytorch](https://pytorch.org/). 
    

!!! medium "Medium &emsp; [Minecraft Clone](project/minecraft/)"
    Coding a simple game using the [Ursina game engine](https://www.ursinaengine.org/) (Minecraft clone).
    
!!! hard "Advanced &emsp; [Personal Website](project/website/)"
    Building and publishing a simple personal website using [MkDocs](https://www.mkdocs.org/) with [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) (the same used for the website you are currently using).
    The website will be hosted on GitHub for free and you will be able to view the website from any browser.

## Disclaimer

This is a companion website for the "Learning Basics of Git" workshop, which is an in-person event, if you are reading this website but have no idea about the workshop, please bare in mind this website was designed to go hand-in-hand with a physical workshop and it's not meant to be used as a standalone resource.

When writing this tutorial I tried to make no assumptions about the prior knowledge of the reader, as such I also cover briefly [pre-requisites](get_started/). Realistically, these should already be understood by anyone who is attending the workshop, but I have included them for completeness.
Some programming experience is also assumed, but I have tried to keep the code as simple as possible.

This workshop is designed to be a fun introduction to the basics of Git and GitHub. 

**It is** intended for beginners who have never used Git before, but it can also serve as a refresher course for those who have used it in the past. 

**It is not** intended to be a comprehensive guide to Git and GitHub. If you are interested in learning more about Git and GitHub I recommend checking out the following resources:

* [Git Documentation](https://git-scm.com/doc)
* [GitHub Guides](https://guides.github.com/)
* [Git Guides](https://github.com/git-guides)
* [Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials)
* [Git Book](https://git-scm.com/book/en/v2)
* [Introduction To GitHub](https://github.com/skills/introduction-to-github)

This tutorial was made in **February 2023** and won't likely be kept up to date beyond the date of the workshop.

<center>
## Let's Start! :wink:

[You can now move to the first session](get_started/index.md)
</center>