# express-scaffold

An express scaffold app written in ES6 syntax that functions as a REST API connected to a MongoDB database.

1. Download
============================

git clone https://github.com/alanacial/express-scaffold
cd express-scaffold/
npm install

2. Setup MongoDB
============================

3. Configure
============================

configure app by replacing the values in 'src/config.json.example' with real values,
setting the port, as well as the username and password to the MongoDB.

Then rename 'config.json.example' to just 'config.json'.

4. Build & Run
============================

npm run build (or npm run dev)
npm start (or nodemon)

This should create a `dist/` folder that your app will execute from.

5. Test End Points
============================

Using a browser or utility (like Postman), end points should be at localhost:<PortNumber>

Still a work in progress.