# How to Host on Heroku

- npm install dotenv
- Convert sequelize json to js
- Create Heroku account
- Create Heroku app
- Connected the Heroku app to the Github repo
- Enabled automatic deployments from the master branch
- Set `app.listen(process.env.PORT)` in app.js
- Configure Heroku Postgres add-on
- Set Heroku environmental variables for Sequelize (ex: DB_NAME)
- Run `nxp sequelize db:migrate` before starting our app
