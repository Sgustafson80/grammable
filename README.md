# Grammable

Grammable is a Twitter clone that allows users to upload images and share them with other users.

## Built With

Grammable was written with HTML5, CSS, Ruby version 2.5.3 on Rails version 5.2.3. Postgresql was used for the database. The Devise Gem is used for user authentication. Amazon Web Services is used to manage user uploaded images. Grammable is deployed on Heroku.

You can run Grammable in your browser at https://grammable-sarah-gustafson.herokuapp.com/

## Running on Local Machine

After installing the files, you will want to run `bundle install` and `rake db:migrate` to install the Ruby Gems and set up the database. It should run in your browser at `localhost:3030`

## Running the Tests

Grammable was written using a test driven development approach. The `rspec` gem was used to set up the testing environment. To run the tests in the Linux command line run `bundle exec rspec`.

## Authors

Grammable was coded by Sarah E. Gustafson

## Acknowledgments

Grammable was coded under instruction of Vanderbilt University Online Coding Bootcamp.