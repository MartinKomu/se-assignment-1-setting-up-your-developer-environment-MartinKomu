[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15246180&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
   Step-by-Step Installation Guide for Windows 11 which I had installed before PLP program
1.	Download Windows 11 Installation Media:
o	Visit the official Microsoft Windows 11 download page: Windows 11 Download.
o	Select "Download Now" under "Create Windows 11 Installation Media" to download the Media Creation Tool.
2.	Create Installation Media:
o	Run the downloaded Media Creation Tool (MediaCreationToolW11.exe).
o	Accept the license terms.
o	Choose "Create installation media (USB flash drive, DVD, or ISO file) for another PC" and click Next.
o	Select the language, edition, and architecture (64-bit).
o	Choose "USB flash drive" if you want to create a bootable USB drive or "ISO file" to create an ISO file for DVD burning.
o	Follow the prompts to complete the creation of the installation media.
3.	Install Windows 11:
o	Using a USB Flash Drive:
	Insert the bootable USB flash drive into your PC.
	Restart your PC and boot from the USB drive. This may require you to enter the BIOS/UEFI settings and change the boot order.
	On the Windows Setup screen, select your language, time and currency format, and keyboard input method, then click Next.
	Click Install Now.
o	Using an ISO File (DVD):
	Burn the ISO file to a DVD.
	Insert the DVD into your PC and restart it.
	Boot from the DVD drive. This may require changing the boot order in the BIOS/UEFI settings.
	On the Windows Setup screen, select your language, time and currency format, and keyboard input method, then click Next.
	Click Install Now.
4.	Enter Product Key:
o	If prompted, enter your Windows 11 product key. If you don’t have one, select “I don’t have a product key”. You can enter the product key after the installation.
5.	Accept License Terms:
o	Read and accept the license terms, then click Next.
6.	Choose Installation Type:
o	Select “Custom: Install Windows only (advanced)”.
7.	Partition Your Drive:
o	Select the drive where you want to install Windows 11. You can delete existing partitions if you want a clean install. Be careful, as this will erase all data on the selected partitions.
o	Click Next to start the installation.
8.	Installation Process:
o	The installation process will begin, and your PC will restart several times during the process.
o	Follow the on-screen instructions to complete the setup, including configuring your region, keyboard layout, and other settings.
9.	Create User Account:
o	Create a user account and set a password.
o	Customize your settings or use the recommended settings.
10.	Final Setup:
o	Windows 11 will finalize the setup and bring you to the desktop.
Post-Installation process:
1.	Install Drivers:
o	After installation, it’s important to install the latest drivers for your hardware. Check the manufacturer’s website for driver updates.
2.	Install Updates:
o	Go to Settings > Windows Update and check for updates to ensure your system is up-to-date.
3.	Install Essential Software:
o	Install necessary software such as web browsers, productivity tools, and any other applications you need.


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   Steps to Install Visual Studio Code on Windows
Step 1: Visit the Official Website of the Visual Studio Code using any web browser like Google Chrome, Microsoft Edge, etc.



1--Official-Page

Step 2: Press the “Download for Windows” button on the website to start the download of the Visual Studio Code Application.

2--Download-File

Step 3: When the download finishes, then the Visual Studio Code Icon appears in the downloads folder.

3--Open-File

Step 4: Click on the Installer icon to start the installation process of the Visual Studio Code.

Step 5: After the Installer opens, it will ask you to accept the terms and conditions of the Visual Studio Code. Click on I accept the agreement and then click the Next button.

4--Accept-License

Step 6: Choose the location data for running the Visual Studio Code. It will then ask you to browse the location. Then click on the Next button.


5--Click-Next

Step 7: Then it will ask to begin the installation setup. Click on the Install button.

6--Click-Install

Step 8: After clicking on Install, it will take about 1 minute to install the Visual Studio Code on your device.

7--Wait

Step 9: After the Installation setup for Visual Studio Code is finished, it will show a window like this below. Tick the “Launch Visual Studio Code” checkbox and then click Next.

8--Finish

Step 10: After the previous step, the Visual Studio Code window opens successfully. Now you can create a new file in the Visual Studio Code window and choose a language of yours to begin your programming journey!

9--Ready
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   Steps to Install and Configure Git on Your Local Machine
Prerequisites:
•	Operating System: Windows 7 or later. Ensure your operating system is up to date.
Step-by-Step Installation Guide:
1.	Download Git:
o	Visit the official Git download page: Git Download.
o	Click on the Download button to download the installer.
2.	Run the Installer:
o	Once the download is complete, locate the downloaded file (Git-2.x.x-64-bit.exe) in your Downloads folder or the location where you saved the file.
o	Double-click on the Git-2.x.x-64-bit.exe file to start the installation process.
3.	Setup Installation Options:
o	Follow the installation prompts:
	Select Destination Location: Choose the default location or specify a different location to install Git.
	Select Components: Choose the default options unless you have specific needs. It's generally a good idea to include Git Bash and Git GUI.
	Adjusting your PATH environment: Select "Git from the command line and also from 3rd-party software".
	Choosing the SSH executable: Use the bundled OpenSSH.
	Choosing HTTPS transport backend: Use the OpenSSL library.
	Configuring the line ending conversions: Checkout Windows-style, commit Unix-style line endings.
	Configuring the terminal emulator: Use MinTTY (the default terminal of MSYS2).
	Configuring extra options: Enable file system caching and enable Git Credential Manager.
4.	Complete the Installation:
o	Click Install to begin the installation.
o	Once the installation is complete, click Finish to exit the installer.
5.	Verify Installation:
o	Open Git Bash by searching for it in the Start menu.
o	Verify the installation by typing the following command and pressing Enter:
bash
Copy code
git --version
o	You should see the Git version number displayed, indicating that Git is installed correctly.
6.	Configure Git:
o	Configure your Git username and email by running the following commands in Git Bash:
bash
Copy code
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Steps to Create a GitHub Account and Host Repositories
1.	Create a GitHub Account:
o	Visit the GitHub website: GitHub Sign Up.
o	Click on Sign up in the upper-right corner.
o	Enter your email address, create a password, choose a username, and complete the CAPTCHA. Click Create account.
o	Follow the prompts to complete the account creation process, including verifying your email address.
2.	Create a New Repository on GitHub:
o	Log in to your GitHub account.
o	Click on the + icon in the upper-right corner and select New repository.
o	Fill in the repository details:
	Repository name: Enter a name for your repository.
	Description: (Optional) Add a description for your repository.
	Public/Private: Choose whether the repository should be public or private.
	Initialize this repository with a README: Check this box if you want to include a README file.
o	Click Create repository.
Steps to Initialize a Git Repository and Make Your First Commit
1.	Initialize a Local Git Repository:
o	Navigate to your project directory using File Explorer or the command line.
o	Right-click in the project directory and select Git Bash Here to open Git Bash in that directory.
o	Initialize a new Git repository by running:
bash
Copy code
git init
2.	Add Files to the Repository:
o	Add the files in your project directory to the Git repository by running:
bash
Copy code
git add .
3.	Commit Your Changes:
o	Make your first commit by running:
bash
Copy code
git commit -m "Initial commit"
4.	Connect to GitHub Repository:
o	Go to your newly created repository on GitHub.
o	Copy the repository URL (use HTTPS for simplicity).
o	In Git Bash, connect your local repository to the GitHub repository by running:
bash
Copy code
git remote add origin https://github.com/yourusername/your-repository-name.git
5.	Push Your Changes to GitHub:
o	Push your local changes to the GitHub repository by running:
bash
Copy code
git push -u origin master



4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  Steps to Install Python on Windows
Prerequisites:
•	Operating System: Windows 7 or later. Ensure your operating system is up to date.
Step-by-Step Installation Guide:
1.	Download Python:
o	Visit the official Python download page: Python Download.
o	Click on the Download Python 3.x.x button. The exact version may vary; the latest stable release is recommended.
2.	Run the Installer:
o	Once the download is complete, locate the downloaded file (python-3.x.x.exe) in your Downloads folder or the location where you saved the file.
o	Double-click on the python-3.x.x.exe file to start the installation process.
3.	Customize Installation:
o	Add Python to PATH: At the bottom of the installer window, check the box that says Add Python 3.x to PATH. This step is crucial as it allows you to run Python from the command line.
o	Click on Customize installation to proceed with custom options.
4.	Optional Features:
o	Ensure that the following options are checked:
	Documentation
	pip (Python package manager)
	tcl/tk and IDLE (development environment)
	Python test suite
	py launcher
o	Click Next to proceed.
5.	Advanced Options:
o	Ensure that the following options are checked:
	Install for all users (requires admin privileges)
	Create shortcuts for installed applications
	Add Python to environment variables
o	Leave the default installation location or choose a different location if needed.
o	Click Install to begin the installation.
6.	Installation Process:
o	The installation process will begin, and it may take a few minutes to complete. Once finished, you will see a screen confirming the successful installation of Python.
7.	Verify Installation:
o	Open the Command Prompt by pressing Win + R, typing cmd, and pressing Enter.
o	Verify the installation by typing the following command and pressing Enter:
bash
Copy code
python --version
o	You should see the Python version number displayed, indicating that Python is installed correctly.
o	Also, verify pip (Python package manager) by typing:
bash
Copy code
pip --version


5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.html
   Download your preferred version. In this example, we selected the Full MySQL Package (B).
 
After selecting a version, you are provided with the option of signing up for a MySQL Community account. If you are not interested, select the No thanks, just start my download option at the bottom of the page.
 
By selecting this option, the download process starts immediately. Once the download is complete, you can execute the MySQL Installer file from the download folder.
It can take a few moments while Windows configures the MySQL Installer and prepares the installation and configuration process.
Set Up MySQL Installer for Windows
After accepting the Oracle license agreement terms, the first screen you encounter allows you to define which MySQL products are going to be installed. You can choose between several predefined options or create your custom setup type.
Note: Preconfigured setups can be customized later if necessary.
After accepting the Oracle license agreement terms, the first screen you encounter allows you to define which MySQL products are going to be installed. You can choose between several predefined options or create your custom setup type.
•	Developer Default installs all the tools you need to develop and micromanage your MySQL databases effectively.
•	Server Only is used to install an instance of the MySQL Server and forgo other MySQL products.
•	Client Only installs all products except the MySQL Server and associated tools.
•	The Full configuration installs all available MySQL products.
A Custom setup allows you to select the individual elements that are to be installed and alter predefined default settings.
In the example below, we select the Server Only option and click Next.
 
At this point, the system tries to resolve possible inconsistencies. It might inform you that additional packages need to be installed for the process to continue (e.g., Microsoft Visual C++ 2019 Redistributable Package). You can also run into Path installation inconsistencies if you have previous MySQL installations on your Windows Server.
Luckily the MySQL Installer auto-resolves issues and installs the latest binary compatible version of missing software. You are now ready to start the installation process in earnest. Click Execute to begin the installation process.
 
Once the status of the installation status is labeled as Complete, you are ready to configure the MySQL database.
Configure MySQL Server on Windows
The MySQL Server 8.0.19 is now ready to be configured. Initiate the process by clicking Next.
 
1. High Availability
The first configuration option affects database availability. It allows you to decide if you want to set up a Standalone MySQL Server or an InnoDB server cluster to improve availability. In this instance, we selected the classic, single server option.
 
2. Type and Networking
The Type and Networking section is used to define several essential features.
The Config Type option lets you choose between three server configuration types. Development Computer, Server Computer, and Dedicated Computer define whether the server is dedicated solely to running your MySQL database or is going to share the underlying system with other applications.
In this example, we decided to create a dedicated MySQL server.
 
The Type and Networking tab can also define the port the MySQL server is listening on. The default setting is port number 3306 and can be changed to suit your needs.
By checking the Show Advanced and Logging Option box, you can set additional logging options at a later stage.
Click Next once you’ve selected the options you feel meet your requirements.
 
3. Authentication Method
It is possible to choose between two authentication methods, the recommended Strong Password Encryption, and the Legacy Authentication Method. Select the recommended Use Strong Password Authentication option.
 
4. Accounts and Roles
You are now prompted to enter a password for your MySQL root user. You can also create additional roles for various users and purposes.
This is only an initial setup, and credentials can be edited once the installation is complete.
 
5. Windows Service
By defining MySQL as a Windows Service, it can now start automatically whenever the Windows system boots.
If you decide to start MySQL as an executable application, you would need to configure it manually.
 
6. Logging Options (Optional)
If you have selected the Show Advanced Logging option in the Type and Networking tab, you are now able to set up MySQL log preferences.
Logging options let you select the types of logs you want to activate and define the log directories.
 
Click Next to reach the Advanced Options section.
7. Advanced Options (Optional)
Advanced Options include setting a unique server identifier, and the type of case (Lower/Upper) to be used for Table Names.
These settings are only available if you have checked the Show Advanced Options box in the Type and Networking tab.
8. Apply Configuration
You have successfully configured the MySQL server and need to confirm for the MySQL Installer to apply the configuration.
An overview of the configurations steps appears on the screen. Click Execute to apply the configuration.
 
The system informs once the configuration process is completed. Select Next to continue the installation process.
 
Complete MySQL Installation on Windows Server
After clicking Next, you are given the option to copy the installation process log to the Windows Clipboard.
 
Click Finish to complete the MySQL server installation on Windows.
"C:\Program Files\MySQL\MySQL Server 8.0\bin\mysqld" --console


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
    Challenges
   1. Configuring User Details:

Problem: Forgot to configure the global user name and email.
Solution: Used the following commands to configure my details:
bash
Copy code
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

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
