
## Installation



Install gem dependencies:

    bundle install

Setup the database:

    rake db:migrate


## Running

To start the web server locally, run:

    rails server

Then go to [localhost:3000](http://localhost:3000) to login and use the app.

## App authentication

When you run this app, you will notice that you get the opportunity to paste in an app id and an app token on the login page. This demonstrates how you can authenticate as an app, rather than as a user. You get the app id and token from the app's "Developer" page. The different ways of authenticating are explained here: https://developers.podio.com/authentication.
