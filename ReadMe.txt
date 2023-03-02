Prototype RunnerTouch using Unity with C#

NPCs use (Arrive (tweaked), Flee and Wander behaviors)
10 NPCs are randomly spawned. 
There are chasers (Red) and evaders (Green) and a player (evader-White)
The goal for the player is to pick as many tokens as possible without getting touched by red players
Once an evader NPC is touched by a chaser it will become frozen. 
The evaders need to unfreeze the victim quickly before it also turns into a chaser!

Parameters can be quickly modified to make the game harder.

Inputs:
Hold shift to run
ASDW: basic movement


To complete:
- Grid based pathfinding
- Flocking behavior for unfreezed NPCs
- Handling Collisions
