# Elaboration

## Pros of Allowing Timed Griefing (Item Use Only):

1. **Reward for Conquerors**: Allowing **Item Use** (without full-scale griefing) can provide the winning nation with some incentive for their effort, giving them a tangible reward like loot or rare items.
2. **Economic Impact**: Raiding conquered towns can affect the economy of the server, possibly increasing the value of well-hidden or secured items and creating an interesting market dynamic.
3. **Balanced Consequences**: By only allowing **Item Use**, players get the thrill of raiding without having the entire town demolished. This could create more strategic planning around how and where towns store their valuables.
4. **Limited Time Window**: Since this is a timed action, the risk of raiding is temporary. It gives defenders hope to recover after the time window ends, reducing the impact compared to unlimited griefing.

## Cons of Allowing Timed Griefing (Item Use Only):

1. **Player Frustration**: Losing valuable items to raiders can still be frustrating for players, even if their buildings aren't destroyed. This could negatively affect the morale of the players in the conquered towns.
2. **Risk of Excessive Losses**: Players may feel that even item raiding results in losses that are hard to recover from, especially if they are storing rare or sentimental items.
3. **Hidden Items Meta**: Players may adapt by hiding items, making raids less rewarding over time. This could make the raiding feature less meaningful if conquerors can't find anything worthwhile.

### Balanced Approach Suggestion

Instead of full griefing, enabling **Item Use** and **Switch** (for opening containers) might be a good compromise:

* **Item Use** will allow raiding, but no physical destruction.
* **Switch** access allows conquerors to open chests, doors, and other interactable blocks, increasing the strategic depth of defending towns.
* Limit this raiding period to a short time (like 10-15 minutes), so the conquering nation has to act quickly, adding some pressure and risk.

### Recommended Configuration

Based on your concerns and objectives, I suggest enabling **timed\_griefing** with the following configuration:

* Set `enabled: true` (with limited time).
* Set `time_period: 10-15m`.
* Set `allowed_action_types: ITEMUSE,SWITCH`.
* Keep **building and destroying** disabled to preserve town structures.

This way, players can raid for items without destroying the environment, which maintains a fair balance between rewarding conquerors and protecting the hard work of builders.



Enabling explosions that revert after 60 seconds while protecting **chests** and **redstone components** can be an effective way to add some dynamic excitement to the conquest without causing permanent damage or disrupting valuable mechanisms. Here’s a deeper look into the pros and cons of this approach:

## Pros of Allowing Explosions with Reversion:

1. **Spectacle and Atmosphere**: Explosions create a dramatic effect during a raid, adding tension and excitement to the conquest without the lasting consequences of traditional griefing.
2. **Strategic Considerations**: The defenders may need to strategically position certain items and areas to avoid potential explosive impacts, encouraging creative defensive planning. However, knowing the explosions revert means they won't be overly concerned about permanent structural damage.
3. **Temporary Chaos Without Lasting Harm**: The temporary nature of the explosions adds a chaotic element to the battle, making it feel more like a real conflict. However, with the reversion, the town’s infrastructure remains intact, preserving the hard work players have invested.

## Cons of Allowing Explosions with Reversion:

1. **Unpredictable Behavior**: Depending on the nature of the structures, even temporary explosions can cause unintended consequences—such as destroying signs, item frames, or temporarily disabling redstone systems—which can disrupt gameplay.
2. **Player Frustration**: Players might still be frustrated if explosions temporarily disable their automated systems or destroy decor, even if those changes are reversed after 60 seconds.
3. **Potential Lag**: If there are multiple towns being conquered at the same time, or if the towns are particularly large, the explosion and subsequent reversion process might cause server lag, which could negatively impact the gameplay experience for everyone involved.

### Balanced Approach Recommendation

Based on what you want to achieve—adding excitement without causing major frustration or long-term damage—here’s what I suggest:

1. **Enable Explosions with Reversion**:
   * Set `allowed_explosions: 'true'` and `do_explosions_revert: 'true'`.
   * This allows explosions to occur but ensures that damage isn’t permanent, keeping the visual impact and thrill of explosions without ruining structures.
2. **Define an Explosion Ignore List Carefully**:
   * Make sure **chests, redstone components, item frames, armor stands, and other valuable blocks** are added to the `war.warzone.explosions_ignore_list`.
   * This will ensure these key elements are protected during the temporary chaos.
3. **Test on a Smaller Scale**:
   * Before implementing server-wide, consider testing this on a smaller scale or with mock battles to see how players respond to it. If they enjoy the experience and you see minimal frustration, it would be safe to roll out across the server.
4. **Provide Communication to Players**:
   * Make sure players are informed ahead of time that explosions will revert and that certain valuable blocks are protected from being exploded. This transparency will help avoid confusion and frustration during conquest.

This setup should strike a balance between the thrilling visual effects of a raid and protecting the hard work and valuable elements of towns. The reversion mechanic provides temporary excitement without lasting consequences, keeping both conquerors and defenders engaged but not discouraged.
