[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15242568&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

#Answers:
***
# 1. Get Windows 11 Installation Media:

   Visit the Windows 11 download page.
   Download the Media Creation Tool and run it.

# 2. Create a Bootable USB Drive (if using ISO file):

   Use Rufus or Media Creation Tool.
   Insert USB drive (8 GB or larger).
   Select the ISO file and create the bootable USB drive.

# 3.Install Windows 11:

   Using Installation Assistant:

      Run the Windows 11 Installation Assistant.
      Follow the instructions for upgrading from Windows 10.
   
   Clean Install Using Bootable USB Drive:

      Insert the bootable USB drive and restart the PC.
      Enter BIOS/UEFI (press F2, F12, Delete, or Esc during boot).
      Set USB drive as the primary boot device.
      Boot from the USB drive and start the Windows 11 setup.
      Select language, time, and keyboard preferences.
      Click "Install Now", enter product key if needed.
      Accept license terms, choose "Custom: Install Windows only (advanced)".
      Select the installation partition, proceed with the installation.
      Follow on-screen instructions to complete setup.

# 4.Set Up Windows 11:

   Personalize settings, create a user account, and connect to a network.
   Install drivers and updates via Windows Update.

   Restore Your Data:

      Transfer backed-up files to the new Windows 11 installation.
***

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

#Answers:
***
# 1. Download the Installer

   Visit the Visual Studio Code download page.
   Download the installer for your operating system (Windows, macOS, or Linux).

# 2. Windows:

   Locate the downloaded .exe file (usually in the Downloads folder).
   Double-click the .exe file to start the installation.
   Follow the prompts, agree to the license terms, and choose the installation location.
   Optionally, check the boxes to add VS Code to your PATH and create desktop and start menu shortcuts.
   Click "Install" and wait for the installation to complete

# 3. Launch Visual Studio Code
   Windows:
      Open VS Code from the Start menu or desktop shortcut.

# 4. Initial Setup
   Install Extensions:

      Open the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or by pressing Ctrl+Shift+X (Cmd+Shift+X on macOS).
      Search for and install extensions to add functionality (e.g., Python, Prettier, ESLint, GitLens).

   Configure Settings:

      Open the settings by clicking on the gear icon in the lower left corner and selecting "Settings", or by pressing Ctrl+, (Cmd+, on macOS).
      Customize settings like theme, font size, key bindings, etc.

# 5. Create a New File or Project

   To create a new file, click on "File" in the top menu and select "New File", or press Ctrl+N (Cmd+N on macOS).
   To open an existing project or folder, click on "File" and select "Open Folder", or press Ctrl+K followed by Ctrl+O (Cmd+K followed by Cmd+O on macOS).
***
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

#Answers:
***
# 1. Install Git
      Windows:

         Download the Git installer from the official Git website.
         Run the downloaded .exe file and follow the installation prompts.
         Choose the default options unless you have specific preferences.

# 2. Configure Git
   Open a terminal (or Git Bash on Windows) and set your username and email:

      git config --global user.name "Micheal Bhekifa Mokwena"
      git config --global user.email "michealbhekifa2@gmail.com"
      git config --global --list

# 3.  Create a GitHub Account
   Go to GitHub.
   Click "Sign up" and follow the instructions to create a new account.
   Verify your email address to complete the account setup.

# 4. Create a Repository on GitHub
   After logging in to GitHub, click the "+" icon in the top right corner and select "New repository".
   Fill in the repository name and description.
   Choose the visibility (public or private).
   Optionally, initialize with a README file.
   Click "Create repository".

# 5.  Initialize a Git Repository Locally
   Open a terminal and navigate to your project directory:

      cd C:/documents/plp-assignments
      git init

# 6. Make Your First Commit
   Add your project files to the staging area:
      git add .
      git commit -m "Initial commit"

# 7. Connect Local Repository to GitHub
   Copy the repository URL from GitHub (SSH or HTTPS).
   In the terminal, add the remote repository:

      git remote add origin https://github.com/Bhekifatech/se-assignment-1-setting-up-your-developer-environment-Bhekifatech.git

# 8. Push Your Changes to GitHub
   Push the changes to the remote repository:

      git push -u origin master/main
***

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

#Answers:
***
# 1. Install Python
   Windows:

      Go to the Python download page.
      Click on the "Download Python" button to download the latest version of the Python installer.
      Run the downloaded .exe file.
      Check the box that says "Add Python to PATH" before clicking "Install Now".
      Follow the installation prompts and wait for the installation to complete.

# 2.  Verify Python Installation
   Open a terminal (Command Prompt on Windows, Terminal on macOS/Linux).
   Type the following command to check the Python version:

      python --version

# 3. Install Python Package Manager (pip)
   Pip is usually installed with Python by default. Verify pip installation:

      pip --version

# 4. Install Python Compilers, Interpreters, or Runtimes
   Depending on your project requirements, you may need specific Python tools or libraries:

   Jupyter Notebook: pip install notebook
                     jupyter notebook
   NumPy (for numerical computations): pip install numpy
   Pandas (for data manipulation and analysis): pip install pandas
   Flask (for web development): pip install flask
   Django (for web development): pip install django
   Matplotlib (for plotting and visualization): pip install matplotlib
***

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

#Answers:
***
# 1. Install pip (Python Package Installer)
   Windows and macOS:

   Pip is typically installed with Python. To verify, run:
      pip --version
         If not installed, download the get-pip.py script from bootstrap.pypa.io, and run:
      python get-pip.py
***

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

#Answers:
***
# 1. Download MySQL:

   Go to MySQL Community Downloads.
   Select your OS and download the installer.

# 2. Install MySQL:

   Windows: Run the .msi installer, configure, and complete the setup.
   macOS: Open the DMG file, run the installer, configure via System Preferences.
   Linux:
   Debian/Ubuntu: sudo apt-get update, sudo apt-get install mysql-server.
   Fedora: sudo dnf install mysql-server, start service.
   Arch Linux: sudo pacman -S mysql, initialize database, start service.

# 3. Secure the Installation:

   Run sudo mysql_secure_installation and follow the prompts.

# 4. Post-Installation Configuration:

   Access MySQL shell: mysql -u root -p.
   Create a new database and user, grant privileges.
***

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

#Answers:
***
# 1. Install Docker
   First, you need to install Docker on your machine. Docker provides installation packages for various operating systems including Windows, macOS, and Linux. You can download Docker from Docker's official website.

# 2. Docker Basics
   Once Docker is installed, familiarize yourself with some basic Docker concepts:

      Docker Image: A read-only template that defines a container's filesystem and dependencies.
      Docker Container: A runnable instance of a Docker image.
      Dockerfile: A text document that contains instructions to build a Docker image.
***

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

#Answers:
***
# 1. Popular Extensions:

   VS Code: "Live Share" for collaborative editing, "GitLens" for Git integration, "ESLint" for JavaScript linting.
   Sublime Text: "Package Control" for package management, "Emmet" for HTML/CSS productivity, "SidebarEnhancements" for file management.
   IntelliJ IDEA: Various plugins for different languages (e.g., Python, Java), code quality tools, and frameworks integrations.

# 2. Popular Plugins:

   WordPress: "WooCommerce" for e-commerce, "Yoast SEO" for search engine optimization, "Contact Form 7" for contact forms.
   Drupal: "Views" for managing and displaying content, "Commerce" for e-commerce, "Token" for customizing patterns.
   Joomla: "VirtueMart" for e-commerce, "JCE Editor" for advanced content editing, "K2" for content construction.
***

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 


#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
