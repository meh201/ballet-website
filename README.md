# Ballet Website

This repository contains the static html/css/js website for the ballet club at pitt

The website is hosted on pitt servers [here](http://www.pitt.edu/~sorc/ballet/).

If you are a pitt student/faculty member you can edit the files on the server if you are granted the correct permissions
by sorc.

## Getting Started

I've also made a [youtube video tutorial](https://youtu.be/sPD_pM-jAdo) on how to get started, it will step you through getting started and some common changes


The first thing you will do, regardless of system is create a [github account](https://github.com/join) and then requesting edit permissions to the repository from me: jacob.heuman@gmail.com


Windows setup will require an additional step, namely downloading a program called



<a href="https://gitforwindows.org/" target="_blank"><img src="https://gitforwindows.org/img/git_logo.png" alt="Git Bash Logo" data-canonical-src="https://gitforwindows.org/img/git_logo.png" width="50" height="50" /> Git bash</a>

### Instructions

- Open git bash (windows) or terminal (macos) and navigate to where you would like the folder to be

    ```cd Documents```
    

- run this command to "clone" this repository, this will download all the files

    ```git clone https://github.com/theheuman/ballet-website.git```
    
- change directory to the directory you just downloaded

    ```cd ballet-website```
    

- run setup script


    ```chmod +x setup```
    
    ```./setup```
    

- Download a program you will use to edit the website.
    
    - <a href="https://www.sublimetext.com/3" target="_blank" ><img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.juoSVspxa-tcDmyNFDxWlQAAAA%26pid%3DApi&f=1" alt="Sublime Logo" data-canonical-src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.juoSVspxa-tcDmyNFDxWlQAAAA%26pid%3DApi&f=1" width="20" height="20" /> Sublime</a> What Maya Used
    - <a href="https://atom.io/" target="_blank"><img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.8oH16cKZ5SnqQ_xTFktumQHaHa%26pid%3DApi&f=1" alt="Atom Logo" data-canonical-src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.8oH16cKZ5SnqQ_xTFktumQHaHa%26pid%3DApi&f=1" width="20" height="20" /> Atom</a>
    - <a href="https://www.vim.org/download.php" target="_blank"><img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.U1ebBdjloi5HABcKYTLbBAHaHa%26pid%3DApi&f=1" alt="Vim Logo" data-canonical-src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.U1ebBdjloi5HABcKYTLbBAHaHa%26pid%3DApi&f=1" width="20" height="20" /> Vim</a> Don't do this, or you'll find yourself the subject of the [vim meme](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fpics.conservativememes.com%2Fwhen-you-finally-exit-vim-you-know-im-something-of-41849715.png&f=1&nofb=1)
    - <a href="https://www.gnu.org/software/emacs/download.html" target="_blank"><img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.NHd_y1bhVYPfx9ynNaEjkgHaHa%26pid%3DApi&f=1" alt="Emacs Logo" data-canonical-src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.NHd_y1bhVYPfx9ynNaEjkgHaHa%26pid%3DApi&f=1" width="20" height="20" /> Emacs</a> Don't do this either, lol
    - <a href="https://www.jetbrains.com/pycharm/download/" target="_blank"><img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.mnNeAoyYzh41NjwBEGzCJgAAAA%26pid%3DApi&f=1" alt="PyCharm Logo" data-canonical-src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.mnNeAoyYzh41NjwBEGzCJgAAAA%26pid%3DApi&f=1" width="20" height="20" /> PyCharm</a> I like using jet brain's IDEs and the community edition is free forever (probably overkill for you, but its nice)
    It will also make this readme look pretty!
    
    Of course you can also use the text editors your OS already has installed 
    
    - Notepad (Windows)
    - TextEdit (MacOs)
    
- Now that you have a text editor, use it to open the folder you just downloaded ~/Documents/ballet-website


## Workflow

 1.) Sync with changes made by others to this repository
 
 ***This is super important, always do this before you start working***
 
     git pull
     
 2.) Make edits
 
 3.) Push changes to server and git
 
 During this step you will be asked for passwords multiple times, when you are typing it will look like nothing is happening,
 but I promise it is! Thats just how the terminal inputs passwords
    
    ./deploy
    

 4.) profit 



