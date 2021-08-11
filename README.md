<div align="center">
  <h1>WordNook</h1>
  <img src="assets/Wordnook banner.png" />
</div>

<hr>
  
<div align="center">
 <h1>A sneak peek into what we have here</h1>
 
![wordnook](https://user-images.githubusercontent.com/54665036/120497609-2e2f3800-c3dc-11eb-96a5-e72dfab93013.gif)


</div>

<hr>

<div align="center">

## About-

![Forks](https://img.shields.io/github/forks/ALPHAVIO/WordNook?style=social) ![Stars](https://img.shields.io/github/stars/ALPHAVIO/WordNook?style=social) [![GitHub issues](https://img.shields.io/github/issues/ALPHAVIO/WordNook?color=green&logo=github&style=flat)](https://github.com/ALPHAVIO/WordNook/issues) [![GitHub PRs](https://img.shields.io/github/issues-pr/ALPHAVIO/WordNook?style=flat&logo=github)](https://github.com/ALPHAVIO/WordNook/pulls) ![Dependabot Status](https://api.dependabot.com/badges/status?host=github&repo=ALPHAVIO/WordNook)  
<!-- **DeepSource:** [![DeepSource](https://deepsource.io/gh/ALPHAVIO/WordNook.svg/?label=active+issues&show_trend=true)](https://deepsource.io/gh/ALPHAVIO/WordNook/?ref=repository-badge) -->
	
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-28-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

[![Discord](https://img.shields.io/badge/Join_ALPHAVIO_Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/9SgPjvhqEj)
	
- 'Blog' and 'blogging' are now loosely used for content creation and sharing on social media, especially when the content is long-form and one creates and shares content on regular basis.  

[![Edit with Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/ALPHAVIO/WordNook)

- This is a dynamically updating Blog posting website developed primarily using Node Js with EJS template engine and Mongoose as ODM(Object Data Modeling library).  
[Visit website](https://word-nook.herokuapp.com/)

</div>

<hr>

## Technology Stack 🛠️

- **Coding Languages**: <img alt="JavaScript" src="https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/> <img alt="HTML5" src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white"/> <img alt="CSS3" src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white"/>

- **Tools & Frameworks**: <img alt="NodeJS" src="https://img.shields.io/badge/node.js%20-%2343853D.svg?&style=for-the-badge&logo=node.js&logoColor=white"/> <img alt="Express.js" src="https://img.shields.io/badge/express.js%20-%23404d59.svg?&style=for-the-badge"/> <img alt="MongoDB" src ="https://img.shields.io/badge/MongoDB-%234ea94b.svg?&style=for-the-badge&logo=mongodb&logoColor=white"/> <img alt="Mongoose" src ="https://img.shields.io/badge/Mongoose-%234ea94b.svg?&style=for-the-badge&logo=Mongoose&logoColor=white"/> <img alt="EJS template engine" src="https://img.shields.io/badge/EJS template engine%20-%23039BE5.svg?&style=for-the-badge&logo=EJStemplateengine"/>

- **Project Management Tools**: <img alt="GitHub" src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white"/> <img alt="Git" src="https://img.shields.io/badge/git%20-%23F05033.svg?&style=for-the-badge&logo=git&logoColor=white"/>


<hr>

## Environment Setup for local use-

* Drop a :star: on the GitHub repository.
<br/>

* Download [Git](https://git-scm.com/downloads) (when you install Git, Git Bash also gets installed by default)
<br/>

* Download and install a code/ text editor.
    - Recommended-
        - [Download VS Code](https://code.visualstudio.com/download)
        - [Download Atom](https://atom.io/)
<br/> <br/>

### Option 1 (Installation using NPM and MongoDB) 

* Download [Node Js and npm(Node package manager)](https://nodejs.org/en/) (when you install Node, npm also gets installed by default)
<br/>

* Mongo DB community editition is free and a great software in order to work with MongoDB applications. [Download Mongo DB community editition](https://docs.mongodb.com/manual/administration/install-community/)
<br/>

* Robo 3T is a desktop graphical user interface (GUI) for Mongo DB. It can help to skip running all the Mongo DB commands manually every time we want to access the data. [Download Robo 3T](https://robomongo.org/download) **(optional)**
<br/>

* Clone the repository by running command
```
git clone https://github.com/<your user-name>/WordNook.git
```
in your git bash.
<br/>

* Run command `cd WordNook`.
<br/>

* Run this command to install all dependencies for the project.
```
npm install
```

<br/>

* Adding secret key for JWT auth.
  * Run this command when inside the root directory to make a `.env` file.
  ```
  touch .env
  ```
  * Now add this to the `.env` file
  ```
  SECRET_KEY = AlphaVio
  URL = mongodb://localhost:27017/wordnookDB
  ```
<br/>

* Testing : Run this command on your terminal/ bash to start the Mongo server on port 27017(default).
```
mongod
```
<br/>

* Run this command to start the project.
```
npm start
```

or

* Run this command to start the project as a developer.
```
npm run dev
```
<br/>

* Open link to view the website in your browser window if it doesn't open automatically.
```
http://localhost:3000/
```
<br/>

### Option 2 (Installation using Docker)

* Download and install [Docker](https://www.docker.com/products/docker-desktop).

* Clone the repository by running command
```
git clone https://github.com/<your user-name>/WordNook.git
```
in your git bash.
<br/>

* Run command `cd WordNook`.
<br/>

* Run this command to start the project:

```
docker-compose up --build 
```

* Now explore the project and make the changes as you want. Once the changes are made then run the following command again:
``` 
docker-compose up --build 
```
This would again create a new image with your changes and will use it to start the containers. Now when you visit `http://localhost:3000/` you would see your changes.

* Once you are satisfied and want to make a PR then run following command:
``` 
docker-compose down 
```
This would stop all the running containers and will also delete them.
<br/><br/>

* Check out our docker image at DockerHub: [Wordnook Image](https://hub.docker.com/r/alphavio/wordnook) or you can directly search `wordnook` on [DockerHub](https://hub.docker.com/search?q=&type=image) (This just for your reference and is not required for installation)

* You can learn more about Docker and its implementation at [Docker Documentation](https://docs.docker.com)

* You can learn more about EJS template engine and its syntax to know how we can use it inside our HTML using the [documentation](https://ejs.co/#docs)
<br/>

* Now you are all set to use this project.  

#### Some useful Mongo DB commands if you are using the terminal instead of the GUI-
```
show dbs
use db <db name>
show collections
<db name> .find()
```

#### Project Deployed on Heroku : [Visit WordNook](https://word-nook.herokuapp.com/)

<hr>

### Note -

<!-- 1. **You must lint your code before making any Pull Request** 
	- To check for any linting errors, run command:
	```
	npm run lint-check
	```
	- To fix linting errors, run command:
	```
	npm run lint
	```
	**Check again for any errors that need to be resolved manually and if the application works fine after you lint the code.**   -->

1. - If your git shows an issue with your `package-lock.json` while installing dependencies or throws error that **lockfile version-2** is not compatible with your system
	Then check your npm version by running command
	``` 
	 npm --version
	```
	- **npm version should be 7 and above for lockfile version-2 that would come by default if you have a node version 15 and above.**  
	[List of Node.js releases and corresponding npm versions](https://nodejs.org/en/download/releases/)

	- After upgrading your npm version, you can delete your `package-lock.json` file and run `npm install` again to fix the issue.


<hr>

## Stargazers over time 🌟

[![Stargazers over time](https://starchart.cc/ALPHAVIO/WordNook.svg)](https://starchart.cc/ALPHAVIO/WordNook)
      
