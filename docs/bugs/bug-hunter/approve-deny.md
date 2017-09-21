# Approving and denying tickets
As a Bug Hunter™ you have the ~~holy~~ respectful ability to approve and deny incoming reports in #Bug-Approval-Queue. All bugs **must** come through here, meaning that if you approve or deny a bug wrongly, there's no way to fix it once it's passed.

⚠️ If you have any questions, or unsure, it's best to **not** approve or deny a bug, and let it be until you decide. If you honestly can't decide, you may want to consult with a Trello Moderator or other Bug Hunters. ⚠️

## Approve/Deny Formatting
When approving or denying a bug, it's good etiquette to:
- Avoid using shorthands if possible
- Include all relevant system and client information
- Don't use dynamic terms, like "latest build" or "newest mac". Be as **specific** as can be!
- Be respectful
- With duplicate reports, include links to the Trello ticket

A common misconception is that you can deny a bug report for a bug in #Denied-Bugs. **This is completely incorrect.** There are no circumstances where bugs can be denied for being related to or a duplicate of a denied bug. However, you might be able to deny a bug for the same reason the bug was denied earlier.
![Dabbit no deny deny](https://itspugle.is-a-bad-waifu.com/ed8718.png)

### Approving Bug Reports
Even when approving, it's a good habit to learn to include a simple note like "can reproduce". Here is an example of some good approve and deny reasons:

`!deny 0001 | Cannot Reproduce on Discord Canary 0.0.154 (Build 3901), macOS Sierra 10.12.6 (16G29) (iMac Retina 5K, 27-inch, Late 2017)`

`!approve 0002 | Can Reproduce - Lenovo ThinkPad [Windows 10 Creators Update], Discord Canary [0.0.163]`

You must include Discord's version number, and it is strongly recommended that you also include your build number. To learn how to find those, click [here](/DiscordApp/docs/bugs/version).

Here's the deny for CNR system for bug reports:

Your operating system | Reports you can deny for CNR
-------- | --------
Windows or macOS | macOS, Windows and Web-App
Linux | macOS, Windows, Linux and Web-App
Android | Android
iOS | iOS

If a bug can be reproduced on more then one category (e.g. Can be reproduced on Android and iOS), the bug should be denied then resubmited in #general-bug-reports.

If you are not on the same platform, you can still deny for NAB, intended, dupe, vague, or Electron bug. Only CNR must conform to the above table.

## Valid deny reasons
### Duplicates (Dupe)
If a report has already been *approved* and a report highlighting the same issue is made, you can deny the report. Every deny message for duplicate must have a link, or code, for the trello included.  
`!deny 0001 | Duplicate Ticket of https://trello.com/abcd1234. Please check the Trello boards before reporting.`

### Cannot Reproduce (CNR)
If you cannot reproduce the bug, and you're on the same platform (ignore device and operating system unless marked as specific or in a specific operating system flow), you can deny the report.  
`!deny 0001 | Cannot Reproduce - MacBook Air 2013 13" [10.12.6 Sierra], Discord Canary [0.0.154]`  

If they are more then two builds out from the current build, or one major build away, make sure to get them to update their client and see if they can still reproduce the bug. It may have been patched in a recent update.

### Not a Bug (NAB)
Not to be confused with intended behaviour, not a bug means that the report... well.. isn't a bug... At least one of the three deny messages should contain a short explanation as to why it's not a bug. Most, if not all, NAB reports are either intended or are feature requests, in which case the user should be sent to Discord Feedback [https://discord.gg/discord-feedback](https://discord.gg/discord-feedback).  
`!deny 0001 | Not a bug - Reason`

### Intended Behaviour
If the report is actually designed, intended or meant-to-be, the report can be denied a intended behaviour. At least one of the three deny messages should contain a little reason over why it's intended. Even though intended ≠ NAB, if a report is intended it's NAB. However, some NAB reports may not be intended.  
`!deny 0001 | Intended behaviour - Reason`

### Vague Report
If the report is vague or any section of the report is empty or non-descriptive, you may deny the report. At least one of the three deny messages should say which section.  
`!deny 0001 | Vague - System Settings`

### Electron Bug
Discord runs off Electron, which means that it inherits any Electron bugs. If Electron bugs are reported, deny it as so.
`!deny 0001 | Electron Bug - Electron Link`

A list of all registered Electron bugs can be found [here](https://github.com/electron/electron/issues).

### Lazy Loading
Discord employs a system called "Lazy Loading" to make sure that imediately required content is fetched first, and then content is fetched as it's needed. If a bug is the result of Lazy Loading, deny it as follows. At least one deny should explain why it's a result of Lazy Loading.  
`!deny 0001 | Lazy Loading - Reason`

##
[< Return to the bug documents navigation](/bugs/bug-hunter)
[< Return to the home page](/index)
