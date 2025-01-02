

## Tood
how to solve land unit pickup or dropoff timing order
consider more special unit cards (like magic cards)


## Concept
Game board is cut down to a small number of systems. Gameplay is focused on combat, diplomacy, and economics, movement and positioning is basically removed.

## Mechanics
Instead of command tokens, players have cards which are restored during strategy phase. When they play a card during a round, they cannot play it again that round unless they get it back somehow.

Each turn every player simultaneously picks a card from their hand (tactics or abilities) then then get resolved.



## Play Phases
    Strategy Phase - Pick cards

    { Action Phase
        Abilities 1 Begin - play ability cards
        Tactics 1 - play a from and to card
        Abilities 2
        Tactics 2
        Abilities 3
        Tactics 3
        Abilities 4 End
    }

    Status Phase - Return fleet cards you have on the board to your hand, reveal objs
    Agenda Phase - elect one player, they do one random agenda power



## Fleet Actions
The board has 7 primary systems: Mecatol in center and 6 surrounding. Then a hex for each home system which is not connected to the board directly. You have a card for each of the primary ones, and one for _your_ home system. During tactical actions you select two cards, representing a Source and a Destination. You typically cannot select two primary systems. Rather, your ships must move back and forth between your home and primary systems unless they have the FAST trait.

When electing to load or or not ground forces: (clock wise speaker last) CWSL



## Quick Rule Changes
when units die you put their value in a pot where you get 50% of it as resources at end of round and remainder is saved
may only elect to retreat TO home, cannot retreat from MR
can never attack home systems
no flagships
planets have money on them at the beginning of the round, until you spend the money, anyone can spend it/take
during the strategy phase your resources value is set to 2 per planet
influence does not exist
commodity does not exist
transactions do not exist
promisory notes redone
PDS fires on ships activating the system
Strategy cards come in two varieties, primaries and secondaries. Primaries can only be picked by one player, but everyone else may choose to pick a copy of the secondary. When a primary is played, the other players do not play the secondary, rather you can think of secondaries as just a weaker version of the strategy card that you cannot also play if you get the strategy card.


## Technologies
6 drawn randomly and available this game
each player handed 3 random special unique unit upgrades
* War Sun Omega: (2 cards in selection) (2 units available per upgrade card), (slightly weaken war sun to 2x 1 hits and bombards, 9 res)
* War Sun Lambda: (2 cards in selection) (2 units available per upgrade card), (slightly weaken war sun to 2x 1 hits and bombards, 9 res)
* Flagship Omega: (2 units available per upgrade card), 7 res, a double dreadnought with special ability
* Flagship Lambda: (2 units available per upgrade card), 7 res, a double dreadnought with special ability
* Mech Omega: (2 cards in selection) (2 units available per upgrade card), sustain, 2x 6 combat, 1 res per
* Mech Lambda: (2 cards in selection) (2 units available per upgrade card), sustain, 2x 6 combat, 1 res per
* Dreadnoughts: +1 cap and combat, +2 bombard dice, Fast, -1 cost, guaranteed hit, suicide 2x,
* Cruisers: +1 cap, bombard, +2 combat, sustain, suicide 1x,
* Carriers: +3 cap, sustain, FAST,
* Destroyer: +2 combat, standard barrage upgrade,
* Infantry: +2 combat, 50% respawn, barrage,
* Fighter: +2 combat, 1/2 fleet, ground combat,


Each Select 1 Strategy primary
Each select 3 secondaries (or player special secondary ability card)
Collect all your fleet cards


Let each player take up to 3 tactical fleet moves and 4 actions alternating, start and end with abilities. 1 of the actions is likely a strategy card. 
_UNTIL DONE MOVING AND ABILITIES_

Move phase
Pick a fleet, direction, modifier cards
May merge fleet immediately fleet token back
Invade and decide which ground forces or fighters are on planets.

Ability
$2 per planet (planet can have other modifiers)
Construct 4/2
Produce 4
Research 4
Victory 
Strategy Card
Action Card

... REPEAT



## Strategy Cards : Primaries and Secondaries
Order always goes: clockwise speaker last if any player wants to wait for another before taking their action. So a player can delay their action until it is their "turn" players that would go after them may choose to go before. You can otherwise resolve things in any order.
These are treated as abilities. During the Strategy Phase you go in a circle where you all at once pick one Primary Card and two Secondary cards, or three Secondary Cards. The symbol `::::` means you cannot pick both the Primary Card and the Secondary Card, you must pick one or neither. As your last ability for the round, you may use any from your hand or any Primary Card you have not used this round. You cannot pick multiples of Secondary cards.


Construct New Fleet - Put a new fleet marker on the board and build units into it. This fleet cannot move this round since you don't have the fleet card in your hand! You could put it into your hand with the Warfare card though!


### Primaries:
* __Trade__ - :::: commit system with another players ships. you gain 5 trade goods and they gain 3
* __Politics__ - :::: commit home. Become speaker, or move it to your right if you are currently it, draw 2 action cards, reorder top agenda to top or bottom ::::
* __Warfare__ - :::: commit system. Pick up a fleet card for a fleet in that system ::::

* __Construction__ - :::: Commit system and place 1 SD or 1 PDS and also then 1 PDS on a planet you control in it ::::
* __Technology__ - :::: Commit tech and gain it for free

* __Industry__ - commit system gain 1 trade good for each resource you control in this system
* __Diplomacy__ - commit system, other players may not use this system card for fleet tactical actions
* __Manufacturing__ - commit system Produce New Fleet with +2 resource and +2 produce limit
* __Imperial__ commit home Add 2 secret obj to hand, then discard 1


### Secondaries:
Trade II - :::: (Exclusive With Primary) - commit system with another players ships. You gain 2 trade goods they gain 1
Politics II - :::: (Exclusive With Primary) commit home Draw 2 action cards and keep 1
Warfare II - :::: (Exclusive With Primary) - commit system Produce New Fleet at target system

Construction II - :::: (Exclusive With Primary) - commit system Place a Space dock OR PDS
Research - commit tech and pay 4 resources

Reinforce - commit system Produce into existing fleet in the system
Leadership - commit system Split or merge fleets there. a fleet split for an expended fleet results in two expended fleets (a ship could never move twice from this ability)
Imperial - commit home score any objective (repeat objective for center) OR draw 1 secret objective




## Action Cards
* __Sabotage__ - commit system PDS units may not fire in that system remainder of this round
* __Interference Matrix__ - commit system Anomalies in that system have no effect until the beginning of the next round
* __Warp Lock__ - commit system No player may retreat from that system for remainder of the round
* __Micro Wormhole__ - commit system Any fleet of yours commit that system during fleet actions this round

TODO SEE ACTION CARDS

## Faction Abilities and Cards (combo of )
Creuss : Micro Wormhole ability card
Nekro : Pay 2 research ability card
Hacan : Trade 3 : 1 ability card
Lizix : Reinforce into any fleet with 3 produce ability card
Muaat : War Suns but no war sun upgrade
Sardakk : May commit ground forces before space combat IFF carrier
Arborec : Infantry do not count toward produce limits






## Design
Reduce player decisions after the fact of picking cards. This prevents order dependencies. Also consider variables in flux at a phase, and prevent input variables from changing.

Variables:
* Commodities
* Trade Goods
* Planet Control
* Ships
* Fleet Cards




## Tactical Variables
Variables that can change during the tactical action, and thus cards that depend on these need to be not available for play, otherwise order dependency matters.

* Unit Position and Presence





## Ability Variables
Variables that can change during the ability action, and thus cards that depend on these from other players need to be not available for play, otherwise order dependency matters.

* Units can be built in a controlled system
* commodities and trade goods (Trade II)
* fleet cards expended
* objectives scored/revealed
* technologies






