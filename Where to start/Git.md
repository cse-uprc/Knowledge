# Git
Git is something EVERY programmer will need to deal with at some point, even though it is never actually taught in any class.  
Hopefully this document will get you up and running, and remember that you can always ask questions if you run into any problems!  

## Setting up
If you are just getting started, I recommend starting off using Github Desktop. Traditionally Git is meant to be done from the command line, but this can be pretty intimidating and challenging, so starting off with [Github Desktop](https://desktop.github.com/) can be a much more approachable system (I still use Github Desktop when I'm on Windows).  
You can download Github Desktop [HERE](https://desktop.github.com/)  

If you maybe have a little knowledge already, or want to start going hard core, you can download [git](https://git-scm.com/downloads), and run the commands from the command line.  
You can download Git [HERE](https://git-scm.com/downloads)  


## The Basics  
(all key words will be in **_italics_**)  
In git you **_commit_** changes to the source code. Those changes are saved locally on your machine. Then using git you track the changes, and then can **_push_** those changes to a remote repository.  
So here is the most basic process for keeping track of your changes.  

0. Make the repository.  
a. This can be done on github or another website. its easiest to make the remote repository first.  
1. **_Clone_** the repository  
    a. This involves finding the https connection to the repo. If you are on Github, you can click on the green 'Clone or download' dropdown and open the repo in Github Desktop  
    b. Now you can save the repository locally, and then click 'Clone'  
2. Make changes  
    a. Make a file, make some changes and save them on your computer  
    b. when you go back to github desktop, and click on the screen, you should see your changes appear. If you don't, go back and make sure you saved your changes.
3. **_Commit_** changes  
    a. This is where the magic starts to happen. In the bottom left of Github Desktop you should see some text boxes. Those allow you to state what changes you made. It's good practice to give useful comments so that later on other programmers can see what changes you made with some quick line.   
    'Updated the first line of text' is an example  
    b. After giving a name to the commit. Click 'Commit to master'  
    c. Congrats you just made a commit
4. The **_Push_**  
    a. The commit you just made is only on *your* machine. To allow other people to access the changes you need to **_push_** them to a remote repository. You should see a 'Push origin' or something similar at the top of Github Desktop. Click that and all your changes are uploaded to the internet. (Noice)  
5. Get other changes  
    a. So changes have been made from another machine, and uploaded to the remote repository, and you want to get those changes. First, Click the '**_Fetch_** origin' button in Github Desktop.  
    b. If there are changes the button should change into a '**_Pull_** origin'. By clicking on that, all the changes will be saved onto your local machine.  
6. Keep using Git  
    a. Now just keep using git as you work. When you finish something, make a **_commit_**. Don't forget to **_push_** your work back to the remote repository.  
    b. It's also good practice to make sure you are always up to date with your code on your machine. So you should **_fetch_** and **_pull_** when you start working everyday.


## Be Better with Branches  
