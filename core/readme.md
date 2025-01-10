

## Todo
scattered, regroup, scrap
write rules
standard fleet 1 dread 2 cruiser 1 carrier 3 infantry 1 fighter
xthian wormhole legendary rephrase Fleets in this system may load ground forces that are in the owners home system.
type rules into readme.md file
playtest




## Concept
Twilight Imperium with fewer systems and simultaneous actions. Gameplay is focused on combat, diplomacy, and economics. Movement and positioning is basically removed.

## Mechanics
Instead of command tokens, players have cards which are restored at the beginning of each round (called the strategy phase). When they play a card during a round, they cannot play it again that round unless they get it back somehow.

Each turn of an action phase, every player simultaneously and secretely commits two cards from their hand (fleet moves or abilities) then then get resolved at the same time.


## Play Phases
    Strategy Phase - Pick cards

    { Action Phase
        Abilities 1 Begin - play ability cards
        Fleet 1 - play a from and to card
        Abilities 2
        Fleet 2
        Abilities 3
        Fleet 3
        Abilities 4 End
    }

    Status Phase - Return fleet cards you have on the board to your hand, reveal objs
    Trade and trade Phase - elect one player, they do one random agenda power



## Fleet Actions
The board has 7 primary systems: Mecatol in center and 6 surrounding. Then a hex for each home system which is not connected to the board directly. You have a card for each of the primary ones (1 through 6 and center), and one for _your_ home system. Notice you cannot move into other players home systems. During tactical actions you select two cards, representing a Fleet number and a Destination. 

When electing to load, or not, any ground forces the order is (clock wise speaker last) CWSL which is the order for every ordering that could matter.

If fleets land in the same system, they have combat where ships roll based on their combat value. At the end of each battle round, after hits have been assigned and ship destroyed, on both sides, one ship with the FAST trait and any other ship may decide to retreat (CWSL).

After any space combat, you may commit forces to one planet for a ground invasion.


## Scattered and Regrouped Forces
When your forces retreat, they are assigned to the scattered forces pool. At the end of each round, all scattered go to the regrouped forces pool. Units in the regrouped forces pool may be built at no resource cost during production. They still impact production limit.


## Scrap Pool
Units that die are moved here. At the end of the round, the owner earns 50% of the value rounded down as Goods and removes the units.


## Technologies
6 public techs drawn randomly and available this game
each player handed 4 random unique unit techs only they can get
Flagships and warsuns are not buildable without special unit tech


## Strategy Phase
First, each MAY select 1 Strategy primary OR 1 secondary
Each select 4 secondaries (or faction specific secondary ability card)
Then collect all your fleet cards for fleets you have on the board


## Quick Rules
only commit forces from fleet onto one planet per fleet phase
all forces must land on planets after invasion if able
commodity does not exist, Trade Goods now called Goods
max 5 major ships per fleet
max 2 fleets per system
resolve one public objective end of round, one secret objective during the round, at end of any phase during the action phase
may only elect to retreat TO home, cannot retreat from MR
can never attack home systems
no flagships or warsuns without specific tech
planets have money placed onto them at the beginning of the round, until you spend the money from the planet, anyone can spend it/take
during the strategy phase your resources value is set to 2 per planet
influence does not exist
promisory notes do not exist
some primary strategy cards have no secondary card associated



## Strategy Cards : Primaries and Secondaries
Order always goes: clockwise speaker last if any player wants to wait for another before taking their action. So a player can delay their action until it is their "turn" players that would go after them may choose to go before. You can otherwise resolve things in any order.
These are treated as abilities. During the Strategy Phase you go in a circle where you all at once pick one Primary Card and two Secondary cards, or three Secondary Cards. The symbol `::::` means you cannot pick both the Primary Card and the Secondary Card, you must pick one or neither. As your last ability for the round, you may use any from your hand or any Primary Card you have not used this round. You cannot pick multiples of Secondary cards.


Construct New Fleet - Put a new fleet marker on the board and build units into it. This fleet cannot move this round since you don't have the fleet card in your hand! You could put it into your hand with the Warfare card though!


### Primaries:
* __Trade__ - :::: commit system with another players ships. you gain 4 trade goods and they gain 2, you may do any# transactions with one person
* __Politics__ - :::: commit home. Become speaker, or move it to your right if you are currently it, draw 2 action cards, reorder top agenda to top or bottom ::::
* __Warfare__ - :::: commit system. Pick up a fleet card for a fleet in that system ::::

* __Construction__ - :::: Commit system and place 1 SD or 1 PDS and also then 1 PDS on a planet you control in it ::::
* __Technology__ - :::: commit a tech whether or not you can pay for it and Redraw any # ship techs in your hand, gain 1 lab free OR gain all planets, then you may buy the committed tech or a public tech

* __Industry__ - commit system gain 1 trade good for each resource you control in this system
* __Diplomacy__ - commit system, other players may not use this system card for fleet tactical actions
* __Manufacturing__ - commit system Produce New Fleet with +2 resource and +2 produce limit
* __Imperial__ commit home Add 2 secret obj to hand, then discard 1


### Secondaries:
Trade II - :::: (Exclusive With Primary) - commit system with another players ships. You gain 2 trade goods they gain 1
Politics II - :::: (Exclusive With Primary) commit home Draw 2 action cards and keep 1
Warfare II - :::: (Exclusive With Primary) - commit system Produce New Fleet at target system

Construction II - :::: (Exclusive With Primary) - commit system Place a Space dock OR PDS
Research - commit a tech whether or not you can pay for it, gain 1 lab by paying 4 resources OR gain all from planets, then you may buy the committed tech OR any public tech

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



## Setup
* 2x each ship tech and deal 4 each player
* shuffle general tech




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


## Balance


1a - 5 r
1b - 4   L
1c - 3 y L
2a - 4 r L

2b - 4 y L
2c - 4 g L
2d - 3 g L
3b - 4 y L L


Wa - 2 L
Wb - 2 L


## Other Ideas
* action card - scry upcoming objectives
* secret obj - participate in combat with 2 or more other players


