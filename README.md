Icing Window Saver
=============

This applet allows you to save and restore all of your windows' positions through a menu, or using hot keys.

 * SHIFT+CTRL+S - Save windows
 * SHIFT+CTRL+R - Restore windows

Requires ```xwininfo``` and ```wmctrl``` packages. Tested on Cinnamon 3.0.7 and Cinnamon 3.2.2.

### Contributing

*  Use [Node 6.x](https://github.com/nodesource/distributions).
```sh
curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
sudo apt-get install -y nodejs
```
*  Install node modules: ```npm install```
*  Install gulp globally if you haven't already. ```sudo npm install -g gulp```
*  Start transpile watch task: ```gulp spawn-watch```
*  Monitor logging output: ```tail -f -n100 ~/.cinnamon/glass.log```