# Simple-PHP-Server
This is code to create a simple PHP server. The version will grab the document.cookie and send back to the server. These methods can me replaced with others if needed.

Make sure to place script.js and index.php on your computer in your server location. 

index.php

You will need to put the remote servers IP address in the index.php file.

script.js

You will need to update the IP addresses in this file on the location of where you are hosting the files locally. 

To Use:

It will be best to make a temp server location mkdir /tmp/server

Place you index.php file and your script.js files in that directory.

Then us command sudo php -S 0.0.0.0:80 to start serving your files
