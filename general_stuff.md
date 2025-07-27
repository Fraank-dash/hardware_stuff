# Renaming The host for _local potatos_
A _local potato_ is a server in your local network
Usecase: "The _local potato_ has a very long name and i need to shorten it, because i am lazy"

```shell
sudo nano /etc/hostname  #change hostname here
sudo nano /etc/hosts #change hostname here aswell for 127.0.1.1
sudo reboot 
```

e.g, change hostname from _raspberrypi_ to _pi5_
- in the hostname-file tehre should be a line like this: `pi5`
- in the hosts file there should be a line then like this: `127.0.1.1       pi5 pi5.local` or this `127.0.1.1   pi5`
  - there are other lines as well, ignore them, dont change things you dont know anything about.
 
> the advantage of short names in your local network is that you can easy access your _local potatoes_
> e.g. instead of `ssh username@local_potato1` use `ssh name@lp1`
