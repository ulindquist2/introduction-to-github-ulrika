Well done on making it to the bonus task! 🌟 Let's dive into some Git CLI fun! 🤿

<details id=0>
<summary><h2>Install Git CLI </h2></summary>

1. Open the Terminal app on your MacBook. You can find it by searching for "Terminal" using Spotlight (the magnifying glass icon in the top right corner of the screen).
2. Install Git using Homebrew by running the command brew install git in the Terminal. If you don't have Homebrew installed, you can install it by running the command /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)". This will install Homebrew and add it to your PATH environment variable.
3. Verify that Git was installed correctly by running the command git --version. You should see the version of Git that was installed.
  
</details>

<details id=1>
<summary><h2>Bonus task</h2></summary>
1. Navigate to the **<> Code** tab of the repository and click the green button that says **<>Code**. Copy the clone URL given in the dropdown. Clone the existing repository to your local machine by running the command ´git clone <repository_url>´ in your terminal. 

This will create a local copy of the repository on your machine.
Navigate to the local repository directory using the command ´cd <repository_name>´. 
  
2. Create a new branch by using the command `git checkout -b dev-branch`  
  
2. Create a new file using the command `nano <filename>`. Replace <filename> with the name of the file you want to create.
This will open the nano text editor with a blank file. Add some content to the file using the nano editor. When you're done editing, press **CTRL + X** to exit nano and save the changes. You will be prompted to save the file if you've made changes. 
  
3. Check the status of the Git repository by running the command `git status`. You should see that the new file is listed as an "untracked file".

4. Add the file to the staging area by running the command `git add <filename>`. Replace <filename> with the name of the file you created. 

5. Check the status of the Git repository again (step 3). You should now see that the file is listed as a "new file" and is ready to be committed.

6. Commit the changes by running the command `git commit -m "Adding a new file"`
This saves the changes to the repository with a brief message describing the changes made in this commit.

7. Make some changes to the file and save it again.
  
8. Check the status of the Git repository and you should see that the file is now listed as a "modified file".
  
9. Add the changes to the staging area by running the command git add <filename>.
  
10. Commit the changes with a descriptive commit message by running the command git commit -m "Update <filename>". Replace <filename> with the name of the file you modified.
  
11. Now you are ready to push your changes to the repository! Run ´git push origin dev-branch´ to push your changes. 
 
12. Your changes should now be visible in the Github repo. 🥳 To view them, you can navigate to the repository and click on the tab **Pull requests** and create a new pull request for your branch. 

</details>
