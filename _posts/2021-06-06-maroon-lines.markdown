---  
layout: post  
title:  "Maroon Lines"  
---  
<img src="/assets/img/logo.png">
### Introduction 
Maroon Lines is a source code editor with in-built version controlling.    
    
"Why not just use Git? That's the holy grail for version controlling!" - This is true. I believe so too. However, Git is more suited for projects. Maroon Lines tries to solve the problem of versioning for standalone files.     
    
Say you fire up your unregistered Sublime Text to solve a LeetCode or Kattis problem set. You write code to solve it, submit it and see it spectacularly fail. You go back to the drawing board to change your logic, and submit again. Fails again.   
  
You realise that the previous version was on the right track and just needed a little change. Unfortunately, you can't just jump back to a previous version - unless you had initialised a git repo, which you did not. Who would initialise a repository for a single file?    
    
Maroon Lines solves this problem by saving a version every time one saves his/her file. In addition, it also provides a intuitive way for the programmer to jump between versions easily - paving a way for one to store and view multiple solutions to a problem set in a single file.  
  
### Usage  
Download the installer for either Windows/MacOS [here](https://github.com/jaivigneshvenugopal/maroon-lines/releases) before beginning to use the software.  
  
The application opens like any other text-editor, however, its specialty raises its head when it starts saving content. Using the 'Save' or 'Save As' functionality implicitly saves a snapshot of the current state of the file.  
  
<img src="/assets/img/1.gif">  
  
Every node represents a version of the file, and no two nodes are alike.  
  
### Accessing Versions  
To access specific/previous versions, click on respective nodes or use the following shortcuts:  
###### Windows  
```  
Alt + Up/Down/Right/Down   
```  
###### MacOS  
```  
Option + Up/Down/Right/Down  
```  
<img src="/assets/img/2.gif">  
  
#### Branching  
To branch off from a file's edit history, move to a specific version and start editing. Follow the aforementioned instructions to save the new version.  
  
<img src="/assets/img/3.gif">  
  
#### Implicit Features  
The versions are saved offline, which means that the versions exist even after the application is closed. Therefore, it is possible to leave the code on a certain node and come back later on to work on it. All versions will be retained.  
  
#### Bottlenecks  
Due to the way the application is designed, it is necessary to change the file's name or location only through the application. If not, renaming the file or moving it to a different location will break the link between the file and its history.  
  
### Thoughts  
I started this project right after graduation, and the main motivation was to create and have something to my name. I have done numerous other projects, however, they mainly served as school projects and work done for my internships. This was different. I needed to know I was capable of planning and building something from the ground up.   
  
The idea struck when I was practicing coding questions on Kattis - and realised how I had to change logic for solutions often. I felt that an application like this would allow programmers like me to do version controlling without having to touch the terminal.  
  
I've dabbled with web applications, however, I wanted to try building a desktop application - in Python. Once I've convinced myself that I would work on this full-time for some time, I started researching on available technologies before diving head in.  
  
This took 3 months to build, and it was 3 months of full-time work. I was starting my graduate studies in 4 months and saw this as a great opportunity to invest my time in for the duration.
   
<p align="center">  
<img src="assets/img/1.png">  
</p>  
  
I am most proud of Maroon Lines among all other projects I've worked on - and I believe it came out amazing :)
