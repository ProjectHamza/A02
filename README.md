# A02 Git, WebStorm, and GitHub Tutorial

This tutorial provides a step by step guide on using Git, WebStorm, and GitHub for version control and collaboration.

# Part 1: Using WebStorm with Git and GitHub

1. **Install Git:** Download and install Git from [https://git-scm.com/downloads](https://git-scm.com/downloads). Follow the instructions for your operating system.

2. **Install WebStorm:** Download and install WebStorm from [https://www.jetbrains.com/student/](https://www.jetbrains.com/student/).

3. **Configure Git in WebStorm:**
    * Open WebStorm.
    * Go to *File* -> *Settings* (or *WebStorm* -> *Preferences* on macOS).
    * Navigate to *Version Control* -> *Git*.
    * Specify the path to your Git executable or WebStorm might auto-detect it.

4. **Create a GitHub Account:** Create a GitHub account at [https://github.com/join](https://github.com/join).

5. **Create a GitHub Repository:**
    * Log in to GitHub.
    * Click the "+" button and select "New repository."
    * Give your repository a name and description.
    * Initialize with a README. Click "Create repository."

6. **Clone the Repository or Import:**
    * **Option 1 (Clone):** Copy the repository URL (HTTPS or SSH). In WebStorm, *VCS* -> *Git* -> *Clone*. Paste the URL and specify the local directory. Click "Clone."
    * **Option 2 (Import):** If starting a new project, *VCS* -> *Import into Version Control* -> *Create Git Repository*. Then, *VCS* -> *Import into Version Control* -> *Share Project on Github*.
    * **Option 3 (Checkout):**  *VCS* -> *Checkout from Version Control* -> *Git*. Enter GitHub repository name and local path.

7. **Open the Project in WebStorm:** After cloning or importing, WebStorm will open the project.

8. **Create Files (e.g., HTML):** *File* -> *New* -> *HTML* -> *HTML 5*. Name the file (e.g., `index.html`).

9. **Make Changes:** Edit your files.

10. **Add Files to Git:** *VCS* -> *Add*. The "Add to Git" dialog opens. Click "Add." This adds files to the *local* Git repository.

11. **Commit Changes:** *VCS* -> *Git* -> *Commit Changes* (or Ctrl+K). Write a clear commit message (e.g., "Task: Initial commit"). Click "Commit." Set Git username and email if prompted (use your.edu email).

12. **Push Changes to GitHub:** *VCS* -> *Git* -> *Push* (or Ctrl+Shift+K). This uploads changes to the *remote* GitHub repository.


## Part 2: Glossary

*   **Branch:** A separate line of development.
*   **Clone:** Create a local copy of a remote repository.
*   **Commit:** Save changes to the local repository.
*   **Fetch:** Download changes from a remote without merging.
*   **GIT:** A distributed version control system.
*   **Github:** A platform for hosting Git repositories.
*   **Merge:** Combine changes from one branch into another.
*   **Merge Conflict:** A situation where Git cannot automatically merge changes.
*   **Push:** Upload changes from local to remote repository.
*   **Pull:** Download and merge changes from remote to local **branch**.
*   **Remote:** A Git repository hosted on a server.
*   **Repository:** A collection of files and their history, managed by Git.

## References

1.  Beer, B. (2018). *Introducing GitHub*. 2ed. O’Reilly Press.
2.  Jetbrains. (2019). Git. Retrieved Feburary 13, 2025, from [https://www.jetbrains.com/help/webstorm/using-git-integration.html](https://www.jetbrains.com/help/webstorm/using-git-integration.html)
3.  GitHub (2019) GitHub Guides Tutorial. Retrieved Feburary 13, 2025, from [https://guides.github.com/activities/hello-world/](https://guides.github.com/activities/hello-world/)
4. Professor Hendala's PowerPoint Presentation: IntroToGitHub-20190318.pptx (03/24/2019)
