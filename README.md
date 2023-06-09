# Bingo Event Plugin
A plugin to play an automated bingo for the clan.
Build specificly for the [BE Active NL] clanchat.

## features
- Sends loot to the configurable server. 
- Send screenshot to Discord; only when an item has been crossed off.
- Dynamic configuration. 
- The configuration can be send from the server to the client.
- Partial anti cheat.

# restriction
Only supports:
-Npcs which drop loot on the ground. Goblin, Graardor for example.
-Loot from chests:
1 Barrows
2 COX
3 TOB
4 TOA
5 Fishing Trawler
6 Wilderniss Loot Chest

# requirements to use
Your own deployed backend, database and frontend to display the data.

# setup for users
To use the plugin the user has to configure it correctly.
Send data to: The url to send the data to. 
Dynamic configuration url: The url to get the configuration.
Eventcode: the code of the event.
Send screenshot: Is used to enable sending screenshots to the webserver.
Discord webhook: The url to send the screenshots to.
