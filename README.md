# SinbadCogs
[![Code style: black](https://github.com/mikeshardmind/SinbadCogs/workflows/black/badge.svg)](https://github.com/ambv/black) 
[![Type Checked with mypy](https://github.com/mikeshardmind/SinbadCogs/workflows/mypy/badge.svg)](https://github.com/python/mypy) 
[![Red](https://img.shields.io/badge/Red-DiscordBot-red.svg)](https://github.com/Cog-Creators/Red-DiscordBot/tree/V3/develop) 


## Availability of Support

Support will be limited while the repo is getting setup, but for general bug reports/feedback feel free to contact me on discord Crossedfall#1001

## Whats here?

Various addons for Red Discordbot. Most of these are focused around utility purposes.


### AntiMentionSpam

This cog provides automated actions against people spamming mentions.

Configuration is available via the `antimentionspam` command.


### BanSync

This cog provides a few functions for handling bans across multiple servers.

More help is available via `help BanSync`


### EmbedMaker

This cog provides a means to create, store, and send embedded messages from the bot.

Full documentation is still pending,
but a robust example is available
[here](https://gist.github.com/mikeshardmind/0e15779370d7761a8608ce94936721ed) for now

### GuildJoinRestrict

Allows controlling and logging which guilds the bot can join based on configurable settings
and either an allowlist or blocklist

### QuoteTools

Provides a quick way to reference other messages without needing to jump to them to view.

### Relays

Mirror messages sent in a channel to other channels.

### RoleManagement

Provides:

 - Reaction roles
 - Self roles
 - Purchasable roles
 - User list data based on roles
 - Mass Role modifications
 
Note: Roles self assigned via reaction or command are subject to
the settings configured in the `roleset` command. 

### RoomTools

Provides two seperate ways to allow users to create temporary channels.

For command based temporary voice channels, see the `tempchannelset` command

For temporary channels generated automatically, see the `autoroomset` command


### RSS

Periodic RSS updates to channels.

For more information, use `help RSS`


### Scheduler

Allows scheduling commands. 

For more information, use `help Scheduler`


## What about the other cogs not listed here?

Use at your own risk, they are disabled, hidden, undocumented,
or intended to be replaced by newer alternatives.

They aren't designed to actively cause harm, but I'm not advertising them.

## License
All changes after [commit cf59da1ffdc449d550525fd06fc0ce1a3d341f5a on 2020/08/20 5:08 PM CDT](https://github.com/Crossedfall/SinbadCogs/commit/cf59da1ffdc449d550525fd06fc0ce1a3d341f5a) are licensed under [GNU AGPL v3](https://www.gnu.org/licenses/agpl-3.0.html).

All code before [commit cf59da1ffdc449d550525fd06fc0ce1a3d341f5a on 2020/08/20 5:08 PM CDT](https://github.com/Crossedfall/SinbadCogs/commit/cf59da1ffdc449d550525fd06fc0ce1a3d341f5a) is licensed under [MIT](https://github.com/Crossedfall/SinbadCogs/blob/v3/MIT)

See LICENSE and MIT-LICENSE for more details
