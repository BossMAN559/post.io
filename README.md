# post.io

while migrating to a new server and setting everything up on docker, i found this poste.io mail server.
https://www.poste.io

after getting the server to work i made a docker-compose file to make things easy on me.
the .env holds the settings to change. 
as i already have services using port 80, i added a second IP address to the network card and specifying that IP in the .env will tell the setup to use it.
