Step #1 - Create separate repo/folders

FrontEnd:
Step - #2 - Installing Angular CLI in the UI repo

Step - #3 - Create new Angular app

Step - #4 - verify if the app is up and running

Step - #5 - Install bootstrap framework - v5.3.2
Step - #6 - Install jquery

Step - #6 - Setup bootstrap files in angular.json

In the angular.json-> projects-> projectName -> architect -> build -> options -> styles[]
add this line -> "node_modules/bootstrap/dist/css/bootstrap.min.css"
In the angular.json-> projects-> projectName -> architect -> build -> options -> scripts[]
add this line -> "node_modules/jquery/dist/jquery.min.js" (if you have used jquery)
add this line -> "node_modules/bootstrap/dist/js/bootstrap.bundle.min.js"

BackEnd:
1 -> Be inside the backend folder (loans-api)
$ npx express-generator


