<h1>Git Hub: Clone, Pull, Push, Branch, Merge </h1>
<h2>

<p>This is the process on how to extract the repository, clone it into my computer. Add files into the imported folder, and prepare it to post back into the cloud.</p>
Learn to create branches to test out different ideas and methods, until it's finalized to merge it into the Main Branch (Standard File Version) and/or (Final Refined Version).</p>

---

*The Steps / Walkthrough.*

---

<h3>

- Create a respository, preferrably with a read.me file.
- Navigate to the repository, check code & find the SSH link.
- Copy the SSH link.
- Open your CLI/Terminal:
    - Create and/or Navigate to the directory file.
    - Type: Git clone ***Paste-copied-SSH-link-here.*** & hit enter.
    - Pull is complete! Files are now in your **Local Computer**.
- Edit and/or Move whichever new Files/Versions from your **Local computer**<br> into the imported repository folder for export into the cloud.
- Open your CLI/Terminal
    - Type: git add -A **(The *-A* command will add all the files.)**
    - Type: git commit -m "A brief message of all changes made"
    - Type: git push origin ***main/master***
    - Push is complete! Files are now exported to the cloud repository.
- How to create a branch for Experimental/Beta Versions.
- Open your CLI/Terminal
        - Type: git checkout -b ***New-Name-For-Branch***
        - Type: git checkout ***branch_name*** "Navigate to the branch name"
    - You Created & Switched into the newly created branch.
    - The branch repository is now free for testing and experimentaion!
    - Push any new versions/files into the branch when ready.
        - Type: git push origin ***branch_name***
- How to merge the branch file into the main/master file.
    - Navigate to the branch file.
    - Find the **Compare & Pull request**
    - Open and Create the Pull request with additional comments.
    - Approve the pull request.
    - The branch file is now merged with the main/master file!
    - Type: git pull
    - Type: git checkout ***main/master***
    - New main/master version is now imported into your **Local Computer**
