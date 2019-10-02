Creating a GitHub Account:
To create a GitHub account, go to https://github.com/join and signup. Git and GitHub are used for a number of things, mainly hosting source code, but also for software development version control, source code management, access control, bug tracking and similar tasks. 

Creating a repository from GitHub:
Creating a repository can be done from the github website. After creating the account, click the + sign in the upper right corner, and click create new repository. This can also be done from Webstorm if you choose to do so.

Downloading and using GIT alogn with GitHub:
Once you've created an account, download git from https://git-scm.com/downloads
To add files to Git, click add, and browse your system then select the file. To push a change to a repository, press CTRL+SHIFT+K (from Webstorm), and that file will now be uploaded and updated onto the proper repository on GitHub.

Using Webstorm:
To install Webstorm, go to https://www.jetbrains.com/student/. To connect GitHub and Webstorm, after Webstorm is installed and running; go to System preferences by pressing CTRL+ALT+S. From here, go to version control and select Git, then locate the Git.exe file on your local machine.

From appearance and behavior in system preferences, you can add a GitHub password. You can also create a repository from Webstorm by selecting VCS and importing to version control.




Definitions:
GIT: Used for version control, used by programmers to track changes withing code during development.

GITHUB: Used alongside of GIT, for hosting code.

Repository: Basically, a folder used to help track changes to files. 

Clone: A copy of a repository that is stored on a computer, not on a file hosting service. 

Commit: Making changes to a file; every time a change is made and saved, it is tracked with a unique ID.

Push: Pushing allows you to save locally made changes to the file hosting service.

Pull: Allows you to take code from the server to the local side

Branch: A development space independent of others.

Merge: A type of pull request. Commits can be merged and combined into one for example. 

Merge Conflict: Trying to merge two files that modify the same area of another file will cause conflict because Git will not know which change to keep.

Fetch: Downloads commits, allows you to see what everyone who has acces to the project has been working on.

Remote: A git repository not on the local system. Through the use of a remote you can access said repository
