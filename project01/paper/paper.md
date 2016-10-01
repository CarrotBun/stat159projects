# STAT 159 Project 1 Paper  
![](https://raw.githubusercontent.com/ucb-stat159/stat159-fall-2016/master/projects/proj01/images/stat159-logo.png)  

##ABSTRACT  
**Author**: Lily Li  

---  

This paper contains details on how Makefiles, Git, Pandoc, and Markdown come together to create a productive workflow for reproducible projects. There is also comments and feedback on the attempt of this project.   

Sections of this paper are divided into:  
	0. Abstract  
	1. Introduction  
	2. Discussion  
	3. Conclusions

For more information about the scope and purpose of this project, refer to [here](https://github.com/CarrotBun/stat159-fall-2016/blob/master/projects/proj01/proj01-essay.Rmd). 

 
##INTRODUCTION

---

### Makefiles
**Explain what is a Makefile and its role in the RR workflow.**  
A Makefile is a file with commands used in the terminal. It also links files and directories together and describes the way they interact. It's extremely useful when a certain source file is modified because the linking in makefiles allow for updates. 


### Git
**Explain what is Git, and its role in the RR workflow.**  
![](https://raw.githubusercontent.com/ucb-stat159/stat159-fall-2016/master/projects/proj01/images/git-logo.png)  
![](https://raw.githubusercontent.com/ucb-stat159/stat159-fall-2016/master/projects/proj01/images/github-logo.png)     
Git is a version control system. It allows for snapshots and merged versions of your project. Along with Github, it allows for collaborative and sharable data because it takes into account of multiple timelines and users and allows for online sharing. It's especially useful when you have multiple authors working on the same project and everyone is working at a different pace. It will combine all the edits effectively without the users worrying about overlaps or undue deletions.


### Pandoc
**Explain what is pandoc.**  
![](https://raw.githubusercontent.com/ucb-stat159/stat159-fall-2016/master/projects/proj01/images/pandoc-logo.png)   
Pandoc is a file converter you can use directly through terminal. It works best when the input is Markdown because this is about the maximum of expressive format pandoc can convert seamlessly. 


### Markdown
**Explain what is markdown.**  
![](https://raw.githubusercontent.com/ucb-stat159/stat159-fall-2016/master/projects/proj01/images/markdown-logo.png)   
Markdown is a text editor designed to be able to be easily converted into other formats. It allows for some formatting such as titles, lists, bolding, italicizing, and indentions but not overly expressive formatting such as margins and colors. 

  
##DISCUSSION

---  

### Project Narrative
**Write a narrative about how you worked on this project.**  
Before I started, I observed the structure of the file organization in the instructions. I then created a new directory in my stat159 local folder, named "projects" to contain all my current and future projects.  
  
I created a new directory "project01" to contain this particular project. Once inside project01, I initiated Git and added a .gitignore file. I also made a Makefile to create some of the subdirectories. It was especially useful for the sections of the paper. On Github, I created a new repository for this project and connected the two. I added my .DS_Store file to my .gitignore because it's just Mac's file ordering information and irrelevant to Github. Whenever I had changes in my files, I would add and commit them. Then I would push them to update my Github backup. 

### Project Resources
Besides the resources mentioned here (makefiles, git, pandoc, markdown), I obtained help from help pages of Github and Makefiles.   

##CONCLUSION

---

**"Easy" Parts**  
The easy part was creating the files and directories.  

**Challenging Parts**  
Some difficulties include connecting my github repository to my local file. There were some permission issues that I had to resolve.   

**What things you were stuck with?**  
I was stuck on creating a Makefile that would generate the "00-abstract.md, 01-introduction.md, etc." in one command. 

**Did you work with and/or get help from someone else?**  
I worked by myself but received help from CS people who were familiar with Github and Git.  

**How much time did it take?**  
I worked on this project on and off for a few days.   