[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15281294&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
WINDOWS 11
Visit the official Microsoft Windows 11 download page: Microsoft's official website.
Click on "Download Now" or similar button to begin the download.
Save the downloaded file to a location on your computer.
![download process for windows 11](C:\Users\Admin\Pictures\Screenshots\Screenshot 2024-06-17 091707.png)
3. Creating Installation Media
After downloading the Windows 11 installation file, you can create installation media using either a USB flash drive (at least 8GB in size) or a DVD.
Insert a USB flash drive or DVD into your computer.
Use the Windows Media Creation Tool (provided by Microsoft) to create the installation media.
Open the downloaded file (MediaCreationTool.exe).
Follow the prompts to create installation media (select USB flash drive or ISO file if you plan to burn to DVD).
4. Installing Windows 11
Insert the installation media (USB or DVD) into the computer where you want to install Windows 11.
Restart your computer and boot from the installation media.
To boot from USB: Enter BIOS/UEFI settings (usually by pressing a key like F2, F12, Delete during startup) and set USB as the primary boot device.
Follow the on-screen prompts to install Windows 11:
Select language, time, and keyboard preferences.
Click "Install Now".
Enter your product key if prompted (skip if upgrading from Windows 10).
Choose the edition of Windows 11 you want to install.
Accept the license terms and click "Next".
Choose "Custom: Install Windows only (advanced)".
Select the partition where you want to install Windows 11 and click "Next".
Follow the remaining prompts to complete the installation.
5. Configuring Windows 11
After installation, Windows 11 will prompt you to set up your preferences:
Choose your region and language settings.
Connect to a network (if required).
Set up your user account and password.
Customize settings like privacy preferences, background, and theme.
Follow any additional setup prompts as needed.




2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   Visit the official Visual Studio Code website: Visual Studio Code website.
Download the installer appropriate for your operating system (Windows, macOS, Linux).
For my case it is windows:
   Download Visual Studio Code: 
![download process for VSCODE](C:\Users\Admin\Pictures\Screenshots\Screenshot 2024-06-17 093512.png)
Install Visual Studio Code:

Windows:

Double-click the downloaded .exe file to start the installation.
Follow the on-screen instructions in the installer. You can choose the default settings unless you have specific preferences.
After installation, VSCode should be accessible from the Start menu.
Here is how mine currently looks like:
![My VSCODE](C:\Users\Admin\Pictures\Screenshots\Screenshot 2024-06-17 094410.png)
Open Visual Studio Code:

Once installed, open Visual Studio Code from your applications menu (Windows/macOS) or by typing code in the terminal (Linux).
Configure Visual Studio Code:

Extensions: Explore and install extensions to enhance VSCode's functionality. You can do this by clicking on the Extensions view icon in the Sidebar (Ctrl+Shift+X or Cmd+Shift+X), searching for extensions, and clicking Install.

Settings:

Customize VSCode settings by clicking on the Settings icon in the Sidebar (Ctrl+, or Cmd+,).
Modify settings.json to tailor VSCode to your preferences. You can access this file by going to File > Preferences > Settings or pressing Ctrl+Comma (Cmd+Comma on Mac).




3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com


1. Install Git
Git is a distributed version control system widely used for managing project source code. Follow these steps to install Git on your local machine:

Windows:

Download the Git installer for Windows from Git official website.
Run the downloaded .exe file.
Follow the installation steps in the installer (accepting the default settings is usually fine).
here is my screenshot:
![How to download git](C:\Users\Admin\Pictures\Screenshots\Screenshot 2024-06-17 095637.png)

2. Configure Git
After installing Git, configure it with your name and email address. Open a terminal or Git Bash (on Windows) and run the following commands:
here is how to do it
![How to configure git](C:\Users\Admin\Pictures\Screenshots\Screenshot 2024-06-17 100252.png)
 These details will be used to identify your commits.
3. Create a GitHub Account
 This account will be used to host your Git repositories remotely.
 4. Initialize a Git Repository
Now, let's initialize a new Git repository for your project:

Create a new directory for your project (if it doesn't exist already):

these are the codes required:
mkdir my-project
cd my-project
Initialize a Git repository in the project directory:
git init
5. Make Your First Commit
Add some files to your project directory (e.g., index.html, app.py, README.md) and follow these steps to commit them:

Add the files to the staging area (index) for Git to track:

git add .
Replace . with specific file names if you want to add only certain files.

Commit the changes with a meaningful commit message:

git commit -m "Initial commit"
Replace "Initial commit" with a descriptive message about the changes made in this commit.

6. Link Local Repository to GitHub
To host your repository on GitHub:

Create a new repository on GitHub:

Log in to your GitHub account.
Click on the "+" sign in the top right corner and select "New repository".
here is my screenshot:
![Git hub screenshot](C:\Users\Admin\Pictures\Screenshots\Screenshot 2024-06-17 100826.png)


Give your repository a name, optionally add a description, and choose other settings as desired.
Link your local Git repository to the remote GitHub repository:

git remote add origin https://github.com/your-username/your-repository-name.git
Replace https://github.com/your-username/your-repository-name.git with the URL of your GitHub repository.

Push your local commits to the remote GitHub repository:

git push -u origin main
Replace main with master if you're using an older Git repository configuration.



4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.


To install Python and set up the necessary tools to build and execute your code, follow these steps:

1. Download Python
Visit the Python Official Website:

Go to Python's official website.
Choose the Python Version:

Python releases are available in different versions (e.g., Python 3.9, Python 3.10). Choose the version that best suits your project requirements. As of writing, Python 3.10 is the latest stable version.

Download Python Installer:
Once downloaded, run the Python installer (e.g., python-3.10.3-amd64.exe).
Click on the download link for your operating system (Windows, macOS, Linux). The website usually detects your operating system automatically and suggests the appropriate installer.
here is the screenshot:
![Python download screenshot](C:\Users\Admin\Pictures\Screenshots\Screenshot 2024-06-17 101422.png)


2. Install Python
Windows:
Run the Installer:
Configure Python Installation:

Select "Install Now" to use the default settings or customize the installation by clicking "Customize installation".
Add Python to PATH:

Enable the option "Add Python to PATH" during the installation. This allows you to use Python from the command line or terminal easily.
Complete Installation:

Follow the prompts and complete the installation.
Verify Installation:

Check if Python is installed correctly by running:
bash

python --version
3. Verify Python Installation
Open a terminal or command prompt and type:

![Python version](C:\Users\Admin\Pictures\Screenshots\Screenshot 2024-06-17 102201.png)

This command should display the installed Python version (e.g., Python 3.10.3). as shown
4. Install Additional Tools (Optional)
Depending on your project requirements, you may need additional tools such as:

pip: Python's package installer. It usually comes pre-installed with Python 3.4 and above. To upgrade pip:

python -m pip install --upgrade pip
Virtual Environments: Useful for isolating Python dependencies for different projects. Install virtualenv using pip:

python -m pip install virtualenv
Summary
By following these steps, you've installed Python on your system and set up the necessary tools to build and execute your Python code. Ensure you have a text editor or IDE installed (like Visual Studio Code, which we discussed earlier) to start writing and running Python scripts effectively. Adjust the installation steps based on your specific operating system and project requirements.





5. Install Package Managers:
   If applicable, install package managers like pip (Python).
   Depending on your project requirements, you may need additional tools such as:

pip: Python's package installer. It usually comes pre-installed with Python 3.4 and above. To upgrade pip:

python -m pip install --upgrade pip
Virtual Environments: Useful for isolating Python dependencies for different projects. Install virtualenv using pip:

python -m pip install virtualenv
Summary
By following these steps, you've installed Python on your system and set up the necessary tools to build and execute your Python code. Ensure you have a text editor or IDE installed (like Visual Studio Code, which we discussed earlier) to start writing and running Python scripts effectively. Adjust the installation steps based on your specific operating system and project requirements.



6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

 Download MySQL Installer
Visit MySQL Website:

Go to MySQL Community Downloads.
Choose MySQL Installer: here is my screenshot
![MySQL download](C:\Users\Admin\Pictures\Screenshots\Screenshot 2024-06-17 103549.png)
you choose the best version and download it


Select the MySQL Community Server edition suitable for your operating system (Windows in this case). As of now, MySQL 5.7 is considered stable, but you can choose the latest version available.
Download MySQL Installer:

Click on the download link for the MySQL Installer for Windows (e.g., mysql-installer-web-community-X.X.X.X.msi). This installer includes the MySQL server, MySQL Workbench, MySQL Shell, connectors, and other tools.

2. Install MySQL
Run the MySQL Installer:

Once downloaded, run the MySQL Installer .msi file.
Choosing Setup Type:

Select "Custom" setup type to customize your MySQL installation, or choose "Typical" for a standard installation. Click "Next".
Select Products:

Choose the MySQL products you want to install. At minimum, select "MySQL Server" and optionally select "MySQL Workbench" for a graphical interface to manage MySQL databases. I personally downloaded MySQL workbench
Installation Configuration:

Configure MySQL Server installation settings (e.g., port number, MySQL root password). Ensure to note down the root password you set during installation.
Complete Installation:

Proceed through the installation wizard, confirming settings and accepting the license agreement.
3. Verify MySQL Installation
Start MySQL Server:

After installation, MySQL Server should start automatically. If not, you can start it manually from the Services panel (services.msc).
Verify MySQL Installation:

Open MySQL Workbench or a command prompt and connect to the MySQL Server using the root credentials set during installation.

MySQL Workbench: Launch MySQL Workbench from the Start menu. Enter the root username and password you set during installation to connect to the MySQL Server.
Command Line: Open a command prompt and type: mysql -u root -p
Here is how mine looks like
![MySQL on command prompt](C:\Users\Admin\Pictures\Screenshots\Screenshot 2024-06-17 104344.png)
Additional Configuration (Optional)
Create Databases and Users:

Use MySQL Workbench or command line tools (mysql client) to create databases and MySQL users based on your project requirements.
Security Settings:

Secure your MySQL installation by setting appropriate privileges for users and configuring firewall settings to restrict access if needed.



7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

 Access Extensions Marketplace
Visual Studio Code provides an extensive marketplace where you can find and install various extensions. Follow these steps to explore extensions:

Click on the Extensions view icon in the Sidebar (or press Ctrl+Shift+X or Cmd+Shift+X).
Explore and Install Extensions
Search for Extensions:
Here is my screenshot on VSCode
![My extensions on VSCODE](C:\Users\Admin\Pictures\Screenshots\Screenshot 2024-06-17 105244.png)

In the Extensions view, you can search for specific extensions using keywords related to your needs (e.g., "Python", "Git", "Markdown").
Filter and Sort:

Use the filter and sort options to refine your search results based on popularity, relevance, or installation status.
Read Extension Details:

Click on an extension to view its details, including its description, publisher, rating, and reviews.
Install an Extension:

To install an extension, click the "Install" button next to the extension name. Wait for the installation to complete.
Enable and Configure Extensions:

After installation, some extensions may require additional configuration. Follow the prompts or instructions provided by the extension in the Notifications or README.
Recommended Extensions by Category:
Here are some popular extensions across different categories that you might find useful:

Programming Languages: Extensions like Python, Java, JavaScript, C#, etc., provide language-specific features and enhancements.
Linting and Formatting: ESLint, Prettier, flake8, pylint for code linting and formatting.
Version Control: GitLens, GitHub Pull Requests and Issues, Git History for enhanced Git integration.
Debugging: Debugger for Chrome, Python extension for debugging support.
Markdown: Markdown All in One, Markdown Preview Enhanced for Markdown editing and previewing.
Themes: Extensions like Material Theme, Dracula Official, One Dark Pro for different editor themes.
4. Manage Extensions
Disable or Uninstall Extensions:
If an extension is no longer needed, you can disable or uninstall it from the Extensions view.
Click on the gear icon next to an installed extension to manage settings or uninstall it.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

N/B:
Setting up a developer environment can come with several challenges, which may vary depending on factors such as the complexity of the project, the technologies involved, and the experience level of the developer. Here are some common challenges that can occur when setting up a developer environment:

Compatibility Issues: Ensuring that all software components (operating system, libraries, frameworks, tools) are compatible with each other can be challenging. Different versions of software may have dependencies or conflicting requirements that need to be managed carefully.

Installation and Configuration: Installing and configuring development tools, libraries, and dependencies can be time-consuming and error-prone. Issues such as missing dependencies, incompatible versions, or configuration errors may arise, especially in complex setups.

Platform Differences: Developers working across different operating systems (Windows, macOS, Linux) may encounter platform-specific issues. Tools and libraries may behave differently or have varying installation procedures across platforms.

Network and Connectivity: Tools and dependencies that require internet access for installation or updates may be hindered by network restrictions or slow internet connections, leading to delays in setup.

Environment Replication: Ensuring consistency across development, testing, and production environments (often referred to as "environment parity") can be challenging. Differences between environments can lead to bugs that are difficult to replicate and debug.

Security Concerns: Managing security configurations and ensuring that development environments are secure from external threats or unauthorized access is crucial but can be complex.

Documentation and Knowledge Sharing: Clear documentation of setup procedures and configurations is essential for onboarding new team members or revisiting setups after a period of time. Inadequate documentation can lead to misunderstandings or delays in troubleshooting issues.

Performance Optimization: Optimizing the performance of development tools and environments, especially for large-scale projects or resource-intensive tasks, requires careful tuning and configuration.

Tool Integration and Workflow: Integrating various tools (IDEs, version control systems, build systems, testing frameworks) into a cohesive workflow can be challenging. Ensuring smooth interaction and data flow between tools is essential for efficient development.

Dependency Management: Managing dependencies and ensuring consistent and reliable updates across different libraries and frameworks can be complex, especially in projects with many dependencies or frequent updates.

Mitigating Challenges:
Planning and Research: Thoroughly research and plan the development environment setup to anticipate and address potential challenges in advance.

Version Control: Use version control systems like Git to manage changes to configuration files and track setup modifications.

Automation: Utilize automation tools (e.g., shell scripts, configuration management tools like Ansible or Docker) to automate setup processes and ensure consistency.

Testing: Test the setup thoroughly to identify and resolve issues early in the process.

Documentation: Maintain detailed and up-to-date documentation of setup procedures, configurations, and troubleshooting steps to facilitate easier replication and troubleshooting.

By addressing these challenges proactively and leveraging best practices, developers can streamline the setup process and create a stable and productive developer environment for their projects.







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
