================================================================================
                      Liberal Crime Squad Linux Notes
================================================================================

For Ubuntu:

sudo apt-get install build-essential autoconf libncurses5-dev
cd lcsgame
./bootstrap
./configure
make

You can ignore the warnings. The binary will be in src/crimesquad and your savefile is in ~/.lcs.

On OSX, it's pretty easy these days to run Ubuntu inside Docker. I do it with Vagrant. :)
