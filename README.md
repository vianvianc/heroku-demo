# heroku-demo

//creates an empty app on heroku
Heroku create
//also creates a git remote named heroku... heroku acts as a git repo for this method of
// deployment
git remote -v

//now we deploy our app by pushing the repo to heroku
//the platform pulls down the app dependencies, assembles the app, deploys it to a container (dyno)
git push heroku master

//see the deployed app
heroku open
heroku add

heroku local
//checks if running locally

git status
git add .
git commit -m ":)"
git push heroku master
