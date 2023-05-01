
## Admin Access
Email Id for Admin is "admin@example.com" and Password is "admin" 

## To Sign In 
A user need to type Email_Id , Password , And there role in organization such as : Admin or Employee
Then Click On Submit Button

## To run the on local machine

* Download the zip file from download option about or do a git pull request from github URL above
* Navigate to the folder where package.json is present
* Type 'npm install' to install all the dependency (node.js should be installed on the system)
* Type 'npm start' to deploy the app on the local machine
* Navigate to 'localhost:8000' to open the app
* Signup if you have not already signed up to open the app

## Website hosting
the website has been hosted here https://spotless-sombrero-eel.cyclic.app/

## Folder stucture
*   .gitignore
*   index.js
*   package-lock.json
*   package.json
*   ReadMe.md
*   
+---assets
*   +---css
*           adminEmployee.css
*           adminPerformance.css
*           adminPerformanceAction.css
*           employeedashboard.css
*           layout.css
*           signin.css
*           signup.css
*           submitfeedback.css
*           
+---config
*       environment.js
*       flashMessageMiddleware.js
*       mongoose.js
*       passport-local-strategy.js
*       
+---controller
*       admin.js
*       adminAction.js
*       employee.js
*       index.js
*       
+---models
*       admin.js
*       employee.js
*       performance.js
*       
+---routes
*       adminEmployee.js
*       adminPerformanceReview.js
*       employee.js
*       index.js
*       
+---views
*       adminEmployee.ejs
*       adminPerformance.ejs
*       adminPerformanceAction.ejs
*       employeeDashboard.ejs
*       layout.ejs
*       signIn.ejs
*       signUp.ejs
*       submitFeedback.ejs

