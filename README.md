# express-scaffold

An express scaffold app written in ES6 syntax that functions as a REST API connected to a MongoDB database.

1. Download
============================

git clone https://github.com/alanacial/express-scaffold
cd express-scaffold/
npm install

2. Setup MongoDB
============================

Create a MongoDB

Optional: mlab.com can host MongoDBs for free. See the following steps for a walk through.
 1) Create a free account
 2) Select "Create new" to create a new deployment
 3) Select "Single-node"
 4) Select Sandbox (free) under "Standard Line"
 5) Name the database
 6) Click "Create new MongoDB deployment"
 7) Select the deployment
 8) Click "Add collection"
 9) Type in collection name (by default type in "MongoCollection")
 10) Take note of the resulting MongoDB URI and drop that into the config file as seen below

3. Configure
============================

Configure the app by replacing the values in 'src/config.json.example' with real values,
setting the port, as well as the username and password to the MongoDB.

Then rename 'config.json.example' to just 'config.json'.

4. Build & Run
============================

npm run build (or npm run dev)
npm start (or nodemon)

This should create a `dist/` folder that your app will execute from.

5. Test End Points
============================

Using a browser or utility (like Postman), end points should be at localhost:3000

Still a work in progress.