# setup_repo_viettech
repository to help new cs students set up their laptop for both MAC and Window

## **HOW TO SET UP VSCODE** <br />
**Window** <br />
**Step 1:** Go to this website https://code.visualstudio.com/  <br />
**Step 2:** Choose your system version (Window). Then click the blue dowload button <br /> 
**Step 3:** Click to the .exe vscode filesetup in the Dowload  <br />
**Step 4:** "I accept the agreement" => default file path location => Ticked "Create a desktop icon" + "Register code as an editor for supported files types" + "Add to PATH" => Install! <br />
**Step 5:** Go to "Extensions" Tab to dowload : "Python v2024.2.1" + "Python Debugger v2024.2.0" + "Live Server v5.7.9" + "Prettier - Code formatter
v10.1.0" + "Material Icon Theme" + "Git Blame" + "Git Graph" <br />
**Step 6:** (Optional) Test HTML with Live Server <br />
**Step 7:** (Optional) Watch this tutorial: https://www.youtube.com/watch?v=naL0cZNQh1g <br />

 
**Mac**  <br />
**Step 1:** Go to this website https://code.visualstudio.com/ <br />
**Step 2:** Choose your system version (Mac Universal). Then click the blue dowload button <br />
**Step 3:** Click to the .zip vscode-univsal file to extract  <br />
**Step 4:** Go to "Extensions" Tab to dowload : "Python v2024.2.1" + "Python Debugger v2024.2.0" + "Live Server v5.7.9" + "Prettier - Code formatter
v10.1.0" + "Material Icon Theme" + "Git Blame" + "Git Graph"<br /> 
**Step 5:** "Command Shift P" + Type "shell command" into the bar => so we can open vscode by terminal <br />
**Step 6:** (Optional) Test HTML with Live Server <br />
**Step 7:** (Optional) Watch this tutorial: https://www.youtube.com/watch?v=w0xBQHKjoGo <br />


## **HOW TO SET UP NODE.JS** <br />
**Window**   <br />
**Step 1:** Go to this website https://nodejs.org/en  <br />
**Step 2:** Choose the "Recommend for most users" version then dowload it  <br />
**Step 3:** "I accept the License agreement" => Default file location => Default Custom Setup => Ticked "Automatically dowload necessary tools" => Install!  <br />
**Step 4:** Waiting and interact with terminal so Node.js can finish dowloading the "Chocolate" <br />
**Step 5:** Test whether node is dowloaded by type "node -v" in terminal <br />
**Step 6:** (Optional) Test node with hello.js file in terminal <br />
**Step 7:** (Optional) Watch this tutorial: https://www.youtube.com/watch?v=__7eOCxJyow <br />

**Mac** <br />
**Step 1:** Go to this website https://nodejs.org/en  <br />
**Step 2:** Choose the "Recommend for most users" version then dowload it  <br />
**Step 3:** Click the ".pkg" node file to extract the file  <br />
**Step 4:** "I accept the License agreement" => Default destination select => Default installation type => Install!  <br />
**Step 5:** Test whether node is dowloaded by type "node -v" in terminal <br />
**Step 6:** (Optional) Test node with hello.js file in terminal <br />
**Step 7:** (Optional) Watch this tutorial: https://www.youtube.com/watch?v=SwUKKCS3r3c <br />


## **HOW TO SET UP GIT** <br /> 
**Window**   <br />
**Step 1:** Go to this website https://git-scm.com/downloads <br />
**Step 2:** Choose the "Window" version then choose "64-bit Git for Windows Setup." => dowload it  <br />
**Step 3:** Click the .exe git file to extract and run program <br />
**Step 4:** Next => Next => Click "Additional icons" => Next => "Using Visual Studio Code as Git's default editor" => Let Git Decide => Git from command lind and 3rd-party software => Use bundled openSSH => Use the OpenSSL Library => Check-out window style, commit the Unix-style line endings => USe MinTTY => Default (fast-forward and merge) => GIt Credential Manager => Enable file system caching => Next => Launch Git Bash => Finish! <br /> 
**Step 5:** Test whether git is dowloaded by typing "git --version" in terminal <br />
**Step 6:** Create a hello.js by terminal in a random file path  <br />
**Step 7:** Initialize "git init" add that same folder <br />
**Step 8:**  git add hello.js => git commit hello.js => Then config the user.name and user.email ![image](https://github.com/PhuocOng/setup_repo_viettech/assets/122703392/faee90fb-3ddd-411c-9d3c-a22dd5df8229) <br />
**Step 9:** git push => Follow the instructions to push to remote repo  <br />
**Step 10:** (Optional) Watch video at : https://www.youtube.com/watch?v=AdzKzlp66sQ

**Mac**   <br />
**Step 1 :** Go to this website https://git-scm.com/download/mac and choose the dowload option that suitable for you <br /> 
**Step 2:** Test whether git is dowloaded by typing "git --version" in terminal <br />
**Step 3:** Create a hello.js by terminal in a random file path  <br />
**Step 4:** Initialize "git init" add that same folder <br />
**Step 5:**  git add hello.js => git commit hello.js => Then config the user.name and user.email ![image](https://github.com/PhuocOng/setup_repo_viettech/assets/122703392/faee90fb-3ddd-411c-9d3c-a22dd5df8229) <br />
**Step 6:** git push => Follow the instructions to push to remote repo  <br />
**Step 7:** (Optional) Watch video at : https://www.youtube.com/watch?v=p0Js7IF17yI


## **HOW TO SET UP SSH KEY FOR GITHUB**  <br />
**Window** <br />
**Step 1:** Open Git bash <br />
**Step 2:** ssh-keygen -t ed25519 -C "your_email@example.com" => Enter <br />
**Step 3:** clip < ~/.ssh/id_ed25519.pub => It will copy into our clipboard then we can CTRL + V to see it <br />
**Step 4:** Login to Github Account => Setting => SSH and GPG Keys => New SSH Key => Title: Personal Laptop - Key Type: Authentication key - Key: Pasting your key into here!  <br />
**Step 5:** Test connection: "ssh -T git@github.com" <br />
**Step 6:** (Optional) Watch this video: https://www.youtube.com/watch?v=X40b9x9BFGo <br />

**Mac** <br />
**Step 1:** Open Git bash <br />
**Step 2:** ssh-keygen -t ed25519 -C "your_email@example.com" => Enter <br />
**Step 3:** $ pbcopy < ~/.ssh/id_ed25519.pub => It will copy into our clipboard then we can Command + V to see it <br />
**Step 4:** Login to Github Account => Setting => SSH and GPG Keys => New SSH Key => Title: Personal Laptop - Key Type: Authentication key - Key: Pasting your key into here!  <br />
**Step 5:** Test connection: "ssh -T git@github.com" <br />
**Step 6:** (Optional) Watch this video: https://www.youtube.com/watch?v=cGcpVQlhbuI

## **HOW TO SET UP POSTMAN** <br />
**Window** <br />
**Step 1:** Sign in/Sign up into https://web.postman.co/home <br />
**Step 2:** Go to https://www.postman.com/downloads/ and dowload your version (ex: window 64-bit)  <br />
**Step 3:** Click into .exe postman file to extract <br />
**Step 4:** Cick Login to run the postman program <br />
**Step 5:** If it ask for permission, ticked "allow public network" <br />
**Step 6:** (Optional) Watch this video: https://www.youtube.com/watch?v=pBo_oClYjjM

**Mac** <br />
**Step 1:** Sign in/Sign up into https://web.postman.co/home <br />
**Step 2:** Go to https://www.postman.com/downloads/ and dowload your version (ex: Mac Intel Chip / Mac Apple Chip)  <br />
**Step 3:** Click into dowloaded postman file to extract <br />
**Step 4:** Cick Login to run the postman program <br />
**Step 5:** (Optional) Watch this video: https://www.youtube.com/watch?v=i9FQWDx8NIY

## **HOW TO SET UP Oh My Zsh!** <br />




