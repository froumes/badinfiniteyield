# badinfiniteyield

A powerful command-line script for Roblox with 400+ commands and extensive developer tools.

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/froumes/badinfiniteyield/refs/heads/master/source"))()
```

## Features

- **400+ Commands** - Comprehensive command set for Roblox exploitation
- **Developer Tools** - 30+ specialized commands for reverse engineering and exploit development
- **Modern UI** - Clean, developer-focused interface
- **Auto-Load on Teleport** - Use `keepiy` to automatically load on server teleports
- **Plugin System** - Extensible plugin architecture
- **Anti-Cheat Protection** - Randomized asset IDs to avoid detection

## Quick Start

1. Copy the loadstring above
2. Paste it into your Roblox executor
3. Press your prefix key (default: `;`) to open the command bar
4. Type `help` to see all available commands

## New Features

### Developer Commands (30+ new commands)

**Search & Find:**
- `findguitext / fgt [text]` - Find GUI elements containing text
- `findremotes / fr` - Find all RemoteEvents and RemoteFunctions
- `findbindables / fb` - Find all BindableEvents and BindableFunctions
- `findscript / fs [name]` - Find scripts by name or content
- `findmodules / fm [name]` - Find ModuleScripts
- `findbyclass / fbc [class]` - Find all instances of a class
- `findbytag / fbt [tag]` - Find instances with CollectionService tags
- And many more...

**Inspection:**
- `getproperties / gp [object]` - Get all properties of an object
- `getchildren / gc [path]` - Get direct children
- `getdescendants / gd [path]` - Get all descendants
- `gethierarchy / gh [path]` - Get full object hierarchy
- `getremoteinfo / gri [name]` - Get remote connection info

**Information:**
- `workspaceinfo / wsi` - Workspace statistics and breakdown
- `getservices / gs` - List all Roblox services
- `getnetworkowner / gno [part]` - Network ownership info

### Utility Commands

- `productfaker / pfaker` - Fake developer product purchases
- `bsh` - Load BSH (LuaArmor loader)
- `umr` - Load Universal Movement Recorder
- `settings / set / config` - Open settings window
- `debug [on/off]` - Toggle debug mode

### Remote Spy

- `remotespy / rspy` - Opens Cobalt Remote Spy (new)
- `oldrspy` - Opens Simple Spy V3 (legacy)

## Key Commands

- `help` - Show all commands
- `cmds` - List all commands
- `keepiy` - Auto-load on teleport
- `settings` - Open settings
- `discord` - Get Discord invite link

## Discord

Join our Discord server for support and updates:
**https://discord.gg/Jcw7U2YeC3**

## Credits

Original Team + austin

## License

This project is open source and available for modification.

## Repository

**GitHub:** https://github.com/froumes/badinfiniteyield

## Changelog

See [CHANGELOG_PLAIN.txt](CHANGELOG_PLAIN.txt) for a complete list of changes and new commands.
