# rpi-alpine-linux-setup
Rpi - Setup Alpine Linux

## Manual steps

Add an APK repository and install Git

`setup-apkrepos -1; apk update; apk add git`
  
Clone this repo

`git clone https://github.com/jeffman78/rpi-alpine-linux-setup ; cd rpi-alpine-linux-setup`

Edit the answer file and ajust hostname, IP settings and DNS server

`vi setup-alpine.in`

## Automatic steps

`setup-alpine -f setup-alpine.in`

You'll be prompted for the root password
 
  
