# Matrix-EmailBot
A simple bot int GOlang to receive emails in matrix


## Information
Only one room and emailaddress are supported currently
<br>
<code>Note: This bot is currently in development so very unstable and buggy</code>
<br>

## Install
Just run <code>go build</code> inside of the folder and execute the created binary. Then you have to adjust the config file to make it work with your matrix server.
Invite your bot and set the "roomID" in the config file to the roomID of your new room. The bot joins automatically 
if everyting is set up correctly and you have to restarted the bot again, your emails will be sent into the room you've set as roomID.

<br>

## Features
- [X]  Receiving Email with IMAPs
- [X]  Use custom IMAPs Server and port
- [ ]  Use the bot with multiple email addresses
- [ ]  Use the bot for multiple user
- [ ]  Use custom mailbox instead of INBOX
- [ ]  Send email
- [ ]  Use commands to move/delete emails