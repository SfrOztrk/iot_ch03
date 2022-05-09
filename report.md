We set up virtual environment and install the dependencies into it. 
We run flask_api_server.py file to start the server. 
Then we could change the brightness of led on  interface of server. 
Also, we get and set the brightness value of led with using curl GET and POST commands on the terminal. 
We used the raspberry pi ip to connect the server instead of using localhost.

Used curl commands on terminal 
GET command >> curl -X GET http://localhost:5000/led
POST command >> curl -X POST -d '{"level": 25}' -H "Content-Type:application/json" http://localhost:5000/led
