---
backlinks-set: 
categories-set: #{"Gaming"}
---
# Core First Person Shooter (FPS) Principles

These are some general guidelines I've learned over my many hours playing FPS
games.  I'm writing them here so I don't forget them, and so others might learn
something - or point out flaws in my reasoning so I can get better!

## Information, and Proactivity

Most FPS fights come down to proactively acting on information about where
exactly your opponent is. If you know with precision where your opponent is,
and they don't know where you are, you can confidently peek at them and often
even prefire (or shoot as you are peeking).  Even if your aim is worse, you
will most of the time win the fight because your opponent has to reactively (1)
notice you, (2) readjust their aim (often >90 degrees of turning), and then (3)
shoot - whereas you get to skip the first two steps.

Additionally, if you are peeking off of an information advantage, you also have
the benefit of controlling the timing of the fight. Since you are peeking
around cover, you can always easily reverse your peek and duck back behind
cover if needed to reload or retreat.  This gives yet another massive advantage
to you.

Usually, proactively peeking someone involves you moving, but it can sometimes
involve you staying still in an unexpected place and using audio cues to
anticipate an enemy coming into view.  Here, even though you are not moving,
you are still the proactive party - your opponent is reacting to you.  Of
course, for this to work, you must be sure your opponent doesn't know where you
are, otherwise they will peek you and almost certainly win since they control
the timing of the fight.

## Getting and Keeping an Information Advantage

To win as many fights as possible, it's crucial to take those fights with an
information advantage. But how do you get this advantage and keep it as much as
possible?

### The Cone of Danger

The most useful way I've found to do this is to always hold in your head a
model of where your opponents might be.  One way to think about this is a "cone
of danger".  Imagine you can see through the walls of the map you are playing
on.  Then draw a cone from the leftmost enemy all the way to the rightmost
enemy.  This is the "cone of danger" you need to expect you opponents to be in.
Practically, since you normally cannot see through walls, you'll need to
constantly estimate this, drawing the cone from corners enemies could peek out
at you from.

![Cone Start](/docs/gaming/cone_of_danger_start.png)

Ideally, you want to keep this code as small as possible:

![Cone Small](/docs/gaming/cone_of_danger_small.png)

while making your opponent's cone as large as possible:

![Cone Large](/docs/gaming/cone_of_danger_large.png)
![Cone Max](/docs/gaming/cone_of_danger_max.png)

The best way to do this is by making it possible for yourself to move around
your opponent freely without them seeing you, while making it so any movement
they make is detectable by you. This generally involves controlling (knowing
for certain no enemies are in) most of the map.

Practically, moving around a lot also helps mess with your opponents cone. Even
if you have the ability to move around your opponent freely, your opponent will
often make the assumption you stayed still - if they are right, then they have
a very small cone when they go to peek you. A good practice is to always move
after an enemy sees you if possible.

Different games provide different tools to help determine where opponents are.
Use these!

### Stealth vs Spotted Mode

One helpful thought pattern is always knowing if you are operating in "stealth
mode" or in "spotted mode".

In "stealth mode", your opponents don't know where you are. When in stealth
mode, the goal is to get into a position where you can get some free shots in on
your opponents from an angle they aren't looking at. Once you do get those shots
in, or are otherwise spotted, you immediately transition to "spotted mode".

In "spotted mode", your opponents know your position and (you should assume)
they are taking steps to peek you as unpredictably as they can. Here, the
primary goal is to get back to either the safety of your teammates or a hidden
location in which you can't easily be trapped (e.g. a room with many exits as
opposed to one or two).

Because the transition between stealth mode and spotted mode is so instant, it's
helpful to always keep in mind an escape route when you are in stealth mode,
just in case you are spotted. This is for instance why a flank like this can be
bad:

```
<T>           |        <O>
     <T>      |      <O>          |   <You>
                     <O>

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
<T> = Teammate
<O> = Opponent
<You> = You
| or - = cover
```

In this case, even if you get a free kill from surprise, your opponents could easily surround and 3v1 you once you are spotted.

It may be better to take an approach like this:

```
<T>           |        <O>
     <T>      |      <O>
                     <O>

                |

                    -------

                   <You>
```

Here at the very least once you are spotted you have a clear, safe path back to
your teammates.

Of course, doing a 180 degree flank may be totally fine if you have some other
way to escape, either due to some map feature or character ability.

## Peeking Unknown Corners

If you are peeking around a corner into an unknown area with many potential
enemy locations, it's best to jiggle peak back and forth around the corner
checking each individual location one-by-one. This will help make sure you are
not fighting multiple enemies at once, and will give you control over fight
timing.  Be careful that this can be difficult when close to a corner, since
every unit of movement you make will expose a lot more of you than if you were
further from the corner.

## Cover

In games like Apex Legends, it's a good principle to keep part of your screen
obscured by cover when fighting, to give your opponent a smaller area to hit. At
the very least, make it so that when you are peeking out of cover you are also
shooting - this way worst case you are trading damage one-to-one with your
opponent.

## Angle Types

Whoever is closest to an angle has a disadvantage when fighting, as their body will be exposed before their opponent's.  Therefore, when holding an angle, it's helpful to be as far away from the piece of cover you expect your opponent to peek out from.  This also makes you a smaller target.

If you must hold close to an angle, you have to bank on your opponent not being thoughough and hide very passively, or be ready to aggresively peek with a close range weapon based on a sound cue.

## Influences

 - [Great break down by CoachNihil of kandyrew's
   gameplay](https://www.youtube.com/watch?v=L4QuNEkLtl8&ab_channel=kandyrew)
   which helped inspire the "cone of danger" thinking.
