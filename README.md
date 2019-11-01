# i3-config
My simple configuration for i3wm.

## Pre-Installation

#### scrot (for screenshot)
``` 
sudo apt-get install scrot 
```

#### alsamixer (for volume controls)
``` 
sudo apt-get install alsa alsa-tools 
```

#### light (for controlling brightness)
* Download the file from [here](https://github.com/haikarainen/light/releases/).

* Run the following commands.
``` 
tar xf light-x.yy.tar.gz
cd light-x.yy/
./configure && make
sudo make install 
```
If you face any problems while installing light, please refer [here](https://github.com/haikarainen/light).

#### rofi (starting dmenu)
```
sudo add-apt-repository ppa:jasonpleau/rofi
sudo apt update
sudo apt install rofi
```
#### background 
```
sudo apt-get install feh
```

After installing these packages, place the configuration file in .config/i3/config
