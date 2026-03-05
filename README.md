# Minecraft bedrock server redirector
Create a custom link to add a minecraft bedrock server directly
##Url Syntax
```
alefouau.github.io/mcserverurl?n=<NAME>&i=<IP>&p=<PORT>
```
Example:
https://alefouau.github.io/mcserverurl?n=MyServer&i=play.myserver.com&p=12345
Clicking this link will open Minecraft Bedrock and will add a server with:
Name: MyServer
IP: play.myserver.com
Port: 12345

###How it works?
Minecraft Bedrock has support for custom url links like "minecraft://something"
This website basically grab the "n", "i" and "p" in the minecraft://?addExternalServer=n|i:p and then redirects the user to this url, if you want to be more direct, you can replace the n with the server name, i with ip, and p with port

###Why this exist?
"If copying and pasting minecraft://?addExternalServer=n|i:p and opening it in a browser it works, why do i need this website?"
Because some applications like Whatsapp doesnt support custom url protocols like minecraft:// (the link isnt clickable), only links to websites, like mine (https://alefouau.github.io)
