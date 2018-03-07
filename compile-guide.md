# Linux (Tested with ubuntu)

Start with updating and upgrading the current operating system

`sudo apt-get update; sudo apt-get upgrade`


Then start installing the necessary dependencies needed to compile the code.

`sudo apt-get install libboost-all-dev cmake make g++ gcc git`


Now, download the repo (AfriCoin) so we can start too build the source and also entering the correct directory to build the files too.

`git clone https://github.com/afrihub/AfriCoin.git; cd AfriCoin; mkdir build; cd build`

Now, we need to run cmake and make and the source files will start to build, once the percentage counter hits %100, you can locate the binaries in the src file.

`cmake ..; make`


# Windows (Used windows server 2012)

