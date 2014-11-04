## Run it

Now, you have the project, let's run it locally.

## Steps

1. In Terminal, go into the project folder
2. Run `rake db:migrate` which would prepare the database structure for you
3. Run `rake db:seed` which would initialize the database with some sample data.
4. Type `bundle install --without production` to prepare the project folder
5. Type `rails server` to start the server locally
6. Visit `http://localhost:3000` in the browser (e.g. Chrome)

## Goals

- You should be able to view the site, with a graph showing up.
