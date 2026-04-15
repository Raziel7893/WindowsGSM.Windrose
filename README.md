# WindowsGSM.Windrose
🧩WindowsGSM plugin that provides Windrose Dedicated server

## PLEASE ⭐STAR⭐ THE REPO IF YOU LIKE IT! THANKS! CHECK BELOW FOR A TIP OPTION

### Notes
- install everything inside serverfiles\Engine\Extras\Redist\en-us _(click Browse => ServerFiles to find it)
  - if that does not help also install https://www.microsoft.com/en-us/download/details.aspx?id=35
  - And if you are on a Server: Install DotNet4.5 via serverConsole https://www.youtube.com/watch?v=uSRMvCjuUdI   


### WindowsGSM Installation: 
1. Download  WindowsGSM https://windowsgsm.com/ 
2. Create a Folder at a Location you wan't all Server to be Installed and Run.
3. Drag WindowsGSM.Exe into previously created folder and execute it.

### Plugin Installation:
1. Download [latest](https://https://github.com/Raziel7893/WindowsGSM.Windrose/releases/latest) release
   Or click Code => Download .zip
3. Either Extract then Move the folder **Windrose.cs** to **WindowsGSM/plugins** 
    1. Press on the Puzzle Icon in the left bottom side and press **[RELOAD PLUGINS]** or restart WindowsGSM
4. Or Press on the Puzzle Icon in the left bottom side and press **[IMPORT PLUGIN]** and choose the downloaded .zip

### Official Documentation
🗃️ Included as PDF in the steamdownload

### The Game
🕹️ https://store.steampowered.com/app/2218970/Plains_of_Pain/

### Dedicated server info
🖥️ https://steamdb.info/app/2227360/infos/

### Port Forwarding (YOU NEED THIS, TO BE ABLE TO CONNECT FROM THE INTERNET(only for servers/pcs at home):
- If You don't know How: Google: YourRouterBrand + Portforwarding
- 7777 UDP - Default
- 7778 UDP - Default Query

### Files To Backup
- Save Game (You could only save serverfiles/Windrose/Saved , but that includes many big logs)
  - WindowsGSM\servers\%ID%\serverfiles/R5/Saved/SaveProfile
  - WindowsGSM\servers\%ID%\serverfiles/R5/Saved/Configs
- WindowsGSM Config
  - WindowsGSM\servers\%ID%\configs

### Available Params
All these params are automatically set by WGSM. Check Serverfiles/Documentation.pdf
- -port=8211                    can be change by Click Edit Config => Port
- -queryPort=27015              can be change by Click Edit Config => QueryPort
- -serverName                   can be change by Click Edit Config => Server Name
- -nographics 					default
- -batchmode					default

### Connecting on a locked server (with password)
For now only Connecting via a the ingame serverbrowser is possible. It is recommended to note down the 5 Options after password and filter your servers accordingly (as there is no name filter either)
- On the left of the join window be sure to click public (not official)
- On the lower part choose your options to filter down the list of servers
- Be sure to favour your server, so they should show up under Favorites on the next time

### Other notes
- The game is currently in Early Access Stage WGSM and this plugin is not taking liability if something happens to your server, the app is only for managing your server easily

### Not having an full IPv4 adress ( named CCNAT or DSL Light )
No game or gameserver supports ipv6 only connections. 
- You need to either buy one (most VPN services provide that option. A pal uses ovpn.net for his server, I know of nordvpn also providing that. Should both cost around 7€ cheaper half of it, if your already having an VPN)
- Or you pay a bit more for your internet and take a contract with full ipv4. (depending on your country)
- There are also tunneling methods, which require acces to a server with a full ipv4. Some small VPS can be obtained, not powerfull enough for the servers themself, but only for forwarding. I think there are some for under 5€), the connection is then done via wireguard. but its a bit configuration heavy to setup) 

Or you connect your friends via VPN to your net and play via local lan then.
Many windowsgsm plugin creators recommend zerotier (should be a free VPN designated for gaming) , see chapter below (or tailscale, but no howto there)

## How can you play with your friends without port forwarding?
- Use [zerotier](https://www.zerotier.com/) folow the basic guide and create network
- Download the client app and join to your network
- Create static IP address for your host machine
- Edit WGSM IP Address to your recently created static IP address
- Give your network ID to your friends
- After they've joined to your network
- They can connect using the IP you've created eg: 10.123.17.1:7777
- Enjoy

### Support
[WGSM](https://discord.com/channels/590590698907107340/645730252672335893)

### Give Love!
[Buy me a coffee on Kofi](https://ko-fi.com/raziel7893)

[Paypal](https://paypal.me/raziel7893)

### License
This project is licensed under the MIT License - see the <a href="https://github.com/raziel7893/WindowsGSM.Windrose/blob/main/LICENSE">LICENSE.md</a> file for details

### Thanks
Thanks to ohmcodes for the Enshrouded and Palworld Plugins which i used for guidance to create this one
