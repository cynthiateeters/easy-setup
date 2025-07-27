# Git Configuration Assignment

**Objective**: Configure your Git settings and verify they work correctly with VS Code's Source Control panel.

## What You'll Accomplish

By completing this assignment, you will:
- Configure your Git username and email settings
- Learn to install VS Code extensions from a file
- Practice using VS Code's Source Control panel for your first commit and push
- Verify your Git configuration is working correctly

## Instructions

### Step 1: Install the Git Configurator Extension

1. **Open this repository in VS Code**
   - Make sure you have this entire folder open as your workspace

2. **Install the extension from the VSIX file**
   - Press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (Mac) to open the Command Palette
   - Type: `Extensions: Install from VSIX...`
   - Press Enter
   - Navigate to this folder and select: `git-configurator-for-grid-0.1.0.vsix`
   - Click "Install"
   - Wait for the installation to complete

### Step 2: Run the Git Configuration

1. **Open the Command Palette again**
   - Press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (Mac)

2. **Run the Git Configurator**
   - Type: `Configure Git For Grid`
   - Press Enter

3. **Follow the extension prompts**
   - The extension will guide you through the setup process
   - Enter your **full name** when prompted (e.g., "John Smith")
   - Enter your **email address** when prompted (preferably your school email)
   - Wait for the extension to complete the configuration

4. **Verify success**
   - You should see a success message
   - A new file called `git-config-check.txt` should appear in your workspace

### Step 3: Commit and Push Your Changes

Now you'll use VS Code's Source Control panel to commit and push the verification file:

1. **Open the Source Control panel**
   - Look for the Source Control icon in the left sidebar (looks like a branching tree symbol)
   - Click it to open the Source Control panel
   - You should see `git-config-check.txt` listed as a new file

2. **Stage the file**
   - In the Source Control panel, you'll see `git-config-check.txt` under "Changes"
   - Click the **`+`** button next to the filename to stage it
   - The file should move to "Staged Changes"

3. **Create a commit**
   - In the text box at the top of the Source Control panel, type a commit message:
     ```
     Add Git configuration verification file
     ```
   - Click the **checkmark** button (✓) above the text box to commit

4. **Push to GitHub**
   - Click the **three dots** (`...`) in the Source Control panel
   - Select **"Push"** from the menu
   - Your changes will be uploaded to GitHub

### Step 4: Verify Completion

1. **Check your commit**
   - Go to your repository on GitHub (in your web browser)
   - You should see your commit with the message "Add Git configuration verification file"
   - The `git-config-check.txt` file should be visible in your repository

2. **Verify your Git identity**
   - Click on your commit on GitHub
   - Verify that your name and email appear correctly as the commit author

## Troubleshooting

### Extension Installation Issues
- **"Command not found"**: Make sure you installed the extension and restarted VS Code if needed
- **"VSIX file not found"**: Make sure you're selecting the file from the correct folder

### Git Configuration Issues
- **"Git not found"**: Make sure Git is installed on your computer
- **Authentication errors**: Make sure you're logged into GitHub and have access to this repository

### Source Control Issues
- **No Source Control panel**: Make sure you have the folder open as a workspace in VS Code
- **Can't see the file**: Make sure `git-config-check.txt` was created by the extension
- **Push fails**: Make sure you have write access to this repository and are logged into GitHub

### Getting Help
- Check that you followed each step exactly as written
- Make sure your repository is open as a workspace in VS Code
- Ask your instructor for help if you're still having trouble

## What This Assignment Teaches

- **Extension Installation**: How to install VS Code extensions from files
- **Git Configuration**: Setting up your identity for version control
- **Source Control Workflow**: The basic Git workflow using VS Code's GUI
- **File Staging**: Understanding the concept of staging changes
- **Commits**: Creating meaningful commit messages
- **Push Operations**: Uploading your changes to a remote repository

## Assignment Complete!

Once you successfully push your commit to GitHub, you have completed this assignment. Your Git configuration is now set up correctly and you're ready for future coding assignments that require version control.

## Next Steps

In future assignments, you'll use this same Source Control workflow to:
- Save your work with meaningful commits
- Track your progress on projects
- Submit assignments by pushing to GitHub
- Collaborate with others on group projects

Great job setting up your development environment! 🎉