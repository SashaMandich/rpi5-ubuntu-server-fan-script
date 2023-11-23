# rpi5-ubuntu-server-fan-script

This script has been written for ubuntu server 23.10 on Raspberry Pi 5, since to date 2023/11/16 the new fan header is unsupported on this specific OS making the fan go to 100% speed all the time.

while loop has been added, thanks to https://www.youtube.com/watch?v=M--nU_Zg-ZQ

## Installation

- clone the project
- copy the script in the desired folder
- give it execution permission with  
   `sudo chmod +x ./fan_script.sh`
- with root priviledge (`sudo su`), run `crontab -e`
- save and close, the script should kick in.

This repository will be archived the moment a proper driver will be released on the ubuntu kernel, this is only a temporary fix.