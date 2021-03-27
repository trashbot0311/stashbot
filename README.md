# stashbot
A discord bot with searchable database for gaming inventory/trading. Wishlists reported with search results for each user. Independent stash/wishlist between platform channels. Relied heavily on tutorial [here](https://www.youtube.com/watch?v=nW8c7vT6Hl4), have to give Lucas the credit and thanks.
## Requirements
* Your Discord ID 
  * 18-Digit code to set you as owner
  * Enable developer mode/right click your name and copy ID.
* Discord Bot token and bot added to server
  * [Tutorial](https://discordpy.readthedocs.io/en/latest/discord.html)
* Three channels added to server 
  * pc-stash
  * ps-stash
  * xb-stash
* Working python 3 environment with discord.py:
  * pip3 install discord.py
## First use / Initialization
* Download/unzip [stashbot.zip](https://github.com/trashbot0311/stashbot/blob/main/stashbot.zip) and edit stashbot.py: 
  * line 22 (your discord id) 
  * line 48 (bot token)
* From terminal cd to the stashbot dir and issue the following command:
  * python3 create_sqlite.py 
## Start/Stop (start bot with command, ctrl+c to stop):
* cd into stashbot dir and issue the following command:
  * python3 stashbot.py
## Administration (All files in /cogs/ dir loaded by default):
* Owner commands (commandname is filename without .py in cogs dir):
  * /load commandname
  * /unload commandname
  * /reload commandname 
## Command usage (in discord channel):
* !usage 
  * Displays command help
* !search item
  * Searches everyones but your stash eg: *!search leather chest* 
* !stash item
  * Adds item to your stash
* !sdel item
  * Deletes item from your stash
* !mystash
  * Displays top 25 items in your stash
* !mystash item
  * Searches your stash eg: *!mystash leather chest*
* !wish item
  * Adds item to your wishlist
* !wdel item
  * Deletes item from your wishlist
* !mywish
  * Displays top 25 items in your wishlist
* !mywish item
  * Searches your wishlist eg: *!mywish leather chest*
 
## Demo server
* All are welcome to see in action here: [stashnet](https://discord.gg/yz2NPD72t2)
  * Message @trashbot#7424 for questions
