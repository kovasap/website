# Using AI: How it's Been Feeling

## Pre-AI

Before AI coding agents got really good, my process of implementing some idea
into software looked something like this:

First, I'd start reading about the part of the system I want to change.
Slowly I'd learn the code and APIs I might need to make my change to see what's
possible.
Through this process I would build an incremental understanding of how all the
parts of the system fit together.
This would show me where to put my new code and how to wire it all up.
Then I would write my code, test it, and be satisfied with the result.
I'll call this way of writing code **Incremental Understanding**.
In this method using AI tooling like autocomplete and search/chat is really
useful and a valid part of this process as I'm defining it.

## Post-AI

In the new age of AI, a new option is now available, which I'll dub the
**Agent Delegation** option.

To take this option, you just feed your idea directly to a coding agent and let
it go wild.
Then you go do something else while it works.
After a hard-to-predict amount of time, you will get some result.
It might work perfectly, it might be broken.
It might be really clean internally, or it might be wired together with duct
tape and messy glue.

From an external, user's perspective, if it works then you are done!
This feels magical and a little surreal.

However, if it doesn't work, you have three options that all feel bad (to me):

1. Scrap all the AI's work and go back to **Incremental Understanding**.
   This feels bad because it feels like you are missing out on the time / energy
   savings that an AI agent would provide.
2. Tell the agent to try again or fix a problem you see, doing another **Agent
   Delegation** loop.
   This feels bad because in the back of my mind I'm expecting the agent to fail
   again, or at the very least expecting to have to do multiple iterations.
   The fact that it takes an unknown amount of time (sometimes hours) to get
   feedback on this makes it a lot worse.
3. Try to understand the agent's code and fix it yourself or delegate other
   agents to fix sub-parts.
   I'll call this **All-at-once Understanding**, as here you are trying to
   understand a complete code artifact that will likely change dramatically on
   the next agent loop.
   This feels bad because (1) understanding code is hard, (2) agent-generated
   code is not always very readable, and (3) all the code may be thrown away
   soon.
   Of course you can ask the AI to try to walk you through the code or make it
   more readable.
   But it can be hard to trust - it always speaks so confidently even about
   things it should be unsure about.

The worst part about this choice is that the first option that was always
available, **Incremental Understanding**, has been somewhat poisoned by the
existence of AI agents.
For me at least, it is hard to motivate the hard work of learning a system or
some arcane API when you can just trust an agent to maybe do it much faster.
This is made even worse by a general cultural shift where there is a lot of FOMO
when not using AI.
"It seems to work for other people, maybe I'm just holding it wrong, let me try
again...".
