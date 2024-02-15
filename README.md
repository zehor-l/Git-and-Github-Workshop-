# Git-and-Github-Workshop-
Git and Github Workshop practice example



### Example1 
## Creating Repository 📂
## On your git bash, type:
```bash
# if this is your first time using git and github, type this to identify yourself for git:
$ git config --global user.name "[username of github account]"
$ git config --global user.email "[email of created github account]"
# if you already did that, skip to this:
cd Desktop    # Navigate to your Desktop.
mkdir example    # Create a new folder named 'example'.
cd example    # Move into the 'example' folder.
touch index.html    # Create a new file named 'index.html'.
git init    # Initialize a new Git repository in the 'example' folder.
git add .    # Add all the files in the folder to the staging area.
git commit -m 'Add index.html'    # Save the changes you made with a message.

rm index.html    # Remove the 'index.html' file.
touch file.py    # Create a new Python file named 'file.py'.
git add .    # Add the new Python file to the staging area.
git commit -m 'Delete index.html and add file.py'    # Save the changes with a message.

git log    # View the history of commits you've made.

# Now, let's say you want to go back to a previous version of your project.
# Replace 'hashcode' with the actual hash code of the commit you want to go back to ( the long key of numbers and letters before your operation title (3876fj88947...... add file)
git checkout hashcode    # Go back to a specific version of your project.

ls    # List the files in your current directory to see the changes.

# Next, you want to share your project on GitHub.
# Go to github.com, create a new repository with same name as your folder you create, here it's example, click create repository down the page, and follow the instructions of adding existing repository to GitHub.
git branch
git remote add origin  #add https adress of your created repo, or basically just copy that line you find in instructions
git push -u origin master
```

## You did it!!🎉🥳
By now, normally if you refresh your github webpage in browser, you will find the pushed project!

## How about we add a branch!🤩
on you git branch continue typing

```bash
git checkout -b new-branch    # Create a new branch named 'new-branch' and switch to it.
git branch    # Check which branch you're currently on.

touch file.css    # Create a new CSS file named 'file.css'.
git add .    # Add the CSS file to the staging area.
git commit -m 'Add file.css'    # Save the changes with a message.

git push origin new-branch    # Push your changes to the new branch on GitHub.
```
when you refresh your page, you can find your new branch clicking on branch that you can find it under your project title. An option for pull request will appear to mege the branches, you can try it and see what happens!👀

