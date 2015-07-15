# csgobash
A very simple bash script to control a CS:GO server

## Features
* Start the server
* Stop the server
* Restart the server
* Send commands to the server
* Launch (or not) the server on boot

## Requirements
* screen - [apt-get install screen]

## Installation
```console
$ cd /etc/init.d/
$ wget https://raw.githubusercontent.com/jpcanoso/csgobash/master/csgo
$ chmod +x csgo
$ update-rc.d csgo defaults
```

## TODO
* Option to update the server easily
