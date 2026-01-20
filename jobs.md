# Jobs System

Jobs are the primary way to earn $KEY on Keystone. Pick a job, do activities, get paid.

## How Jobs Work

1. **Join a job** - Pick from 7 available jobs
2. **Do activities** - Mine, kill mobs, farm, etc.
3. **Get paid** - $KEY deposited automatically
4. **Level up** - Higher levels = slightly better pay

## Job Commands

| Command | Description |
|---------|-------------|
| `/jobs browse` | Open job selection GUI |
| `/jobs join <job>` | Join a specific job |
| `/jobs leave <job>` | Leave a job |
| `/jobs info <job>` | See job details and pay rates |
| `/jobs stats` | View your job levels and progress |
| `/jobs top <job>` | See top players in a job |

## Job Limits

- **Maximum jobs**: 3 at once
- **Switching**: Can leave and join anytime
- **Level loss**: Leaving a job loses 30% of levels

## Available Jobs

### ⛏️ Miner

**Description**: Earn $KEY by mining ores and stone.

**Best World**: Resource World

**Activities & Pay**:

| Block | $KEY |
|-------|------|
| Stone | 0.005 |
| Deepslate | 0.008 |
| Coal Ore | 0.10 |
| Iron Ore | 0.20 |
| Copper Ore | 0.10 |
| Gold Ore | 0.50 |
| Redstone Ore | 0.15 |
| Lapis Ore | 0.30 |
| Diamond Ore | 3.00 |
| Emerald Ore | 4.00 |
| Ancient Debris | 20.00 |

**Tips**:
- Deep mining (Y -59 to -64) for diamonds
- Nether for ancient debris
- Resource world has fresh ores

---

### 🏹 Hunter

**Description**: Earn $KEY by killing mobs.

**Best World**: Any (Resource, Survival caves, PVP)

**Activities & Pay**:

| Mob | $KEY |
|-----|------|
| Chicken | 0.01 |
| Pig/Cow/Sheep | 0.02 |
| Zombie | 0.10 |
| Skeleton | 0.12 |
| Spider | 0.08 |
| Creeper | 0.20 |
| Enderman | 0.50 |
| Blaze | 0.50 |
| Wither Skeleton | 0.80 |
| Witch | 0.50 |
| Piglin Brute | 1.00 |
| Elder Guardian | 10.00 |
| Warden | 50.00 |
| Wither | 100.00 |
| Ender Dragon | 200.00 |

**Tips**:
- Nether fortresses for blazes and wither skeletons
- End for endermen grinding
- Boss kills pay big

**Note**: Spawner farms do NOT pay (anti-exploit)

---

### 🌾 Farmer

**Description**: Earn $KEY by harvesting crops.

**Best World**: Survival World

**Activities & Pay**:

| Crop | $KEY |
|------|------|
| Wheat | 0.02 |
| Carrots | 0.02 |
| Potatoes | 0.02 |
| Beetroot | 0.025 |
| Melon | 0.01 |
| Pumpkin | 0.03 |
| Sugar Cane | 0.01 |
| Bamboo | 0.005 |
| Cactus | 0.01 |
| Cocoa | 0.03 |
| Nether Wart | 0.05 |
| Sweet Berries | 0.02 |

**Tips**:
- Large farms = steady income
- Nether wart pays best
- Combine with other jobs for variety

**Note**: Auto-farms work but pay is intentionally low

---

### 🪓 Woodcutter

**Description**: Earn $KEY by chopping trees.

**Best World**: Survival or Resource

**Activities & Pay**:

| Log Type | $KEY |
|----------|------|
| Oak Log | 0.02 |
| Spruce Log | 0.02 |
| Birch Log | 0.02 |
| Jungle Log | 0.025 |
| Acacia Log | 0.02 |
| Dark Oak Log | 0.025 |
| Mangrove Log | 0.03 |
| Cherry Log | 0.03 |
| Crimson Stem | 0.04 |
| Warped Stem | 0.04 |

**Tips**:
- Use VeinMiner to chop faster
- Jungle and dark oak give more logs
- Replant for sustainability

---

### 🎣 Fisherman

**Description**: Earn $KEY by fishing.

**Best World**: Survival

**Activities & Pay**:

| Catch | $KEY |
|-------|------|
| Raw Cod | 0.10 |
| Raw Salmon | 0.15 |
| Tropical Fish | 0.20 |
| Pufferfish | 0.25 |
| Treasure Items | Bonus |

**Tips**:
- AFK fishing works but is slow
- Luck of the Sea enchant helps
- Peaceful activity while chatting

---

### 🏗️ Builder

**Description**: Earn $KEY by placing blocks.

**Best World**: Survival

**Activities & Pay**:

| Block Type | $KEY |
|------------|------|
| Common blocks | 0.01 |
| Crafted blocks | 0.02-0.05 |
| Rare blocks | 0.05-0.10 |

**Note**: Builder pays less than other jobs to prevent exploit loops (place/break).

**Tips**:
- Good secondary job
- Combines well with other jobs
- Building bases earns passive income

---

### ⚔️ Raider

**Description**: Earn $KEY by PVP kills.

**Best World**: PVP World (Factions)

**Activities & Pay**:

| Action | $KEY |
|--------|------|
| Player Kill | 10.00 |

**Restrictions**:
- Only works in PVP-enabled areas
- Cooldown between same-player kills
- Anti-boosting measures in place

**Tips**:
- High risk, high reward
- Gear up before PVPing
- Group up with faction members

---

## Leveling Up

As you work a job, you gain experience and level up.

### Level Benefits
- **Slightly higher pay** - 0.5% more per level
- **Prestige** - Show off your dedication
- **Leaderboards** - Compete for top spots

### Max Level
- All jobs cap at **level 100**
- Max bonus at level 100: +50% pay

### Experience Formula
Higher levels require more XP:
```
XP needed = 100 * (1.13 ^ (level - 1))
```

## Hourly Limits

To prevent exploitation, there are hourly earning caps:

| Total Job Levels | Max $KEY/Hour |
|------------------|---------------|
| 0 | 2,000 |
| 100 | 3,000 |
| 200 | 4,000 |
| 300 (max) | 5,000 |

When you hit the limit, you'll be notified. The limit resets every hour.

## Job Strategy

### For New Players
1. Start with **Miner** - easy and consistent
2. Add **Hunter** - variety while mining
3. Consider **Farmer** for passive income

### For Grinders
1. **Miner** + **Hunter** + **Raider**
2. Mine in resource world
3. Kill mobs you encounter
4. PVP when you want action

### For Builders
1. **Builder** + **Woodcutter** + **Farmer**
2. Gather materials
3. Build and earn
4. Farm for extra income

### For PVP Players
1. **Raider** + **Hunter** + **Miner**
2. PVP for main income
3. Hunt mobs between fights
4. Mine for gear materials

## FAQ

**Q: Can I change jobs?**
A: Yes, anytime. But you lose 30% of levels when leaving.

**Q: Do jobs stack?**
A: Yes! Mining while having both Miner and Hunter means you earn from ores AND any mobs you kill.

**Q: Why am I not getting paid?**
A: Check if you:
- Have the job (`/jobs stats`)
- Haven't hit hourly limit
- Aren't near a spawner (no pay)
- Are in a valid world

**Q: What's the best job?**
A: Depends on playstyle. Miner is most consistent. Hunter is fun. Raider is high risk/reward.
