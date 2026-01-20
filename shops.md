# Player Shops

Keystone uses **ChestShop** for player-to-player trading. There's no NPC selling - all trade happens between real players.

## Why Player Shops?

- **Real economy** - Prices set by supply and demand
- **No exploits** - Can't dupe items and sell to NPCs
- **Community** - Interact with other players
- **Opportunity** - Buy low, sell high

## The Market

The Market is a dedicated area for player shops.

### Getting There
```
/warp market
```
Or walk through the **yellow (west) portal** at spawn.

### Market Features
- 6 shop stalls available
- Tutorial wall with instructions
- Protected area (no griefing)
- Chest access enabled for trading
- Return portal to spawn

## Creating a Shop

### What You Need
1. A chest
2. A sign
3. Items to sell
4. The right format

### Step-by-Step

**Step 1**: Place a chest
```
Put down a chest where you want your shop
```

**Step 2**: Place a sign on the chest
```
Put a sign on the front of the chest
```

**Step 3**: Write the sign in this format
```
Line 1: [Leave blank - your name auto-fills]
Line 2: Quantity
Line 3: B price : S price
Line 4: Item name (or ? for item in hand)
```

### Sign Format Explained

```
┌─────────────────┐
│    YourName     │  ← Auto-filled
│       64        │  ← Quantity per transaction
│   B 100 : S 50  │  ← Buy/Sell prices
│    DIAMOND      │  ← Item name
└─────────────────┘
```

**Line 1**: Leave blank. Your username appears automatically.

**Line 2**: How many items per transaction (e.g., `64` for a stack)

**Line 3**: Prices in $KEY
- `B 100` = Others BUY from you for 100 KEY
- `S 50` = Others SELL to you for 50 KEY
- Use `:` between them
- Can use just `B` or just `S` if one-way

**Line 4**: Item name
- Type the item name (e.g., `DIAMOND`)
- Or type `?` while holding the item

### Examples

**Selling Diamonds (64 for 1000 KEY)**:
```
[blank]
64
B 1000
DIAMOND
```

**Buying and Selling Iron**:
```
[blank]
32
B 50 : S 25
IRON_INGOT
```

**Selling Single Netherite Ingot**:
```
[blank]
1
B 5000
NETHERITE_INGOT
```

## Using Shops

### Buying from a Shop
1. Find a shop with `B` price
2. Left-click the sign
3. Items transfer, $KEY deducted

### Selling to a Shop
1. Find a shop with `S` price
2. Have items in inventory
3. Right-click the sign
4. Items transfer, $KEY received

## Item Names

Use official Minecraft item names. Common ones:

| Item | Shop Name |
|------|-----------|
| Diamond | `DIAMOND` |
| Iron Ingot | `IRON_INGOT` |
| Gold Ingot | `GOLD_INGOT` |
| Emerald | `EMERALD` |
| Coal | `COAL` |
| Netherite Ingot | `NETHERITE_INGOT` |
| Diamond Pickaxe | `DIAMOND_PICKAXE` |
| Oak Log | `OAK_LOG` |
| Wheat | `WHEAT` |

**Tip**: Use `?` on Line 4 while holding the item to auto-fill!

## Shop Management

### Restocking
Just open your chest and add more items.

### Collecting Money
Money goes directly to your balance. Check with `/bal`.

### Removing a Shop
Break the sign or chest.

### Checking Stock
Open your chest to see remaining items.

## Market Stalls

The Market has 6 pre-built stalls for rent/use.

### Stall Layout
```
     TUTORIAL WALL
          ↑
   ┌──┐  ┌──┐  ┌──┐
   │#1│  │#2│  │#3│   North Stalls
   └──┘  └──┘  └──┘

      [Pathway]

   ┌──┐  ┌──┐  ┌──┐
   │#4│  │#5│  │#6│   South Stalls
   └──┘  └──┘  └──┘
          ↓
    ENTRANCE/EXIT
```

### Using a Stall
1. Find an available stall
2. Use the pre-placed chest
3. Create your shop sign
4. Stock with items

### Stall Rules
- First come, first served
- Don't grief other stalls
- Keep it stocked or lose it
- One stall per player (for now)

## Shop Outside the Market

You can create shops anywhere you have build permission:

- Your claimed land in Survival
- Your faction territory in PVP
- Any area you own

Just place a chest + sign and you're set.

## Pricing Guide

Suggested prices (market varies):

| Item | Suggested Price (per 1) |
|------|------------------------|
| Diamond | 15-25 KEY |
| Iron Ingot | 1-2 KEY |
| Gold Ingot | 3-5 KEY |
| Emerald | 20-30 KEY |
| Netherite Ingot | 200-300 KEY |
| Coal | 0.5-1 KEY |
| Ancient Debris | 80-120 KEY |
| Enchanted Gear | Varies |

**Tip**: Check other shops to see going rates!

## Tips for Success

### As a Seller
1. **Price competitively** - Check other shops
2. **Stay stocked** - Empty shops lose customers
3. **Good location** - Market gets traffic
4. **Advertise** - Mention in chat occasionally
5. **Variety** - Sell what people need

### As a Buyer
1. **Shop around** - Prices vary
2. **Buy in bulk** - Often cheaper
3. **Check stock** - Don't assume availability
4. **Build relationships** - Regular sellers = deals

## Troubleshooting

**Shop sign says "Out of stock"**
- Restock your chest with items

**"Not enough money"**
- Check your balance with `/bal`
- Earn more through jobs

**Sign didn't create properly**
- Check the format carefully
- Make sure item name is correct
- Try using `?` for item name

**Can't create shop**
- Must have chest-access in that area
- Some areas may be protected

## FAQ

**Q: Is there a shop tax?**
A: No, all money goes directly to you.

**Q: Can I have multiple shops?**
A: Yes, as many as you want (where you can build).

**Q: Can shops be robbed?**
A: In protected areas, no. In PVP world, potentially.

**Q: What if someone undercuts my prices?**
A: That's the free market! Adjust or offer better service.
