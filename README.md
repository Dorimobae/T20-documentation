# T20-documentation

## How to read this documentation

This documentation shows you how to use T20's botscript and walks you through different setups and commands to improve your server!

Do not literally type out <> [] | etc.

> Arguments - Arguments is the message put after calling the command. for example, "c.set modlog #modlog-channel", "modlog" is the first argument and "#modlog-channel" is the second argument

The prefix used in the documentation is "-", replace this with your server's prefix if you set a custom prefix.

# Table of content

* [Setting up the bot](#setting-up-the-bot)
* [Toggling commands](#Toggling-commands)
* [Toggling logging](#Toggling-logging)
* [Introduction to Botscript](#Introduction-to-botscript)
* [Botscript - Advanced usage](#Botscript---Advanced-usage)
* [Embed builder](#Embed-builder)
* [Auto moderation](#Auto-moderation)
* [Resetting data](#Resetting-date)
* [Upcoming commands and features](#Upcoming-commands-and-features)
* [Changelog](#Changelog)


# Setting up the bot

When you first add the bot to your server, you'll need to set it up and configure it to suit your server. 

The first step to setting up the bot is running the setup command, this command allows you to configure the server for the first time.

In order too start the setup, use "-set" to start channel configurations.

-set modlog | set the modlog channel, a modlog channel is a channel where all moderation actions are recorded and logged.
> Expected arguments: -set modlog <modlog channel> 

-set messagelog | set the message log channel, a message log is a channel which is used to record all message actions, such as record deleted messages, show edited messages etc.
> Expected arguments: -set messagelog <message log channel> 

-set serverlog | set the server log channel, a server log is a channel which is used to record and log all server actions, including created channels, deleted channels, created roles etc.
> Expected arguments: -set serverlog <serverlog channel>


-set memberlog | set the member log, a member log channel is a channel which records all member changes, including changed usernames, avatars, etc.
> Expected arguments: -set memberlog <member log channel>

-set joinlog | set the join/leave log, a join/leave log records user information on users who join the server, this can include account creation, trusted level etc.
> Expected arguments: -set joinlog <join/leave log channel>

-set voicelog | set the voice log, a voice log channel logs users who joined/left a voice channel. 
> Expected arguments: -set voicelog <voice log channel>

**Note-:** Using "-set" without any arguments gives you all available options to set for your server

# Toggling commands

# Toggling logging

# Introduction to botscript

# botscript - Advanced usage

# Embed builder

# Auto Moderation

# Resetting data

# Upcoming commands and features

# Changelog




