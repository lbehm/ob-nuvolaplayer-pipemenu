ob-nuvolaplayer-pipemenu
========================

An Openbox pipe menu to access the Nuvolaplayer

Installation
============
1. Copy the script to the right place

	```sudo cp ob-nuvolaplayer-pipemenu /usr/bin/```
2. Be nice

	```sudo chmod 755 /usr/bin/ob-nuvolaplayer-pipemenu```
	```sudo chown 0:0 /usr/bin/ob-nuvolaplayer-pipemenu```
3. Place the following line in your menu.xml

	```<menu execute="ob-nuvolaplayer-pipemenu" id="pipe-nuvolaplayer" label="Nuvola Player"/>```

