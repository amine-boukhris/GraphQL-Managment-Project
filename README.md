# Welcome
- this was made using create-react-app for some reason, which is really bad...
- main focus of the project was GraphQl

## Credits
- this is a course project
- made by Traversy Media at:
- https://www.youtube.com/@TraversyMedia

## Install and run locally
- clone repo
- run `npm install`
- create a .env file in the root directory
- add the following to .env file
```
NODE_ENV=development
PORT=5000
MONGO_URI=<your_mongodb_url>
```
- you can use a local mongo database or connect to the cloud via mongodb atlas
- run `npm start` or `npm run dev` (require nodemon) in the root directory to start the server
- change directory to the client and run `npm start` and open the browser on given port (3000)
- make sure that the PORT in .env file match with the apollo client url in the App.js file
- you can open graphiql by going adding `/graphql` to the server url 
