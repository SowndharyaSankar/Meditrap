# Meditrap
MEDITRAP
----------------------------------------------------------
This is a web application that allows users to digitally send and receive prescription from doctors and it also allows the users to identify the nearby pharmacies via the google map.
Features
----------------------------------------------------------
•	Sends and receives prescription digitally.
•	Searches for drugs in the nearby pharmacy.
•	Directs the user to the pharmacy.
Prerequisites
----------------------------------------------------------
•	Node installer
•	Mongodb installer 
•	Atom IDE
Node installer:
•	The installer for respective operating are needed to be installed in the systems. 
•	Installer: https://nodejs.org/en/download/
•	Steps to install node and setup in system: 
https://www.youtube.com/watch?v=tlntE8fe6u4 (for windows)
•	To check whether it is installed correctly or not:
	Open command prompt and type node. It shows the version installed.
Mongodb installer:
•	Mongo Db also has installer for different operating system.
•	Installer: https://www.mongodb.com/download-center#atlas 
•	Installation process: https://docs.mongodb.com/manual/installation/
	If the mongodb is installed properly then, it will connect to the mongodb server and connection to server and database can be established easily.
Atom IDE:
Atom is a free and open-source text and source code editor for macOS, Linux, and Microsoft Windows with support for plug-ins written in Node.js, and embedded Git Control, developed by GitHub.
•	Atom to download for windows: https://atom.io/ 
•	Installation: https://www.youtube.com/watch?v=nshxC0YO_X0 
Creating a new project
	To create a new project using above prerequisites the following steps are used.
1.	Open command prompt.
2.	Set path to desktop.
3.	Create a new folder to a desired location (here it is desktop).
4.	Move to the folder.
5.	Type the command npm init.
6.	Leave all defaults.
7.	Some packages required to run the project are installed inside the folder.
8.	Open atom and select the folder.
9.	In that go to package.json file.
10.	Enter the code to start the project project.
“start”: “node index.js” where index.js is the file from which the node starts running the project folder.
11.	Go to command prompt and type npm start
12.	If any output statement is given in the file that will be executed in the command prompt.
13.	Then try to create a simple http server.
(https://www.w3schools.com/nodejs/default.asp )
14.	To run the server type npm start again in the command prompt.
15.	To create an api for an application express is required, so go to the place of folder i.e, desktop.
16.	Type npm install –g express-generator which installs express.
17.	To check installation type express –version in command prompt and it would show the version of express installed.
18.	Required packages can be installed by typing the command npm install package name
19.	To install dependencies go to folder and type npm install only.
20.	Api’s required for an application can be done in a single file itself.
Running a project
1.	Open command prompt and type node. It connects to the node installed.
2.	Open another command prompt and type mongod which connects database with the mongo server.
3.	Open another command prompt and type mongo to work with database and collections. 
4.	Open another command prompt and move to the project folder.
5.	Now type npm start. This runs the project at the host mentioned.
The project runs only when all the four command prompts run simultaneously. Each time when there is a change in the server programming the stop the server by clicking ctrl+c and give npm start again inodder to make change permanently in the server.
Files & folders in the project
-------------------------------------------------------------------------------
bin folder
   www file
	Module dependencies required for executing a server are located in this file. HTTP server and event listeners for the servers are implemented here. This file is installed by npm itself. When server is started the node starts executing from this file only.
Node-modules folder
	It consists of all modules of dependencies required to run a project.
Public folder
	It includes three folders in which images, java scripts and css files required for the project can be added. In this project there are no files in the folders except a simple css that has not called.
Routes folder
	The main folder in which the frontend and backend present. All the html pages developed for the project has been placed here. A server file named login.js file which contains backend programming is also located here.
  Login.js file 
	It consists of server programming that includes all display code of html pages, api for database, etc.


Services folder
It has a file to establish a connection between server and mongodb using a mongo driver.
Views folder
  App.js file
	It creates variables for all installed dependencies. calls a require function for it. The path required must be specified here. The backend file to be executed is directed from this file only.
Package.json file
	Gives details about the express and dependencies installed
Package-lock.json file
	Gives detailed description about the dependencies installed.
Code implementation
-------------------------------------------------------------------------------
  



