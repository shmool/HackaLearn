# Preparing an Angular environment

Make sure you have Node.js version 12.14 or 14.15 and npm.
The Angular CLI requires a minimum Node.js version of either v12.14 or v14.15.

## Install the Angular CLI globally
After installing Node.js and npm, run the following commands in the terminal.

Check if you already have the Angular CLI installed by chance.
```
ng v
```

If you do, uninstall it to get the latest version
```
npm uninstall -g @angular/cli
npm cache verify
```

Install Angular CLI
```
npm install -g @angular/cli@latest
```

Go to your project folder where you want to create your Angular project.

Run:
```
ng new HackaLearn
```
This will create an Angular project called HackaLearn.

You will be presented with two questions.

1. Would you like to add Angular routing? Select *Yes*.
2. Which stylesheet format would you like to use? Select *SCSS*.

An Angular project is being created. 
When it's done, enter the folder HackaLearn.
```
cd HackaLearn
```

Run the application.
```
ng serve
```

Open the application in the browser, at 
```
localhost:4200
```

You should see the boilerplate app with its name:
![image](https://user-images.githubusercontent.com/4953875/119804210-6e744f00-bee0-11eb-8c5f-f862d6425843.png)

## Open the app in your IDE
If you're using VS-Code and have it installed in PATH, simply run 
```
code .
```
in the terminal, when inisde the project folder. (Otherwise, specify the path to the project, for instance `code HackaLearn`.)

Or, open the IDE, fo to `File --> Open workspace` and select the HackaLearn folder.

### VS Code tip
Install the [Angular Essentials Extension Pack](https://marketplace.visualstudio.com/items?itemName=johnpapa.angular-essentials) by John Papa.

