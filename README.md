# Mozart
[![Python version](https://img.shields.io/badge/python-3.5%2C%203.6%2C%203.7-blue.svg)](https://python.org)

## Setup
Setting up Mozart is relatively painless - just follow one of the [guides](https://narehood.github.io/Mozart/). After that, configure the bot to ensure its connection to Discord.

![Main](https://i.imgur.com/FWcHtcS.png)

The main configuration file is `config/options.ini`, but it is not included by default. Simply make a copy of `example_options.ini` and rename it to `options.ini`. See `example_options.ini` for more information about configurations.

### Commands

There are many commands that can be used with the bot. Most notably, the `play <url>` command (preceded by your command prefix) will download, process, and play a song from YouTube or a similar site. A full list of commands is available [here](https://just-some-bots.github.io/MusicBot/using/commands/ "Commands").

### Further reading
* [Project license](LICENSE)

#Fork Information
MusicBot is the original Discord music bot written for [Python](https://www.python.org "Python homepage") 3.5+, using the [discord.py](https://github.com/Rapptz/discord.py) library. It plays requested songs from YouTube and other services into a Discord server (or multiple servers). Besides, if the queue becomes empty MusicBot will play through a list of existing songs with configuration. The bot features a permission system allowing owners to restrict commands to certain people. As well as playing songs, MusicBot is capable of streaming live media into a voice channel (experimental).
