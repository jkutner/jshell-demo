# JDK 9 JShell Demo

This project can be deployed on Heroku to give the JDK 9 JShell a spin.

## Demo

![JShell Demo](http://i.imgur.com/5wl1JIV.gif)

## Usage

Install the [Heroku Toolbelt](http://toolbelt.heroku.com) then run these commands:

```sh-session
$ git clone https://github.com/jkutner/jshell-demo
$ cd jshell-demo
$ heroku create
$ git push heroku master
$ heroku run jshell
Running `jshell` attached to terminal... up, run.7933
Aug 23, 2015 5:32:46 PM java.util.prefs.FileSystemPreferences$1 run
INFO: Created user preferences directory.
|  Welcome to JShell -- Version 0.819
|  Type /help for help

->
```

Here is an [InfoQ article with some suggestions on what commands to try](http://www.infoq.com/articles/Java9-New-HTTP-2-and-REPL).

Happy shelling! 
