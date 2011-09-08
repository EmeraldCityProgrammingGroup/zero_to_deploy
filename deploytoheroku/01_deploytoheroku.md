!SLIDE 
# Heroku #
## Service for hosting Rails applications ##
## Built on top of Amazon EC2 ##
## Free for applications that need limited resources ##
## Also supports Java, Node.js, & Clojure apps ##

!SLIDE bullets
# Heroku - Sign up #
* Sign up at https://api.heroku.com/signup
* Getting started with Heroku - http://devcenter.heroku.com/articles/quickstart
* Getting started with Rails 3.0 on Heroku - http://devcenter.heroku.com/articles/rails3
* Getting started with Rails on Windows - http://devcenter.heroku.com/articles/windows

!SLIDE
# Heroku - Set up #
    $ gem install heroku
    $ heroku keys:add
    $ heroku create [ --stack bamboo-ree-1.8.7 ]
    
!SLIDE commandline
# Deploy to Heroku #
## Execute the following commands: ##
    $ git push heroku master 
    $ heroku open
