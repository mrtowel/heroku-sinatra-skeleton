# Heroku Sinatra Skeleton
Skeleton app for [Heroku](https://heroku.com/) using [Sinatra](http://www.sinatrarb.com/). 

# Quick start
In `app/application.rb` change module name to whatever you wish, e.g. `Dildo`. Then update `config.ru` to `run Dildo::App`.

If you want to use [Foreman](https://github.com/ddollar/foreman) in your development environment, create `.env` file in root directory of the project and specify server port, e.g. `echo "PORT=3000" >> .env` and run `foreman start`. App will be available at http://localhost:3000/. 

# Example 
Visit https://heroku-sinatra-skeleton.herokuapp.com/.
