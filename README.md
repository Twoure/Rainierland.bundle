Rainierland.bundle
===================

This is a plugin that creates a new channel in Plex Media Server to view content indexed by the website www.rainierland.com

System Requirements
===================

- **Plex Media Server:**
	- Tested Working:
		- Windows
		- Linux (Ubuntu) Installation of a Javascript runtime may be required
		  sudo apt-get install nodejs (installs nodejs)
- **Plex Clients:**
	- Tested Working:
		- Plex Home Theater
		- Plex/Web
		- Samsung Plex App
		- Android Kit-Kat (Samsung Galaxy S3)
		- iOS (Apple iPhone6)

How To Install
==============

- Download the latest version of the plugin.
- Unzip and rename folder to "Rainierland.bundle"
- Delete any previous versions of this bundle
- Copy Rainierland.bundle into the PMS plugins directory under your user account:
	- Windows 7, Vista, or Server 2008: 
	C:\Users[Your Username]\AppData\Local\Plex Media Server\Plug-ins
	- Windows XP, Server 2003, or Home Server: 
	C:\Documents and Settings[Your Username]\Local Settings\Application Data\Plex Media Server\Plug-ins
	- Mac/Linux: 
        ~/Library/Application Support/Plex Media Server/Plug-ins
- Restart PMS

Known Issues
==============
- Thumbnails of items are not fetched due to 302 redirection (cookie/header not being used)
- Some movies will not play, currently depending on where hosted or removed.

Acknowledgements
==============
Thanks to jwsolve for inputs