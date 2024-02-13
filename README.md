# A02 Create a Github Account with Git/Webstorm/Github/Tutorial. 
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
### Step 4: Add Github Password to Webstorm
  * In Webstorm press (Ctrl+Alt+S) for system preferences
  * Select Appearance and Behavior | System Settings | Passwords
### Step 4: Create a New Repository 
  * Log in to the Git hub account you created
  * Click on "+" icon in the top right corner and select "New repository"
  * Enter a name for your repository
    * add a description(optional)
    * choose public or private for your repo
  * Click "Create repository"   
### Step 5: Clone the Repository
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
### Step 6: Make Changes and Commit
  * Make Changes:
    * Open the project in WebStorm
    * Make changes to the files as needed
  * Commit Changes:
    * Open the Git tool window in WebStorm
    * Stage the changes you want to commit by selecting the files
    * Enter a commit message describing the changes
    * Click "Commit"     
### Step 7: Push Changes to GitHub
* Click “Ctrl --> Shift --> K” OR “VCS --> Git --> Push”
#### Step 8: Collaborate with Others
* Go to "Settings" and then "Collaborators"
* Add the GitHub usernames or email addresses of the people you want to collaborate with
* Use "Pull" in Git tool window to pull changes from the remote repository before making your own changes

#### Reference List
** Git Documentation: git-scm.com/doc
** WebStorm Documentation: jetbrains.com/help/webstorm




## Part 2: Glossary to include these terms in a bulleted list.
 * ### Branch
 * ### Clone
 * ### Commit
 * ### Fetch
 * ### GIT
 * ### Github
 * ### Merge
 * ### Merge Conflict
 * ### Push
 * ### Pull
 * ### Remote
 * ### Repository

