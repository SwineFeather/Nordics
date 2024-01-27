# Bounties

A **bounty** is a reward given for killing someone. Nations uses a custom plugin that allows players to set cash bounties awarded for killing a certain player or destroying one of their Movecraft vehicles.

&#x20;

### Setting Bounties <a href="#setting-bounties" id="setting-bounties"></a>

Before creating a bounty, you need to decide on the following:

* **Who** to set the bounty on (the **target**)
  * _The target cannot be a friendly player._
* **How much** the bounty should pay out (the **reward**)
  * _The minimum bounty is $1,000._
  * _5% of the bounty reward is taken as tax._
* **Who** is allowed to collect the bounty reward (the **availability level**). This can be:
  * a specific player (`player`)
  * residents of a specific town (`town`)
  * residents of a specific nation (`nation`)
  * residents of a specific nation and all of its allies (`nation_and_allies`)
  * _For exploit prevention reasons, you cannot create bounties available to everyone._
* The bounty **type**
  * `pvp` - the bounty is awarded if the target is killed
  * `movecraft` - the bounty is awarded if a Movecraft vehicle controlled by the target is sunk
* Whether the bounty is **public** or **private**
  * If a bounty is public, everybody can see it.
  * If a bounty is private, only its creator and the people it is available to can see it.

&#x20;

Once you have decided, type:

`/bounty place <target name> <reward> <availability level> <the name of the player, town or nation>`

A menu will then open prompting you to finish setting up the bounty.&#x20;

&#x20;

#### Deleting Bounties <a href="#deleting-bounties" id="deleting-bounties"></a>

You can delete a bounty using `/bounty delete <name of target>`. The reward money, after being taxed, will be refunded to you.&#x20;

&#x20;

#### Raising Bounties <a href="#raising-bounties" id="raising-bounties"></a>

You can increase the reward of your bounties using `/bounty raise <name of target> <amount to raise reward by>`.

&#x20;

#### Bounty Expiry <a href="#bounty-expiry" id="bounty-expiry"></a>

Bounties expire naturally if either the bounty creator or target do not login for 90 days. They also expire if they are only available to a specific town or nation which is then deleted. Expired bounties return their reward money to their creator.

&#x20;

### Viewing Bounties <a href="#viewing-bounties" id="viewing-bounties"></a>

Bounties can be seen through the `/bounty list` GUI.

Bounties in the GUI will be coloured according to their relation with you:&#x20;

* **Blue** bounties are bounties that you have placed
* **Green** bounties are bounties available to you
* **Red** bounties are bounties placed on you!
* Bounties represented by a **barrier block** are not available to you

&#x20;

#### Total Bounty Value <a href="#total-bounty-value" id="total-bounty-value"></a>

You can see the total value of the bounties placed on someone using `/bounty total <player name>`.

&#x20;

&#x20;

### Collecting Bounties <a href="#collecting-bounties" id="collecting-bounties"></a>

<figure><img src="https://wiki.ccnetmc.com/nations/bounties/bounty_trophy.png" alt=""><figcaption><p>A bounty trophy. Note that you cannot actually collect your own bounties. This is just for illustrative purposes.</p></figcaption></figure>

You can collect any bounty that is **available** to you (`/bounty list available_to_me`).

* **PvP bounties** are collected by simply killing the target while they are not inside a [siege zone](https://wiki.ccnetmc.com/Nations/WarSieging).
* **Movecraft bounties** are collected by sinking a craft piloted by the target. You need to land the killing shot for it to count.

As well as receiving the bounty reward money, a **Bounty Trophy** — a special player head —will also drop for you. The Trophy has the target's skin and lists the details of the bounty.

&#x20;

&#x20;

&#x20;

### Target Tracking <a href="#target-tracking" id="target-tracking"></a>

You can **track** players who have more than **$10,000 in bounties** available to you. Tracking displays your approximate distance from a target.&#x20;

1\. To begin tracking, you need to craft a **Bounty Tracking Compass**. Like a normal compass, the Bounty Tracking Compass can be used to hide from the map.

* _Note: The echo shards required to craft the recovery compass can drop from wardens._&#x20;

<figure><img src="https://wiki.ccnetmc.com/nations/bounties/bounty_tracking_compass.png" alt=""><figcaption><p>1x Recovery Compass, 4x Copper Ingot, 4x Redstone</p></figcaption></figure>

2\. After crafting the compass, hold it in your hand and type `/bounty track <target>`.

* _The Bounty Tracking Compass is reusable. You can use this command again to change the target._

3\. Your compass will now track the target. Right-click the compass to see the target's distance and direction relative to your position. This has a cooldown of **one minute**.&#x20;

* The distance is rounded to the nearest 500 blocks.
* When successfully right-clicked, the compass will also points towards the target.
  * But be aware the compass direction will reset if you log out or die.&#x20;

&#x20;
