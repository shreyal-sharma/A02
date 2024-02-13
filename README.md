# A02 Create a Github Account with Git/Webstorm/Github/Tutorial. 

|      Term     | Definition|
| ------------- | ------------- |
| Git           | Git is a distributed version control system (VSC) that tracks file changes and allows collaboration among multiple developers.  |
| GitHub        | GitHub is a web-based platform for hosting Git repositories and collaborating on software development projects. It provides tools for version control, issue tracking, and project management.  |
| WebStorm      | WebStorm is an Integrated Development Environment (IDE) developed by JetBrains. It provides a comprehensive set of tools for web development, including code editing, debugging, and version control integration.  |



## PART 1: Directions on Using Webstorm
### Step 1: Install Git and WebStorm
  * Download Git from: [https://git-scm.com/](https://git-scm.com/)                                                                   
    * Install Git for your OS
  * Download WebStrom from: [jetbrains.com/webstorm](https://www.jetbrains.com/webstorm/)
    * Install WebStrom for your OS
### Step 2: Configure Git
  * Set up Git:
    * Open terminal
    * Using following template to set your name and email address:
       git config --global user.name "Your Name"
       git config --global user.email "your.email@example.com"
### Step 3: Create a GitHub Account
  * Create Github Account at [github.com ](https://github.com/)
### Step 4: Connect Github with Webstorm
  * In Webstorm press (Ctrl+Alt+S) for system preferences.
  * Select Version control --> Git.
  * Enter the path to the git.exe
### Step 5: Add Github Password to Webstorm
  * In Webstorm press (Ctrl+Alt+S) for system preferences
  * Select Appearance and Behavior | System Settings | Passwords
### Step 6: Create a New Repository 
  * Log in to the Git hub account you created
  * Click on "+" icon in the top right corner and select "New repository"
  * Enter a name for your repository
    * add a description(optional)
    * choose public or private for your repo
  * Click "Create repository"   
### Step 7: Clone the Repository
  * Copy the URL of your repo from GitHub
  * Open WebStrom
  * Select VCS and Import into Version Control
  * From Main page Select Checkout from version control --> Git
    OR
  * From within Webstorm Select VCS --> Checkout from version control --> Git
  * Enter Github repository name
  * Enter local path name
  * Choose File --> HTML --> HTML 5 or File --> Stylesheet
  * Click Add
### Step 8: Make Changes and Commit
  * Make Changes:
    * Open the project in WebStorm
    * Make changes to the files as needed
  * Commit Changes:
    * Open the Git tool window in WebStorm
    * Stage the changes you want to commit by selecting the files
    * Enter a commit message describing the changes
    * Click "Commit"     
### Step 9: Push Changes to GitHub
* Click “Ctrl --> Shift --> K” OR “VCS --> Git --> Push”
#### Step 10: Collaborate with Others
* Go to "Settings" and then "Collaborators"
* Add the GitHub usernames or email addresses of the people you want to collaborate with
* Use "Pull" in Git tool window to pull changes from the remote repository before making your own changes

#### Reference List
* Git Documentation: git-scm.com/doc
* WebStorm Documentation: jetbrains.com/help/webstorm
* Used [Lecture Slides](https://njit0-my.sharepoint.com/:p:/g/personal/ss856_njit_edu/EXRFJePz-q1LhfyXKbnh99MBxI9IfKPYWH7bXkK5kPrzug?e=bYZsWd)

## Part 2: Glossary to include these terms in a bulleted list.
 * **Branch**: This is a separate line of development in a Git repository, allowing users to work on features or fixes without affecting the main codebase. 
 * **Clone**: Creating a repository copy, including all its files, branches, and commit history. 
 * **Commit**: a snapshot of changes made to files in a repository at a specific point in time. Allows users to keep track of changes that are made at different times.
 * **Fetch**: This is downloading changes from a remote repository to local storage w/o merging them with a local branch. 
 * **GIT**: A distributed version control system tracking file changes and coordinating work among multiple developers.
 * **Github**: A web-based platform for hosting Git repositories and collaborating on software development projects. It provides tools for version control, issue tracking, and project management.
 * **Merge**: Combining changes from one branch (e.g., a feature branch) into another (e.g., the main branch) to integrate the modifications into the codebase.
 * **Merge Conflict**: A situation that occurs when Git cannot automatically merge changes from different branches due to conflicting modifications in the same file. Manual intervention is required to resolve these conflicts.
 * **Push**: Uploading local commits to a remote repository, making them accessible to other users, and updating the repository's history.
 * **Pull**: Fetching changes from a remote repository and merging them into the local branch, updating the local storage with the latest modifications.
 * **Remote**: A remote repository hosted on a server, such as GitHub, that stores the project's files and commit history, allowing users to collaborate and share changes.
 * **Repository**: A storage location where Git stores files and their history, along with metadata about the project. It contains all versions of the project, branches, and commit history.
 

