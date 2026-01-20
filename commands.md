# Commands Reference

Complete list of commands available on Keystone.

## Essential Commands

| Command | Description |
|---------|-------------|
| `/spawn` | Teleport to spawn |
| `/home` | Teleport to your home |
| `/sethome [name]` | Set a home location |
| `/delhome <name>` | Delete a home |
| `/homes` | List your homes |
| `/back` | Return to last location |
| `/tpa <player>` | Request teleport to player |
| `/tpaccept` | Accept teleport request |
| `/tpdeny` | Deny teleport request |

## Economy Commands

| Command | Description |
|---------|-------------|
| `/balance` or `/bal` | Check your $KEY balance |
| `/pay <player> <amount>` | Send $KEY to a player |
| `/withdraw <amount>` | Withdraw $KEY to wallet |
| `/deposit <amount>` | Deposit $KEY from wallet |
| `/linkwallet <address>` | Link Solana wallet |
| `/baltop` | View richest players |

## Jobs Commands

| Command | Description |
|---------|-------------|
| `/jobs browse` | Open jobs GUI |
| `/jobs join <job>` | Join a job |
| `/jobs leave <job>` | Leave a job |
| `/jobs info <job>` | View job information |
| `/jobs stats` | View your job stats |
| `/jobs top <job>` | View job leaderboard |

## Factions Commands

| Command | Description |
|---------|-------------|
| `/f create <name>` | Create a faction |
| `/f join <faction>` | Join a faction |
| `/f leave` | Leave faction |
| `/f claim` | Claim chunk |
| `/f unclaim` | Unclaim chunk |
| `/f home` | Teleport to faction home |
| `/f sethome` | Set faction home |
| `/f invite <player>` | Invite player |
| `/f kick <player>` | Kick member |
| `/f map` | View territory map |
| `/f info [faction]` | View faction info |
| `/f chat <f/a/p>` | Switch chat mode |
| `/f help` | Full factions help |

## Warp Commands

| Command | Description |
|---------|-------------|
| `/warp <name>` | Teleport to warp |
| `/warp list` | List all warps |
| `/warp spawn` | Warp to spawn |
| `/warp survival` | Warp to survival world |
| `/warp resource` | Warp to resource world |
| `/warp pvp` | Warp to PVP world |
| `/warp market` | Warp to market |

## Chat Commands

| Command | Description |
|---------|-------------|
| `/msg <player> <message>` | Private message |
| `/r <message>` | Reply to last message |
| `/ignore <player>` | Ignore a player |
| `/unignore <player>` | Unignore a player |

## Utility Commands

| Command | Description |
|---------|-------------|
| `/kit starter` | Get starter kit |
| `/kits` | View available kits |
| `/time` | Check server time |
| `/list` | See online players |
| `/ping` | Check your latency |
| `/help` | General help |
| `/rules` | View server rules |

## Land Claim Commands (GriefPrevention)

| Command | Description |
|---------|-------------|
| `/claim` | Info about claims |
| `/abandonclaim` | Delete claim you're in |
| `/abandonallclaims` | Delete all claims |
| `/trust <player>` | Trust player in claim |
| `/untrust <player>` | Remove trust |
| `/trustlist` | List trusted players |
| `/containertrust <player>` | Trust for containers only |
| `/accesstrust <player>` | Trust for buttons/doors |
| `/permissiontrust <player>` | Let player trust others |
| `/trapped` | Escape if trapped in claim |

### Claim Tools
- **Golden Shovel** - Create/resize claims
- **Stick** - Check claim info

## Sorting Commands

| Command | Description |
|---------|-------------|
| `/sort` | Sort inventory |
| `/chestsort` | Toggle auto chest sorting |

## VeinMiner

Hold **sneak (shift)** while mining to use VeinMiner:
- Mines connected ore blocks
- Works with axes on trees
- Consumes durability per block

## Admin Commands

*For staff only*

| Command | Description |
|---------|-------------|
| `/gamemode <mode>` | Change gamemode |
| `/tp <player>` | Teleport to player |
| `/tphere <player>` | Teleport player to you |
| `/kick <player>` | Kick player |
| `/ban <player>` | Ban player |
| `/mute <player>` | Mute player |
| `/vanish` | Go invisible |

## Command Shortcuts

| Shortcut | Full Command |
|----------|--------------|
| `/bal` | `/balance` |
| `/f` | `/factions` |
| `/msg` | `/message` |
| `/r` | `/reply` |
| `/h` | `/home` |
| `/j` | `/jobs` |

## Permission-Locked Commands

Some commands require ranks:

| Rank | Additional Commands |
|------|---------------------|
| Default | Basic commands |
| Member | `/withdraw`, 3 homes |
| VIP | 5 homes, colored chat |
| Admin | All commands |

## Tips

1. Use **Tab** to autocomplete commands
2. Most commands have help: `/command help`
3. Case doesn't matter: `/SPAWN` = `/spawn`
4. Player names autocomplete with Tab

## Getting Help

If a command doesn't work:
1. Check spelling
2. Check you have permission
3. Try `/help <command>`
4. Ask in chat or Discord
