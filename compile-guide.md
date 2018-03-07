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
We recommend compiling using a fresh device.

Start with downloading and installing the necessary dependencies:

* Microsoft Visual Studio 2017 (Link: https://www.visualstudio.com/downloads/)
* CMake 3.9.5 (Link: https://cmake.org/)
* Boost with MSVC 14.1 Support (Link: https://studiofreya.com/2017/04/23/building-boost-1-64-with-visual-studio-2017/)
* Git CLI (Link: https://desktop.github.com/)
