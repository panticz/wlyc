Linux Yamaha Receiver Webcontrol
====

![](http://dl.panticz.de/wlyc/wlyc.jpg)

Simple Webinterface for Linux Yamaha receiver control: https://github.com/panticz/lyc


### Install on OpenWRT router
1. Login to OpenWRT router  
`ssh root@YOUR_OPENWRT_IP`

2. Download wlyc (because OpenWrt wget can only acces http use a redirection to GitHub)  
`wget -q http://dl.panticz.de/wlyc/wlyc -O /www/cgi-bin/wlyc`

3. Set permissions  
`chmod 755 /www/cgi-bin/wlyc`


### Usage
Open wlyc web interface in a browser  
`http://YOUR_OPENWRT_IP/cgi-bin/wlyc`  

Direct access (e.g. change input to DVD)  
`http://YOUR_OPENWRT_IP/cgi-bin/wlyc?p1=input&p2=dvd`

### JavaScript Yamaha Receiver Webcontrol for Yamaha RX-V3900
Live Demo available under:
http://dl.panticz.de/wlyc/wlyc3900.html
