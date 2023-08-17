# first-dapp

this is first app sample that has been created by me .
1. install "nodeJS and npm" or (check if available)->  node-v/npm -v
2. Create a folder (my-webapp) where you want to create your project. Go to the folder and run the following command in your windows shell or terminal to initiate the node project -> npm init
3.  Install expressJs  -> npm install express
4.   Now create a server.js file and put the following content in it---
                             "var express = require('express');
                              var app = express();
                               const port = 3000;
                         app.get('/', function (req, res) {
                        res.sendFile(__dirname+'/index.html');
                         });
                        app.listen(port, function () {
                       console.log('listening on *:' + port);
                         });  "

     if you are using windows use res.sendFile(__dirname+'\index.html');  on 7th line instead of  res.sendFile(__dirname+'/index.html');
     
5. Create an HTML file with the name index.html and put the following sample HTML code in it.

   "<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome</title>
</head>

<body>
    <div style="font-size:30px; text-align: center; margin-top: 50px;">
        Hello there, <br>
        Congratulations !! on Building your web app ! <br>
        Keep Learning ! and Best Wishes from DApp World :)  
    </div>
</body>
</html>"

6.  Run your server->   node server.js
