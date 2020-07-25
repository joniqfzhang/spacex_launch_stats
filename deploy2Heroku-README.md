1. go to heroku.com
2. Sign up a new account
3. download and install heroku cli 
4. check installation success by open cmd terminal with command: heroku
5. cd to project location
6. heroku login
7. login as heroku instructions:
heroku: Press any key to open up the browser to login or q to exit: 
Opening browser to https://cli-auth.heroku.com/auth/cli/browser/0789b504-646f-43a6-b231-ef4d2fb2deb2
8. heroku create
Creating app... done, agile-caverns-32665
https://agile-caverns-32665.herokuapp.com/ | https://git.heroku.com/agile-caverns-32665.git
9.git push heroku master
...
remote: -----> Build succeeded!
remote: -----> Discovering process types
remote:        Procfile declares types     -> (none)
remote:        Default types for buildpack -> web
remote:
remote: -----> Compressing...
remote:        Done: 28.3M
remote: -----> Launching...
remote:        Released v3
remote:        https://agile-caverns-32665.herokuapp.com/ deployed to Heroku
remote:
remote: Verifying deploy... done.
To https://git.heroku.com/agile-caverns-32665.git
 * [new branch]      master -> master
10.heroku open
11.opened in browser the app deployed:
https://agile-caverns-32665.herokuapp.com/  