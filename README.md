Hello!!

Welcome to Visual Studio Code


I'll show you around, This will be a step by step guide how to navigate, use, and get you writing your first code is VS code!

There will be 8 steps:


First Part__

To get started, you'll need three tools;

1. GitHub
2. Visual Studio Code
3. Git




2 - Setting up Git and Github

            Github

    2A. Got to www.GitHub.com
    2B. Click Sign Up and follow the instructions on the screen.
    2C. Once signed in, create a repository to store your code.
    

            Git

    2a. Download Git from https://git-scm.com/downloads
    2b. open your terrminal (It could be bash or zsh) and set up your user information
    2c. Verify your installation by using this command

            git --version

        If you get the git version and other information, that means Git has been succesfully installed!

3 - Cloning and Setting Up VS Code

            Clone your Repository 

    3A. Open VS code and open the terminal (Ctrl + ~ on windows, Cmd + ~ on Mac).

    3B. Clone your GitHub Repository to your local machine

            Use this command: git clone <your github repo url>

    3C. Navigate in your folder that you'll be working on 

            command: cd <.../Your Repo/>

    3D. I have made a slide about Visual Studio Code; Please review it So you have a more better understanding of VSCode (* mportant* Please to in Slideshow view): 

             https://docs.google.com/presentation/d/19COVacbYtSUF0CMXDnVNppXbKQm8D6VVsJJaBJGSFek/edit?usp=sharing 



4 - Making Changes and Using Git

            Making and Committing Changes

        
    4A. Open your project folder in VS Code.

    4B. Make chnages to files (example the README.md)

    4C. Stage the changes: 

            git add .

    4D. Create a commit:

            git commit - m "Any message here"

5 - Syncing Your Code with Github

            Push and Pull Changes

    5A. Upload (push) your changes to GitHub:

            git push origin main

    5B. If for some reason you want to get the latest changes from Github use this command:

            git pull origin main

6 - Working with Branches 

            Working with branches

    
    6A. Create a new branch to work on a feature:

            git branch new-feature

    6B. Switch to your new branch:

            git checkout new-feature

    6C. Make a commit changes, then merge them back:

            git checkout main
            git merge new-feature

    6D. A little information on Handling Merge conflicts.
        If Git cannot automatically merhe changes, you may encounter a merge conflict. This will happens when the line of code that is the same is modified in a different branches. In order to fix this you need to manually edit the file to resolve the issue before merging.

7 - Fetching and Managing Remote Repo

            Fetch Latest Updates

    7A. If you want to check for new updates from without applying them immeditately, use this command:

            git fetch

8 - Understanding Remote Repo

    8A. If you want to check which remote your project fikle is linked to, use this command:

            git remote -v

        

        This is my little tortial on understanding, and using Git, Github, and Visual Studio Code. 


                        Thank you!





Definitions__

Branch - A separte version of the code that allows developers to work on new features without it effecting the main project

Clone - A cone is a copy of a repository from github to your local machine

Commit - A commit is a snapshot of chnages in your project, allowing you to track your modification.

Fetch - Fetch is a command that retrieves the latest changes in your code. 

GIT - is the version control system that keeps track of the chnages, it works well with github 

Github - GitHub is a cloud platform that host git repositiores 

Merge - Merge is Combining different branches of code into one

Merge Conflict - Merge conflict is the result from an issue when Git cannot merge changes 

Push - Push is uploading local commits to a remote repository on Github

Pull - Pull is the opposite of Push as it downloading and applying the latest chnages from the repo to your computer

Remote - Its basically GitHub

Repository - A repo is a storage location for a project that has all the files like, history, files and branches