#Command, tutorials, documentation

##MERN

####Install Node.js, MongoDB, Express, React.

####Start React server (in project folder)

	npm start

####Start nodemon server (in project's backend)
	
	nodemon server

If that command don't work:

*First add this lines to backend's package.json*

	"scripts": {
	    "serve": "nodemon server.js"
  	},
*Start server with:*

	npm run serve

###To run the database server

	mongod
	

