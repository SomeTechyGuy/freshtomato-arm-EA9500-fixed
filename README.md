# **FreshTomato-ARM-EA9500-fixed** #

# This port has TONS of bugs and you MUST have UART access to your router to set dhd24=1 in the nvram FROM CFE OR ELSE YOUR ROUTER IS BRICKED, YOU WILL BRICK YOUR ROUTER EVEN IF YOU HAVE A BACKUP FIRMWARE ON THE OTHER PARTITION

### you must run WITH UART (I DONT CARE WHAT THE AI SAYS) ```ifconfig vlan1 add 192.168.1.1 netmask 255.255.255.0``` in freshtomato to make the network function

### if you need to tftp flash something in cfe, use ethernet port 8, no other port works for some reason

# if this damages your router or mental health (due to trauma because you tried to make this stupid thing work), I'm not responsible.

## The patches in this firmware are made with AI, I don't have any programming knowledge to do this myself.
  
***Disclaimer: I am not responsible for any bricked routers, nor do I encourage other people to flash alternative firmwares on their routers. Use at your own risk!***  
