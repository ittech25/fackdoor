# Fackdoor
a backdoor written in python but the vicim and the attacker's pc communicate through fbchat module 
the backdoor_victim script connects to the fb act given by the user and starts listening for messages (commands) sent by the account made for the backdoor_server script and that way you can even send commands to the pc by your phone 

# Usage
First create 2 random facebook accounts
then run the backdoor_server script with the server_act username and the server_act pwd
and victim_act username and the victim_act pwd

```
python backdoor_server.py -sa <server_act username> -sp <server_act pwd> -va <victim_act username> -vp <victim_act pwd>
`` ''
to get the help of the commands use
```
python backdoor_server.py --help
`` ''