# Ballet Website

This repository contains the static html/css/js website for the ballet club at pitt

The website is hosted on pitt servers [here](http://www.pitt.edu/~sorc/ballet/).

If you are a pitt student/faculty member you can edit the files on the server if you are granted the correct permissions
by sorc.

## Getting Started

The first thing you will do, regardless of system is create a [github account](https://github.com/join) and then requesting edit permissions to the repository from me: jacob.heuman@gmail.com


Windows setup will require an additional step, namely downloading a program called

Git bash

<a href="https://gitforwindows.org/">
<img src="https://gitforwindows.org/img/git_logo.png" alt="Git Bash Logo" data-canonical-src="https://gitforwindows.org/img/git_logo.png" width="200" height="200" />
</a>

### Instructions

- Open git bash (windows) or terminal (macos) and navigate to where you would like the folder to be

    ```cd Documents```
    

- run this command to "clone" this repository, this will download all the files


    ```git clone https://github.com/theheuman/ballet-website.git```
    

- run setup script


    ```chmod +x setup```
    
    ```./setup```
    

- Download a program you will use to edit the website.
    
    - Maya used [sublime]()
    - [Atom]()
    - [Vim]() Dont do this, or you'll find yourself the subject of the [vim meme](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fpics.conservativememes.com%2Fwhen-you-finally-exit-vim-you-know-im-something-of-41849715.png&f=1&nofb=1)
    - [Emacs]() Dont do this either, lol
    
    - I like using jet brain's IDEs and you can download [pycharm]() for free
    
    Of course you can also use the text editors your OS already has installed 
    
    - Notepad (Windows)
    - Text Editor (MacOs) #FIXME name of mac program
    
- Now that you have a text editor, use it to open the folder you just downloaded ~/Documents/ballet-website


## Workflow

 1.) Sync with changes made by others to this repository
 
     git pull
     
 2.) Make edits
 
 3.) Push changes to server

    
    ./deploy_to_server
    
 
 4.) Push changes to this repository


  	- git add .
  	- git commit -m "description of changes you made"
  	- git push
  		1.)enter information your prompted for


2.) zip them up using this command

  	tar -cvf website.tar css js fonts index.html BALLETCLUBLOGO.png
  						 ^files and folders to include in the compressed file

  3.) Push your changes to the git
  
  	- git add .
  	- git commit -m "description of changes you made"
  	- git push
  		1.)enter information your prompted for

  4.) send the tar file to the server 
  	
  	-------
  	to send to ballet server:
  	sftp meh201@unixs.cssd.pitt.edu:../../../s/o/sorc/public/html/ballet <<< $'put website.tar'

  5.) ssh into the pitt server

  	ssh meh201@unixs.cssd.pitt.edu

  6.) navigate to the correct directory
  	
  	------
  	to go to ballet server:
  	cd ../../../s/o/sorc/public/html/ballet

  7.) extract the tar file
  	
  	tar -xvf website.tar

  8.) profit 



