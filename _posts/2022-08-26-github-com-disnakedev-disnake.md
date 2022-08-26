---
title: disnake
categories: ['python', 'discord-py', 'discord-api']
---
## [disnake](https://github.com/DisnakeDev/disnake)

### An API wrapper for Discord written in Python.


``` py
import disnake
from disnake.ext import commands

bot = commands.InteractionBot(test_guilds=[12345])

@bot.slash_command()
async def ping(inter):
    await inter.response.send_message("Pong!")

bot.run("BOT_TOKEN")
```
