git init
git add .
git commit -m "init"
heroku create --stack heroku-20
git push heroku master


heroku addons:create heroku-postgresql
heroku run rake db:migrate
