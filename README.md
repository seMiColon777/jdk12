## Learning JVM through JDK12

### Prepare in Ubuntu
1. install gcc  
   I tried the commandline below in Ubuntu 20.04, it installed the gcc/g++ 9, which caused compile failed.
```commandline
   sudo apt-get install build-essential  
```

then I used the commandline below instead:
```commandline
   sudo apt-get install gcc-7  
   sudo apt-get install g++-7  
   sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-7 100  
   sudo update-alternatives --config gcc  
   sudo update-alternatives --install /usr/bin/g++ g++ /usr/bin/g++-7 100  
   sudo update-alternatives --config g++  
```

2. install other libs
```commandline
   sudo apt-get install libfreetype6-dev  
   sudo apt-get install libcups2-dev  
   sudo apt-get install libx11-dev libxext-dev libxrender-dev librandr-dev libxtst-dev libxt-dev  
   sudo apt-get install libasound2-dev  
   sudo apt-get install libffi-dev
   sudo apt-get install autoconf
```
3. install another jdk
```commandline
   sudo apt-get install openjdk-11-jdk
```
