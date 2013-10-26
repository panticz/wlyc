Linux Yamaha Receiver Webcontrol
====

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
