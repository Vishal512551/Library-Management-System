# Library Management Mystem




## Technologies used
- HTML
- CSS
- Bootstrap
- Javascript
- Node.js
- Express.js
- Mongodb
- ejs




## Installation and Setup
1. Install all the dependencies
	sh
	npm install
	
2. Create a file named ".env" and enter the following credentials:
	js
	MONGO_URI=your-mongo-uri
	
3. Run the application
	sh
	npm start
	
4. Open http://localhost:5000
5. You need to first signup and then login as admin or student to run the application.
6. Admin signup page can't be accessed from the application. However, I have created a hidden route to access the page: /auth/admin-signup
