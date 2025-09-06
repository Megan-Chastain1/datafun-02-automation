# datafun-02-automation
These tasks are part of the standard developer workflow and are performed using a terminal, not Python code. Here are the step-by-step instructions with the commands to run in your VS Code terminal to accomplish each task.

### 1\. GitHub Account & Repository

You must do this part in your web browser.

1.  Go to **github.com** and sign up for a new account.
2.  Once logged in, click the **New** button to create a new repository. Name it **`datafun-02-automation`**. It's a good idea to check the box to add a README file.

-----

### 2\. Local Project Setup 📂

Use these commands to set up your project folder and connect it to GitHub. Open your VS Code terminal (using **Ctrl + \`**), and run these commands.

```
# Navigate to the C: drive and create a folder named Repos
C:
cd \
mkdir Repos

# Change into the new folder
cd C:\Repos

# Clone the repository from GitHub. Replace 'youraccount' with your username.
git clone https://github.com/youraccount/datafun-02-automation.git
```

-----

### 3\. Add Files and Sync 🔄

After cloning, add the required files and push them to GitHub.

```
# Change into the cloned repository's folder
cd C:\Repos\datafun-02-automation

# Add the .gitignore and requirements.txt files in the VS Code file explorer.

# Stage all new files for the next commit
git add .

# Save the changes with a descriptive message
git commit -m "Add .gitignore and requirements.txt files"

# Upload your saved changes to GitHub
git push -u origin main
```

-----

### 4\. Create a Virtual Environment 🐍

A virtual environment keeps your project's dependencies separate from your system's Python. Run this command inside your project folder.

```
# Create a virtual environment named .venv
py -m venv .venv
```
