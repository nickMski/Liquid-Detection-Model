# Liquid-Detection-Model

[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Ggv3651E)
# Fall 24-25 Innovation Lab

### Welcome to the Innovation Labs! 🥳
📝 [Link to Official Rubric](https://msoe365-my.sharepoint.com/:w:/g/personal/paulsonb_msoe_edu/ERxEIGv5rMZDl78QqILSCLMBul3Q-D74qAjXg4iYWX4fiQ?e=BhT5lC)

This repository contains the base code for the Fall 24-25 Innovation Lab -- provided by the MSOE AI-Club as a great baseline model to get started from!

**Innovation Labs Theme:** "Getting Creative with Liquids", sponsored by [Brady Corp](https://www.bradyid.com/?s_kwcid=AL!10720!3!324787930987!e!!g!!brady%20corp&cid=ppc&camp=ppc-us-brand-google.com-search-trademark_exact-core-brady%20corp&gad_source=1&gbraid=0AAAAAD_q4JoWPyDb3DoIKPlDKF_IL6RWq&gclid=CjwKCAjw9eO3BhBNEiwAoc0-jS3rWRXG3OB2bC1SvFTFoPwxIPRgEkwjO25c9z2BHDZrVFYQkafnPRoCkLcQAvD_BwE)!

**We are looking for solutions that:**
 - Accurately predict the volume of liquid in a container.
 - Expand upon the volume prediction in a creative way.
 - Showcase recognition of how your solution correlates to business applications.

**Examples of "additionally creative" solutions include:**
 - Predicting the content within the container.
 - Parsing the label on the container.
 - Determining the fill-level of multiple containers.
 - ...and many more. Be creative!

<br/>

All code must be committed to this repository by **11:59PM December 6th**.

Make sure that all team members in your group join your team if you created the repository so that everyone can work on the same code. **See the GitHub tutorial below for more info.**

Best of luck, and have fun!

Feel free to send any questions to hailea@msoe.edu or any other member of the [AI-Club leadership team](https://msoe-maic.com/Contact.html).

---

# Getting Started
Once you've cloned the respository and have it running on your machine (see GitHub tutorial in the next section), run through the instructions seen in the Jupyter Notebook titled `example_code.ipynb`.

If you haven't worked with Jupyter Notebooks before, you can think of them as a way to run code in a more interactive way. You can run code cell-by-cell, see the output of each cell, and even add your own notes and comments in between cells!

---

# GitHub Tutorial
GitHub is a platform that allows you to collaborate with others on code. It is a great tool for working on projects with multiple people, as it allows you to see changes that others have made and to work on the same codebase together.

### How to join a team
1. Go to the repository that your team created.
2. Click on the "Settings" tab.
3. Click on the "Manage Access" tab.
4. Click on the "Invite a collaborator" button.

### How to "clone" the repository
"Cloning" a repository means that you are downloading the code from the repository onto your computer. This allows you to work on the code locally on your computer.

1. Go to the repository that your team created.
2. Click on the green "Code" button.
3. Copy the URL that is shown.
4. Open a terminal on your computer.
5. Navigate to the directory where you want to store the code.
6. Run the command `git clone <URL>`, where `<URL>` is the URL that you copied in step 3.

### How to "commit" changes
"Committing" changes means that you are saving the changes that you have made to the code. This allows you to keep track of the changes that you have made and to share them with others.

1. Make changes to the code on your computer.
2. Open a terminal on your computer.
3. Navigate to the directory where the code is stored.
4. Run the command `git add .` to add all of the changes to the commit.
5. Run the command `git commit -m "<message>"`, where `<message>` is a short description of the changes that you made.
6. Run the command `git push` to push the changes to the repository on GitHub.

### How to "pull" changes
"Pulling" changes means that you are downloading the changes that others have made to the code. This allows you to see the changes that others have made and to work on the same codebase together.

1. Open a terminal on your computer.
2. Navigate to the directory where the code is stored.
3. Run the command `git pull` to pull the changes from the repository on GitHub.

### How to "create a branch"
Creating a branch allows you to work on a separate copy of the code without affecting the main codebase. This is useful if you want to work on a new feature or experiment with changes.

1. Open a terminal on your computer.
2. Navigate to the directory where the code is stored.
3. Run the command `git checkout -b <branch-name>`, where `<branch-name>` is the name of the branch that you want to create.

### How to "merge a branch"
Merging a branch means that you are combining the changes that you made on a separate branch with the main codebase. This allows you to incorporate the changes that you made into the main codebase.

1. Open a terminal on your computer.
2. Navigate to the directory where the code is stored.
3. Run the command `git checkout main` to switch to the main branch.
4. Run the command `git merge <branch-name>`, where `<branch-name>` is the name of the branch that you want to merge.

**If you ever get confused or stuck, feel free to reach out! Chat-GPT is also excellent at helping with Git-related questions. 😉**

# RECOMMENDED: Virtual Environment
A virtual environment is a great way to ensure all your outside libraries stay consistent and version-controlled when others want to run your code. This can reduce the amount of time spent debugging and ensure that everyone is on the same page when they begin the project.

Python is famous for its large volume of community-made Open Source packages, but if you're not careful you can cause conflicts between projects. When this happens, it can get messy. [See our learning tree article here](https://msoe-maic.com/library?nav=Articles&article=4-vscode-environments).

### How to set up a virtual environment
Run the following in the terminal:
1. `pip install --user virtualenv`
2. `python3 -m virtualenv venv` There might be a pop-up in the lower lefthand corner asking if you want to add the virtualenv to your workspace. I recommended against this as it can sometimes cause issues. After running the above lines, you should have a folder called `venv` in your workspace
3. Activate the virtualenvIf you're on Windows run this: `\\venv\Scripts\activate`
    * If you're on MacOS run this: `source venv/bin/activate`
    * **NOTE:** Sometimes you might have permission issues with running batch scripts. If this is the case, navigate to the `Activate.ps1` file, open it in VSCode, and Run it.
    
Once you've followed the above steps, there should be a `(venv)` tag before your shell commands. Last steps:
1. Click on the `Python 3.XX.X` jupyter kernel on the right side of the toolbar for the jupyter notebook.
2. Click `Python Environments`, then click `venv (Python 3.XX.X)`.
3. You're done! You've made a virtual environment

---

