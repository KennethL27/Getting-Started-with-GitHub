# Download
### *For Windows 10*

1. Vist: [link](https://git-scm.com/) and Download the Latest Version (currently 2.20.1).
2. Go through the download, no settings needs to be changed but you may changed them if you like. 
3. Now once the download is complete you may hit the Finish button. 
4. Using the search bar on your Windows computer opening up `cmd`. (command line prompt)
5. To set your name (used for when you contribute to a repo) use: `git config --global user.name "INSERT NAME"`

### *The folowing steps are for setting up your GitHub to git*
1. In your command line use `git config --global user.username "INSERT USERNAME"`, *Note: this username is the same username you use on GitHub*
2. To connect your email use `git config --global user.email "INSERT EMAIL"`,  *Note: this email is the same email you use on GitHub*
3. Make a directory either by creating one with the file explorer or using `mkdir <file_name>`. Then enter the directory in the command line (`cd <file_name>`).
4. Use `git init` to create a git repo in the current directory. 
5. If there is a repo that you are already apart of and need to initalize a "pull" then use `git pull https://github.com/user-name/repository.git`
6. Now since its the first time pulling from this repo, you need a "Personal Access Token".
7. With access to the repo you must create a remote repo by using `git remote add <name_of_origin> https://github.com/username/repository.git`.
8. To pull the most up to date files use `git pull <name_of_origin> master`

### __Getting Access Token__ *Note: you must have your email verified before procceeding*
1. Go to your GitHub page. 
2. Click on the drop down bar on your profile and click "Settings"
3. Now scroll down and on the left side there will be a "Developer settings", click on that.
4. On the left side click "Personal access tokens".
4. Now click on the "Generate new token"
5. Select the options you want the token to have. This can be changed at a later date.
6. Now click on "Generate token"
7. Copy the token and paste it into the window from previous section's step 6.
