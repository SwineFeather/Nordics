# Elaboration

The **Occupational Control** settings introduce an interesting concept, allowing for a middle ground between complete annexation (conquering) and simply winning a battle without lasting consequences. Here are my thoughts on the pros and cons of using **Occupational Control** with a focus on **replace\_mayor\_or\_king** and **alter\_residents** options.

#### Pros of Occupational Control:

1. **Dynamic Gameplay Without Permanent Loss**:
   * Instead of outright conquering or merging, **Occupational Control** keeps the defeated nation or town intact. This provides a meaningful outcome to the conflict without completely erasing what the defeated players have built, making wars less of a zero-sum game.
2. **Strategic Importance**:
   * The ability to **replace the mayor or king** introduces an interesting power dynamic. It adds an element of humiliation and domination, giving conquerors real authority over the defeated territory, without permanently disbanding the community.
   * It can also lead to interesting political situations where the new leadership may be resented or undermined by residents, adding intrigue and fostering alliances or rebellion opportunities.
3. **Community Building and Rebellion**:
   * Occupied towns and nations can try to regain their freedom after the control period ends. This encourages collaboration and alliances between players to plan a successful rebellion or to free themselves, adding a layer of depth and potential for future gameplay.
4. **Less Harsh Consequences for the Defeated**:
   * By keeping their nation or town intact, defeated players may feel less discouraged. They have an incentive to continue playing and rebuilding, rather than starting over from scratch. This can lead to better player retention and a more enjoyable experience for the community.

#### Cons of Occupational Control:

1. **Frustration Over Limited Control**:
   * Allowing the winning king or mayor to **alter residents** can be a major pain point for the losing side. If their community is being tampered with—especially if residents are kicked out or new residents are forced in—it could lead to frustration and resentment, potentially driving players away.
2. **Potential for Abuse**:
   * Replacing the **mayor or king** could lead to leadership changes that players in the defeated town or nation may feel are unfair, especially if the new leader behaves poorly or does not represent the interests of the residents. It may also result in issues if the winning side installs someone without community approval, causing internal disputes.
3. **Temporary Inconvenience**:
   * During the **control\_time\_duration**, the losing town or nation effectively becomes less autonomous, which could be demotivating. This might lead to inactivity during the occupation period if players feel they don’t have much control or meaningful actions to take.

#### Balanced Approach Recommendation

If you want to add a sense of consequence without completely dismantling the defeated town or nation, **Occupational Control** can be a great feature. However, I’d recommend some tweaks to make it less frustrating for the losing side:

1. **Replace Leadership but Not Residents**:
   * Keep **replace\_mayor\_or\_king** as `'true'` to allow some control by the conquerors, but consider setting **alter\_residents** to `'false'` to avoid the potential abuse of removing or adding residents without the consent of the occupied community. This way, the conquerors can still assert their influence, but they don’t completely undermine the existing community dynamics.
2. **Limit Control Period**:
   * Keeping the **control\_time\_duration** relatively short (like 1 day, as you currently have) is ideal. It gives the conquerors a window to make changes, but it ensures that the defeated community doesn’t feel under someone else's rule for an extended period.
3. **Involve Diplomacy**:
   * If possible, you could introduce a diplomatic element during the control period, where the occupied nation or town has some options to negotiate terms or even end the occupation sooner through certain actions. This can add a layer of choice for both conquerors and the defeated.
