# GSecurity
GSecurity Windows Hardening

# This app will use builtin windows files to debloat and harden windows. None of the code is mine, I just copy pasted it from all over the net. If you have 3rd party security apps active, you should disable them for this to work or they may interrupt it. 

# GSecurity will use powershell commands to uninstall all apps except store and xbox identity, which methinks are needed for normal system operation. 

# It will also import tweaked 2004 microsoft security baseline. The tweak is in disabling usb writing protection unless the usb is encrypted and the 2nd tweak is allowing users to run even files that smartscreen doesn't approve of. 

# Next it will import firewall rules. Some firewall rules belong to other hardening apps, some belong to lists of malicious ips. 

# Next it will delete ssdpsrv service, which is a requirement for upnp service, which has a vulnerability not patched for a long time.

# Next it will setup a pac file maintained by a private person (not me), which is based on easy lists hosts file for your protection. 

# Next it will apply some performance tweaks. 

# Next it will add a bunch of context menus to make your life easier. 

# And next it will import SSRP, software restriction, which is made by me, and should ensure an additional layer of protection against some threats I encountered personally.
