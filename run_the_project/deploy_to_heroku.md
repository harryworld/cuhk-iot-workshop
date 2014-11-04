## Deploy to Heroku

The project that you are working on is ready to deploy to the server.

## Steps

1. Register an account on [Heroku](http://www.heroku.com/).
2. Download [Heroku Toolbelt](https://toolbelt.heroku.com/) for your operating system, which is the command line tool to deploy the app.
3. Type `heroku login`, you will be prompted with login.
4. Enter the email, the email will be shown.
5. Enter the password, the password will not be shown for security reason, just type the password and enter.
6. Press enter at the prompt to upload your existing `ssh` key or create a new one, used for pushing code later on.
7. To check that your key was added, type `heroku keys`. If your key isn’t there, you can add it manually by typing `heroku keys:add`.
8. Now, create an app on Heroku using `heroku create`.
9. Push the code to Heroku using `git push heroku master`.
10. Finally, prepare the database on Heroku using `heroku run rake db:migrate`.
11. You can now type `heroku open` in terminal to visit the page.

## Goals

- You should be albe to view the site in the browser.
- The path would be like `http://[appname].herokuapp.com`

## References

- [Getting Started with Rails on Heroku](https://devcenter.heroku.com/articles/getting-started-with-ruby#introduction)
