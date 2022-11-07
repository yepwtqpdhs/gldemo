Download docker-compose.yml file (depending on version of docker, may require edits)
Build and start docker image
Use Netcat to listen to port 1234 (or any port you like)
Download attack_url.txt file 
Insert local IP addr into attack file where specified
Send attack to gitlab through the import repo by url option
Observe that the flag appears in netcat
Change gitlab version to 11.4.8
Try attack again and observe that it no longer works
