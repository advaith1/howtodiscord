# Bug Hunter Commands
[< Return to the home](/index)  
[< Return to the Bug Hunter navigation](/bugs/bug-hunters)

As a Bug Hunter™ you are awarded an elevated permissions level, which grants you access to several Bug Hunter only commands.  Whilst these commands aren't going to end the world if you misuse them, it's important to double-check your command before you press enter.

## Ticket Management
### Approve
Used to signify acceptance of a bug report in the #Bug-Approval-Queue. Three approvals required for the report to be added to the Trello boards.  
`!approve <ticket #> | Can Reproduce - <system settings>`

### Deny
Used to signify rejection of a bug report in the #Bug-Approval-Queue. Three rejections are required for the report to be dismissed and moved to #Denied-Bugs.  
`!deny <ticket #> | <deny reason>`  

Please read [this article](approve-deny) for more information before denying any bug reports.

## Ticket Support
### Attach
Used to attach media, such as images and videos, to tickets in the #Bug-Approval-Queue or to existing approved bug reports. Not all media platforms work with attach, but sites like YouTube, Imgur or a direct image upload on Discord work.  
`!attach <ticket # or trello url> | <media url>`

### Note
Used to add a note to approved reports (does not work with #Bug-Approval-Queue). It's important to use this command sparingly, as it can easily clog up report tickets.  
`!note <trello url> | <note>`
