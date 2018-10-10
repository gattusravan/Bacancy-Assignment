# README

rvm use 2.5.1

bundle install

Update config/database.yml file with your mysql password

rake db:create
rake db:migrate

redis-server
bundle exec sidekiq -d -L log/sidekiq.log

rails s



#to install redis-server
https://www.digitalocean.com/community/tutorials/how-to-install-and-use-redis

* ...
