---
title: iRacing Reports Discord Bot - Switching to Version 3
---

# Switching to Version 3

Thanks for your continued support of my iRacing Reports Discord Bot project.

Over the past months I’ve been working away on a total re-write of the iRacing Reports Discord Bot, I’m declaring that this is version 3! The key change is that users now interact with the bot using slash commands, rather than the current !<command> style commands. You can read [about this new version here](https://discordbot.iracingreports.com/version3) and I have a [demo video](https://youtu.be/5YbMBCv1fVc) that you can check out to see how the new slash commands work.

I have switched the bot over to the new v3 version system, you may have noticed that the commands aren't working in your server. 

To get the bot working again, I need to have you complete the following 5 steps:

1. Connect your Patreon account with iRacing Reports
2. Connect your Discord account with iRacing Reports
3. Kick the iRacing Reports bot from your server
4. Use the new bot invite link to grant permission to "Create commands in a server"
5. Check that you've granted the correct permissions to the Bot's role

With these steps completed, your driver list and any other configured options will have been maintained.

If you have any problems please don't hesitate to direct message me on Discord: Rob Crouch#9161

To begin the process, please open the following URL in a new tab:

## [https://iracingreports.com/accounts/login](https://iracingreports.com/accounts/login)

## 1) Connect your Patreon

For the iRacing Reports systems to know that you're a supporter and what tier you're on, you'll need to use a system called OAuth to connect your Patreon account with the iRacing Reports website. For more information about OAuth, you can read this excellent explanation on the Patreon support site: [https://www.patreon.com/portal/start/oauth-explained](https://www.patreon.com/portal/start/oauth-explained)

Click the **CONNECT WITH PATREON** button:

![1-connect-patreon](https://user-images.githubusercontent.com/658935/171343965-7e969b08-43d6-42c1-acb2-e9b4ebd3a0f4.png)

You'll enter the email address associated with your Patreon account and your password. Note, this information is sent to Patreon not us! You'll see that the URL is a patreon.com address.

![2-patreon-login](https://user-images.githubusercontent.com/658935/171344016-b9ce5312-8468-4e09-a74c-6a300e29d27d.png)

You'll be informed of the information that will be shared with us, click the **Allow** button.

![3-patreon-info](https://user-images.githubusercontent.com/658935/171344050-6e70bd2b-1733-4a9f-8c2e-abf2be4c31ef.png)

With this completed, you'll be returned to the iRacing Reports website and you should see the details of your Patreon account, along with what tier you're subscribed on and your payment status.


## 2) Connect your Discord

To link up your Patreon account with your Discord account, you'll have to do a similar process with Discord.

Click the **CONNECT WITH DISCORD** button:

![4-connect-discord](https://user-images.githubusercontent.com/658935/171344566-bbf9519a-df36-429e-abda-f5adb6c4f7ce.png)

You can either login using the email address associated with Discord and your password, or use the [QR Code Login](https://support.discord.com/hc/en-us/articles/360039213771-QR-Code-Login-FAQ) feature.

![6-discord-login](https://user-images.githubusercontent.com/658935/171344115-5cdfd007-285f-446f-95fa-7cb17b00c14b.png)

You'll be informed of the information that will be shared with us, click the **Authorize** button.

![7-discord-info](https://user-images.githubusercontent.com/658935/171344128-84cecc63-fa59-4e50-81f2-8e3a16b6efe8.png)

With this completed, you'll be returned to the iRacing Reports website and you should now also see the details of your Discord account.

## 3) Kick the iRacing Reports bot

Right click on the `iRacing Reports` bot in a channel of your server, and hit the `Kick iRacing Reports` option from the menu.

![8-kick-bot](https://user-images.githubusercontent.com/658935/173489397-005b30be-761c-4bb1-b5b3-8680c445df53.png)

## 4) Invite the bot back in

You'll need to do this to set up the correct permissions and have the bot create the new slash commands.

**[Click this new invite link](https://discord.com/api/oauth2/authorize?client_id=663521697860943936&permissions=309237762112&scope=applications.commands%20bot)**.

![9-invite-bot](https://user-images.githubusercontent.com/658935/171344148-e537d881-1e63-4e97-952e-09b28bb53faa.png)

Select the server you want to invite the bot into, and click the **Continue** button.

![10-select-server](https://user-images.githubusercontent.com/658935/171344164-38406048-2293-45e4-bd5c-cbb7a596fbb3.png)

**Note** If you've configured 2 factor authentication on your server, you'll need to enter an auth code from your authentication app.

You'll be shown a list of the permissions that will be granted to the bot. Click the **Authorize** button.

![11-bot-perms](https://user-images.githubusercontent.com/658935/171344180-d1da031d-74f8-4467-9500-0e94843ef186.png)

With this completed, the bot will appear in your server!

Thanks!


## 5)

The permissions that the bot's role will require in channels where you want it to be able to respond to commands are:

* View Channel
* Send Messages
* Send Messages in Threads
* Create Public Threads
* Embed Links
* Attach Files
* Add Reactions
* Read Message History

Note: be sure that you've granted the `@everyone` role permission to `Use Application Commands` either in the entire server or in the channel(s) where you want the bot to be used.

![11-app-commands-perms](https://user-images.githubusercontent.com/658935/173550106-85c5555f-b01f-42aa-88c5-e8503dc65635.png)
