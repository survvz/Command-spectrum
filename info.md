# Commands

## Admin

* **$addrole [user] [role]** - Add a role to an user on your server, in order to assign a role the bot role must be above the others.
* **$ban [user] [reason]** - Ban an user from the server.
* **$deletemsg [number]** - Delete an amount of messages, the number must be between 2 and 100.
* **$kick [user] [reason]** - Kick an user from the server.
* **$mute [user] [ms]** - Mute an user for a specific amount of time, you have to create a new role called mute to make the command work.
* **$removerole [user] [role]** - Remove a role of an user.
* **$setbotname [name]** - Set a name for the bot.
* **$setbotstatus [status]** - Set bot status.

## Giveaway

* **$start --> To Start a Giveaway.
* **$groll --> To Choose Another Winner.
* **$gend  --> To End a giveaway.

## Games

* **$csgo [MySteamID]** - Get csgo stats for an user given by STEAMID64.
* **$csgofloat [inspect Url]** - Get informations about a skin or a weapon.
* **$lolcprot** - Display the current champion rotation in EU West.
* **$loltopfive [SummonerID]** - Display the top 5 played champions of a summoner, based on the SummonerID. You can find your SummonerID at http://www.lolking.net/

## Info

* **$help or $help [commandName]** - Display the list of commands if you just type $help or if you type $help commandName display the current command info.
* **$serverinfo** - Get server info.
* **$serverinvite [ChannelID]** - Get an invite for the server, but you must type the channelID to get the command work.
* **$uptime** - Get bot uptime.
* **$userinfo** - Get your user info.

## Music

* **$deletetrack [PositionNumberInQueue]** - Delete a song from the queue, if you want know your current queue, just type $queue and you will get the songs.
* **$joinchannel** - Make the bot join in a voice channel, you must be in a voice channel.
* **$nowplaying** - Show the currently playing song.
* **$pause** - Pause the currently playing song.
* **$resume** - Resume the currently playing song.
* **$playother [StreamUrl]** - Play a stream url.
* **$playtube [youtubeUrl]** - Play an youtube video.
* **$queue** - List the songs in queue.
* **$skip** - Skip the current playing song.
* **$stop** - The bot leaves the voice channel.
* **$volume [Number]** - Set bot volume in the voice channel, you must type a number betweem 0-200.
* **$ytsearch [SongName]** hit enter then type a **number** - Search for a song on youtube, then type a number between 1-20 (or less).

## Random stuff

* **$distance [latitude1] [longitude1] [latitude2] [longitude2]** - Get the distance between the sets of coordinates
* **$dogs** - Find some cute dog pictures.
* **$flipcoin** - Flip a coin.
* **$google [query]** - Get 3 search queries from Google Custom Search, you need to provide in the json file called googleConfig, your Custom Search Api Key and your CX.
* **$ping** - Ping the bot.
* **$randomcolor** - Generates a random hex color with preview.
* **$rolldice** - Roll a dice.
* **$setafk [status]** - Set your status afk or notafk.
* **$weather [location]** - Get the forecast information for a location.
