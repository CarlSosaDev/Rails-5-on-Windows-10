
 
 Ruby On Rails 5 On Windows 10.

Requirements:

For a decent Ruby Stack and web development environment on Windows 10 at least we need the follow things:

  1- Ruby interpreter (the programing language).

  2- Ruby on Rails (the framework).

  3- Databases (Postgres or Mysql for production,development, Sqlite for test).

For web development in general:

  1- NodeJs/npm  (you should read info about both, if you don't know).

  2- Grunt (Javascript task runner).

  3- Gulp  (Build system automating tasks).

  4- Bower (a package manager).

Tools:

  1- text editor or IDE (Rubymine,Sublime text,atom,Visual Studio Code,...).

  2- Web browser(Chrome, Firefox,Edge...).

  3- Heroku toolbelt.

  4- Git (version control system) ---It's very important.

   Steps

    Download Bitnami RubyStack 

          Bitnami RubyStack has much of the tools that we need to install Ruby on Rails on      windows, it come with Git, Mysql, Postgresql, Sqlite, Ruby, Rails, RVM, and others.

           Go to https://bitnami.com/stack/ruby, and download the latest version of the     installer.

 Once installed it in your computer we need to add the path of Ruby interpreter to the system variables, do the following:

 1- right click in Windows menu,then choose "System".

 2- click the Advanced System settings.

 3- click Environment variables.

 4- click System variables.

 5- Choose "Path"from the list.

 6- Click the new button or edit button.

 7- Copy the path of ruby interpreter and add it, we'll find it in c:\Bitnami\rubystack-x.x.x\ruby\bin.

 8- apply and accept the new configuration.

 

 Optional:

 9- Do the same process mentioned above for Nodejs, python, postgresql, Mysql and git.

 But, It's time to test that the interpreter is available from Command Prompt or CMD:

 1- Open CMD.exe

 2- type ruby -v .

 if you see a message like this: ruby 2.2.4p230 (2015-12-16 revision 53155).... 

 everything was ok, but don't worry if it's not the same, it mightt be different.

 This steps above were for get Ruby interpreter available for wherever you can use a Command Prompt. Now,  it's time for get Rails. First, I need to tell you that Rails is installed because Bitnami installer did so, but it's an  earlier version than Rails 5, so we want to install Rails 5, for do that, we need to type the following in Command  Prompt:

 gem install rails 

 and that's it. This process might take a while, be patient. 

 Then test rails with the follows commands:

 1- let's make a directory for our projects from command prompt: md railsprojects

 2- move to the new directory: cd railsprojects

 3- let's create a new app: rails new myapp

 4- move to myapp folder: cd myapp

 5- optional type: bundle install

 6- start the server: rails s

 7- open the browser: http://localhost:3000

     You must see a meesage: Yay! You’re on Rails!.

 

Heroku toolbelt (optional)

  Heroku is a Cloud provider, so you can use it for hosting your apps, but you can use another provider.

  Go to the  link below and follow it's steps:

         https://devcenter.heroku.com/articles/heroku-command-line
 
 
