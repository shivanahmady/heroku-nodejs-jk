![Node.js CI](https://github.com/shivanahmady/heroku-jk/workflows/Node.js%20CI/badge.svg?branch=master)
![.github/workflows/blank.yml](https://github.com/shivanahmady/heroku-nodejs-jk/workflows/.github/workflows/blank.yml/badge.svg)

 heroku-nodejs-JK
========================

> Automatic deploys from  master are enabled
> Heroku gateway-1 ---> heroku app


## HEROKU BASIC 
 `heroku create`
 `git push heroku master`
 `heroku ps:scale web=`
 `heroku open`

## init procfile file 
 `web: node index.js`
-- web states it uses HTTP Routing

## Check Dynos to Scale
`heroku ps`         
`heroku ps:scale web=0`

 
## declare app depdencies
`npm init --yes`
`npm install`
  
  
RUN LOCAL
> heroku local web
 
