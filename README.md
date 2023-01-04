# Getting started
Prerequisites
In order to use this bot, you will need to have the following:

A Discord account and server
A Python 3.8+ environment
The discord.py library (install with pip install discord.py)
Setting up the bot
Create a new Discord bot by following the instructions here. This will give you a token that you will need to use to authenticate the bot with your server.

Clone or download this repository to your local machine.

In the root directory of the repository, create a file called .env and add the following line:

Copy code
DISCORD_BOT_TOKEN=<your bot token>
Replace <your bot token> with the token you obtained in step 1.

Run the bot by running the following command in the root directory of the repository:

Copy code
python bot.py
Using the bot
Available commands

# The following commands are available:

!schedule - displays the stream schedule for the week

!nextstream - displays information about the next scheduled stream

!uptime - displays the current uptime of the stream

!game - displays the current game being played

!title - displays the current stream title

# Customizing the bot

You can customize the behavior of the bot by modifying the code in the bot.py file. For example, you can modify the schedule or change the messages that the bot sends in response to commands.

# Contributing

If you would like to contribute to the development of this bot, please fork the repository and submit a pull request.

# Support

If you have any questions or need assistance, please join the support server or create an issue in the repository.
