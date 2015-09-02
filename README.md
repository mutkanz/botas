# basicBot (source)
> A not so basic bot for plug.dj

---

[CLICK HERE TO CUSTOMISE BASICBOT!](https://github.com/Yemasthui/basicBot-customization)
-

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/Yemasthui/basicBot?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge) [![facebook group](https://ssl.benzi.io/dump/facebook-group-badge.svg)](https://facebook.com/groups/basicBot) [![twitter](https://ssl.benzi.io/dump/twitter-badge.svg)](https://twitter.com/bscbt)

Email enquiries: [bnz.mngn [at] gmail [dot] com](mailto:bnz.mngn@gmail.com)

---

Developers
-------------

__Current:__
 - [Benzi](https://github.com/Benzi) __(Maintainer)__

__Past:__
 - [Yemasthui](https://github.com/Yemasthui) __(Creator)__

###__IMPORTANT__

__basicBot has been updated to work under plug's major update. There may still be bugs and functionality is not guaranteed.__

__Make sure to update your bookmark, as the link has changed recently!!!__

__Important changes in version 2.x.x:__

- Now should be fully compatible with Firefox.
- You can now change the bot's name, no need to make a fork to change it anymore. Available under custom settings as "botName".
- The bot's variable is now exposed outside of the script. You can access it as the variable "bot" in the console. This should allow for secondary scripts extending the bot without the need to fork and lose support on its basis.
Be careful when extending it to make sure commands or features interact properly with the rest of them.
An example script to extend the bot is provided under exampleExtension.js. Please do not fork this repository to just change that file. Details of how to use are provided inside.
This is NOT needed to run the bot as it is provided, only if you want to add functionality.
- Command checking has been reworked to facilitate adding commands through secondary scripts as explained above.
- __There is now support for custom chat messages. This means you can use your own custom wording or translate it into your own language.__

Usage
-------

Bookmark the following code. To run the bot, run the bookmark.

`javascript:(function(){$.getScript('https://rawgit.com/Yemasthui/basicBot/master/basicBot.js');})();`

If this does not work, go to https://raw.githubusercontent.com/Yemasthui/basicBot/master/basicBot.js and copy paste its content into your console (accessible in chrome by pressing f12) when on plug.dj in your community.

### Commands

These can be found in [the commands file](https://github.com/Yemasthui/basicBot/blob/master/commands.md).

### Blacklists
Examples of blacklists can be found in [the customization repository](https://github.com/Yemasthui/basicBot-customization/tree/master/blacklists).
You can add blacklists in the settings of the bot via the methods given in that same repository. See below for more information.

### Extending functionality and custom default settings

basicBot can be customized to fit your needs. Please refer to [the customization repository](https://github.com/Yemasthui/basicBot-customization) for more info.
Please do not try to if you are not confident in your javascript capabilities.


### Translations

Official translations will be supported. Available ones can be found under [the language folder](https://github.com/Yemasthui/basicBot/blob/master/lang/langIndex.json). You can set a language in the room settings.
You can use your own translation or wording by translating the values of in [the English pack](https://github.com/Yemasthui/basicBot/blob/master/lang/en.json) and uploading it to a public hosting service. Put the link into your custom room settings, under chatLink.

__When translating the chat messages, please note that it is a json format, meaning it is structured as ```"key":"value"```, please only translate the "value" parts, and leave anything between %% (eg. %%NAME%%) as is, they are variables that get filled in by the bot.__

Useful Tools
---------------

### basicBot Chrome Extension

- [Get the Official basicBot Chrome Extension](https://chrome.google.com/webstore/detail/basicbot/bjinmbkeneigmkkkpcmcokphbjkepeie)

### Command Autocomplete Plugin

[![Command Autocomplete](http://i.imgur.com/hBMuB5F.png)](https://github.com/ExtPlug/advanced-autocomplete)

Check out [this](https://github.com/ExtPlug/advanced-autocomplete) helpful command autocomplete browser plugin by [goto-bus-stop](https://github.com/goto-bus-stop) made to work with basicBot's commands.


Credits
--------

I would like to thank the following people:

- Fungus: His Tastybot has been a source of inspiration for most of the features, and his help with coding problems has been invaluable to make this bot.
- TAT, Origin and other Litebot contributors: Their Litebot has inspired features like Roulette.
- Henchman: Never knew this undertaking would give me a friend too.

|Language | Translator|
|:------:|:---------:|
|Portuguese|[Motel Bible](https://github.com/motelbible)|
|French|[NDA](https://github.com/NDAthereal)|

__I would also like to thank everyone who contributed in translating the bot via the [translation centre](http://translate.benzi.io/admin/collaborators)__


### Copyright

Copyright &copy; 2014-2015 Yemasthui

Modifications (including forks) of the code to fit personal needs are allowed only for personal use and should refer back to the original source.
This software is not for profit, any extension, or unauthorised person providing this software is not authorised to be in a position of any monetary gain from this use of this software. Any and all money gained under the use of the software (which includes donations) must be passed on to the original author.


Disclaimer
------------

This bot is developed independently. Changes may be made without notice. There is no guarantee for the bot to be functioning perfectly.
plug.dj admins have the right to request changes.
By using this chatbot you agree to not use it for violating plug.dj's Terms of Service.
You also agree not to alter the bot's code, unless in the cases explicitly stated above, for personal use, or for the sole purpose of submitting a pull request with a bug fix or a feature update, at which point it will be looked at and decided by the authors of the project.
Please refer to the original author/repository at all times, even on personal forks that are not private.
Any requests for changes can be requested via email, through github or via plug.dj.
