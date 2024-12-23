# Discord Py Bot Template

Discord.py is a library that allows you to make discord bots with python. this repo is a template of a bot made using Discord.P should look like. Enjoy!  
- ✨I am trying to help the bot development community with this template✨

## Features

- 10+ ready-to-use functions.
- Easy start for beginner bot developers.

## Notes From The Developer
> It is recommended to use other sources to get started with Discord bot development, then return to this repo when struggling, or when you want an idea as to the structure of a finished discord bot.
> 
# Setup

Bot requires [Python 3](https://www.python.org/) to run.

### Install the dependencies

```sh
pip install -r requirements.txt
```
> Or you can use the setup file to run this code automatically.

### Setting up the bot properties

```python
#Insert the token which you can get from Discord's developer page.
TOKEN = '' 

#Set the bot status below.
BotStatus = "Example Bot"

#Set your bots prefix.
Prefix = "."
```

# How to run
* The bot can be started with a python command:
    ```sh
    python bot.py
    ```

# How to run using docker
1) First configure your bot then build the docker image with command:
    ```sh
    docker build -t my-bot-app .
    ```
2) Then run the bot with command:
    ```sh
    docker run my-bot-app
    ```

# Contribution
You can always make pull requests to this repo, if you report or fix a bug or if you add more commands to the template I'll be happy to merge them.
