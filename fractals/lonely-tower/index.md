---
hasCM: false
cycle: Day
hidden: true
layout: src/layouts/Fractal.astro
date: "2024-05-23T05:19:18.507Z "
title: Lonely Tower
difficulties:
  - level: 100
    ar: 150
consumables: []
record: {}
long_description: Immediately following the foundation of the Astral Ward,
  Eparch finally returned to Tyria to strike back against Isgarren's
  "betrayal"—this time with a full entourage. Help Isgarren, Mabon, and Dagda
  navigate the crumbling halls of the Wizard's Tower and push the Kryptis back
  to where they came from.
image: images/lonelytowerheader.jpg
api: 26231
bosses: 2
description: Mabon, Isgarren. Pick a god and thank her for your survival...
group: T4
sigils: []
---
  
You can also use little animations. for that, please just record the video in good quality with minimal ui and effects, and send only the snippet to princeps. 
princeps has a transcode script, which makes the videos small and webfriendly.
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />

## Documentation
  
https://discretize.pages.dev/docs/

 
Immediately following the foundation of the Astral Ward, Eparch finally returned to Tyria to strike back against Isgarren's "betrayal"—this time with a full entourage. Help Isgarren, Mabon, and Dagda navigate the crumbling halls of the Wizard's Tower and push the Kryptis back to where they came from.  
 
<Divider text="Normal Mode"/>
<Grid>
<GridItem>
<Achievement title="Wizard's Tower Is Ours, Eparch ">
Complete the Lonely Tower fractal on any tier. 
</Achievement>
</GridItem>
<GridItem>
<Achievement title="Wayfind Yourself Out ">
Complete the Lonely Tower fractal on the Master tier.
</Achievement>
</GridItem>
<GridItem>
<Achievement title="Lonely Tower Fractal">
Complete all the achievements associated with the Lonely Tower fractal.

**Reward:** <Item name="Endless Midnight King Combat Tonic"/> 
</Achievement>
</GridItem>
</Grid>

Upon entering the fractal take the _Mistlock Singularity_ and head out the starting room and follow the corridor to your right. Whilst moving down the corridor avoid Cerus's Despair attack (the falling red orbs, leaving AoEs on the ground), standing in this attack will apply <Effect name="Agony"/> and 5 stacks of <Condition name="Torment"/>. At the end of the corridor you will see Cerus standing in the Astral Purifier room.

## Astral Purifiers
<Grid>
<GridItem>
Inside the room, you will find four Astral Purifier Nodes that must be repaired. Interacting with a node will give you the effect _Time Running Out_. It will turn your weapon skills into a Simon Says styled minigame, where you will have to press a highlighted skill 10 times, before the 30 second timer runs out. Pressing the wrong skill will knock you back and cancel the minigame, requiring you to start again.

During the minigame, three Avatars of Spite will spawn and fixate on the player reapiring the node. When they get close they will apply <Condition name="Poisoned"/> and explode knocking the player back, cancelling the minigame. These can either be dealt with by the rest of the party, using crowd control and killing them, or alternatively the player on the node can b e given or use their own source of <Boon name="Stability"/> to negate the knockback, allowing them to continue the game. The <Boon name="Stability"/> method allows multiple nodes to be completed at the same time.  
</GridItem>
<GridItem>
<GifPlayer sourceId="snowblind-throw-firewood" caption="Soloing an Astral Purifier Node with Stability " />
</GridItem>
</Grid>

## Brothers
Once you have completed the Astral Purifier event, you can _/gg_ to respawn in the starting room. Leave the starting room, once again taking the _Mistlock Singularity_ if availible. However, this time turn left and move down the corridor. This time as well as Cerus's Despair attack (the falling red orbs) from before, you will also have to deal with Deimos's Grasping Hands, that apply <Condition name="Poisoned"/>, <Condition name="Torment"/>, and <Condition name="Crippled"/>. At the end of the corridor you will come to a single Astral Purifier node, which requires you to play the same minigame as before. Repairing this node will allow access to the room with the brothers Cerus and Deimos standing in.

<Grid>
<GridItem>
<Achievement title="Brothers, Together">
Defeat Cerus and Deimos within 5 seconds of each other in the Lonely Tower fractal. 
</Achievement>
</GridItem>
</Grid>
<Information>
Providing you can deal with the mechanics, the easiest strategy to kill the brothers quickly (and get the achievement) is to pull them together.
</Information>
### Cerus
Something

### Deimos
Something

## Eparch
Once you have defeated the brothers, take the portal to the final boss. Before fighting Eparch, you will have to kill some trash mobs. Once you have dealt with them you can _/gg_ again, to reset cooldowns and prestack boons while Eparch spawns. When ready aproach the white circle on the ground to enter the arena.

<Grid>
<GridItem>
<Achievement title="Emotionless ">
Defeat Eparch in the Lonely Tower fractal without allowing him to reach 20 stacks of any emotional attunement.
</Achievement>
</GridItem>
<GridItem>
<Achievement title="Fissure Walker ">
Defeat Eparch in the Lonely Tower fractal without taking damage from his rage fissures.
</Achievement>
</GridItem>
</Grid>

<Information>
There is no status reset upon starting a boss encounter in this fractal, so it is advisable to take advantage of the _Mistlock Singularity_ to prestack boons, since the fight mechanics require you to move and split shortly after entering combat.
</Information>
Something 

### Orbs

| Orb (Colour)          | Mechanic     | Player Effect                                                                          | Boss Effect                                               |
|-----------------------|--------------|----------------------------------------------------------------------------------------|-----------------------------------------------------------|
| **Despair (Blue)**    | Puddle Spawn | -3% Incoming Strike Damage, -3% Outgoing Strike Damage                                 | -3% Incoming Strike Damage, -3% Incoming Condition Damage |
| **Envy (Green)**      | Line Attack  | +5% Boon Duration, +5% Condition Duration, -50% Incoming Condition Damage, +5% unknown | Boss attacks strip Boons                                  |
| **Gluttony (Orange)** | Spin Attack  | ~108.5 lifesteal on ~3s cd (cd unconfirmed), 100 Damage taken per second               | Heals boss                                                |
| **Malice (Purple)**   | Chasing AoEs | +4% increased defiance break                                                           | Boss attacks inflict additional Conditions                |
| **Rage (Red)**        | Wave Attack  | +5% Outgoing Strike Damage, +5% Incoming Strike Damage                                 | +5% Outgoing Strike Damage, +5% Outgoing Condition Damage |
| **Regret (Yellow)**   | Adds         | Grants Gluttony stack upon collection                                                  | 20 (unconfirmed) damage reflect                           |

### CC
Something

### Mechanics
<Grid>
<GridItem sm="4">
#### Puddle Spawn
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Something
</GridItem>
<GridItem sm="4">
#### Wave Attack
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Something
</GridItem>
<GridItem sm="4">
#### Line Attack
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Something
</GridItem>
<GridItem sm="4">
#### Spin Attack
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Something
</GridItem>
<GridItem sm="4">
#### Chasing AoEs
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Something
</GridItem>
<GridItem sm="4">
#### Adds
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Something
</GridItem>
</Grid>