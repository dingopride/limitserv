###### Requirements
* [Python](https://www.python.org/downloads/) *(**Note:** This script was developed to be used with the latest version of Python.)*
* [PySocks](https://pypi.python.org/pypi/PySocks) *(**Optional:** For using the `proxy` setting.)*

###### Information
The bot will automatically give voice *(+v)* to people after they have been in a channel for a certain amount of time.

It will also set a channel limit *(+l)* every few minutes to limiting the channel to only allow a certain amount of more users.

This is to prevent people from loading a massive amount of bots or clones into the channel at once.

###### Anope Usage
Add a new services operator if you already are one by doing:
- `/msg OperServ OPER ADD LimitServ Services Root`

To have the bot automatically join channels, register the bot with NickServ and then do:
- `/msg NickServ AJOIN ADD LimitServ #channel`

###### Mirrors
- [acid.vegas](https://git.acid.vegas/limitserv) *(main)*
- [SuperNETs](https://git.supernets.org/acidvegas/limitserv)
- [GitHub](https://github.com/acidvegas/limitserv)
- [GitLab](https://gitlab.com/acidvegas/limitserv)
- [BitBucket](https://bitbucket.org/acidvegas/limitserv)
