I basically followed this tutorial here for now, just as a proof of concept. 
http://socket.io/get-started/chat/

It's also running on heroku, but no guarantees that that's working 
https://immense-sands-16023.herokuapp.com/

#Setup

First setup mysql database:

    mysql -u[username] -p[password] < setup.sql

Then run envconf.sh or just use the defaults (below):

    cat defaults.conf | bash envconf.sh

Then install the dependencies and start the server:

    npm install
    node index.js

Go to http://localhost:3000/

Each tab in the browser will be a different user.


#Troubleshooting
