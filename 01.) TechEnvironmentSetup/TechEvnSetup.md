># **MINIPROJECT1-TechEnvironmentSetup**
## **Content**
- [**Content**](#content)
  - [Tech Environment Setup](#tech-environment-setup)
  - [Visual Studio Code](#visual-studio-code)
  - [Git](#git)
  - [VirtualBox](#virtualbox)
  - [Ubuntu on VirtualBox](#ubuntu-on-virtualbox)
  - [Github account](#github-account)
  - [Amazon Web Services account](#amazon-web-services-account)
### Tech Environment Setup
This project has to do with outlining and explaining the tech setup needed on your computer, which is required for properly learning desired skills to become a practising Devops Engineer/practional. It covers a list of the essential tools that have been installed and configured on my PC shown below:

**Essential Tools installed are:**

  - Visual Studio Code (VS code)
  - Git
  - Virtual box
  - Ubuntu on Virtual box
  - Github account
  - Amazon Web Services account
  
It further details a step by step breakdown of how each tool was installed on my PC using screenshots taken at each step. Then showing a simple test carried out to validate the successful installation of the tool, also highlighting any specific configuration done to achieve the effective setup. Thus, confirming the tool is is functioning properly as it is meant to and providing screenshot evidence to this regard. Let's take a look at each item on the list explaining what they are, what they are used for (functions) and relevance (reasons why they are needed).

### Visual Studio Code

Is a streamlined, lightweight and versatile code editor, developed by Microsoft that is available for Windows, Mac OS and Linux. It is used for a wide range of development tasks and supports a variety of progamming languages including C, C#, C++, Fortran, Go, Java, Javascript, Node.js, Python, Rust and Julia. VS code basically is a more robust integrated development environment which provides more features for users, is generally nicer to use and is open source (free). Besides supporting hundreds of languages, it helps you navigate your code with ease, offering an environment where you can easily perform activities like Debugging, IntelliSense code completion, Source control, Extensibility, Automation and Customisation.

**Steps to install VS code**
1. Open your preferred web browser and type the visual studio code website address (https://code.visualstudio.com).
3. Then on the web page, select "download for Windows".
4. When download is completed, locate the downloaded.exe file, double-click to run the installer. click "Next" through the installation wizard and next to all the remaining prompts. Then click "FINISH" to complete the installation, when installation is complete.
5. Finally, Launch VS code from your desktop (double click VS code shortcut icon) or from the windows desktop search tab (type VS code and click VS code icon). This will bring you to the welcome page, as shown below:
![VS code Welcome page](https://github.com/user-attachments/assets/e288a48d-3a8d-4aba-8a00-9db349caf4aa)

**Validating VS code has been successfully installed**

There are several methods of validating and confirming the successful installation and effective setup of VS code on your PC, one of which is with the use of Command Line.

  - Launch command prompt by typing "command" on the windows search and click command prompt. This opens the command prompt window on your desktop as shown in the screenshot below:
  - Then type "code --version" and press enter on the keyboard. It would then display the installed version as shown below:
![Img-2](https://github.com/user-attachments/assets/98ab838b-097c-44df-927c-aed88e122dec)
This confirms VS code has been properly installed.
### Git
Git is a free, open-source distributed version control system created by Linus Torvals in 2005 originally to manage Linux Kernel development. It is basically, used to track changes in source code during software development (or to track changes in files during development of software). By enabling maintaining and keeping track of different versions of developers code, it allows and help developers revert to previous versions of their code if needed and revert changes when needed.

Highly regarded for its distributed architecture, Git is an example of a **DVCS** (hence Distributed Version Control System). As suppose to having only one single place for full version history of the software, with Git, every developer's working copy of the code is also a repository that can contain the full history of all changes.

In DevOps, Git is essential besauce it enables: Collaboration across teams, Automation via **CI/CD** pipelines, Security and Compliance with trails and Reliable developments using **GitOps**. Without Git, mordern DevOps practices like **CI/CD**, **IaC** and **GitOps** wouldn't exist.

**Steps to install Git**

1. Go to Git website for Windows (https://git-scm.com).
2. On the Git web page, click "Download" to download the Git installer for Windows. Ensure to select the lastest 64-bit version of Git for Windows.
3. When the download is complete, locate the downloaded.exe file and double-click to run the installer.
4. Ensure to select "Use Git from the Windows Command Prompt". "Use the OpenSSL Library". "Checkout as-is, commit as-is". "Use Windows default console window". 
5. Lastly, click install to complete the installation. When installation is complete click **FINISH** to complete the installtion.
6. Launch Git from the desktop shortcut icon or type "git" on the windows search tab. This opens the Git window as shown below:
![Img-3](https://github.com/user-attachments/assets/37e7b113-295d-4746-8cd9-25563edc57f2)
**Validating Git has been properly installed**

  - Launch Git by clicking on the Git shortcut icon or type "git" on the windows search tab and then click on Git bash app. This opens Git window on your desktop as shown below:
  - Then type the command "git --version" and enter. It would display the installed version as shown below:
![Img-4](https://github.com/user-attachments/assets/94de766f-ced5-4ccd-a6e8-5fea0e6049e1)
This confirms Git has been properly installed.
### VirtualBox
VirtualBox is a free, open-source virtualisation software developed by Oracle, that allows you to run multiple operating systems simulteneously on a single computer. With VirltualBox, you can create a virtual environment within your computer, allowing you to install and run guest operating systems alongside your host operating system. Essentially, it enables you to create virtual machines (VM) within your existing operating system, each machine with its own operating system. VirtualBox allows you to test different softwares, experiment with different configurations, isolate environments for increased security and run applications without affecting your main operating system.

By using VirtualBox, developers can deliver code faster by running multiple operating systems on a single device. So that IT teams and solution providers can reduce operational costs and shorten the time needed to securely deploy applications on-premises and to the cloud. DevOps engineers mainly use it for testing Infrastructure as code (**IaC**) in isolated environments. 

**Steps to install VirtualBox**

  * Go to VirtualBox website (https://www.virtualbox.org/wiki/Downloads).
  * On the web page select download for Windows host version.
  * Locate the downloaded.exe file, double-click to run the installer.
  * Click "Next" through the installation wizard. Click next to all the remaining prompt, leave every option to "default".
  * Then click install to complete the installation. When installation is complete click "**FINISH**" to complete the installation.
  * Launch VirtualBox from the Start Menu or the VirtualBox Shortcut icon on the desktop or just type Virtual on the Windows search tap and select VIrtualBox App. This Opens the VirboxBox with the welcome page as shown below:
![Img-VBM](https://github.com/user-attachments/assets/c7366b82-2302-42b4-9d09-acbc8b1c5844)
**Validating VirtualBox has been properly installed**

  - Having launched the VirtualBox graphical interface and the VirtualBox Manager window opens without crashes it confirms VBox has been installed successfully.

### Ubuntu on VirtualBox
This involves creating a virtual machine (VM) for Ubuntu in the installed VirtualBox in my Windows host machine.

**Steps Ubuntu (Linux Distro) on VirtualBox (Windows Host)**

  - Launch the installed Virtual box.
  - Create a new VW by clicking NEW or Plus symbol at the top center of the virtual box window.
  - Select Linux as the type, and Ubuntu as the version. Allocate a minimum of 2GB of RAM for the VM.
  - Choose "Create a virtual hard disk now" and click "Create" and choose "VDI (VirtualBox Disk image)" and click "Next". Then choose "Dynamically allocated" and "Next".
  - Set the location and size for the virtual hard disk.
  - With the new virtual machine selected, download Ubuntu ISO.
  - Click start with the virtual machine selected, follow the on-screen instructions to install Ubuntu
  - Choose language and click install Ubuntu, follow the installation wizard and proper configuration.
  - Once installation is complete, click "Restart Now". Enter your login details you created when Ubuntu boots the desktop. This signs you in the VM as shown below:
![Img-Ubuntu](https://github.com/user-attachments/assets/9c0f1eee-e0eb-470d-b1d3-fcf6be13e81a)

### Github account
![Img-GHub01](https://github.com/user-attachments/assets/7aa1a2ae-21d4-4d53-b0be-a2c2ea734dfc)
![Img-GHub-Acct-Dashboard](https://github.com/user-attachments/assets/e30f1017-c207-4a66-b193-52c5ffc5268e)

### Amazon Web Services account
![Img-AWS-Sign-in](https://github.com/user-attachments/assets/df9f02a6-ce0a-49de-b079-364f888802ee)
![Img-AWS-Acct-page](https://github.com/user-attachments/assets/3f2c831b-fb50-4367-91a3-56400fd0e243)
