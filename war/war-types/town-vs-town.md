# Town vs Town

#### Pros of Current Town vs Town War Settings

1. **Accessibility and Engagement**:
   * **Startup Delay (45 seconds)** and **min\_online\_each\_town (3)**: These values strike a good balance, ensuring there is sufficient time for players to prepare while also preventing one-sided engagements when not enough players are present. This ensures the war starts off on a fair footing.
2. **Cooldown and Win Conditions**:
   * The **cooldown of 2 days** between wars is a great way to avoid burnout. It gives towns some time to recover and regroup after a conflict, allowing players to refocus on building or other activities.
   * Having a **max time duration of 48 hours** for a town war ensures wars don’t last indefinitely, while still being long enough for strategic play and potential counterattacks.
3. **Occupational Control**:
   * Instead of dissolving towns after a loss, you've opted for **winner\_gains\_occupational\_control**. This adds depth to the outcome of a war without completely erasing a losing town, making the consequences significant but not overly harsh. This promotes more activity rather than discouraging players.
4. **Surrender Flexibility**:
   * **Surrender Allowed** with options for trading **towns and money** adds flexibility. This allows towns to negotiate terms, possibly ending a war in a way that both sides can agree upon. It can make the wars more about political maneuvering, which is engaging for players who enjoy diplomacy.
5. **Townblock Health Mechanics**:
   * **Townblock HP** allows for territory battles during a war, adding strategic depth. Players must choose which parts of their town to defend, making warfare about both positioning and tactical decision-making.

#### Cons and Considerations for Improvement

1. **Impact of Townblock Ownership and Switching**:
   * **townblocks\_switch\_towns: false** and **townblocks\_single\_use: false**: These settings mean that townblocks will not change ownership or be permanently fought over during a war. This could limit the strategic impact of focusing attacks on certain town areas. Allowing townblocks to **switch towns** could make wars more consequential, as each block would directly affect town boundaries and power.
2. **Winner Takes Over Town (false)**:
   * Currently, **winner\_takes\_over\_town** is disabled, meaning that losing a war doesn’t lead to complete assimilation of a town. This makes the consequences less severe, which could encourage more players to participate without fear of losing everything. However, this can also mean that winning a town war doesn't feel as rewarding as it could be. You could consider enabling this for high-stakes wars, though it would need careful handling to avoid discouraging players.
   * Since **winner\_gains\_occupational\_control** is enabled, the current setup is more forgiving and allows towns to rebuild, which aligns well with your general philosophy of avoiding harsh punishments.
3. **Resident and Mayor Lives**:
   * **Equal Lives for Residents and Mayor (6 each)**: Similar to the riot settings, the **mayor's lives** are the same as residents, which might reduce their significance. You could consider giving the mayor more lives (e.g., 8 or 10) to reflect their importance or set **mayor\_death to true** to create a critical win condition.
4. **Switch and Item Use**:
   * **switch\_use: true** and **item\_use: false**: Allowing **switch use** while disabling **item use** is a balanced approach. It lets players interact with tactical elements like doors and levers while preventing chest looting or tampering with other containers. This retains strategic options without introducing full-scale looting.
5. **No Score-Based End Condition**:
   * With **max\_score.enabled: false**, there’s no clear way for a war to end via point accumulation. While having wars end based on territorial control is strategic, adding a **max score as an alternate win condition** (perhaps enabled for quicker wars) could give towns more ways to claim victory, catering to a variety of play styles.
6. **Neutral Towns in Wars**:
   * **does\_neutrality\_prevent\_town\_war: true**: This setting means that neutral towns are exempt from being challenged, which aligns well with a non-aggressive playstyle. However, this might create a scenario where towns simply set themselves as neutral to avoid conflict, potentially reducing opportunities for wars. Consider adding a cost or limit for maintaining neutrality to add some balance.
7.
