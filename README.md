# Portainer Templates V0.1
I have no idea what I'm doing with GitHub, should have forked, didn't do that, downloaded some stuff and trying to get this to work for just the apps I like. Kinda using this as a backup of sorts for my apps.

### Prerequisites

1. A server/NAS with docker installed.
2. A Portainer-CE setup.

### Installing

1. Login to your Portainer setup go to settings
2. Go to:  Application settings > App Templates
3. Add the url: `https://raw.githubusercontent.com/SighMonIs/portainer/main/template.json` then go to app templates and hit refresh at the top.

### Information - this needs to be updated once I figure out the file location stuff
All templates are already configured to bind mount to various places on your drive. The following folders are all created in **/portainer/**

* **Files** - General file storage.
  * **AppData** - Subfolder where application data (unrelated to served data) is stored.
    * **Config** - Subfolder where configuration files for every container are stored.
* **Downloads** - Where bittorrent and usenet downloaders download files to.
* **TV** - Where tv shows are stored/moved to after downloaded.
* **Movies** - Where movies are stored/moved to after downloaded.
* **Music** - Where music is stored/moved to after downloaded.
* **Books** - Where books are stored/moved to after downloaded.
* **Comics** - Where comics are stored/moved to after downloaded.
* **Podcasts** - Where podcasts are stored/moved to after downloaded.

## App List
- Organizr2
- Overseerr
- qBittorrent
- Sonarr
- Radarr
- Lidarr
- Lidify
- Kapowarr
- Prowlarr
- Maintainerr
- Bazarr
- Komga
- Plex
- Mealie
- Wiki.JS
- PinchFlat
- MeTube
- FileBrowser
- WireGuard - Easy
- FlareSolvarr
