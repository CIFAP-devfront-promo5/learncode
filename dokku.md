    node:
	procfile]]	web: node app_name.js
	package.json
	...
		"optimist": "~0.5.0",
 		"pg": "~1.1.2",
 		"jsdom": "*",
 		"underscore": "~1.4.4"
	},
	app.js
	pg.connect(process.env.DATABASE_URL, function(err, client, done) {
    python:
        procfile
        web: gunicorn app_name:app
	    requrements.txt

***

`dokku help`

`dokku postgres:create app_name`

`env var DATABASE_URL`

`dokku postgres:info app_name`

`dokku postgres:logs app_name`

`git remote add dokku dokku@zxtiger.com:node-js-sample`
