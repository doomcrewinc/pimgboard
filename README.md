README

pinterest clone

Ruby version: 

    ruby -v >= 2.6.0

System dependencies: 

    included in Gemfile, note: gem 'sqlite3', '~> 1.3.6' Most current version throws an error for some fucking reason.

Configuration: none at this time.

Database: 

    sqlite3

Database initialization:

    rake db:migrate

How to run the test suite: N/A at this time

Services (job queues, cache servers, search engines, etc.): none at this time.

Deployment instructions:

    download/clone repo
    bundle install
    rake db:migrate
    rails server

I'm sure this is riddled with bugs and terrible styling, feel free to submit a pull request if you fix something or make it look cool.