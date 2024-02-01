# 📃 Moderator Commands

### Variables
- Some commands contain an optional option to only show it for the person using the command.
- NAME - Replace this with the user.
- REASON - Replace this with the actual reason.
- CHOICE - Replace with choices.
- TITLE - Replace this with a title.
- DESCRIPTION - Replace this with a description, new lines can be added using **\n** in the description, like "Hello\nHows you".
- DATE - Using DD/MM/YYYY format, Day, Month, Year.
- TIME - Using HH:MM format, Hour, Minute.

## Commands
- **/ban NAME REASON** -> Bans a user from the server.
    - Requires the user to have BanMembers permission.
    - Defaulted to only show the command user the message.
- **/kick NAME X** -> Kick a user from the server.
    - Requires the user to have KickMembers permission.
    - Defaulted to only show the command user the message.
- **/timeout NAME X** -> Timeout a user.
    - Requires the user to have MuteMembers permission.
    - Defaulted to only show the command user the message.
- **/purge X** -> Deletes X amount of messages.
    - Requires the user to have ManageMessages permission.
    - Defaulted to only show the command user the message.
- **/poll CHOICE** -> Create a poll with up to 10 vote options.
    - Requires the user to have CreateEvents permission.
- **/signup TITLE DESCRIPTION DATE TIME** -> Creates a signup poll for events, movie nights, etc.. you decide.
- **/guild** -> Shows information about the server it's used in.
    - Requires the user to have ManageMessages permission.
- **/user** -> Shows information about the user.
    - Requires the user to have ManageMessages permission.
    - This command is very different than the Profile command.