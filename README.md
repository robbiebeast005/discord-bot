# Discord Bot
This is a very basic guild to make your first discord bot.

## Install discord.py
First of all, you need to install de discord library. With python3, you can install the library by pasting the following pip command:
```
pip install discord.py
```
After this, you need to create a `.py` file to write (or copy) all of the code in.
## Setting up
The first thing we need to do, is to import some modules from the discord.py library. You can copy this below and past it in your script.
```py
from discord.ext import commands
from discord.utils import get
from discord.ext.commands import bot

bot = commands.Bot(command_prefix="!")
```
