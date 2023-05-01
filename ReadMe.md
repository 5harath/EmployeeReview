
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
ª   .gitignore
ª   index.js
ª   package-lock.json
ª   package.json
ª   ReadMe.md
ª   
+---assets
ª   +---css
ª           adminEmployee.css
ª           adminPerformance.css
ª           adminPerformanceAction.css
ª           employeedashboard.css
ª           layout.css
ª           signin.css
ª           signup.css
ª           submitfeedback.css
ª           
+---config
ª       environment.js
ª       flashMessageMiddleware.js
ª       mongoose.js
ª       passport-local-strategy.js
ª       
+---controller
ª       admin.js
ª       adminAction.js
ª       employee.js
ª       index.js
ª       
+---models
ª       admin.js
ª       employee.js
ª       performance.js
ª       
+---routes
ª       adminEmployee.js
ª       adminPerformanceReview.js
ª       employee.js
ª       index.js
ª       
+---views
        adminEmployee.ejs
        adminPerformance.ejs
        adminPerformanceAction.ejs
        employeeDashboard.ejs
        layout.ejs
        signIn.ejs
        signUp.ejs
        submitFeedback.ejs
