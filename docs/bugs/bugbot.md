# Bug Bot
Bug Bot (Bug-Bot#1660) is the Official bot that powers the Discord Testers program. It links between the Server and Trello, powers reporting, approving and denying as well as attachments. Honestly, without Bug Bot, Discord wouldn't be half as good as it is now.  Not all commands are included here, as some are Administrator only commands.
P.S. Bug Bot's open-source! Check her out @ [SamEm/Bug-Bot](https://github.com/SamEm/Bug-Bot)!

## User Commands

Command | Description
---------- | ----------
!submit | Submit a bug for Bug Hunter review - [Dabbit's Report Generator](https://dabbit.typeform.com/to/mnlaDU). Post in the respective channel.
!edit | Edit a submitted bug in the Bug Approval Queue. Check #bot-help for the section names
!storeinfo | Stores system and client information for ease of !canRepro and !cannotRepro. Check #bot-help for the flag codes
!canRepro and !cannotRepro | Indicate your reproduction status on an approved ticket

## Bug Hunter Commands

Command | Description
---------- | ----------
!approve | Approve a ticket in the Bug Approval Queue
!deny | Deny a ticket in the Bug Approval Queue
!revoke | Revoke an approval or deny of a ticket - You can reuse !approve or !deny to override existing stance
!attach | Attach media to a file
!addnote and !note | Add a note to an approved Bug Report
