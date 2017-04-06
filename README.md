<h4>==========================================</h4>
<h1> Template for Django-React </h1>
<h4>==========================================</h4>
<br/>
<h4>
	The Django DRF for REST calls, and nodejs server serving React pages<br/>
	Webpack + npm for the management of node/react modules
</h4>


<h3>
Project Name:&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp <i>streak</i><br/>
Application name: 	&nbsp <i>streaker</i>
</h3>
<br />
<h3>To setup:</h3>

```bash
#installs django 
$pip install django			

#installs webpack integration with django
$pip install django-webpack-loader	

#inits npm
$npm init				

#this should install all the npm packages in package.json
$npm install
	
#this will compile your jsx files into js files according to webpack.config.js
$/node_modules/.bin/webpack --config webpack.config.js

#React components will be served by a node server, defaulting from port 3000
$node server.js				  
```
