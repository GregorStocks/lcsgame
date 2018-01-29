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
