# Steps-in-making-a-Pull-Request<br>
Here are my own step-by-step, simple instructions on how I can make a pull request (PR) for any repos I want on a PC. There are two methods to go about doing this:<br> 
## Method 1: github.dev web editor
- Choose the repo you want to make a PR for
- On the same browser tab, you can open the [github.dev](https://docs.github.com/en/codespaces/the-githubdev-web-based-editor) in the following ways:<br>
1. To open the repository in the same browser tab, press **the period key ( . )** while browsing any repository or pull request on GitHub
2. To open the repository in a new browser tab, press **Shift + . (>)**
3. Change the URL from "github.com" to "github.dev"
4. When viewing a file, select the dropdown menu on the right next to the pencil button (Edit this file) and click "github.dev"
- In the web editor, look to the left hand side to see  "Source Control" view along with the explorer panel which displays all of the repo's files
- Navigate to the file of your choice and click on them to open a tab and begin typing. If the tab in on preview, simply double click to edit in markdown.
-  Once you are done, scroll down the Source Control view to see the **Commit & Push** button. Type in the message textbox pertaining what you did (This is mandatory), then press the aforementioned button below.
- If it is done properly, a popup will appear asking if you want to fork the project you are trying to make changes to. Press **Fork Repository**. 
- Another popup will appear, asking you to provide a new branch name. Type in the name you want then either Press **Enter** to confirm, or **Escape** to cancel.
- Once this is done, a popup will appear asking whether you want to switch to your fork to continue making changes. You can either press **Switch to Fork** to continue, or **Cancel** to close the popup.
- If you're ready to make a pull request, press **Cancel** then navigate to your fork in the browser view and you will see a line above your fork that should say "**(Your branch name) had recent pushes 1 minute ago**". Press **Compare & pull request**
- If this line doesn't appear, you can navigate to your branch by pressing **(number) branches** which is next to the "**main**" dropdown menu button to move to another page in the same tab that displays all your branches, to which then you may press **New pull request**
- This will take you to another page on the same tab where it will begin comparing changes to see whether the base repository and the head repository - that being your fork - can be merged. If they are able to merge, you can now press **Create Pull Request**

## Method 2: Traditional
- Choose the repo you want to make a PR for
- [Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) the repo to your own account
- Install [Git](https://git-scm.com/) and [Github Desktop](https://desktop.github.com/) (Git is a prerequisite for the next steps, and Github Desktop will make the subsequent steps easier)
- Clone the repo to be stored locally. To do this, open a normal terminal or command prompt window and run the following command:<br>
  `git clone https://github.com/**<your-username>**/lp-compat.git`<br>
  Example: `git clone https://github.com/**rarelygoeshere**/lp-compat.git`
- Once this is done, locate where the repo's folder is saved. Use [Everything by Voidtools](https://www.voidtools.com/) to hasten this search
- Open Github Desktop.
- Add the local repo to Github Desktop. You can start by either clicking **Add an existing Repository from your hard drive** or navigate to the File button at the top leftmost, then click it to open a drop-down list, then choose **Add local repository...**. Moreover, you can quickly use the hotkey `Ctrl + O` to open the Add local repository window
- Press **choose...** to start locating your repo folder manually, or copypaste the address of the repo folder to the local path textbox
- Press **Add repository**
- Once the process is completed, press "Show in Explorer", or the hotkey `Ctrl + Shift + D` to view the files of your repository in Explorer
- Select the files you want to change and open with the editor of your choice normally([Notepad++](https://notepad-plus-plus.org/) is a good recommentation)
- Once you saved the changes you made, Github Desktop will display the changes on its window for you to review. If you found everything to be satisfactory, then press **commit to main**
- Afterward, if you are satisfied with what you've changed, press **Push Origin**
- Nagivate to your browser and click the forked repo in your account, and press **Contribute**, then press **Open pull request**.
- Add a title and/or description to your pull request, then press **Create pull request**.
- 

## Method 3
- Choose the repo you want to make a PR for
- Click on the page you want to edit
- Select the edit button (the pencil icon button) and make your changes
- ![github file edit button](https://github.com/rarelygoeshere/Steps-in-making-a-Pull-Request/assets/125143953/d53cf5ec-6ed9-47b0-ab69-7a57b5c7a983)
- Select **Fork this repository** and begin making your changes
- ![github fork repo button](https://github.com/rarelygoeshere/Steps-in-making-a-Pull-Request/assets/125143953/6b01b898-ad98-48f8-b815-8eb8518801c1)
- Select **Commit changes...** once you are finished
- Select **Propose changes** (The commit message and extended description are optional)
- Select **Create pull request** on the next page
- Select **Create pull request** again on the next page to create a PR




