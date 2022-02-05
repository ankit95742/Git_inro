![Image](https://fedingo.com/wp-content/uploads/2021/03/git-clone-730x410.png)
# Git_intro
 ---
### In this blog post, we are going to learn some basic commands of Git and why we should use Git.

> A topic we are covered in this blog is 
1. What is a git?
      1. What is a version control system?
      2. what are the benefits of using version control systems?
2. Why should you use a git?
3. What is different between a git and GitHub?
4. Understanding some basic commands of a git?
---
let's start
1. What is a git?

Git is the most commonly used version control system. Git tracks the changes that you made in your project from the starting date to the present date. It stores the history of your work. It allows you to go back to the history of your project and see what changes you made throughout your project. It also allows you to make changes in the project, makes collaboration easier, allowing changes by multiple people to all to be merged into one source.

Git is software that runs locally. Your files and their history are stored on your computer. You can also use online hosts (such as GitHub or Bitbucket) to store a copy of the files and their revision history. Having a centrally located place where you can upload your changes and download changes from others, enable you to collaborate more easily with other developers. Git can automatically merge the changes, so two people can even work on different parts of the same file and later merge those changes without losing each other’s work!

i. What is a version control system?

> Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help the software team to manage changes to source code over time. In software development source code change many times if we want to what changes are made when this change is made, what person made these changes. These are all question answers in finding if we use a version control system.

ii. what are the benefits of using version control systems?

> The version control system helps manage the source code for the software team by keeping the track of all the code modifications. It keeps track of all the changes made to the code. It will help you to compare the versions of the code. For experiment and making a new feature in a project with isolation version control system will help you to do that using the branching and after the new feature is made correctly then we add this to main source code using the merging.

---

2. Why should you use a git?

Because it's trank all the change that we made throughout the project. We can see that who made which change and Why this change is made. It provides all the history of your project. Allowing to work collaboratively. Software development projects usually require many people to work together. Git provided the developer with a systematic way of doing that. Git is open source and it's the Distribute version control system.

---

3. What is different between a git and Github?

![Image](https://blog.devmountain.com/hs-fs/hubfs/Imported_Blog_Media/Gitvs_Github-1c-750x321-1.jpg?width=600&name=Gitvs_Github-1c-750x321-1.jpg)

---

4. Understanding some basic commands of a git?

> Basic workflow
  Assume that I started the new project in my project directory. If I want to make a new git repository for my project. Then I use git init command for that.
  Then I use **git init** command for that.
  
  After that I make the new file like a **index.html**. And I want this file to store in repository?
  
  ![Image](https://miro.medium.com/max/673/1*MeoUmANEJmkpgFCGw6U_uQ.png)
  
  First I use the **git add index.html** command to move the file from working directory to staging area.
  Staging area is files that are going to be a part of the next commit.
  After we use **git commit** command to transfer the file for staging area to repository.
  
  **git clone**
  This command is used to target an existing repository and create a copy of the target repository and save it to a local repository.
  
![Image](https://bobbelderbos.com/assets/git-clone.png)

 **git push**
  This command is used when we want to deploy our work into a remote repository.
  
  **git pull**
  This command is used when we want the commits that are not present in our local repository or our team member    made some commits into report repository that we want into our local repository then we used git pull command.
  
  ![Image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRNHrVjf8gmbmwlcuq9C4RN86H8-U8-v8L-HQ&usqp=CAU)
 
 ---
 
> Image Sources:

 1. https://blog.devmountain.com/hs-fs/hubfs/Imported_Blog_Media/Gitvs_Github-1c-750x321-1.jpg?width=600&name=Gitvs_Github-1c-750x321-1.jpg
 2. https://miro.medium.com/max/673/1*MeoUmANEJmkpgFCGw6U_uQ.png
 3. https://bobbelderbos.com/assets/git-clone.png
 4. https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRNHrVjf8gmbmwlcuq9C4RN86H8-U8-v8L-HQ&usqp=CAU

> Reference list:

 1. https://blog.devmountain.com/git-vs-github-whats-the-difference/#:~:text=GitHub%E2%80%A6-,what's%20the%20difference%3F,help%20you%20better%20manage%20them.
 2. https://www.simplilearn.com/tutorials/git-tutorial/what-is-git
 3. https://www.atlassian.com/git/tutorials/what-is-git
 4. https://www.nobledesktop.com/learn/git/what-is-git
