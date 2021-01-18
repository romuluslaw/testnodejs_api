# Currency Exchange API – NodeJS

1) save as a template from the devops site 
2) Use branches track and approve the following amendments: 
   email changed to myself 
   docker run changed to my own docker 
   set action - docker run check 
   set applet a push notification to telegram for every pull request to this link - note code in the git action here
3) tested through the google shell and MS visio its ok 

Note if use MS visio to test, copy the entire app.js. First install  express (npm i express). Then run it (node app.js). check the results with this URL - http://localhost:8080/fx
 

docker run -d -p 8080:8080  romlaw/testnodejs_api

curl -i http://localhost:8080/fx
