# Finding your Version and Build
[< Return to the home](/index)  
[< Return to the bugs navigation](/bugs)

When reporting bugs, or responding to bugs, it's crucial to include information about your Discord client. For Desktop, you can put either the build number, version number, or both. We recommend you include both, but if you only include one, the build number is preferred.

## Desktop and Web Build Number
To get your Build Number for Discord, you'll need to:
1. Press `Ctrl-Shift-I` (`Command-Option-I` on macOS).  
2. Scroll up to the top.
3. One of the earliest messages should say contain the Build Number.
![Console Build Info](https://image.prntscr.com/image/aElHTPCQRjWNTUMIP631oQ.png)

## Desktop Client Version Number
### Windows
For Windows, press Win+R and enter `%appdata%/discord<version>`, and press enter,

Build Version | Folder location
------------ | -------------
Stable Build | `%appdata%/discord`
Public Test Build | `%appdata%/discordptb`
Canary Build | `%appdata%/discordcanary`

It should open a folder in File Explorer, the highest folder in that is the version number. (should start with 0.0.)

### macOS
For macOS, just click the `Discord <Version>` menu on the menu bar, then click the `About Discord` option:  

<img src="https://cdn.discordapp.com/attachments/252296452708106240/356152267679858688/Screen_Shot_2017-09-09_at_12.01.44_PM.png" alt="About Discord" style="width: 400px;"/> <img src="https://cdn.discordapp.com/attachments/252296452708106240/356152439109582848/Screen_Shot_2017-09-09_at_12.02.01_PM.png" alt="About Discord Menu" style="width: 400px;"/>

### Linux
For Linux, open a terminal whilst Discord is running and enter the package name.

Release Channel | Command
------------ | -------------
Stable | `discord`
PTB (Public Test Build) | `discord-ptb`
Canary | `discord-canary`

## Mobile Version and Build
To get your Build Number for Discord, you'll need to:
1. Open your User Settings.
2. Scroll to the bottom if you have a small screen.
3. It should say the version number in the bottom right, with the build number in parantheses. Example: 1.2.3 (135)
