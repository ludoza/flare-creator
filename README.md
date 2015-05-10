# flare-creator

This is still in planning, so this is a setup of our development environment.

Note the commands below does not include the [flare-engine] or other setup instructions, consult their respective [INSTALL.engine.md]() instructions.

```sh
# install git, qtcreator and our map editor
# ubuntu (debian)
sudo apt-get tiled qtcreator git
# os x (http://brew.sh/)
brew install tiled qtcreator git
# windows (https://chocolatey.org/)
choco install tiled qt-sdk-windows-x86-msvc2012_opengl git
# I see flare as a collection of all the related git repo's
mkdir flare
cd flare
# git clone our game engine into flare directory
git clone https://github.com/clintbellanger/flare-engine
# clone our random map generator
git clone https://github.com/Paul-Wortmann/Random_Map_Generator.git
# clone our commander
git clone git@github.com:brothers-of-the-moot/flare-cmd.git
# clone our map editor, if you would like to edit it as well with qtcreator.
# git clone https://github.com/bjorn/tiled.git 
```

Compile all the checked out projects, and download a couple of mods [flare-game], [flare-mod-noname], `$MSG_ME_UR_MOD`.

To get started open up flare and load the fantasycore and devlab mod, and start to play!
Follow the instruction given by the programmers in the game.

# FAQ

Q: Your instructions for my $OS does not work?
A: I only have access to OS X.

[flare-engine]: https://github.com/clintbellanger/flare-engine
[flare-game]: https://github.com/clintbellanger/flare-game
[map-generator]: https://github.com/Paul-Wortmann/Random_Map_Generator.git
[flare-mod-noname]: https://github.com/igorko/flare-mod-noname.git 
[tiled]: http://www.mapeditor.org/
<link rel="stylesheet" type="text/css" href="http://goo.gl/A0Ah1C">
