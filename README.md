# testSyncAndroidStudio
Just testing github sync with VCS Android Studio.

## Getting Started
You can following as below step for sync your Android Studio project with GitHub.

**[1]** Let’s login to [GitHub](http://github.com/) and create a new repository.

**[2]** Open **Android Studio** and create a **new project**.
Call your new application such as "testSyncAndroidStudio".

**[3]** On the top menu, select **VCS > Import into Version Control > Create Git Repository**.

Leave it all as default and click at root your project folder and push **OK**.

**[4]** Open **cmd.exe** and goto your root project folder and type Git bash screen appears, type:
```
git remote add origin https://github.com/[username]/[project_name].git
```
An example of a Git repository URL is: https://github.com/nsrw-surasak/testSyncAndroidStudio.git<br />
Then press enter. The GitHub remote will be added to your Git repository.

**[5]** Jump back into **Android Studio**, right click your projects root directory and select **Git > Add**.<br />
This will add all your project files to your Git repository. It will seem like nothing has happened,<br />
but trust me, the project files are added.

**[6]** Now right click the project name again and this time select **Git > Commit Directory**.<br />
In the next screen, type a **Commit Message** and select **Commit**.

**!!! If a Code Analysis warning appears**, click **Commit**. <br />

**[7]** Right click the project name, select **Git > Repository > Push**.

**[8]** Check on **Push current branch to alternative branch** and leave the branch name as **master**. Then select **push**.

**[9]** And last step is **GitHub Login** and **Password**. Then click **OK**.

and **congratulations! your project has been sync with GitHub successfully!!!**

### Prerequisites

Firstly, You must install [Git for Windows](https://git-scm.com/download/win)

## Versioning

* First and last version.

## Authors

* **Surasak Nasuriwong** - [nsrw-surasak](https://github.com/nsrw-surasak)

I was following [London App Developer](https://goo.gl/NKzbK5) site. 
