<h1>Knock<img src="https://raw.githubusercontent.com/ApexieDevelopment/Knock/main/KnockbackFFA.gif" height="64" width="64" align="left" alt=""></h1><br>

[![Discord](https://img.shields.io/badge/chat-on%20discord-7289da.svg)](https://discord.gg/a75eNEAtrt)
[![License](https://img.shields.io/github/license/ApexieDevelopment/Knock)](https://github.com/ApexieDevelopment/Knock)
[![Poggit](https://poggit.pmmp.io/shield.dl.total/KnockbackFFA)](https://poggit.pmmp.io/p/KnockbackFFA) <br>
<b>The classic sumo minigame fun to play for PocketMine-MP.</b>

### Features
- Easy to setup
- Customizable scoretag for the players
- Arena map loading when starting the plugin
- Ingame sounds, to make the gameplay alive
- Customizable game behaviour
- Random maps <b>(Coming soon)</b>
- Permissions <b>(Coming soon)</b>
- Scoreboard <b>(Coming soon)</b>

### How to setup & play
The plugin itself it's easy to setup. Follow the steps:
- Install the plugin
- Change the config values as you like
- Go to your server and type /kbffa
- Enjoy ;)

### Developers and API
#### Getting a killstreak
You can get the killstreak of any player from the event listener as it shows here here:
```php
\ItzLightyHD\KnockbackFFA\EventListener::getInstance()->getKillstreak($player->getName());
```
If the player isn't playing KnockbackFFA, the function will return as "None".

### Contributing
[![Become a Patreon!](https://shieldsio-patreon.vercel.app/api/?username=itzlightyhd&type=patrons)](https://patreon.com/ItzLightyHD)
Click the button right here to become a Patreon of ItzLightyHD, the main developer of this plugin. You can also help us with finding bugs through issues and help us with the plugin by doing some pull requests.