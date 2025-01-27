# Elaboration

#### Pros of the Riot War Settings:

1. **Player-Driven Conflict**:
   * Allowing riots gives power to residents within towns to challenge leadership, adding depth and making internal politics more dynamic and unpredictable.
2. **Restrictions for Riot Declarations**:
   * **Minimum Membership Time (14d)**: This prevents new residents from causing chaos right away, which is crucial for preventing players from joining towns solely to disrupt them.
   * **Minimum Online Players (4)**: Setting a threshold for online members helps prevent riots from occurring when few people are around, ensuring that riots happen when there's enough activity to make them meaningful.
   * **Cooldown (1d)**: The cooldown between wars gives towns a breather, which is important for balancing player experiences and avoiding burnout.
3. **Win Conditions and Limits**:
   * **Max Time Duration (5h)**: Limiting riots to a maximum duration helps prevent wars from dragging on too long, keeping the experience engaging and fast-paced.
   * **Max Score (50)** and **Resident/Mayor Lives (6)**: These rules help structure the riot by adding win conditions and consequences for deaths, creating a goal-oriented event without making it endless.
4. **Flexibility for Neutral Towns**:
   * **does\_neutrality\_prevent\_riot (false)**: Allowing neutral towns to experience riots makes sense from a gameplay perspective, as neutrality shouldn’t necessarily prevent internal conflicts.
5. **Surrender and Spoils**:
   * **Surrender Allowed**: This gives towns an option to give up if they see no path to victory, reducing frustration.
   * **Base Spoils (10.0)**: Having a starting war spoil provides an incentive for players to participate, though it’s not overly lucrative.

#### Cons and Potential Improvements:

1. **Resident Lives and Mayoral Death**:
   * **Equal Lives for Mayor and Residents**: Giving the **mayor and residents both 6 lives** may reduce the importance of the mayor. It could be beneficial to either give the mayor more lives to make them harder to eliminate or to set **mayor\_death to true** as an alternate win condition. This would make protecting the mayor an important strategic element.
   * **mayor\_death (false)**: If the mayor’s death doesn’t end the riot, there might be less emphasis on leadership dynamics. Allowing the mayor’s elimination to end the riot could make the mayor’s survival a critical focus of the riot, increasing the stakes.
2. **Winner Takes Over Town (false)**:
   * Currently, the **winner does not take over the town**, which means that a riot has limited impact on actual town control. If you want riots to be impactful and lead to real changes, setting **winner\_takes\_over\_town to true** could make riots more significant. It would give rioters a tangible outcome for their efforts, which could also deter pointless riots if there’s a lot at stake.
3. **Participation and Complexity**:
   * The **min\_online\_in\_town (4)** might be a bit high for smaller towns. You could consider making it scalable based on town size—like requiring a percentage of the town to be online, which would make it fairer across small and large towns.
   * **Token Cost (20)** for riot declaration may be seen as a bit too much for newer towns or players without a well-established economy. Depending on the average resources players have, you might consider adjusting this to make rioting more accessible if it aligns with your gameplay goals.
4. **Limited Actions in Warzone**:
   * **switch\_use (false)** and **item\_use (false)** in warzones limit players' ability to interact with the environment during riots. Allowing some degree of **switch use** could add more strategic options, like opening doors or activating levers, making the riots more immersive. It’s worth considering if allowing limited interactivity might make riots more engaging without leading to major issues.

#### Suggestions for Fine-Tuning:

* **Increase the Consequences of Riots**:
  * You could make the **winner\_takes\_over\_town** setting `'true'` for added stakes, meaning successful riots lead to tangible changes in power. This could create more motivation for residents to rebel only when they’re serious, preventing frivolous riots.
* **Adjust Mayor and Resident Lives**:
  * Make the **mayor\_lives** a bit higher—maybe **8 lives** instead of 6—to emphasize their importance. Alternatively, consider **mayor\_death as a win condition**.
* **Increase Interactive Gameplay**:
  * Enabling **switch\_use** during riots could enhance tactical depth, allowing rioters and defenders to make use of redstone devices or other switches. This would keep the focus on combat while adding some puzzle-like challenges in strategic areas.
