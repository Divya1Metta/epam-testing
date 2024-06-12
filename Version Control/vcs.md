# Fundamental concepts of version control
 
The operating system, which implies sharing the folder via network. Let's imagine that I want to share some of my code with the team. We can do is share some folder or the network and edited at the same time in the defined network location. But what problems could be slipped to where? Is the last one to save the file overrides the changes made by the other person? If me and other person are simultaneously editing the same file, the first safe will override the original file and then the second safe will consequently overwrite the previous save and this is completely unacceptable for us because it won't let us save all the changes made by everyone who is participating in the development
of a specific project. We could take a step further and move on using some sort of cloud storage.

We could install Dropbox, one drive, Google Drive or Yandex disk, but we will still be faced with the issue of file synchronization. This means that more people are modifying the same file at the same time. The system cannot understand which modifications are correct and we should not. 

Mainly we changes are correct in which can be deleted. So the system ask the humans to make that choice. But imagine that we have very, very many files and were forced to make such choices daily. This workflow is not suitable for us. It may be applicable for some binary documents possible in Microsoft Word files or access precious.


Maybe a power point presentation? How it's definitely wrong for working with code, working with programming language files. I think in general what could be the requirements? 

## What could be the goals of a version control system? what makes a good version control system and what it must be able to do


It must be able to create some kind of **backup** as well as how to restore itself from the back up. 

It should be able to handle is the **synchronization** of work of multiple developers. 

being able to **cancel some of the changes**. In other words, click controls that repaired the notification. 

If I did something wrong, or overestimated myself and decided to continue the next day, I should be able to quickly  **rollback** the
changes I have made. 

the ability to track changes and **change ownership**,meaning the people who made these changes. I want to be able to clearly understand
**who and when** made specific changes. 


Fixing things helps to understand the revision history, and it's extremely convenient feature that should really be in every version control server.


The first one is **sandbox** in these debility, crates and boxes, which type of isolated
system which can be used to test something you something **we're not sure about yet**, so we have some folder where we store the final version and would not be embarrassed to show it to the customer coworkers. And there is a certain directorywhere I conduct my experiments, and I feel like trying something new. A new version of library or some new algorithm, but I'm not ready to share it yet, so I'm not
responsible for his quality.

But I need some place to store it and branching's ability to create separate branches and then to merge them.

There are many different version control systems out there. They probably appeared at the same time as programming itself. And if it will take a look at the market, we will see that these systems can be split in several categories using certain criteria and the very first
criteria we can apply to form these categories is the **flow of how exactly these systems work with files**. We can define to measure **popular strategies** here. The first one is called **lock, modify, unlock and the second one is copy and modify,merge**. 


