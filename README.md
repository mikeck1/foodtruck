# foodtruck-api  --- (▀̿Ĺ̯▀̿ ̿)
<h2>Node.js express mongoose+mongodb ES6 babel body parser</h2>
<h3>API backend for adding foodtrucks w/ details, and reviews.</h3>
<h4>Use Postman or web/mobile client to control API.</h4>
<p>demo [will not work in browser (aside from view all/byID trucks), use postman! V</p>
<p>In Postman, for your header.. key:Authorization value: Bearer INSERT_TOKEN_HERE</p>
<p>Also, for body, click raw and toggle to JSON application/json (Same process for editing/adding a foodtruck)</p>
<code>https://3dgreens.com/api/v1/account/register</code>
<code>https://3dgreens.com/api/v1/account/login</code>
<code>https://3dgreens.com/api/v1/foodtruck/add</code>
<p>To View Food Trucks use postman or a browser</p>
<code>View All -> https://3dgreens.com/api/v1/foodtruck 
View One -> https://3dgreens.com/api/v1/foodtruck/UNIQUE_ID 
  https://3dgreens.com/api/v1/foodtruck/UNIQUE_FOOD_TYPE
</code>
<h5>Refer to model and controllers for CRUD requests</h5>
<br></br>
<h4>How to install: (Assuming MongoDB is installed/running and Node.js is installed)</h4>
<p>First, Pull up terminal</p>
<p>Get the git file and install dependencies</p>
<code>git clone https://github.com/mikeck1/foodtruck-api.git</code><br></br>
<code>cd foodtruck_api</code><br></br>
<code>npm install</code>
<p>To run:</p>
<code>npm run dev   // Runs in dev mode</code>
<br></br>
<p>If running on server in production environment</p>
<code>npm run build   // Builds a dist</code><br></br>
<code>npm install -g pm2    // popular production daemon (pre-config'd in package.json)</code><br></br>
<code>npm start  // Injects & Runs instance dist and pm2 for daemon</code><br></br>
<code>sudo pm2 startup systemd  // Runs pm2/dist at startup</code><br></br>
<code>sudo apt-get install nginx  // go between server and api</code><br></br>
<code>sudo nano /etc/nginx/sites-available/default</code><br></br>
<p>Refer to google to configure nginx routing on your machine</p><br></br>

<code></code><br></br>
