::FireFall IRC::
====================

An ingame IRC client for FireFall.

More info in this [thread here](http://www.firefallthegame.com/community/threads/addon-ingame-irc.65422/) :)

###::FireFall Addon::
====================
###[Download Addon](https://github.com/ArkyChan/FireFall-IRC/raw/master/IRC.zip)
====================

You can either use Melder from [here](http://www.firefallthegame.com/community/threads/addon-manager-melder.52327/) or extract the zip to "system\gui\components\MainUI\HUD\Addons" in your FireFall install, if you don't have an Addons folder just make one.
![Ingame shot](http://www.yayifications.net/firefall/addons/irc/IRC_FULLSCREEN.png "Ingame Shot")


###::Relay Server::
====================
###Dependencies:
The relay server is written for Node.js so it has a few dependency that you will need to install. Thank fully it shouldn't hurt too badly :P
*  Node.js.
* 	Socket.io.
* 	node-irc 

###Installation:
Use one of these methods to install Node.js and npm: https://gist.github.com/579814

Then just navigate to the directory where you want to locate the server and run this script:
 ```bash
curl https://raw.github.com/ArkyChan/FireFall-IRC/master/IRCRelay/get.sh | sh
  ```
That script should install the dependencies and grab the latest version of the server, now you just have to launch the server.

Like so:
 ```bash
node app.js [port] [IRC server URL](optional)
  ```

change [port] to your liken.

[IRC server URL] is optional, but if set it will only allow connections to that IRC's URL, if omited than the relay can connect to any network. 

Annnd done :)
