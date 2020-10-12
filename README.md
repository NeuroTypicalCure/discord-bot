��#   d i s c o r d - b o t  
 
In order to use this bot, a file named ".env" must be included in the bot's
directory to include the token for your bot. This file can be created in a text
editor and should look similar to the example here:

--------------------------------------------------------------------------------

DISCORD_TOKEN=JIKDSKLFJ-THISisRANDOMtext.LoOKsLIkeAt0k3N-ASDFgHjkL
COMMAND_PREFIX=$
LOG_FILE=discord_bot.log

--------------------------------------------------------------------------------

Only the DISCORD_TOKEN variable is required. The bot code has a default value of
"$" for the COMMAND_PREFIX and "discord_bot.log" for the LOG_FILE. The command 
prefix is the prefix used by users to initiate a bot command, and the log file
is where errors are logged to for troubleshooting.

To obtain a bot token, follow the directions below:

1)  Go to https://discord.com/developers/applications

2)  Click on the "New Application" button and choose a name for your app.

3)  Under the "Settings" menu, click the "Bot" selection.

4)  Click "Add Bot" to cause an alert to pop up saying that this action is
    irreversible. Click "Yes, Do it!" to transform your app into a bot.

5)  Below your bot's username should be a TOKEN. You can click to reveal the
    token or you can simply click the "Copy" button to add it to your clipboard.
