# spring-boot-jar-in-heroku

If for some reason, you just need to deploy jar file instead push all the source code, this repository is for you


# steps

- compile your spring boot wherever (windows, linux, jenkins, etc). As a result you must have target/my_app.jar
- create account in heroku 
- create an  app (any name, for example pet-web) in heroku using cli o web
- install the heroku cli : https://devcenter.heroku.com/articles/heroku-cli and enable login in your commandline
- execute : heroku git:clone -a pet-web
- this step is like : git clone heroku ....

- clone this github repository in other folder of your desktop or in your server
- compile your spring boot wherever using the commandnline of your desktop or server. As a result you must have something like target/my_app.jar
- move this file target/my_app.jar as app.jar to the heroku cloned folder
- just perform a git add ,  git commit -m "bla bla" and git push heroku master in your heroku cloned folder
- thats all, your app spring boot, will be uploaded to heroku and should be start.

# regards

- jrichardsz (me)

