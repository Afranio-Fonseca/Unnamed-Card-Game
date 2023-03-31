[<- Home](../README.md)

## Game Rules
The game is to be played by 2 players, each one will build a main consisting of 40 cards and a card pool consisting of 10 cards, there can't be more than 4 cards of the same id combined between both the deck and card pool.

The players take alternating turns until a player reaches a winning or losing condition, the player to take the first turn is decided by the players that wins a coin toss.

At the start of the game each player shuffles both their deck and card pool then reveal 3 cards of the pool and draw 6 cards to their hand then set 3 cards to their protection zone face down. After that the turn player may begin with the respective turn phases in order.

## Turn phases

#### Draw Phase
If the turn player has no card in their deck he loses the game otherwise he draws 1 card from his deck and gets to choose to put one of his cards to the bottom of the deck and add 1 revealed card in his card pool to his hand and reveal.

#### Main Phase
During the Main Phase the turn player can choose to do any of the following as much times as possible:
- Play a unit card to an empty unit zone;
- Play a tech card;
- Equip a equip card to a unit;
- Play a land card to an empty land zone;
- [Rest] 2 a unit to Attack with that unit;
- [Rest] 2 a unit to move that unit to an empty unit zone that is adjacent to its current zone;
- Trigger a [Main] effect from a unit or land card in a respective zone.

When the player chooses to not do any action in his main phase the turn is passed to the other player

## Zones

Each player has an identical set of zones belonging to that player, the following zones describes the set of zones that each individual player has:

#### Hand zone

Cards in this zone can only have its identity seen by the owner of this zone.

#### Deck zone

The entire deck of the respective player is placed here before the start of the game with all cards face down, when the player draws he takes the top card of his deck and places it in their hand zone.

#### Pool zone

The entire card pool of the respective player is placed here before the start of the game with all cards face down, when revealing a card from the pool the top card of the pool is flipped face up and is considered revealed.

#### Protection zone

When a lane of the player is attacked with no defending units one card in the protection zone is moved to the owner's hand or if there are no cards in the protection zone the defending player loses the game.

#### Graveyard zone

Units that die by any means are sent to this zone.

#### Trash zone

Discarded cards and used tech cards are sent to this zone.

#### Lanes(Unit & Land zones)

Each lane in the game has the following set of zones:
- Frontline unit zone: Unit zone where the unit here has its effective power calculated by their frontline power.
- Backline unit zone: Unit zone where the unit here has its effective power calculated by their backline power.
- Land zone : A land zone that will interact with units in both the frontline and backline zone of this lane.

The standard way to place each zone in a lane is the frontline at the front followed by the land zone then followed by the backline.
Each player has three(3) lanes which directly faces one of the other player's lane.

## Attack resolution

The standard way of winning a match is by attacking with the units in your unit zones, this, as stated in the Main Phase section, requires you to rest the unit for 2 turns.
When a unit attack resolves the lane opposite to the lane of the attacking unit is checked and the following happens:
- If the opposite lane has a unit in the frontline the attacking unit starts combat with that unit.
- Else if the opposite lane has a unit in the backline the attacking unit starts combat with that unit.
- Else the attacking unit checks the protection zone once if its effective power is higher than 0(Refer to the protection zone section).

## Combat resolution

At combat resolution the effective power of both cards is compared and the result determines one of the following outcomes.
- If a unit has higher effective power than the other it wins combat and the other unit dies.
- If both units have equal effective power and their effective power is higher than 0 both units die.

[<- Home](../README.md)
