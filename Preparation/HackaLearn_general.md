# Preparing for HackaLearn

To enjoy HackaLearn please come with your computer set up with the following:

1. Azure account
2. Node.js
3. npm
4. Git
5. GitHub account
6. IDE (VS Code for instance)

See further instructions below.

Further prerequisites are subject to the specific event. For instance, framework installation.

## Azure
HackaLearn involvs working with Azure. You can [open a free account](https://azure.microsoft.com/free/?WT.mc_id=javascript-20968-shjacobs) with $200 credit. 

Some events may supply Azure Passes with which you can open an account with fewer steps (no credit card required). 
The passes have a limited lifetime, and you can transform the account to a regular free account (with the $200 credit) afterwards. 

## Node.js and npm

Node.js allows running JavaScript code on your computer. 
Not only does it help when developing servers locally, but it enables many tools that Web-developers work with. 

Node.js comes with npm built in.

Check whether you have the latest version of Node.js and npm. Some tools require a minimal version (you may get an error message when trying to install them).

Install Node.js from the official website: https://nodejs.org/

If you have projects that require older versions of Node.js, use a [Node Version Manager](http://npm.github.io/installation-setup-docs/installing/using-a-node-version-manager.html).

Once you have Node.js installed, check the version of npm by running 
```
npm -v
``` 
and update it if needed with 
```
npm i -g npm
```
You may need to run this command with `sudo` if it alerts for permission denied.
```
sudo npm i -g npm
```

## Git
Git is a free and open source distributed version control system. Besides the many benifits of source control (preserving older versions and managing collaboration), you'll need it to connect your project to GitHub.

Install Git from the official website: https://git-scm.com/

## GitHub
GitHub is an online code repository, where you can share your code and manage collaboration. 

We'll use GitHub to
1. deploy the app on Azure Static Web Apps
2. manage the HackaLearn - the message board is part of this repository.

If you don't already have a GitHub account, please create one: https://github.com/join

## IDE (VS Code)
IDE is an Integrated Development Environment. In simple words, it's a super-powered code editor.

You can use the IDE of your choice. If you don't already have one, we recommend VS Code.

VS Code is an rich, open-source (free) IDE. 
Get it here: [https://code.visualstudio.com/](https://code.visualstudio.com/?WT.mc_id=javascript-20968-shjacobs)

### VS Code Tips 
- Configure VS Code to run with the `code` command on terminal:
https://stackoverflow.com/questions/30065227/run-open-vscode-from-mac-terminal

- Configure VS Code to auto-save: Open `Code -> Preferences -> Settings`, search for "auto save", and change the `Files: Auto Save` to "onFocusChange".

