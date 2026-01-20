# Factions & PVP

The PVP World features full **Factions** gameplay. Claim land, build bases, raid enemies, and dominate.

## What Are Factions?

Factions are player-created groups that can:
- Claim and protect land
- Build bases together
- Declare enemies and allies
- Raid other factions
- Compete for power

## Accessing the PVP World

```
/warp pvp
```
Or walk through the **red (south) portal** at spawn.

⚠️ **WARNING**: Full PVP is enabled. You WILL lose items on death.

## Getting Started with Factions

### Creating a Faction

```
/f create <name>
```

Example:
```
/f create Legends
```

**Cost**: 500 $KEY

### Joining a Faction

If invited:
```
/f join <faction>
```

To see open factions:
```
/f list
```

## Faction Commands

### Basic Commands

| Command | Description |
|---------|-------------|
| `/f create <name>` | Create a new faction (500 KEY) |
| `/f join <faction>` | Join a faction |
| `/f leave` | Leave your faction |
| `/f disband` | Disband your faction (leader only) |
| `/f info [faction]` | View faction information |
| `/f list` | List all factions |
| `/f map` | View territory map |
| `/f help` | Full command list |

### Territory Commands

| Command | Description |
|---------|-------------|
| `/f claim` | Claim the chunk you're in |
| `/f unclaim` | Unclaim the chunk |
| `/f autoclaim` | Auto-claim as you walk |
| `/f claimlist` | List your claims |
| `/f sethome` | Set faction home |
| `/f home` | Teleport to faction home |

### Member Commands

| Command | Description |
|---------|-------------|
| `/f invite <player>` | Invite a player |
| `/f kick <player>` | Kick a member |
| `/f promote <player>` | Promote member |
| `/f demote <player>` | Demote member |
| `/f title <player> <title>` | Set member title |
| `/f owner` | Set chunk owner |

### Diplomacy Commands

| Command | Description |
|---------|-------------|
| `/f enemy <faction>` | Declare enemy |
| `/f ally <faction>` | Request alliance |
| `/f truce <faction>` | Request truce |
| `/f neutral <faction>` | Go neutral |

### Chat Commands

| Command | Description |
|---------|-------------|
| `/f chat f` | Faction-only chat |
| `/f chat a` | Alliance chat |
| `/f chat p` | Public chat |

## Power System

Power determines how much land you can claim.

### How Power Works

- Each player has **power** (0-20)
- Faction power = sum of all members' power
- **1 power = 1 chunk** you can claim
- Power regenerates over time
- Power is lost on death

### Power Stats

| Stat | Value |
|------|-------|
| Starting Power | 10 |
| Maximum Power | 20 |
| Power per Death | -5 |
| Power Regen | 0.25/minute |

### Example

A 5-player faction where everyone has 20 power:
- Total power: 100
- Can claim: 100 chunks

If 2 players die:
- Power drops by 10 (5 × 2)
- Some claims may become vulnerable

## Claiming Land

### How to Claim

1. Stand in the chunk you want
2. Type `/f claim`
3. 50 $KEY is deducted
4. Chunk is now yours

### Claim Costs

| Type | Cost |
|------|------|
| Wilderness claim | 50 KEY |
| Additional multiplier | +30% per claim |
| Claiming from enemy | 1.5x cost |

### What Claims Protect

- Block breaking/placing by enemies
- Chest access (unless raidable)
- Build griefing

### What Claims DON'T Protect

- PVP (you can still be killed)
- TNT if faction is raidable
- Enderpearling in

## Raiding

### When Can You Raid?

A faction becomes **raidable** when:
```
Faction Power < Number of Claims
```

Example:
- Faction has 50 claims
- Power drops to 40 (deaths)
- Faction is raidable!
- Enemies can break/access blocks

### How to Raid

1. Check enemy power: `/f info <faction>`
2. Kill enemy members to lower power
3. When raidable, their claims are vulnerable
4. Break in and take loot
5. Claim their land if desired

### Raid Defense

- Keep power high (don't die!)
- Don't overclaim
- Build smart defenses
- Have members online
- Use multiple vaults

## Base Building

### Base Tips

1. **Hidden location** - Don't build near spawn
2. **Underground** - Harder to find
3. **Multiple vaults** - Spread valuables
4. **Buffer claims** - Extra land around base
5. **Water walls** - Slow raiders
6. **Obsidian** - Takes time to break

### What to Store

- Keep valuables in ender chests (safe)
- Spread items across multiple chests
- Don't keep everything in one place
- Log off with best gear

## PVP Tips

### Gear Recommendations

**Minimum**:
- Iron armor
- Iron sword
- Shield
- Food
- Ender pearls

**Recommended**:
- Diamond armor (Protection IV)
- Diamond sword (Sharpness V)
- Bow with arrows
- Golden apples
- Ender pearls
- Potions

### Combat Tips

1. **Strafe** - Don't stand still
2. **Crit hit** - Jump and hit on way down
3. **Shield** - Block axes and arrows
4. **Pearls** - Escape or chase
5. **Totems** - Second chance
6. **Terrain** - Use environment

## Faction Ranks

| Rank | Permissions |
|------|-------------|
| **Leader (★★★)** | Everything |
| **Co-Leader (★★)** | Most management |
| **Moderator (★)** | Invite, kick recruits |
| **Member (+)** | Basic access |
| **Recruit (-)** | Limited access |

### Promoting Members

```
/f promote <player>
```

Promotes one rank at a time.

## Alliances & Enemies

### Allies
- Can't damage each other
- Can access each other's land
- Shared chat channel
- Coordinate attacks

### Enemies
- Marked red on map
- Priority targets
- War declarations

### Truce
- Temporary peace
- No attacking
- Neutral standing

## Economy in Factions

### Costs

| Action | $KEY Cost |
|--------|-----------|
| Create faction | 500 |
| Claim chunk | 50+ |
| Set home | 50 |

### Earning in PVP World

- **Raider job**: 10 KEY per player kill
- **Hunter job**: Kill mobs
- **Loot**: Take from raids

## Tips for New Factions

1. **Start small** - Don't overclaim
2. **Recruit carefully** - Insiders can betray
3. **Stay hidden** - Build far from spawn
4. **Grind gear** - Before major fights
5. **Make allies** - Strength in numbers
6. **Be patient** - Don't rush into war

## FAQ

**Q: Can I play solo?**
A: Yes, but you're vulnerable. Solo factions are possible but challenging.

**Q: What happens if my faction disbands?**
A: All claims are released. Grab your stuff first.

**Q: Can I have multiple factions?**
A: No, one faction per player.

**Q: Is teaming allowed?**
A: Yes, that's what allies are for.

**Q: Can I betray my faction?**
A: Technically possible but may result in bans if extreme.
