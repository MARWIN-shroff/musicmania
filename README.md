


<h3>What's Coming?</h1>

  - See TODO in Projects tab

## Prerequisites:

#### API Keys
* Discord - https://discord.com/developers


Obtained keys must be entered into ```config/config.py```

#### Requirements

* Installation of Python 3.7+

Install dependancies:
```
pip install -r requirements.txt
```
* Located in ```/config```


### Installing - Self hosting

1. Download release if available, alternatively download repository zip
2. Complete Prerequisites
3. Start ```run.py``` in project root
4. See configuration options in /config/config.py

Button play plugin:
* Set emoji with the setting command to enable this feature
* Emote must be in same server as bot
* Needs Manage Message permissions

Custom Cookies:
* Extract cookies.txt from you browser using your preferred method
* Overwrite the existing cookies.txt in /config/cookies/
* (Optional) Set a custom cookies.txt location by modifying COOKIE_PATH in config.py

## Commands:

### Music

After the bot has joined your server, use ```$help``` to display help and command information.


```
$p [link/video title/key words/playlist-link/soundcloud link/spotify link/bandcamp link/twitter link]
```

* Plays the audio of supported website
    - A link to the video (https://ww...)
    - The title of a video ex. (Gennifer Flowers - Fever Dolls)
    - A link to a YouTube playlist
* If a song is playing, it will be added to queue

#### Playlist Commands

```
$skip / $s
```

* Skips the current song and plays next in queue.

```
$q
```

* Show the list of songs in queue

```
$shuffle /$sh
```

* Shuffle the queue

```
$l / $loop
```

* Loop the current playing song, toggle on/off

```
$mv / $move
```

* Move song position in queue

#### Audio Commands

```
$pause
```

* Pauses the current song.

```
$resume
```

* Resumes the paused song.

```
$prev
```

* Goes back one song and plays the last song again.

```
$np
```

* Shows more details about the current song.

```
$volume / $vol
```

* Adjust the volume 1-100%
* Pass no arguments for current volume

```
$stop / $st
```
* Stops the current song and clears the playqueue.


### General

```
$settings /$setting/ $set
```
* No Arguments: Lists server settings
* Arguments: (setting) (value)
* Use "unset" as an argument to reset a setting
* Example: $setting start_voice_channel ChannelName
* Administrators only

```
$c
```

* Connects the bot to the user's voice channel

```
$cc
```

* Switch the bot to the user's voice channel

```
$dc
```

* Disconnects the bot from the current voice channel

```
$history
```
* Shows you the titles of the X last played songs. Configurable in config.config.py


### Utility

```
$reset / $rs
```

* Disconnect and reconnect to the voice channel

```
$ping
```

* Test bot connectivity

```
$addbot
```

* Displays information on how to add the bot to another server of yours.

## License

This program is free software: you can redistribute it and/or modify
it under the terms of the [GNU General Public License](LICENSE.txt) as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.


## Acknowledgments

https://github.com/adriansteffan/DiscordJockey
