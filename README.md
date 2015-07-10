
     ,-----.,--.                  ,--. ,---.   ,--.,------.  ,------.
    '  .--./|  | ,---. ,--.,--. ,-|  || o   \  |  ||  .-.  \ |  .---'
    |  |    |  || .-. ||  ||  |' .-. |`..'  |  |  ||  |  \  :|  `--, 
    '  '--'\|  |' '-' ''  ''  '\ `-' | .'  /   |  ||  '--'  /|  `---.
     `-----'`--' `---'  `----'  `---'  `--'    `--'`-------' `------'
    ----------------------------------------------------------------- 


Hi there! Welcome to Cloud9 IDE!

To get you started, create some files, play with the terminal,
or visit http://docs.c9.io for our documentation.
If you want, you can also go watch some training videos at
http://www.youtube.com/user/c9ide.

Happy coding!
The Cloud9 IDE team

// Init npm
$ npm init

// Install Express
$ npm install express --save
$ npm install express-generator -g
$ express

// Install mongodb
$ mkdir data
$ echo 'mongod --bind_ip=$IP --dbpath=data --nojournal --rest "$@"' > mongod
$ chmod a+x mongod

// Install dependencies
edit package.json under dependencies add:
1. "mongodb":"*"
2. "mongoose":"*"
3. "connect-flash":"*"
4. "express-validator":"*"
5. "express-session":"*"
6. "express-messages":"*"
7. "passport":"*"
8. "passport-local":"*"
9. "passport-http":"*"
10. "multer":"*"
then
$ npm install

// Run mongodb server
$ ./mongod

// To run mongo cli
// make sure server is running
$ mongo

// Run node.js server
$ npm start