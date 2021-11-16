# Git!  
## What is Git?  
Git is a version control system.  
## What is a version control system?  
A version control track and manage changes to code.  it does this by allowing you or your team to:
* Go back to older versions of your code before changes were implemented. 
* Track changes in code and who changed the code. 
* Collaborate between team members working on the same project.
* Allows coders to leave breif messages as to what changes were made.

### Editing git code on your computer and sending it back to git.
you can import the current version of your code from git to your computer.  From there you can edit the code using a text editor.  When this is done the code on git does not change until you tell it too.  
#### How to import/edit/send back code.
1. Enter the directory you would like the code to be placed through the terminal.
2. Type `git clone` then copy and paste the file address.  this brings the code to your computer in it's current state.
3. Open the file in terminal using `cd` name of file.
4. Open whatever text editor you have installed.
5. Edit your code as you wish
6. When done editing you add the file to the terminal with `git add` and the file name. 
7. You then commit the file by typing `git commit` at this point you can add a `-m` to add a message to your edits. The file still has not been fully sent back to your git.
8. To add the new version to your get you must push the commit.  do this by typing `git push origin main` this will send your new version and the message you added back to git where git will add this version as the current working version or "head".  


[main](reading-notes.md)
