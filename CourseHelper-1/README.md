# CourseHelper

* An app to help a teacher with an outline and some content ideas for a course given a set of instructions in a system agent and the user provided course plan.
* The app should have a server handling the requests to OpenAI API and the system agent instructions.
* User agent instructions should be sent in to the server via a REST API
* The first front end for users should be a web page, with a form accepting a text or a file with the course contents.
* The return should be presented nicely in the webpage and preferably be easy to copy.
* An optional feature is delivery of a downloadable generated .pdf out from the page.
* Update from Zoom 28/11-24
    * Kursplan = Webbutveckling... eller AI...
    * Kursinstruktion = Flipped


# server.js
To run server.js
1. Go to project directory in terminal
2. run command: `npm install`
3. run command: `node server.js`
4. go to http://localhost:3000/


# openAiClient.js
setup:
1. Create an .env file in the project root folder
2. Put this line in it and replace with your actual key: 
    OPENAI_API_KEY=your-api-key-here

