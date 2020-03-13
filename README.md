# zemoso_training
## 1. First To Create Repository zemoso_training in our Github acoount

 Sign in your github account and create a repository named zemoso_training.

## 2. Create a local git repository in your home folder – first_git_repo

**mkdir first_git_repo**

**cd first_git_repo**

**git init**


**mkdir** : 
     	used to create a directory
	
	
**cd** : 
	   it is usedd to change our present working dirctory to specified directory
	   
	   
**git init** :
	       this command is used to initialize an git respository.
	       
	       

After executing this command we made our local repository named first_git_repo


## 3.Create a text file named hello_world in u  and copy text given text

**touch hello_world**

copy given data to this file using any editor like nano

**touch** : 
	  It is used to create files.

## 4.Commit to your local repository and push it to the Github repository

**git add hello_world**

**git status**

**git commit -m “initial commit”**

**git remote add origin url**

**git pull origin master**

**git push origin master**

we now commit hello_world file to our local repository first_git_repo

**git add** :
	    This command adds our files to the staging area.
	    
**Staging Area**:
		      This is the area or place between our working directory and commit area.This is where we organize 		      files which we intend to commit.
		      
**git status**:
		      This command gives describes which files are in staging area and working directory.
		      
**git commit**:
		      This command commits files in staging area where -m flag helps us add message to commit which helps in                       identifying commits.

Now to push our branch master to Remote Repository




**git remote add origin url of remote repository:**
				This command helps us to add our remote repository location(url) as origin which can be ued 				    to referenece our remote repository in future contexts
	

**git pull origin master:**
			This command is used to synchronize changes between our remote and local repository.
     			Where origin represents Remote Repository(git hub repository) and master represents local 				repository
			

**git push origin master:**
			      It is used to push our Local repository contents to Remote Repository.It pushes commits of     				   local repository to remote repository.
			      

## 5.Replace all "to" words in hello_world file by your name. Check git diff to make sure all to words have been replaced and make another commit and push it to Github.

We replace all to words in hello_world file using text editor.

**git diff**

**git add hello_world**

**git commit -m “second commit”**

**git push origin master**

**git diff:**
	      This command is used to check the differences between two commands.
       	      By default it differentiates last two commits. We can even differentiate any two commits using their hashid.
  
now we have made our second commit and pushed it to github.

## 6.Revert back to Step 5 and check in again.

Now we have to revert back to our first commit in our local repository first_git_repo

**git revert hashid of commit to be reverted:**

**git revert:**
	        It is used to revert back to any commit using their hashid. This command creates a new commit which has 		effect of reverting back to specified commit

## 7.Create a new git branch called new_branch

**git checkout -b new_branch :**
		This command is used to create a branch and checkout to that branch.





## 8.Replace all "Torvalds" words with your name in this new_branch and commit + push it to Github

after replacing all the words with Torvalds to sandeep run these commands:

**git add hello_world**

**git commit -m “new branch commit”**

**git push origin new_branch**


**git push origin new_branch:**
				This command is pushing all the commmits in new_branch to  origin.
				

## 9.Create Pull Request and Merge new_branch to the previous branch

## 10.Create a new folder called git_clone_repo in your home folder.
  
**mkdir git_clone_repo**

**cd git_clone_repo**

## 11.Clone the main repository on your Github to this folder from Github.

Now to clone github repository to  git_clone_repo
 
**git clone url-of-github-repository  location-to-clone**

           This command clones the remote repository into the specified directory.


