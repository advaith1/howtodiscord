# Approving and denying tickets
As a Bug Hunter:tm: you have the ~~holy~~ respectful ability to approve and deny incoming reports in #Bug-Approval-Queue. All bugs **must** come through here, meaning that if you approve or deny a bug wrongly, there's no way to fix it once it's passed.

## Approve/Deny Formatting
When approving or denying a bug, it's good etiquette to:
- Avoid using shorthands if possible
- Include all relevant system and client information
- Use dynamic terms, like "latest build" or "newest mac"
- Be respectful
- With duplicate reports, include links to the Trello ticket

A common misconseption is that you can deny a bug report for a bug in #Denied-Bugs. **This is completely incorrect.** There are no circumstances where bugs can be denied for being related to or a duplicate of a denied bug.  
![Dabbit no deny deny](https://itspugle.is-a-bad-waifu.com/ed8718.png)

Even when approving, it's a good habit to learn to include a simple note like "can reproduce". Here is an example of some good approve and deny reasons:
```
!deny 0001 | Cannot Reproduce - MacBook Air 2013 13" [10.12.6 Sierra], Discord Canary [0.0.154]   
!approve 0002 | Can Reproduce - Lenovo ThinkPad [Windows 10 Creators], Discord Canary [0.0.163]
```

:warning: If you have any questions, or unsure, it's best to **not** approve or deny a bug, and let it be until you decide. If you honestly can't decide, you may want to consult with a Trello Moderator or Dabbit Prime. :warning:

## Valid deny reasons
### Duplicates
If a report has already been *approved* and a report highlighting the same issue is made, you can deny the report. Every deny message for duplicate must have a link, or code, for the trello included.  
`!deny 0001 | Duplicate Ticket of https://trello.com/abcd1234. Please check the Trello boards before reporting.`

### Cannot Reproduce
If you cannot reproduce the bug, and you're on the same platform (ignore device and build unless marked as specific), you can deny the report.  
`!deny 0001 | Cannot Reproduce - MacBook Air 2013 13" [10.12.6 Sierra], Discord Canary [0.0.154]`

### Not a Bug
Not to be confused with intended behaviour, not a bug means that the report... well.. isn't a bug... At least one of the three deny messages should contain a short explanation as to why it's not a bug.  
`!deny 0001 | Not a bug`

### Intended Behaviour
If the report is actually designed, intended or meant-to-be, the report can be denied a intended behaviour. At least one of the three deny messages should contain a little reason over why it's intended.   
`!deny 0001 | Intended behaviour`

### Other Reasons
If the bug report isn't valid, let's say it's an electron bug, deny it explaining it's an electron bug etc.  
`!deny 0001 | Electron Bug - <<link to GitHub Electron Issue>>`
