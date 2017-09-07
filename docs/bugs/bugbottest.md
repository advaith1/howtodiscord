# Bug Bot
Bug Bot (Bug-Bot#1660) is the Official bot that powers the Discord Testers program. It links between the Server and Trello, powers reporting, approving and denying as well as attachments. Honestly, without Bug Bot, Discord wouldn't be half as good as it is now.  Not all commands are included here, as some are Administrator only commands.  
P.S. Bug Bot's open-source! Check her out @ [SamEm/Bug-Bot](https://github.com/SamEm/Bug-Bot)!

## Using her - Users

Command | Description
--- | ----
!submit | Submit a bug for Bug Hunter review - [Dabbit's Report Generator](https://dabbit.typeform.com/to/mnlaDU). Post in the respective channel.
!edit | Edit a submitted bug in the Bug Approval Queue. Check #bot-help for the section names
!storeinfo | Stores system and client information for ease of !canRepro and !cannotRepro. Check #bot-help for the flag codes
!canRepro and !cannotRepro | Indicate your reproduction status on an approved ticket

## Using her - Bug Hunters

Command | Description
--- | ----
!approve | Approve a ticket in the Bug Approval Queue
!deny | Deny a ticket in the Bug Approval Queue
!revoke | Revoke an approval or deny of a ticket - You can reuse !approve or !deny to override existing stance
!attach | Attach media to a file
!addnote and !note | Add a note to an approved Bug Report


-----TESTING------

Command | Description
---|----
%^restart | Restarts the bot. **Bot Owners Only**
%^help | Shows a list of commands.
%^ping | Replies with "Pong!"
%^rate | Rate something /10.
%^invite | Shows a link to invite Chewbotcca to your server and a discord invite link to the help server.
%^namemc | Shows a link to search results for a response, or if there''s one result, will show detailed info.
%^stats | Shows basic stats for Chewbotcca.
%^rip | Makes someone or something rip. No spaces, letters and numbers only.
%^memedb | It's the meme database, What more do you need??
%^namecheap | Searches namecheap.com for a domain name. No spaces or special characters, just a normal domain search.
%^mcavatar | Shows a mcavatar for the specified user.
%^sinfo | Shows basic stats for the server.
%^uinfo | Shows basic stats for the user.
%^eval | Evaluate expressions in ruby. **Requires Bot Owner in config**
%^shoo | Kills the bot, no restart. See `%^restart`
%^connect | Makes the bot connect to your voice channel.
%^songs | Lists `%^play`able songs.
%^play | Plays a song from the database.
%^cat | Shows a random cat. meow.
%^catfact | Shows a catfact
%^info | Type in a command (NO PREFIX) and it will give info on the command.
%^trbmb | That really blanks my blank.
