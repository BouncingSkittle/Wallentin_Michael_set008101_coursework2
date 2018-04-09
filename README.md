Install Node.js
https://nodejs.org/en/
version used: 8.11.1 LTS

_____________________________________________________________________________________

Install MongoDB
https://www.mongodb.com/download-center?jmp=nav#community
version used: Windows Server 2008 R2 64-bit and later, with SSL support x64
(download msi)


set up options for mongodb in command promt:
navigate to C:\mongodb\bin>

install it as a service to run in the background: 
--directoryperdb --dbpath C:\mongodb\data\db --logpath C:\mongodb\log\mongo.log 
--logappend --rest --install

to start the mongodb service:

navigate to C:\mongodb\bin>
> net start mongodb
> mongo
> use nodekb
_____________________________________________________________________________________

Text Editor

Install Atom
https://atom.io/
version used: 1.25.1


Install pug package for atom for syntax highlighting:
Settings > Install > Search 'pug' : language-pug
_____________________________________________________________________________________

Command Prompt

Install Git and GitBash
https://git-scm.com/download/win

_____________________________________________________________________________________

Modules installed through command promt for the blog functionality:

npm install --save express pug mongoose body-parser express-messages express-session 
connect-flash express-validator passport passport-local bcryptjs

nmp install -g nodemon bower
(nodemon: to keep running server, not having to restart everytime there is a change)

bower install bootstrap
