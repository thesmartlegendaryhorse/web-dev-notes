 # Git 
 ## what does it mean 

 
- so basically git is a save button for files and directories its what we call a version controll system
a save in the text editor might work for 1 file but sometimes you gotta create alot of versions of the same file and it might become a little hard to remember right so
git gives you the perfect solution with historical record of each save , as a developer thats really usefull to have since it lets you see how your project is growing and to 
restore previous versions if some kind of chage make it not work (most likeley lol)and once connected to the network git allows you to push your changes into github ( literally where this is located ) or other alternatives like Bitbucket , Beanstalk or Gitlab for sharing and collaborating with other devs 
while git runs on our devices  locally github is a remote storage facility on the web for all coding projects so by learning git we will get to showcase our portfolio on github its important cuz all companies consider git as an essential skill to have a modern web dev or  a dev in general. 

## Assignment 
  - explain the difference between git and github 
  
## Getting Started section of Pro Git
 so what is a version controll you gonna ask and why should we care , a version control is a system that records changes to a file or a set of files overtime so that you can recall specefic versions later.
if you are web designer and you want to keep every version of an image or a layout a version control system (VCS) is a wise thing to use.
It allows you to rewind kind of the selected files to previous state , revert the ENTIRE project to a previous state , compare the changes etc etc (even see who modified what and more ).
Using a VCS also generally means that if you screw up or lose files you can recover them gg ez and you get all this for very little overhead so win win.

# Local Version Control Systems
 the most common approach of people to a version control method is to copy files into another directory , but it is also incredibly error prone.
its kinda easy to forget which file is in which directory right and accidentally write to the wrong file or copy over files you dont mean to and make a big mess like my love life.
to fix this problem , programmers long ago developed local VCSs that had a database that kept all the changes to files under revision control.

## Figure 1, Local version cotrol diagram
 one of the most popular VCSs tool was a system called RCS, which is still distributed with many computers today. RCS works by patching differences between files (sets) in a special format on disk ,it can then recreate what any file looked like at any point of time by adding up all the patches.

# Centralized Version Control System
 the next bg problem people get is that they need to collaborte with other devs on other systems we cant stay local forever right . to deal with this problem, Centrelized Version Control Systems (CVCSs) were developed. 
these systems (such as VCS, Subversion, and Perforace) have a single server that cintains all the versioned files, and a number of clients that ch eck out files from that central server.
for many years, this has been the standard for version control.

## Figure 2. Centralized version control diagram
 this setup offers many adventages, especially over local VCSs. for example, everyone knows to a certain level what everyone else is doing on the project. Administrators have nice control over who can do what to put some order into that mess, and its far easier to administer a CVCS than it is to deal with local databases on every client.

BUt this settup got some serious problems. the most obvious one is that one problem with the centralized server for example it goes dow for 1h, then during that hour nobody can collaborate at all or save versioned changes to anything they're working on which is a real letdown right but there is a worse senario.
if the hard disk of the database becomes somewhat corrupted, and proper backups havent been kept, you lose absolutely everything god damn, the entire history of the projects except whatever is left in the local machines of people who used that database.
Local VCSSs suffer from the same problem but CVCSs failiure  can affect multiple people rather tha just the local machine with VCSs so yeah higher risk for CVCSs but better reward.

# Distributed Version Control Systems

 this is where Distributed Version Control Systems (DVCSs) step in. 
In a DVCS like Git (the goat) , Mercurial or Darcs, clients fully mirror the repository including its full history so if any server dies , amd these systems were collaborating via that server, any of the client repos can be copied back up to the server to restore it like it never happned.
every clone is a really full backup of all the data which is super cool.
## Figure 3. Distributed version control diagram

 many of these systems deal pretty well with having several remote repos they can work with, so you can collaborate with different groups of people in differet ways at the same time on the same project. this allows to set multiple types of workflows that aren't possible in centralized systems , such as hierarchical models.
   
# Git basics 

heheee now thats where serious stuff starts, so basically im gonne just try to put a screenshot of all commands needed plus like highlight the ones i use to publish this repo like add changes and everything just like its working for text it works even better for code which is the main goal of github lol anyway be back in a minute




<img width="701" height="668" alt="git_cheatsheet" src="https://github.com/user-attachments/assets/29f13baf-a861-435c-ad07-660128baa7eb" />



nice so it worked im lowk a genius cuz i figured it by myself anyway erm oh in few minutes it will be 14th august which is the birthday of a friend so i have to not forget, anyway i got a lil off topic but anyway 
so the lines i use are 



<img width="648" height="117" alt="commands_of_git_that_i_use_for_noting_my_work" src="https://github.com/user-attachments/assets/e40754c9-397e-4dc5-ba64-07186fbef1ac" />




- plus the git push and pull when i need to send what i edited on my pc to github or the opposite in order of course

