# VillagerCoins
Minecraft modpack to make villagers use coins instead of emeralds. 

### Installation 
This is a modpack, and so it can be installed like any other for a vanilla Minecraft experience with the addition of villagers using coins for trade.

If you already have a favorite modpack and wish to add villager coins to it, then perform the following three steps:
1. Add the [Villager Trade Tables](https://www.curseforge.com/minecraft/mc-mods/villager-trade-tables) mod to your modpack
2. Add the [Just Coins](https://www.curseforge.com/minecraft/mc-mods/just-coins) mod to your modpack
3. Unzip the [latest release](https://github.com/AngleWyrm10/VillagerCoins/releases) source code and put the contained config folder into your .minecraft/config folder

##### Known Incompatibilities
[Minecraft Comes Alive](https://github.com/AngleWyrm10/VillagerCoins/issues/1)


### Orientation
Ever notice how bizarre the villager prices are? There are trades that clearly will never be made by a player because they're awful. And there are trades that vastly outweigh everything else that could be purchased.

This modpack seeks to correct those anomalies by switching away from using clunky emeralds as currency, into something a bit more suitable to the Minecraft fantasy genre: Coins of copper, silver, and gold.

#### What is currency?
Money is a type of portable storage for value, in some ways similar to [Refined Storage](https://www.curseforge.com/minecraft/mc-mods/refined-storage), [Applied Energistics](https://www.curseforge.com/minecraft/mc-mods/applied-energistics-2), and [ProjectE](https://www.curseforge.com/minecraft/mc-mods/projecte). That value can be stored as money by trading things for money, and then drawn back out by trading money for things. It is a liquid asset that can take the shape of anything it can be traded for.

#### Stability & Inflation
If a copper coin can be traded for a rabbit, and a rabbit can be traded for a copper coin, then that copper coin holds the promise of a rabbit. This reversible trade gives the coin the property of holding the value of a rabbit for later trade.

But if the trade is lossy, like some of those coal guzzling generator mods that continue to burn fuel when there's no benefit, then we have what they call inflation and players will look elsewhere to store their valuables.  No one wants a leaky purse.

So for this modpack I've endeavored to maintain as much stability as possible. The method I've chosen for establishing the merit of trades is the Energy-Matter Currency (EMC) pricing system developed in the mod [ProjectE](https://www.curseforge.com/minecraft/mc-mods/projecte). That mod is neither required nor included in this modpack.

#### Coins of the Realm
For the coins, I've gone with the [Just Coins](https://www.curseforge.com/minecraft/mc-mods/just-coins) mod, which offers a suitable set of coins that can be interchanged with each other by crafting to the next higher/lower denomination. I've chosen a somewhat arbitrary target EMC value of 64 for the base copper coin, because it places the most common trades in the copper-silver range, with gold coins for expensive trades.


| Coin | EMC |
|------|-----|
| copper | 64 |
| silver | 512 |
| gold | 4,096 |
| sack of coins | 36,864| 
