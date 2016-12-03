
#Setup 


##1 - Set up a new project folder

Set up a new folder on your `u` drive called `git_project`. Leave it empty for now, later on this will hold our project

##2 - Download and install GIT 

- [Download and install GIT](README.md#how-to-install-Git)
 
##3 - Configure GIT 

- [Open your terminal window](REDME.MD)


##4 - Set up you GITHUB account 









#Task 1 - Creating your first GIT repository


#1 Initiate an empty GIT Repo

- Navigate to your project root folder, you can do this by typing the following command into the shell: 
 
	`cd u:\git_project`


- Ensure that you are in your project root directory, by running the command below (this will print the current directory that you're in). 
	
	`pwd`
    

- Next, run the command:

	`git init`

- If everything runs well, you should be prompted that an empty GIT repo has been created:

	 `Initialized empty Git repository in c:/your/folder/location`

- Run `git status` this tells you the current state of the repository. You should see the following output:

```bash
On branch master  
Initial commit 
nothing to commit (create/copy files and use "git add" to track) 
``` 
	 
	
#2 Make and commit some changes

- Within your project folder create a new file called `test.txt`, you can do this using a text editor

- Run `git status`, you should be prompted that there is an untracked file:
	
  ![](assets/bash_output.jpg) 

- Run the command `git add -A`, git now the adds all files in the directory to the staging area

- Run `git status` again, you should now see that test.txt is in the staging area and is ready to be committed

- To make your first commit run `git commit -m "Blank document" git will now track all future changes to test.txt

- Type `git log` this gives log of everything updated in the repository 	

**You now have a snap shot of your work**


>> TIP If your shell/terminal window becomes choked out you can type: `clear` and press enter
 


#3 Making further commits 

- Make some further commits

![](assets/commit1.jpg)

![](assets/commit2.jpg)

![](assets/log_output_2.jpg)

![](assets/multiple_commits.jpg)

- Type `git log` into the command widow and check your 


#Task2 - Hosting your repositories on gitHub 


##1 Set up a gitHub account 

##2 Sign up for a gitHub student pack



