---
description: /plot menu
---

# Plot Management

If you run a town, it is common to want to allow the town's members to buy and settle on plots. This page explains how to create plots and how to let the town's members use them.

A town consists of several land blocks, where the size of each land block is always 16×16 blocks. When a land block is claimed, it is owned by the town, but it does not become a plot immediately. The land that belongs to the town, but is not a plot, can only be built on and demolished by the town's assistants and mayor.

### Sell Plot

For a player to be able to settle on the plot, the player typically needs to become the owner of it. As an assistant, vice mayor, or mayor, you can determine who should own a plot with the command /plot set owner. However, this does not force the owner to pay for the plot, so if you want payment, it is better to put it on the market.&#x20;

To put a plot for sale, type `/plot forsale <price of the plot>` while standing inside it. By default, the plot price will be set 0. Residents can then buy the plot by typing /plot claim. If the plot has a price, the amount paid will go to the town bank.

You can change the default price for newly set-for-sale plots with `/town set plotprice <price>`

### Plot Permissions

The owner of a plot can control who can access it by typing /plot set perm \<group> \<permission> \[on/off] while standing inside it.

Groups are:

* friend - players on your friend list. You can edit your friend list with /res friend.
* resident - players from your town.
* ally - players from your town, nation and allied nations.
* outsider - players not from your town, nation or an allied nation.

Permissions are:

* build - controls whether a group can build in your plot
* destroy - controls whether a group can break blocks in your plot
* switch - controls whether a group can use chests, hoppers, furnaces, doors, dispensers, etc.
* itemuse - controls whether a group can place/destroy minecarts, use buckets and bone meal, etc.

For example, /plot set perm build ally on would allow players from your town, nation and allied nations to build in the plot you are standing in.

If you want to control permissions for _all_ your owned plots, use /resident set perm \<group> \<permission> \[on/off]

Mayors can control permissions for all unowned plots with /town set perm \<group> \<permission> \[on/off].

### Plot Types

Plots can be of different types, which have unique functions. You can change a plot's type by typing /plot set \<plot type> while standing in it.

* default - the default plot type. All plots are default when first claimed. Non-default plots can be made default again with /plot set reset.
* shop - designates a player shop area. The plot will appear red on the map.
* arena - arena plots have PvP and friendly fire enabled at all times.
* embassy - if for sale, embassy plots can be bought by any player, even if they're not a resident of the town.
* bank - designates a bank, which allows you to deposit and withdraw from your town and nation banks.
* jail - designates a jail, where players will be sent to if imprisoned - see the section on ranks.
* farm - designates a farm, where the only blocks that can be placed and destroyed are crops.
* wilds - designates a semi-protected wilderness plot, where trees, flowers, mushrooms etc can be broken but all other blocks cannot.
