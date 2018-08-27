# HMA! Pro VPN Linux connection script (Old)
--------------

## Basic overview

These are the HMA! Pro VPN Linux scripts which allow you to establish a connection to HMA! Pro VPN via OpenVPN protocol.

### hma-openvpn.sh

* Dialog-based OpenVPN® connection script; asks for server & protocol choice (TCP/UDP)
* Features: daemon-mode, server-pingtest, auto-connect to fastest server, show status
* Requires packages: curl wget openvpn dialog sudo fping

### hma-vpn.sh

* Features protocol choice (UDP/TCP), daemon mode, auto-login, port choice, show status, server-pingtest, auto-connect to fastest server
* Required packages: curl wget openvpn sudo fping

### Which script to choose?

**For Linux beginners** we recommend using the "hma-openvpn.sh" script by simply running it by typing **sudo bash hma-openvpn.sh**

**For advanced Linux users** we recommend the "hma-vpn.sh" script as it offers a variety of additional features for various purposes.

--------------

