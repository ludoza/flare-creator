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
# clone flare creator
git clone https://github.com/ludoza/flare-creator
# open the flare-creator, qt project in qtcreator; build; run; deity mode!!1 
```

Remember to compile flare and the random map generator, before executing flare-creator, it is also recommended to have a couple of mods [flare-game], [flare-mod-noname], $MSG_ME_UR_MOD.

# FAQ

Q: I can not find the qt project?
A: #TODO

Q: Your instructions for my $OS does not work?
A: I only have access to OS X.

[flare-engine]: https://github.com/clintbellanger/flare-engine
[map-generator]: https://github.com/Paul-Wortmann/Random_Map_Generator.git
[flare-mod-noname]: https://github.com/igorko/flare-mod-noname.git 
<link rel="stylesheet" type="text/css" href="http://goo.gl/A0Ah1C">
