# Minecraft-Pi-raspi--Multiplayer-game
This game uses a server (or core) python script to communicate with the client python script. The communication is via setting blocks in a specific location in order to teleport players to a death location from the player's client program.
run the server core script on one of your raspberry pi. On the same LAN, run the client script on any other raspi. The client can also run on the same raspi as the core script.

The core script sets blocks in a certain location in the world to indicate whether the client should teleport (setPos) the remote player. The client script checks a specific block position to determine if it should teleport the player to a location which causes falling to death.
The core and client are currently designed with some hard coded features. The client has to set the ip address of the raspi running the core script. Also, both core and client are designed to handle up to six players running the client.

This code was written by "Eli," a 12 year old student in my summer camp program.
