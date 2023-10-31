# cs2-connectionlogs
 Replace `<HintPath>E:\Github\cs2-cph\API\CounterStrikeSharp.API.dll</HintPath>` inside of the ConnectionLogs.csproj and then run _compile.bat to compile the plugin, it will be placed in `\bin\Debug\net7.0` folder.

## Description
This plugin adds players to a database to track when they join.
It prints to discord through a webhook when a player joins and leaves.
It has a command !connectedplayers that prints the 50 recent players that joined the server.

## Config
The config will automaticly be generated on first run and will be placed inside of the same directory as the plugin itself.
Colors can be used in the "ChatPrefix" like so {White} or {Red}, every color in the ChatColors class can be used.

