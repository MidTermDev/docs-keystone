# The $KEY Economy

$KEY is the currency of Keystone. It's not just server money - it's a real cryptocurrency on Solana.

## Understanding $KEY

### What is $KEY?

$KEY is a Solana SPL token. When you earn $KEY on the server, you're earning real cryptocurrency that you can:

- Hold in your server balance
- Withdraw to a Solana wallet
- Trade on decentralized exchanges
- Send to other players

### Why Does $KEY Have Value?

1. **Limited supply** - We don't print infinite tokens
2. **Earning caps** - Players can only earn so much per hour
3. **Real utility** - Used for trading, factions, and more
4. **Demand** - Players want $KEY to progress

## Earning $KEY

### Jobs (Primary Method)

Jobs are the main way to earn $KEY. See the [Jobs Guide](jobs.md) for full details.

| Job | Typical Earnings |
|-----|------------------|
| Miner | 500-2000 KEY/hour |
| Hunter | 500-1500 KEY/hour |
| Farmer | 300-1000 KEY/hour |
| Raider | Varies (PVP kills) |

### Hourly Limits

To keep the economy healthy, there are earning limits:

| Player Level | Max KEY/Hour |
|--------------|--------------|
| New player | 2,000 KEY |
| Level 100 | 3,000 KEY |
| Level 300 (maxed) | 5,000 KEY |

When you hit your limit, you'll get a notification. Wait for the next hour or do something else.

### Trading

Buy low, sell high. Use the [Market](shops.md) to trade items with other players.

## Checking Your Balance

```
/balance
```

or

```
/bal
```

Shows your current $KEY balance.

## Paying Other Players

Send $KEY to another player:

```
/pay <player> <amount>
```

Example:
```
/pay Steve 100
```

Sends 100 $KEY to Steve.

## Withdrawing $KEY

This is how you get your $KEY out of the game and into your Solana wallet.

### Step 1: Link Your Wallet

First, connect your Solana wallet address:

```
/linkwallet <your-solana-address>
```

Example:
```
/linkwallet 7xKXtg2CW87d97TXJSDpbD5jBkheTqA83TZRuJosgAsU
```

**Important**:
- Use YOUR wallet address
- Double-check for typos
- We recommend Phantom or Solflare wallet

### Step 2: Withdraw

Once linked, withdraw anytime:

```
/withdraw <amount>
```

Example:
```
/withdraw 1000
```

Sends 1000 $KEY to your linked wallet.

### Withdrawal Notes

- **Minimum**: 100 KEY
- **Fee**: Small network fee deducted
- **Time**: Usually instant, up to a few minutes
- **Verify**: Check your wallet to confirm receipt

## Depositing $KEY

Want to bring $KEY back into the game?

```
/deposit <amount>
```

This pulls $KEY from your linked wallet back into your game balance.

**Requirements**:
- Wallet must be linked
- Must have sufficient $KEY in wallet
- Small network fee applies

## Economy Protection

We have safeguards to prevent exploits and maintain value:

### Anti-Exploit Measures

| Protection | Description |
|------------|-------------|
| Hourly caps | Max earnings per hour |
| No /sell | Can't sell items to NPCs |
| Spawner disabled | No AFK mob farm payments |
| Balance cap | 1 million KEY max per player |
| Anti-cheat | Vulcan monitors for cheats |

### Why No /sell Command?

We disabled selling items to NPCs because:
1. Prevents dupe exploits from draining treasury
2. Encourages player-to-player trading
3. Keeps item values market-driven

Use the [Market](shops.md) to trade items instead.

## Economy Tips

1. **Diversify jobs** - Different activities, steady income
2. **Check market prices** - Don't undersell rare items
3. **Save for factions** - Claiming land costs KEY
4. **Withdraw regularly** - Don't keep everything in-game
5. **Trade smart** - Player economy has opportunities

## Token Information

| Property | Value |
|----------|-------|
| Name | KEY |
| Blockchain | Solana |
| Type | SPL Token |
| Decimals | 9 |
| Contract | [View on Explorer](#) |

## FAQ

**Q: Is $KEY real money?**
A: $KEY is a real cryptocurrency. Its value fluctuates based on supply and demand.

**Q: Can I buy $KEY?**
A: You can trade for $KEY on Solana DEXes, but you can't buy advantages in-game.

**Q: What if I lose my wallet?**
A: We can't recover lost wallets. Keep your seed phrase safe.

**Q: Are there taxes?**
A: Server doesn't tax. Consult a tax professional for your jurisdiction.
