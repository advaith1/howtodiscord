# Finding your Version and Build
When reporting bugs or approving/CRing them, you must include the build number. We also recommend you provide the version number. For mobile bugs, you must include the version number.

## Desktop Build
To find the Build of Discord Canary, follow these steps:  
1. Press `Ctrl+Shift+I` (`Command+Shift+I` on macOS)
2. Click Console
3. Scroll up to the top.
4. The third message should say:
![Console Build Info](https://cdn.discordapp.com/attachments/252296452708106240/356153419561435147/Screen_Shot_2017-09-09_at_12.06.19_PM.png)  
On a different release channel? For now, just include the build number.

## Mobile
For Mobile, open User Settings in Discord and scroll all the way down on the screen that opens. At the bottom, it will say the version number, followed by the build number in parentheses.

### Desktop Version
Even though the version number is not required for desktop, it is recommended. Note that the web client doesn't have a build number.
#### Windows Client
To find the version of Discord, enter `%appdata%/discord<version>` in the directory location of a File Explorer window.

For the Public Test Build, go to `%appdata%/discordptb`.  
For Canary, go to `%appdata%/discordcanary`.  
For Stable, go to `%appdata%/discord`.  

#### macOS Client
For macOS, just click the `Discord <Version>` menu on the menu bar, then click the `About Discord` module:  

<img src="https://cdn.discordapp.com/attachments/252296452708106240/356152267679858688/Screen_Shot_2017-09-09_at_12.01.44_PM.png" alt="About Discord" style="width: 400px;"/>
<img src="https://cdn.discordapp.com/attachments/252296452708106240/356152439109582848/Screen_Shot_2017-09-09_at_12.02.01_PM.png" alt="About Discord Menu" style="width: 400px;"/>

#### Linux Client
Open a terminal while Discord is running, and type the package name.

For Stable, `discord`.  
For PTB, `discord-ptb`.  
For Canary, `discord-canary`.
