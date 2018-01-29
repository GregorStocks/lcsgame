## What is this?

Liberal Crime Squad. This version has everything from https://sourceforge.net/projects/lcsgame/, which became inactive in 2015. It's been updated to compile, for me, in Visual Studio 2017. I might keep adding features.

## Compiling

### Windows

Open the solution file in workspaces/ in Visual Studio 2017.

### Ubuntu

```
sudo apt-get install build-essential autoconf libncurses5-dev
cd lcsgame
./bootstrap
./configure
make
```

You can ignore the warnings. The binary will be in `src/crimesquad` and your savefile is in `~/.lcs`.

### OSX

Try the Ubuntu instructions, good luck! You might be better off running Ubuntu in Vagrant.
