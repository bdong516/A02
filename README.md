## A02 IS117-102 Bd293 NJIT SPRING 24

### PART 0: Installing **Git**

##### How to Install **Git**
- Download the installer from the official **Git** website (https://git-scm.com/) and follow the installation instructions appropriate for your operating system.
- After **Git** is installed you'll need to configure it with your name and email address. To do that open the terminal and run the following commands
```
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

##### Creating a GitHub Account
- If you haven't already create a **GitHub** account at https://github.com/.

##### Creating a new **Repository**
- Once you are logged in to **GitHub**, click on the "+" icon in the top-right corner and select "New **repository**." Give your **repository** a name, optionally you can add a description. Then choose whether you want your **repository** to be public or private, and click the "Create **repository**" button.

##### Cloning a Repository
- If you want to work on a **repository** locally, you must **clone** it. To **clone** a **Repository** copy the **repository** URL from **GitHub** and run the following command
```
git clone <repository_url>
```

##### Making Changes and Commits to the **repository**
- Go to the directory where you cloned the **repository**. Make changes to the files in your local copy by using your IDE, once done you need to stage them for **commit** using the '**git add .**' command
- This stages all changes in the current directory for the next **commit**. You can also specify individual files instead of using '**.**' to stage all changes.
- After staging your changes, **commit** them to your local **repository** along with a message by running the following command
```
git commit -m "Your commit message here"
```

##### Pushing the Changes to GitHub
- To **push** your changes to **GitHub** run the command below
```
git push origin <branch_name>
```

### PART 1: How to install and setup WebStorm

- Submit a request for a free educational license at https://www.jetbrains.com/shop/eform/students
- Use the *"Offical document"* option when applying for a license
- After getting a License ID, download the WebStorm software
  https://account.jetbrains.com/licenses
- Follow the instructions to install WebStorm on your computer
##### Setting up Git Integration in WebStorm
- Open WebStorm
- Go to File > Settings (or WebStorm > Preferences on macOS).
- In the Settings/Preferences dialog, navigate to Version Control > **Git**.
- Check if **Git** is installed. If not, install it and specify the path to the
  **Git** executable.
- Click Apply and then OK to save the changes.
##### Cloning a GitHub Repository
- Open WebStorm
- Go to VCS > Get from Version Control > **Git**.
- In the URL field, enter the URL of the **GitHub repository** you want to **clone**.
- Choose a directory for the local **repository**.
- Click **Clone**.
##### Making Changes and Commits
- Open the project in WebStorm.
- Make changes to the files in the project.
- Go to VCS > **Git** > **Commit** File
- Enter a **commit** message describing the changes.
- Click **Commit** to **commit** the changes to your local **repository**.
##### Pushing Changes to GitHub
- After committing your changes, go to VCS > **Git** > **Push**....
- Make sure the correct **branch** is selected.
- Click **Push** to **push** your changes to the **remote GitHub repository**.
### PART 2: Glossary
- **Branch:** A new/separate version of a **repository**, allowing you to work on different features or fixes simultaneously.
- **Clone:** Creates a local copy of a **repository** from a **remote** source.
- **Commit:** Save changes to the local **repository**.
- **Fetch:** Gets all the change history of a tracked**branch**/**repository**.
- **Git:** A version control system used to track changes in files and coordinate work among multiple developers.
- **GitHub:** A web-based platform for hosting and sharing code repositories.
- **Merge:** Combines the current **branch** with a specified **branch**.
- **Merge Conflict:** Occurs when **Git** cannot automatically **merge** changes and requires manual intervention.
- **Push:** Upload local **repository** changes to a **remote repository**.
- **Pull:** A combination of **fetch** and **merge**. It is used to **pull** all changes from a remote **repository** into the **branch** you are working on
- **Remote:** A version of a **repository** hosted on a server, such as **GitHub**.
- **Repository:** A storage location for a project's files and revision history.
### References
- JetBrains WebStorm Documentation: https://www.jetbrains.com/help/webstorm/
- GitHub Guides: https://guides.github.com/
- Pro Git Book: https://git-scm.com/book/en/v2
- w3schools: www.w3schools.com/git