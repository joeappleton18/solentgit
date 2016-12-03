#GIT and GitHub pratical 



#Setup 


##1 - Set up a new project folder

Set up a new folder on your `u` drive called `git_project`. Leave it empty for now, later on this will hold our project

##2 - Download and install GIT 

- [Download and install GIT](README.md#how-to-install-Git)
 
##3 - Configure GIT 

- [Open your terminal window and set configure git with your email and username](https://github.com/joeappleton18/solentgit/blob/master/README.md#initial-configuration)


##4 - Set up you GITHUB account 

- If you don't already have a gitHUB account, visit [http://www.github.com](http://www.github.com) and set up a new profile. **Make sure you sign up with your university email address.** This will give you access to the student developer pack(see below)
- After you've created an account set apply for the get your Student Developer Pack [from here](https://education.github.com/pack)
 


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


#4 Mess up you work and roll back

- Run `git log` and ensure you have  a clean working directory 
- Next, make some changes to your text file 
- Run the command `git reset --hard`
- As if by magic your text file will resemble its state from the last commit


#Task 3 - Pushing up your repository on GITHub


- [Create a new repository on GitHub](https://help.github.com articles/create-a-repo/)
	- As we'll be pushing existing work up to the repository, **do not** select the `Initialize this repository with a README` option
	- The repository can be public or private 

- Next, GitHub will give you some instructions on how to push an existing repository from command line to GitHub.  You should run these in your project directory. They'll look something like this:

```bash
git remote add origin https://github.com/joeappleton18/test2.git
git push -u origin master

```

#Advanced Task - GIT Branching

- Look into what is meant by GIT branching. [This git branching resource will help](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging)
- See if you can create a feature branch


