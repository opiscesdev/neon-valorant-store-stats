# Valorant store checker - Discord Bot (BETA)
Discord bot that shows your daily store offer without open the VALORANT by using the Ingame API.
written using Python and the [Discord.py](https://github.com/Rapptz/discord.py) library <br>

## Screenshot

* Embed Design by [Giorgio](https://github.com/giorgi-o)

![image](https://i.imgur.com/uF9THEa.png)

* Notify skin

![image](https://i.imgur.com/ijjvQV3.png)

* Battlepass

![image](https://i.imgur.com/GhzLBSr.png)

## Installations

* [Python 3.8+](https://www.python.org/downloads/)

* Install requirements

* Create the [discord bot](https://discord.com/developers/applications) and invite bot to server with scope `applications.commands`

* Clone/[Download](https://github.com/staciax/ValorantStoreChecker-discord-bot/archive/refs/heads/master.zip)

```
pip install -r requirements.txt
```

```
# manual install package

pip install git+https://github.com/Rapptz/discord.py@master
pip install requests
pip install python-dotenv
```

* Store discord bot token in [.env](https://github.com/staciax/ValorantStoreChecker-discord-bot/blob/master/.env)
```
TOKEN='INPUT DISCORD TOKEN HERE'
OWNER_ID='INPUT YOUR DISCORD ID'
```
* Run the bot
```
python bot.py
```
* Slash Command in the global happens instantly `(takes 1 hour to process.)` | force global `-sync global`
* if you want use in server now `-sync guild` to setup the commands.

## Usage

| Command                       | Action                                                                                                     |
| :---------------------------- | :--------------------------------------------------------------------------------------------------------- |
| `store`  | Shows your daily store |
| `point`  | Shows your valorant point |
| `login`  | Log in with your Riot acoount |
| `logout`  | Logout your Riot acoount |
| `misson`  | View your daily/weekly mission progress |
| `notify add`  | Set a notification when a specific skin is available on your store |
| `notify list`  | View skins you have set a notification for |
| `notify mode`  | Change notification mode `Specified skin` or `all skin` |
| `notify test`  | Testing notification |
| `nightmarket`  | Shows your nightmarket |
| `battlepass`  | View your battlepass' current tier |
| `bundle`  | inspect a specific bundle `credit by Giorgio` |
| `bundles`  | Show the current featured bundles `credit by Giorgio` |
| `debug`  | command for debug `emoji`, `skin price`,`cache` is not loaded |

