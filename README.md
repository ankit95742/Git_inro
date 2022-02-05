![Image](https://fedingo.com/wp-content/uploads/2021/03/git-clone-730x410.png)
# Git_intro
 ---
### In this blog post we are going to learn some basic concept of Git and why we should use a Git.

> topic we are covered in this blog is 
1. What is a git?
      1. What is a version control system?
      2. what are the benifit of using version control systems?
2. Why should you use a git?
3. What is different between a git and github?
4. Understanding some basic concept of a git?
---
let's start
1. What is a git?

Git is the most commonly used version control system.Git tracks the changes that you made in your project from staring date to present date.It strore the history of your work.It allow you to go back to history of your project and see what change that you made throughtout your project.It also allow you to make changes in project, makes collaboration easier, allowing chages by maltiple people to all be merged into one source.

Git is software that runs locally. Your files and their history are stored on your computer. You can also use online hosts (such as GitHub or Bitbucket) to store a copy of the files and their revision history. Having a centrally located place where you can upload your changes and download changes from others, enable you to collaborate more easily with other developers. Git can automatically merge the changes, so two people can even work on different parts of the same file and later merge those changes without losing each other’s work!

i. What is a version control system?

> Version control, also known as source control, is the practice of tracking and managing changes to software code.Version control systems are software tools that help software team to mange changes to source code over time.
In the software development source code change many times if we want to what changes are made, when this changes is made, what person made this changes.this all question answer in find if we you a version control system.

ii. what are the benifit of using version control systems?

> The version control system helps manage the source code for the software team by keeping the track of all the code modification.
> It keeps track of all the changes that made to the code.
> It we will help you to comapre the versions of the code.
> For experiment and making new feature in project with isolation version control system will help you to do that using the branching and after the new feature is made correcly then we add this in to main source code using the merging.

---

2. Why should you use a git?

Because it's trank all the change that we made thougthout the peoject. We can see that who made which change and Why this change is made. It provide all the history of your project.
Allowing to work collcboratively. Software development projects usually require many peopel to work together. Git provided the developer with systemtic why of doing that.
Git is open source and it's the Distribute version control system.

---

3. What is different between a git and github?

![Image](https://blog.devmountain.com/hs-fs/hubfs/Imported_Blog_Media/Gitvs_Github-1c-750x321-1.jpg?width=600&name=Gitvs_Github-1c-750x321-1.jpg)

4. Understanding some basic concept of a git?

> Basic workflow
  Assume that I started the new project in my project directory. If I want to make new git repository for my project.
  Then I use **git init** command for that.
  
  After that I make the new file like a **index.html**. And I want this file to store in repository?
  
  ![Image](https://miro.medium.com/max/673/1*MeoUmANEJmkpgFCGw6U_uQ.png)
  
  First I use the **git add index.html** command to move the file from working directory to staging area.
  Staging area is files that are going to be a part of the next commit.
  After we use **git commit** command to transfer the file for staging area to repository.
  
  **git clone**
  This command is used to target an existing repository and create a copy of the target repository and save it to     local repository.
  
![Image](https://bobbelderbos.com/assets/git-clone.png)
