# StuHub

This is the repository for StuHub, an online app built using Ruby on Rails and hosted on Heroku.

## Installation
This cannot be run properly in a local environment without the appropriate Environment Variables. Contact the developers for those.

Software required: Redis Server for Rescue.

Otherwise, just clone it or download an archive.

With an appropriate Heroku setup, run `bundle exec puma -C config/puma.be inside the StubHub folder.

You'll also need to run `redis-server` for the Redis server and then `env QUEUE=* TERM_CHILD=1 bundle exec rake environment rescue: work
` to launch the rescue server.

If you need the chat server, run `bundle exec rackup private_pub.ru -s thin -E production` inside the StubHub-Faye folder.

For more specific things, don't hesitate to get in touch with the developers.


## Issues
Please open an issue for any errors, problems, and suggestions.

## update 2015.10.17
Created login feature
Created database User

## Change Log
[Go to Change Log](StuHub/CHANGES.md)

## Credits
CMPT276 Fall 2015 Group 5
