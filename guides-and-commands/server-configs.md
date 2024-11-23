# Server Configs

## Server Hardware

The server restarts daily at 4 am Swedish time.&#x20;

An automatic backup is made every 12 hours.

## Towny

### **Upkeep & Titles Guide**

This guide provides an overview of how **town and nation upkeep** changes based on the number of residents and how titles and bonuses are applied as your town or nation grows. It also explains how to include **color codes** for titles and surnames.

***

#### **Town Upkeep and Growth**

As your town grows in population, its upkeep, title, and available plots will change. Here's a breakdown of how upkeep modifiers and other factors shift as your town increases in size:

<table data-header-hidden><thead><tr><th></th><th width="82"></th><th></th><th></th><th width="70"></th><th></th><th></th><th></th></tr></thead><tbody><tr><td><strong>Town Level</strong></td><td><strong>Residents</strong></td><td><strong>Upkeep Modifier</strong></td><td><strong>Town Block Limit</strong></td><td><strong>Outposts</strong></td><td><strong>Peaceful Cost Multiplier</strong></td><td><strong>Mayor Title</strong></td><td><strong>Town Name</strong></td></tr><tr><td><strong>Ruins</strong></td><td>0</td><td>1.0</td><td>1</td><td>1</td><td>1.0</td><td>Spirit</td><td><em>Name</em> Ruins</td></tr><tr><td><strong>Settlement</strong></td><td>1</td><td>1.0</td><td>16</td><td>1</td><td>1.0</td><td>Hermit</td><td><em>Name</em> (Settlement)</td></tr><tr><td><strong>Hamlet</strong></td><td>2</td><td>1.0</td><td>32</td><td>1</td><td>1.0</td><td>Chief</td><td><em>Name</em> (Hamlet)</td></tr><tr><td><strong>Village</strong></td><td>6</td><td>0.95</td><td>96</td><td>2</td><td>1.05</td><td>Baron Von</td><td><em>Name</em> (Village)</td></tr><tr><td><strong>Town</strong></td><td>10</td><td>0.92</td><td>160</td><td>2</td><td>1.08</td><td>Viscount</td><td><em>Name</em> (Town)</td></tr><tr><td><strong>Large Town</strong></td><td>14</td><td>0.90</td><td>224</td><td>2</td><td>1.12</td><td>Count Von</td><td><em>Name</em> (Large Town)</td></tr><tr><td><strong>City</strong></td><td>20</td><td>0.87</td><td>320</td><td>3</td><td>1.15</td><td>Earl</td><td><em>Name</em> (City)</td></tr><tr><td><strong>Large City</strong></td><td>24</td><td>0.85</td><td>384</td><td>4</td><td>1.18</td><td>Duke</td><td><em>Name</em> (Large City)</td></tr><tr><td><strong>Metropolis</strong></td><td>28</td><td>0.80</td><td>448</td><td>4</td><td>1.25</td><td>Lord</td><td><em>Name</em> (Metropolis)</td></tr></tbody></table>

**Key Points:**

* **Upkeep Modifier**: The larger your town, the lower the upkeep modifier, meaning towns with more residents pay less upkeep proportionally.
* **Town Block Limit**: This increases as your town grows, allowing for more plots to be claimed.
* **Outpost Limit**: More residents unlock additional outposts.
* **Peaceful Cost Multiplier**: The cost for peaceful towns increases slightly with growth.

***

#### **Nation Growth and Titles**

Nations also grow with resident numbers, offering **bonuses**, **titles**, and **upkeep discounts**. Here’s how nations progress based on population:

| Nation Level         | Residents | Bonus Plots | Nation Zones | Upkeep Modifier | Title Prefix | Title  | Peaceful Cost Multiplier | Bonus Outpost Limit | Capital Bonus Outpost Limit | Discount (%) |
| -------------------- | --------- | ----------- | ------------ | --------------- | ------------ | ------ | ------------------------ | ------------------- | --------------------------- | ------------ |
| Land of _Name_       | 0         | 10          | 1            | 1.0             | Leader       | Nation | 1.0                      | 0                   | 0                           | 0%           |
| Federation of _Name_ | 10        | 20          | 2            | 0.9             | Count        | Nation | 1.0                      | 1                   | 1                           | 10%          |
| Dominion of _Name_   | 20        | 40          | 3            | 0.86            | Duke         | Nation | 1.1                      | 2                   | 2                           | 14%          |
| Kingdom of _Name_    | 30        | 60          | 4            | 0.84            | King         | Nation | 1.15                     | 3                   | 2                           | 16%          |
| The _Name_ Empire    | 40        | 100         | 5            | 0.82            | Emperor      | Empire | 1.2                      | 4                   | 3                           | 18%          |
| The _Name_ Realm     | 60        | 140         | 6            | 0.80            | God Emperor  | Realm  | 1.3                      | 5                   | 3                           | 20%          |

**Key Points:**

* As nations grow, they gain **bonus plots** and an **upkeep discount which is both for the towns and the nation**.
* **Title Prefixes** change with the nation’s size, from **Count** for smaller nations to **God Emperor** for the largest.
* Nations with 60+ residents will benefit from the highest discount (20%).

## CombatLog

dShould players be prevented from flying during combat?

## Default: true

prevent-flying: true

## If a players flight is deactivated by CombatLogX, should the plugin prevent them from taking fall damage?

## The fall damage prevention only works once after flight is disabled.

## Default: true

prevent-fall-damage: true



