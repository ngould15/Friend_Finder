# Friend_Finder

<h1>Project Description</h1>

The user will take a 10 question survey, where they give answers on a scale of 1-5.  Once the user submits the survey, they will be matched up with a friend who is the most compatible for them, based on the answers they have submitted.

![Most Compatible Friend](../master/images/BestMatch.png)

The FriendFinder is a full stack node app deployed on heroku. It uses Express to configure and operate the server, Body-Parser to pass the JSON data back and forth between files & functions, and fs to read & write from the data files on the server.

 Various routes are setup to complete the survey, view the JSON API, and post data into the app. A general catch-all route will bring all users to the homepage, regardless of the path the user attempts to access. Deployment on a node server is required. This app is setup to listen on a Heroku default port.
