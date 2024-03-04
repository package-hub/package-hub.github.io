---
title: Foundation
categories: ['java', 'minecraft', 'plugin']
---
## [Foundation](https://github.com/kangarko/Foundation)

### Foundation™ helps you create highly customized Minecraft plugins (based on Spigot/Paper API) that support multiple MC versions.


1. Import Foundation using Maven/Gradle (see the Importing section).
2. Change "**extends JavaPlugin**" to "**extends SimplePlugin**" (we need that to register things and listeners on our end automatically)
3. Change **onEnable()** to **onPluginStart()** and **onDisable()** to **onPluginStop()** (we occupy these methods to perform logic)
4. If you use a **static getInstance()** method in your main plugin's class, change it to return **(T) SimplePlugin.getInstance()** where T is your plugin instead. Delete the instance of your plugin from your class if you use it (if you have myPlugin = this anywhere, remove it).

For a sample plugin, see [PluginTemplate](https://github.com/kangarko/plugintemplate).

A complete tutorial on how to use this library is a part of our Project Orion training available [here](https://mineacademy.org/project-orion)

If you just want a quick start into Minecraft plugin development, [check out this guick gist](https://gist.github.com/kangarko/456d9cfce52dc971b93dbbd12a95f43c).
