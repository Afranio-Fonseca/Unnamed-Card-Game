[<- Home](../README.md)

## Trigger parameters
Triggers may contain parameters that may be part of the effect requirements or interacted by the effect;
- reach: Where the condition of the trigger must happen, if a [On Unit Death] trigger has a reach units dying outside of it won't trigger it.
- unit: The unit that is part of the trigger, if a [On Unit Summoned] trigger has a unit parameter cards that don't meet the unit parameters will not cause the card to trigger.
- land: The land that is part of the trigger, if a [On Land Placed] trigger has a land parameter cards that don't meet the land parameters will not cause the card to trigger.

## Possible triggers for trigger effects
#### Unit/Land triggers
- [Start of Turn]
- [Start of Main]
- [End of Turn]
- [Main]: During the Main Phase in a neutral state the player may use an action to activate this trigger effect.
- [On Play]
- [On Unit Summoned]{reach}{unit}: Happens after a unit is moved from a zone that is not a unit zone to a unit zone.
- [On Unit Death]{reach}{unit}: Happens after a unit is moved from a zone that is not the graveyard to the graveyard.
- [On Unit Attack]{reach}{unit}: Happens after the [When Attacking] of a unit is triggered.
- [On Land Placed]{reach}{land}: Happens after a land is moved from a zone that is not a land zone to a land zone.
- [On Land Destroyed]{reach}{land}: Happens after a land leaves a land zone.

#### Unit triggers
- [When Attacking]
- [Start of Combat]
- [On Combat Victory]
- [On Combat Loss]
- [End of Combat]
- [End of Attack]
- [On Death]: Happens after the unit is moved from a zone that is not the graveyard to the graveyard.
- [On Kill]

#### Land triggers
- [When Destroyed]: Happens after the land is moved from a land zone to a zone that is not a land zone.

#### Land triggers

[<- Home](../README.md)
