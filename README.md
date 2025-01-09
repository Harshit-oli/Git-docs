<h1>ChaiCode Cohort Github</h1>
<h2>Title</h2>                                                                                                                          
<p>
 Welcome to Git and GitHub at ChaiCode Cohort!                                  
</p>
 <h2>Purpose of Documentation</h2>
    <p>
     The main purpose of this documentation is to provide proper knowledge about Git and github to new employees.
    </p>
    
  <h2>Why</h2>
   <p>The answer of why is because many employees are using GitHub to store their project. It is very useful because multiple people can work on the same project, even if they are not connected to a common server. Our company’s employees are work on github.</p>

   <h2>Basic about Git and Github</h2>
   <p>Git is a tool used to keep track of changes to files, especially the code of the projects. It is termed a distributed version control system because of its behaviour to allow multiple people to work on the same project, even if they are not connected to a common server.</p>
   
   <h1>Brief overview on git and github</h1>
   <p>Git is a distributed version control system designed to track changes in source code during software development. It allows multiple developers to work on a project simultaneously without interfering with each other's work. Git was developed by Linus Torvalds in 2005 and is known for its speed, data integrity, and support for distributed, non-linear workflows.
GitHub, on the other hand, is a web-based platform that hosts Git repositories. It provides a graphical user interface (GUI) for Git, making it easier to manage and collaborate on projects. GitHub was launched in 2008 and is maintained by Microsoft. It offers additional features such as issue tracking, project management, and user management, which are not available in Git1.
Key Differences Between Git and GitHub
1.	Nature: Git is a software tool, while GitHub is a service1.
2.	Interface: Git is primarily a command-line tool, whereas GitHub provides a graphical user interface1.
3.	Installation: Git is installed locally on your system, while GitHub is hosted on the web.
4.	Maintenance: Git is maintained by the Linux community, while GitHub is maintained by Microsoft.
5.	Focus: Git focuses on version control and code sharing, while GitHub focuses on centralized source code hosting.
</p>

<h2>Installing Git on Windows</h2>
 <p>
  To use Git on the command line in Windows, you first need to install it. Follow these steps:

1. Download Git for Windows: Navigate to the Git for Windows installer and download the latest version.

2. Run the Installer: Once the installer is downloaded, run it and follow the instructions in the Git Setup wizard.

3. Verify Installation: After installation, open the Command Prompt or Git Bash and type git version to verify that Git is installed correctly.
 </p>

  <h2> commands for configure Git with user name and email</h2>
   <p>
    1. git config --global user.name "Your Name"
    2.git config --global user.email "your.email@example.com"
   </p>
     <h2>
      create a GitHub account
     </h2>
      <p>
Step 1: Go to the website Open your web browser and go to the GitHub website: https://github.com/ </br>
Step 2: Click on the ‘sign up button. </br>
Step 3: Enter basic details. </br>
Step 4: Complete the puzzle. </br>
Step 5: Verify your account. </br>
Step 6: Enter more details. </br>
Step 7: Choose a plan. </br>
   </p>
<h2>
 Steps to Clone a Repository
</h2>
<p>
 Navigate to the Repository on GitHub: Open your web browser and go to the main page of the repository you want to clone.

Copy the Repository URL: Click on the green "Code" button located above the list of files. In the dropdown menu, you will see options to clone the repository using HTTPS, SSH, or GitHub CLI. Click on the clipboard icon next to the URL to copy it.

Open Terminal or Command Prompt: Open the terminal (on Mac or Linux) or Command Prompt (on Windows) on your computer.

Navigate to the Desired Directory: Use the cd command to change the current working directory to the location where you want to store the cloned repository. For example: cd /path/to/your/directory

Clone the Repository: Type git clone followed by the URL you copied earlier. For example: git git clone https://github.com/ChaiCode/example-repo.git Press Enter to execute the command. Git will create a local copy of the repository in the specified directory.

Verify the Cloning Process: Once the cloning process is complete, navigate to the directory where the repository was cloned to ensure that all files and folders have been copied correctly. You can use the ls command (on Mac or Linux) or dir command (on Windows) to list the contents of the directory.
</p>

<h1>Git Basic commands</h1>
<p>
 git status command: After making code changes you have to add the files for that you have to check which files are not added. For that use git status. The command git status can show you the status of your current file whether it is added or committed or pushed. </br>
 git add <FileName> command: When you get to know which files are not added by typing git status(red-colored files are not added). Then type git add <file name> to add files.</br>
  git commit -m <message> or git commit -am<message> command: After that, you have to commit those added files (type git status to check status, and green colored files are not yet committed). Type git commit -m <message> (message is nothing but a text that tells about what is changed in files) (there are many types of commit command you can check out git documentation in git official website). </br>
   git push command: At last, you have to push your code changes in your local repo by typing git push and then make a pull request.</br>
   pull request: After pushing your code to your local repository you have to make a pull request to merge your code to the real repository. To do that just go to your local repo and click on the pull request. </br>
   
</p>


   
  
 


   
  

