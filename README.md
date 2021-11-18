# express-authentication-firebase
MIT week 26 firebase assignment for express and firebase authentication 

A basic frontend form (index.html)
A server file (index.js)
An admin configuration file (admin.js)
A login.js configuration file (login.js)

At a high level, you will:

Take the token presented to browser client
Add the token to the HTTP header
Pass the token to the back end
Use a Firebase package to verify the token

 View the server file, index.js. There, you will see that Express is required along with two routes. One route is not authenticated (the open route) and one route is authenticated. You can see that the authenticated route needs to examine and verify the token that is being passed in.

 Install your packages

Now, install express and the firebase packages. Do so by running the following commands in your command line:

npm install

npm i firebase

npm install firebase-admin --save
Note: you can see the dependencies for the project that get installed with this command by looking at the dependencies section of the package.json file.

7. Run your server and test your routes

To run your server, run the following command: 

node index.js


Then, navigate to localhost:3000/login.html
<img width="1175" alt="Screenshot 2021-11-18 at 6 16 14 PM" src="https://user-images.githubusercontent.com/81912588/142397486-1f41fb57-19cf-4d53-9a62-21954b70b364.png">
![Screenshot 2021-11-18 at 6 13 41 PM](https://user-images.githubusercontent.com/81912588/142397509-590c6378-67b7-40d7-8397-e43ed5996115.png)
![Screenshot 2021-11-18 at 6 11 34 PM](https://user-images.githubusercontent.com/81912588/142397516-44566511-fcbe-4053-8965-341c34adee84.png)
![Screenshot 2021-11-18 at 6 11 01 PM](https://user-images.githubusercontent.com/81912588/142397519-cb826a66-023e-43b2-9504-abd436d0c38f.png)
![Screenshot 2021-11-18 at 6 10 36 PM](https://user-images.githubusercontent.com/81912588/142397524-87462e72-48e0-4008-af8a-aa842d6d34f9.png)

MIT-Auth-Routes.json contents have been deleted so you need to go to firebase and generate a new project and new private key under Service Accounts.  Please keep this info strictly private.

apiKey, messagingId, and appId also deleted so you need to go to your firebase project and copy your configurations to login.js file
