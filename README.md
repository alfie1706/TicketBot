
# TicketBot
Developed and maintained by [alfie1706](https://github.com/alfie1706) @ [VoidServices](https://github.com/VoidServices).

This tool aims to help your company by giving you the ability to setup your own bot in less than 5 minutes!

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://paypal.me/alfieturner1706)

## Dependencies
.NET Framework 2.0 or later

 - Windows installation: https://dotnet.microsoft.com/download
 - Linux installation: https://dotnet.microsoft.com/download/linux-package-manager/ubuntu18-04/sdk-2.1.301 (Be sure to choose your correct linus distro!)
 - 
## So, I have the dependencies. How do I setup?
Excellent! These next steps will guide you through the initial startup of the TicketBot.

To launch the bot for the first time, you will need to do the following.

 1. Clone this repository to your computer/server
 2. Ensure you have .NET framework 2.0 or later installed (see above for downloads)
 3. Navigate to the directory you cloned the repository to and execute commands
3a. linux - `dotnet TicketBot.dll` `bash run.sh`
3b. Windows - `dotnet TicketBot.dll` or open application `run.bat`

### First-time installation:
 1. To get a bot token (as seen in the first step upon startup) you will need to create a bot user. An in-depth tutorial can be found at this link [here](https://discordpy.readthedocs.io/en/rewrite/discord.html). If you need any further assistance with this please do not hesitate to reach out to me!
 2. Choose your bot prefix (This is commonly set to '!' or '?')
 3. Choose what your bot will display as [Playing](https://why-am-i-he.re/mEqQkd.png)
 4. Should the bot say "Unknown Command" when it doesn't recognise a command (only true/false response accepted)
 5. Tickets support role ID (You can get this by escaping a mentioned role like this; "\@Role")

After this, press enter and the bot will launch for the first time! No more setup required.
## Feature Requests
I'm more than happy to take on feature requests and implement them, please open an issue with the Feature Request Label!
