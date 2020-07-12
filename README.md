This repo will house all the html, css, and javascript files for the website, but no backend


Important Commands


      ssh -l meh201 -p 22 unixs.cssd.pitt.edu
  
  
      sftp meh201@unixs.cssd.pitt.edu:public/html/ <<< $'put file_name_goes_here'
  


  How to push code to the server

  1.) Make the edits you want 

 	---- Make sure you are in the correct folder in the terminal for commands 2 and 3 ---- (cd ~/Jottacloud/BalletClubWebsite/ballet-website/)
  2.) zip them up using this command

  	tar -cvf website.tar css js fonts index.html Logo10.png
  						 ^files and folders to include in the compressed file

  3.) Push your changes to the git
  	a.) git add .
  	b.) git commit -m "description of changes you made"
  	c.) git push
  		1.)enter information your prompted for

  4.) send the tar file to the server 

  	sftp meh201@unixs.cssd.pitt.edu:public/html <<< $'put website.tar'
  	
  	-------
  	to send to ballet server:
  	sftp meh201@unixs.cssd.pitt.edu:../../../s/o/sorc/public/html/ballet <<< $'put website.tar'

  5.) ssh into the pitt server

  	ssh meh201@unixs.cssd.pitt.edu

  6.) navigate to the correct directory
  	
  	cd public/html
  	
  	------
  	to go to ballet server:
  	cd ../../../s/o/sorc/public/html/ballet

  7.) extract the tar file
  	
  	tar -xvf website.tar

  8.) profit 



