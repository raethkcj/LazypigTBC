# LazypigTBC

LazyPig is a WoW addon that originated in the vanilla (1.x) version of the game and features a series of small Quality of Life improvements such as loot automation, battleground automation, group invitations, chat filters, salvation removing and several other things.

This is a repository for the migration of Lazypig to the TBC (2.4.3) version of WoW, created by Flierr (Premonition) of the Feenix Archangel server.

Current state: Testing. The addon still spawns a number of errors (see issues) in some of the features. WoW TBC uses a different version of LUA, and has many changes in the WoW API. I recommend disabling the improved right click feature. Use the addon at your own risk.

========

## Installation and Usage

Download the latest release (see release tab) and extract it to your <code>Worldofwarcaft/Interface/Addons</code> directory. As with all addons, make sure the name of the addon folder matches the name of the `.toc` file. In this case, both should be `_LazyPig`. Enable the addon from the character pane. Open lazypigs interface settings with <b>/lp</b>

## Features

- Auto sell grey items and repair at vendors by holding down shift
- Auto roll selected option (Need/Greed/Pass) on green items when pressing Ctrl-Alt
- Auto roll selected option (Need/Greed/Pass) on Coins, Bijous, Mark of the Illidari, Fel Armaments, Arcane Tomes, Amani Hex Sticks
- Auto passing on Heart of Darkness
- Can mute world chat in dungeons, raids etc.
- Can Enter/Leave/Queue/Release Battlegrounds
- Can Auto accept invites from people
- Can Filter chat (testing needed)
- Can Automaticly remove salvation if you are a tank
- Auto accept summons
- Position loot window
- Several more things
