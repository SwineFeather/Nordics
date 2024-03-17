---
description: /plot menu
---

# Create, sell, and rent out plots

If you run a town, it is common to want to allow the town's members to buy and settle on plots. This page explains how to create plots and how to let the town's members use them.

A town consists of several land blocks, where the size of each land block is always 16×16 blocks. When a land block is claimed, it is owned by the town, but it does not become a plot immediately. The land that belongs to the town, but is not a plot, can only be built on and demolished by the town's assistants and mayor.

/plot new plot-name It is possible to change the name of a plot afterwards with the command /plot set name.

Sell a plot For a player to be able to settle on the plot, the player typically needs to become the owner of it. As an assistant, vice mayor, or mayor, you can determine who should own a plot with the command /plot set owner. However, this does not force the owner to pay for the plot, so if you want payment, it is better to put it on the market.&#x20;

This is done with the command:

/plot market price and allows members of the town to buy the plot by standing on it and typing /plot buy. If, at a later stage, you want to withdraw a plot from the market so that it can no longer be bought, you use this command:

/plot market - If a player buys a plot that is not owned by anyone, the money will go to the town. However, if a plot is already owned by a player when it is for sale, the money will go to that player if the plot is bought.

Rent out with leasehold An alternative to selling a plot, where you only get paid once, is to rent it out with leasehold. This means that the owner pays a so-called leasehold fee, a rent, to use the plot. The leasehold fees are paid weekly, at midnight between Sunday and Monday, just before the taxes are drawn. To determine the leasehold fee for a plot, use the command...\
`/plot set rent`&#x20;
