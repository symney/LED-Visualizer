# LED Visualizer
<br>This is a python webserver that allows you to control a sequence of led lights with custom commands all from your phone. Unlike store bought versions of typical LED lights, you actually have control of every led in the strip and each light can change color on a full range of RGB. It also has the capability to integrate with alexa voice commands.<br>
<br>
The coolest part about this project however is that is can create light sequences based off of the waveform of a song


<h1>The features from version 1</h1>
* Persistent login and login storage<br>
* Real time messaging<br>

<h1>New Features</h1>
Updated Login Security and fields<br>
User Searching<br>
Multiple chat Windows<br>
Persistent Messaging<br>
Private Messaging<br>
Profile Pictures<br>
File Uploads<br>
Typing Indicators<br>



<h1> The Tech Stack</h1>
* MongoDb to store user login information and chat data<br>
* Multer for file Uploads<br>
* Passport JS for login security<br>
* Express For networking with Node.js<br>
* NodeJS as the backend js runtime enviornment<br>
* HTML/JS/CSS for the visuals<br>
* SOCKET IO for the real time messaging protocol,typing indicators, and searching<br>
<h1>How to set up</h1>
1) install Node .js<br>
2) clone the project to a folder<br>
3) run npm install<br>
4) Set up a mongo database and replace the database uri with your uri<br>
5) node index.js<br>


<h1> Usage Notes</h1>
Create an account first by using create account button once an account is created you will be taken to the application automatically <br>
* The live chat is where you can anonymously send messages to every user in the application with message persistence<br>
* Pressing the button in the chat window on the bottom right is for file uploads. To send your message press enter.



