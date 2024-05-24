---
cover: ../../../.gitbook/assets/Cultivation (1).webp
coverY: 0
---

# 1.3-1.3.11 (Economy & Features)

**Major Updates:** **New Features & income source:**

* **Fishing System:** 🎣
  * _New fishing features added! Enjoy a minigame while fishing and sell your catch._
  * Use `/sellfish` to sell your fish.
  * To access a **catalog** of all the fish species you have caught, type in `/lfish catalog`.
  * On average, each fish costs **€0.4** per kg, and their weight can vary from 0 to 5 kg.
* **Bounties: ⚔**
  * _Feeling frustrated with unruly players? Take charge and set a bounty to uphold fairness._
  * `/bounty raise <player>` **sets a bounty** on a player. (_Only items_)
  * `/bounty list` Displays the list of active bounties.
  * `/bounty silentraise <player>` Raises the bounty for a player, hiding the benefactor's identity.
  * `/bounty reset <player>`removes a player's bounty.

**Changes:**&#x20;

* Repaired broken terrain in Sweden-region
* Smoothed out steep lakes in Finland & Sweden-region
* Added spawn locations on Dynmap [http://nordics.world:8123/](http://nordics.world:8123/)



**Minor Update**

* Increased view and simulation distance
* Added starter tools and Welcome message to new players.
* Added `/suicide` command.
* Fixed weird terrain, mostly in Norway Region



**Update**

* **Cultivation** **🌾**
  * _You can now make money from harvesting wheat!_
  * Use the command `/sell all` to sell all **Hay Bales** in your inventory
    * One stack of Hay Bale will give `€5.76` _(Price may fluctuate)_
  * `Right-click` on a fully-grown plant to harvest and replant it instantly.
  * _**The Sickle tool**_
    * _Craft a sickle to easily harvest larger parts of a field._
    * _Make sure you have `Server Resource Packs: Enabled`. Hit `Edit` in the server list._
  * **Grass Paths** will now increase your **speed.**
* **Changes:**
  * **Unlocks** all **recipes** for a player when they first join the server.
  * Lowered starting balance for new players from `€100` to `€60`
  * `/headdb` command changed to `/heads` for Golden Kala ![:Kultakala:](https://cdn.discordapp.com/emojis/976582854890893322.webp?size=40\&quality=lossless) rank
  * Decreased the **price of fish** by `17%`
  * Increased the drop-rate of rare items by fishing _(Noticeably XP-Bottles, rods, and bows)_
  *   **Double doors** will now automatically synchronize their sides, so both doors open and close simultaneously.

      <figure><img src="../../../.gitbook/assets/Cultivation.webp" alt=""><figcaption></figcaption></figure>

**Hotfix:**

* Bankruptcy now works as intended
  * Town will be **deleted** after `7 days` if their bank runs out of money.
  * If a town has reached their **debt cap** and is unable to pay the upkeep with debt it will be **deleted**
* Decreased the price of fish by `20%`
* All Christmas kits removed
* **Fishing Leaderboard** _(Player with the biggest catch will be displayed in the catalog)_

**New Rules:** _We recently discovered that client mods can cause crashes for players without any errors specified in the console. Therefore we would like to clarify our rules regarding the use of client mods_

* **Client mods**
  * Players are prohibited from using client mods that are known to cause server crashes or instability. Any client mods that have the potential to disrupt the server/player performance or cause crashes are strictly forbidden. Any concerns about specific mods should be brought to the attention of the server administrators for evaluation and approval before use.
* **Redstone rules**

> * Passive and Active redstone farms
>
> Active redstone machines are not allowed; however, passive machines are permitted with restrictions. They must not exceed 2 chunks in size, be stacked higher than 2 units, and should only be activated by observers, daylight sensors, or a player. Avoid constant activation of triggers, as it is considered active redstone.
>
> * Large scale redstone farms
>
> Each town allows only one large-scale farm (except for bamboo and kelp farms), limited to 5 by 5 chunks on a single layer. Redstone components must stay within 20% of the total farm area and operate solely on player-initiated power. Prohibited are redstone clocks, daylight sensors, and continuous triggers; instead, a button press initiates one cycle of operation.
>
> * Redstone machinery
>
> Non-farm-related redstone machines are welcome, provided they don't put undue strain on the server.



&#x20;**New Port and Host**  We are pleased to inform you that the server migration is now complete! You can join the server using the same IP, but make sure to add the port **:25612** to the IP address. The Dynmap will however take a day to complete its render. This new hosting change will significantly extend the lifespan of our server, as it has effectively reduced the monthly cost by half. This means we can continue to provide a stable and enjoyable Minecraft experience. See you in the game, and a big thank you for your support, with special appreciation to our patrons on: [https://www.patreon.com/nordics](https://www.patreon.com/nordics)



**Minor Update** Changes to Dynmap-Towny and Tab List:

* Tab list now features new info: ping, /rules, /einfo commands, Dynmap link, and Discord link, with a sleek new look and animations. Ranks will now show as a Prefix to the player names.
* Dynmap-Towny info-window now displays expanded details, including bank balances, upkeep, taxes, residents count, town quotes, mayor, and most importantly, town and nation flags.

**Hotfix**

* You can now enable default fishing through `/lfish catalog`
* Town upkeep reduced, from `0.3` to `0.2`
* Dynmap chat enabled, it will remember your IP so no register needed, but if it doesn't work use command `/dynmap webregister` ingame.
* `/dynmap URL` will return the user a link to the dynmap

**Minor Update**

New Features:

* **Structures** have been placed randomly across the map, including shipwrecks, mineshafts, and custom mineshafts

New Commands:

`/helpop <message>` - Message online admins.&#x20;

`/getpos` - Get current position/coordinates with a compass.&#x20;

`/afk` - Let others know you're AFK.

&#x20;`/seen` - Check the last online date or playtime of a player.&#x20;

`/time` - See the world time in chat.&#x20;

`/list` - View all online players and their ranks.

New Server Ranks Prefixes:

* Patreon supporter prefixes updated with finer colors: Blue for Kala/Supporter, Green for Fancy Kala, and Gold for Golden Kala.
* Staff prefixes added: Admin, Moderator, and Helper/Chat Mod in Blue color; Developer in Grey color; and Management/Head Admin in red color.

Additional Changes:

* Player Join/Leave text updated with simpler \[+] and \[-].

**Team Update:** We are introducing our newest developer, \[D] MigningSM, to the Operators team! With his extensive experience in Server administration we're confident that he will be valuable to the Nordics. In addition, has helped with the following update.

#### New Features:

* Now, you can connect to the server with a client version **older** or **newer** than the server version.
* **Gravestones**: your inventory will be stored in a gravestone, allowing you to reclaim your items. _The grave will decay after 2 minutes, which leaves your items vulnerable._

#### New Commands:

* //calc \[math] - Supporters :kala: In-Game calculator in chat
* /discord - Sends the user a clickable invite link to the Nordics discord.

#### Additional Changes:

* Increased simulation distance
* Use `/fish catalog` instead of /lfish catalog
* removed ping under the tablist

#### Nation Upkeep System and Taxes:

* **Nation per plot Upkeep** - Uses the total number of plots that a nation has across all of its towns to determine upkeep. `€0.1` per plot
* Nation capitals can now pay nation tax
* max town/nation tax changed from `25%` to `10%`
* Flat taxes now have a maximum cap
  * Plot tax - `€10`
  * Town tax - `€15`
  * Nation tax - `€30`

**Minor Update:**

* Changed Prismarine Crystals recipe: _Glowstone dust & Glow Ink Sack_
* Changed Prismarine Shard recipe: _Clay & Glow Ink Sack, will appear after next restart_
* Cleared chunks in Nether/End that have not been active for more than 2 minutes in total. _(Clear memory and lag)_
* Updated the appearance of the Dynmap
* Swapped Kala and Fancy Kala colors, Kala is now Green and Fancy Kala is now blue.\


**Features**

* Death Locations map after death.
* Animated Doors
* Chat [**Emoticons**](https://wiki.nordics.world/additional-guides-and-commands/others/chat-emoticons)
* Craftable Tipped Arrows in the\*\* Fletching Table\*\*

**Misc**

* New Rank Icons, _Staff & Supporters_
* **Town & Nation Upkeep**
* Nation, Town and Plots can now have **negative tax**, instead of taking money from the residents, negative tax will result in every resident being paid by the town bank.
* **Nation Levels:** As the population of a nation increases, the upkeep costs will decrease accordingly.
  * 10 residents: `10%`
  * 20 residents: `14%`
  * 30 residents: `16%`
  * 40 residents: `18%`
  * 60 residents: `20%`

