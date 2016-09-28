# rpi-headers
A tool to build linux-headers on your Raspberry Pi.

## Reasoning
The [raspberrypi.org](http://archive.raspberrypi.org/debian) and [raspbian.org](http://archive.raspberrypi.org/debian) APT repositories do not contain very many versions of linux-headers packages, especially newer ones that are necessary after using [Liam McLoughlin's](https://github.com/Hexxeh) [rpi-update](https://github.com/Hexxeh/rpi-update) tool.

## Dependencies
```
$ sudo apt-get install wget git make gcc-4.7 bc dkms
```

## Execution
```
$ ./rpi-headers
```

## Credits
- [niksula.hut.fi/~mhiienka](https://www.niksula.hut.fi/~mhiienka/Rpi/linux-headers-rpi) for building and hosting pre-built linux-headers packages.
