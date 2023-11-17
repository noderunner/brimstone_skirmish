# "Brimstone Skirmish" - Design Goals

## The Main Pitch
- A minimal set of core rules that can fit on a few pages.
- 60 minute or less average play times.
- Played on 2D Map with a square grid.
- Minimal component table-clutter.
- Roughly 60/40 skill/luck ratio.
- Low player downtime.

## Strategic Features

### Incentavize Movement & Positioning
One big difference from the mechanics of the board game is that players should be incentivized to keep moving and re-positioning models instead of standing in the same place. The best tactical position should generally require the model move to a new position each time it is activated. The goal is keep the match feeling dynamic. The game mechanics should directly incentivize movement throughout a match.

### Resource Management
Resource management adds a mix of longer-term strategic planning with short term tactical decions where emphasizing one often compromises the other. There should only be a single resource to gain/spend/manage in the game, and the rules for it should be simple.

### Player-Influenced Tempo
Players should be able to impact the tempo of the game. This could be things like being able to take bigger/more activations at certain times, push harder at the expense of resources or greater risk, etc. But there should be some mechanism within the game rules which provide a way for players to affect the tempo of how agressive or conservative they play. When to go all out and make a "big push" adds a climactic rise and fall to the emotional tension in the game.

### Asymetrical Unit Design
Units should be designed with a "rock-paper-scissors" approach in mind. That is, a typical unit design will have situations in which they excel, and situations which they struggle, as opposed to a "jack of all trades" approach. Great "generalist" units that excel in all situations should be avoided because it makes those units the most obvious choice for most army-building decisions.

Asymmetic units should create a "cat-and-mouse" kind of feel to the gameplay, where units are naturally incentivised to keep moving around the map for a better position so that they can chase down opposing units they are strong against, while trying to avoid being chased down by ones they are weak against. 

For example, a U.S. Marshal unit with a long range rifle might be strong against tough, slow moving enemies. But the extra focus it takes the Marshal to aim their rifle for accuracy makes them vulnerable to quick flanking attacks by fast, melee focused enemies. Having specific strengths and weaknesses in mind when designing units should help with this goal.  

### Opportunities for Bluffing/Misdirection
Giving players opportunities to misdirect their opponent opens the game up to different types of skills where it isn't necessarily the case that the most analytically gifted player will dominate each match.

A straightforward way to achieve this is by incorporating some element of hidden information, whether it be models in hidden deployment on the map or having a pesonal hand of cards.

### Low Complexity Unit Profiles
Each unit should have the most minimal set of attributes and properties required in order to make each unit feel interesting and destinct, but no more. The rules for all unit abilities should fit on a single double-sided reference sheet.  

# Mechanics
This section will discuss specific design mechanics of the game rules and ideas for their implementation. They are meant to provide examples and brainstorming ideas for the game rules and also work as examples for Large Language Models assisting with game design.  

### Activation System

**Card-Driven**  
I like the mechanic of playing cards to activate units (Mythic Battles, Super Fantasy Brawl). There are several aspects of this I think work well:

- No need to track which units have activated with tokens and other clutter.
- Narrowing down the choices players have to just what is in their hand cuts down on AP.
- Higher level goals of resource management, tempo, and bluffing are all achieved in one simple mechanic.

There are some downsides:

- Players can feel frustrated if they can't activate a unit they want.
- Eliminated units become "dead" cards without some compensating rules.
- Assembling your deck of cards can increase setup time depending on the implementation.

## Dice Combat
Most skirmish games use dice to resole combat and other game effects, although there are exceptions, such as Malifaux which remove dice in favor of a deck of cards.

**Buckets of Dice**  
This is usually considered the Games Workshop approach. Rolling large handfuls of D6 dice, with certain values considering a success or failure. The values required for success are usually modified by game context (e.g. a flanking bonus for being behind the target of an attack).  
It's fun to roll big chunks of dice and the small numbers on each die are easy to work with. This approach can be a bit messy on the table though. But this is the system tha the Shadows of Brimstone board game uses, so it would b a natural fit for a skirmish variant.

**2D6**  
This is probably my personal favorite approach. 2D6 gives a nice probability curve, with more common results toward the middle and more rare results on the ends (double 1's and 6's). This has a nice effect where common results happen more often and rare results happen less often, which feels "right".  

Another thing I like about this is less table clutter and easy to apply modifiers. 

I'm leaning towards a 2D6 system with two different colored dice, one of them being designated the "effect" die. This has been done before and is a simple way to add extra effects to combat that can trigger depending on the situation.

### Movement
Focusing on a 2D grid map is a no-brainer since that is how the base game works and it would not require players to invest extra money in 3D terrain. The very popular Frontier Town/Feudal Village expansions come with a great "battle map" out of the gate, which is the ideal way to playtest. 

I don't see a need to modify the already solid system that the Frontier Town expansion provides with rules for:

- Cover
- Moving from building interiors to rooftops
- Shooting through windows
- Leaning around corners


