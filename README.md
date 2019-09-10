#Express Boilerplate
This is a boilerpolate to start new Express/Node projects
##Set Up
Complete the following steps to start a new project (NEW-PROJECT_NAME):
1. Clone this repository to your local machine `git clone BOILERPLATE-URL NEW-PROJECTS_NAME`
2. `cd` into the cloned repository
3. Make a fresh start of the git history for this project with `rm -rf .git && mgit init
4. Insall node dependencies `npm install`
5. Move the example Environment file to `.env` that will be ignored by git and read by the express server `mv example.env .env`
6. Edit the contents of the `package.json` to use NEW-PROJECT-NAME instead of `"name": "express-boilerplate".`

## Scripts
Start the application `npm start`
Start nodemon for the application `npm run dev`
Runt he tests `npm test`
##Deploying
When your new project is ready for deployment, add a new Heroku application with `heroku create`. This will make a new got remote called "heroku" and then you can `npm run deploy` which will push to this remote's master branch.
##Readme
Once this project is deployed, you should update this README file 