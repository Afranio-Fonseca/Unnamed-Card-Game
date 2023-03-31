## Timings on the player's turn

- [Start of turn]: Before the Draw Phase
- [Start of main]: Before any player action in the Main Phase
- [End of turn]: After the player ends its Main Phase

# Action Steps
If at the end of any step a change occured in the game state that triggers an effect: that trigger happens and all resulting effects must be resolved at that time before going to the next step.

## Unit play steps

1. Cost is paid if any then Unit is moved to an empty unit zone of the player's choice and Continuous effects are applied to the played unit before The played unit's continuous effects that meet their requirements if any are applied;
2. Effects triggered from changes in game state from previous steps are resolved including [On Play] and [On Summon] effects of the unit played;
3. Return to neutral game state

## Unit summon steps

1. Cost is paid if any then Unit is moved to an empty unit zone that the effect indicates as valid and Continuous effects are applied to the played unit before The summoned unit's continuous effects that meet their requirements if any are applied;
2. Effects triggered from changes in game state from previous steps are resolved including [On Summon] effects of the unit summoned;
3. Return to neutral game state

## Field play steps

1. Cost is paid if any then land card is moved to an empty land zone of the player's choice continuous effects are applied to the played land before the played land's continuous effects that meet their requirements if any are applied;
2. Effects triggered from changes in game state from previous steps are resolved including [On Play] effects of the land played;
3. Return to neutral game state

## Tech play steps

1. Tech card is revealed and its effect is resolved;
2. Tech card is sent to the trash zone;

## Unit attack steps

1. [Rest] 2 is applied to the attacking unit and its [When Attacking]is triggered;;
2. Combat steps or protection removal steps happen;
3. [End of Attack] from attacking unit is triggered if it is still in a unit zone;
4. Return to neutral game state

## Combat steps

1. [Start of Combat] from both units are triggered;
2. If both units in combat are at 0 effective power at this moment jump to combat step 7;
3. Combat winners and losers are determined by both units' effective power at this moment(tied powers makes both units losers);
4. Turn player's unit in combat's [Combat Victory] or [Combat Loss] is triggered if it won or lost respectively;
5. Opponent of turn player's unit in combat's [Combat Victory] or [Combat Loss] is triggered if it won or lost respectively;
6. Loser unit(s) are moved to the graveyard and if they do the [On Kill] from winner unit in unit zone is triggered at the same time as the loser unit's [On Death];
7. [End of Combat] from units still in a unit zone are triggered;

## Protection removal steps
1. If there's no card in defending player's protection zone the game ends with the attacking player as the winner;
2. Card from top of protection zone of defending player is moved to his hand;
3. [On Protection Hit] from attacking unit is triggered;
