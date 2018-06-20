## VueJS Sample Project

This is a sample VueJS project bootstrapped via webpack 4 to assist new students in learning how to easily setup a VueJS project from scratch.

Effort has been taken to balance between simplicity and features.

### Step 1: Fork this Repository

Click the **Fork** button at the top right side of this repo

A copy of the project will be copied to your Github Account

### Step 2: Clone the Repo

Once the Fork is complete and the project is copied to your Github Account clone the project to your local machine (Do this on the new project that has been cloned to your Github Account).

```
1. Open Command Prompt and create a new folder for storing your project
2. Navigate to that folder using the cd command
3. Clone the repository using git clone command
- you can find your clone url by clicking clone or download
in the repository on your Github account

```


### Step 3: Install Dependencies

Once the project is cloned to your local machine install dependencies by running npm install command. Make sure this completes successfully, if it fails cancel the operation and try again

**NB:** npm install must be run inside your project directory.

```
npm install
```

### Step 4: Run the development server

This setup comes preconfigured with a development server that we can use
to test the application during development. Type the following command in your Command Prompt to start it.

```
npm start
```

### Step 5 - Preview the App during development

The development server runs on port 8080 on localhost. Visit this url in your browser to see the app running

http://localhost:8080

### Step 6 - Make changes and continue developing

At this point everything is setup to allow you to continue developing your app

Your browser will automatically reload any new changes you make to the code so you can preview much faster.

Watch for errors in your **Terminal/Command Prompt**

**NB:** Your Terminal/Command Prompt must remain open during development as it runs the development server which  we are accessing via the localhost url

### Notes:

1. Every time you want to work on the app you have to run the `npm start` command from the root of your project.

2. When you are done developing you can stop the server by pressing `Ctrl + c` in your command prompt.

3. You can not have multiple instances of the server running on the same port. If you have problems accessing the preview url check to see if you have a command prompt window already running the app.

4. The default preview url is http://localhost:8080 but it can be modified in the future.

5. After you have completed your development server you can generate production ready code (code that can be published online) by running the command `npm run build` your project will be compiled and copied to the `dist` directory/folder in the root of your project.

6. Always watch for errors in your command prompt during development. If there's a syntax error in your code, the command prompt will display it.
