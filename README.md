nitrous-pgb-helloworld
======================

Starting Phoengapp Developer App for Nitrous.io

Try using this auto setup button called a hack


[![Hack hpssjellis/nitrous-pgb-helloworld on Nitrous.IO](https://d3o0mnbgv6k92a.cloudfront.net/assets/hack-l-v1-3cc067e71372f6045e1949af9d96095b.png)](https://www.nitrous.io/hack_button?source=embed&runtime=nodejs&repo=hpssjellis%2Fnitrous-pgb-helloworld&file_to_open=https%3A%2F%2Fgithub.com%2Fhpssjellis%2Fnitrous-pgb-helloworld%2Fblob%2Fmaster%2Fwww%2Findex.html)



Or do things the long way and follow the steps below: Note: the HACK only does the first section you must still install connect and connect-phonegap


1. Login http://www.nitrous.io
 1. New Box (only one free box so terminate any old boxes)
 1. Select Node, give your project a name such as MY-BOX-NAME
 1. Start with a github repo such as https://github.com/hpssjellis/nitrous-pgb-helloworld.git
 
1. click IDE if it does not auto take you there 
 1. Go to the terminal at bottom of the screen
 1. npm install connect
 1. npm install connect-phonegap 
 
 1. Out of terminal (optional if www folder already available)
 1. On left panel right click MY-REPO-NAME make a new folder call it www
 1. Drag all files into the www folder except nitrous.js

1. Back in terminal Type dir to get to your working directory
 1. cd  workspace
 1. dir
 1. cd  MY-REPO-NAME
 1. node nitrous.js
 
1. Click preview. Then record the URL to enter into the Phonegap Developer App.
  1. Load your mobile free Phonegap Developer App
  1. Enter the URL from the nitrous preview web page

1. Optional to save changes to your github repository- First connect to a github repo
 1. Go back to your box and activate public key (click on power icon 50/250 to authorize with github)
 1. go to the terminal
 1. git init
 1. git remote add origin https://github.com/hpssjellis/nitrous-pgb-helloworld.git (If you want to push to a blank repo then you must first login to github and make that blank repo)
 1. git remote -v
 1. git config user.name "a-name"
 1. git config user.email "an-email@gmail.com"
 1. git pull origin master (not needed if you are sending to a blank repo)
 
1. Once setup just keep repeating the following after you have made changes. Use up arrow to autoload
 1. git add .
 1. git commit -m "initial commit"
 1. git push origin master




