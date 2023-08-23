# Steps-in-making-a-Pull-Request<br>
Here is my own step-by-step, simple instructions on how I can make a pull request (PR) for any repos I want on a PC<br>
Method 1: github.dev web editor
- Choose the repo you want to make a PR for
- On the same browser tab, you can open the [github.dev](https://docs.github.com/en/codespaces/the-githubdev-web-based-editor) in the following ways:<br>
 &nbsp; 1. To open the repository in the same browser tab, press . while browsing any repository or pull request on GitHub.
 &nbsp; 2. To open the repository in a new browser tab, press >.
 &nbsp; 3. Change the URL from "github.com" to "github.dev".
 &nbsp; 4. When viewing a file, select the dropdown menu and click github.dev.
- 
Method 2: Traditional
- Choose the repo you want to make a PR for
- [Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) the repo to your own account
- Install [Git](https://git-scm.com/) and [Github Desktop](https://desktop.github.com/) (Git is a prerequisite for the next steps, and Github Desktop will make the subsequent steps easier)
- Clone the repo to be stored locally. To do this, open a normal terminal or command prompt window and run the following command:<br>
  `git clone https://github.com/**<your-username>**/lp-compat.git`<br>
  Example: `git clone https://github.com/**rarelygoeshere**/lp-compat.git`
- Once this is done, locate where the repo's folder is saved. Use [Everything by Voidtools](https://www.voidtools.com/) to hasten this search
- Open Github Desktop.
- Add the local repo to Github Desktop. You can start by either clicking "Add an existing Repository from your hard drive" or navigate to the File button at the top leftmost, then click it to open a drop-down list, then choose "Add local repository...". Moreover, you can quickly use the hotkey `Ctrl + O` to open the Add local repository window
- Press "choose..." to start locating your repo folder manually, or copypaste the address of the repo folder to the local path textbox
- Press "Add repository"
- Once the process is completed, press "Show in Explorer", or the hotkey `Ctrl + Shift + D` to view the files of your repository in Explorer
- Select the files you want to change and open with the editor of your choice normally([Notepad++](https://notepad-plus-plus.org/) is a good recommentation)
- Once you saved the changes you made, Github Desktop will display the changes on its window for you to review. If you found everything to be satisfactory, then press "commit to main"
- Afterward, if you are satisfied with what you've changed, press "Push Origin"
- Nagivate to your browser and click the forked repo in your account, and press "Contribute", then press "Open pull request".
- Add a title and/or description to your pull request, then press "Create pull request".


