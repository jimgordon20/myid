# myid
Send players IDs to discord webhook on join.

![Desktop 2023 10 23 - 05 58 27 01 - frame at 0m1s](https://github.com/jimgordon20/myid/assets/110393030/4da73acd-9480-487e-9eb0-83106913f4e1)
![Opera Snapshot_2023-10-23_060906_game iceline host](https://github.com/jimgordon20/myid/assets/110393030/e65708bd-4fb6-4883-ab1d-51be2690cc03)


author 'jim gordon the on and only  <https://github.com/jimgordon20>'



-- instructions:

fill out commented parts in server.lua






-- Description:

This script is designed to enhance server administration and player tracking by logging important information when a player connects to the server. When a player joins, the script captures their details and performs two key actions: sending a Discord log message and printing their identifiers to the server console.

-- Features:

-- Player Connecting:

This script actively monitors player connections and triggers a response as soon as a player joins the server.
Player Information:

For every connecting player, the script collects and displays various identifiers, making it easier for administrators to identify and manage players. The information includes:

-- Player:

The player's in-game username or ID (as applicable).

-- Identifiers:

The player's important identifiers, such as:

License: -- The player's game license identifier.

Xbox Live -- (XBL): The Xbox Live identifier.

Xbox Live -- (Live): The Xbox Live gamertag (if available).

Discord: -- The player's Discord identifier.

FiveM: -- The player's FiveM identifier.

License2: -- A second game license identifier (if applicable).

IP: -- The player's IP address.

-- Discord Integration:

The script sends a log message to a designated Discord channel, notifying administrators and moderators about the player's connection. This is invaluable for real-time monitoring and managing player activity.

-- Server Console Output:

Simultaneously, the script prints the collected player identifiers to the server console. This provides administrators with instant access to player information, allowing for quick and informed decisions regarding server security and player behavior.
