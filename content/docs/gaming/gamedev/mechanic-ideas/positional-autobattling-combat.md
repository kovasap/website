# Positional Autobattling Combat

## Inspiration

In many turn based tactics games there is a large amount of player effort spent
on manually moving characters and using abilities.

I think that not all of these actions are really that interesting - what IS
interesting is the positional placement of units, and perhaps their "stance"
(are they attacking or defending).

## System

All actions taken by characters are "cooldown based".
Cooldowns are defined in terms of "ticks"; one tick will happen around every
0.25 - 0.5 seconds to give the game a more "turn based" feel.

For example, a character can try to move every tick.
They may be stopped because they are in the zone of control of another unit (a
la Battle Brothers).
Characters will not move unless ordered to go to a location by the player.

Attacking will work a similar way.
Target selection is automatic by default, but the player can set priority
targets.

Defending works on a "charge" basis, like shields in FTL.
Every tick, the character regains some blocking or dodging power.
When their power is above certain thresholds, then the next attack they receive
will be blocked/dodged and their power will decrease based on the attack.

If they character has not enough power, they will be hit.
