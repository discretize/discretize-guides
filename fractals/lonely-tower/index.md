---
title: Lonely Tower
image: images/header.jpg
group: CM
bosses: 2
difficulties:
  - level: 100
    ar: 150
potions:
  - id: 50082
  - id: 8887
hasCM: true
cycle: Day
hidden: false
layout: src/layouts/Fractal.astro
date: "2025-02-09T19:44:38.753Z "
consumables: []
record:
  time: 2 min 25 sec
  by:
    - name: Boomer Fishing Club
      tag: BFC
long_description: Immediately following the foundation of the Astral Ward,
  Eparch finally returned to Tyria to strike back against Isgarren's
  "betrayal"—this time with a full entourage. Help Isgarren, Mabon, and Dagda
  navigate the crumbling halls of the Wizard's Tower and push the Kryptis back
  to where they came from.
api: 26231
description: Mabon, Isgarren. Pick a god and thank her for your survival...
sigils:
  - id: 24615
  - id: 24664
---

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

**Reward:** <Item id="101867"/>
</Achievement>
</GridItem>
</Grid>

Upon entering the fractal take the _Mistlock Singularity_ and head out the starting room and follow the corridor to your right. Whilst moving down the corridor avoid Cerus's Despair attack (the falling red orbs, leaving AoEs on the ground), standing in this attack will apply <Effect name="Agony"/> and 5 stacks of <Condition name="Torment"/>. At the end of the corridor you will see Cerus standing in the Astral Purifier room.

## Astral Purifiers 
<Grid>
<GridItem sm="8">
Inside the room, you will find four Astral Purifier Nodes that must be repaired. Interacting with a node will give you the effect <Label>Time Running Out</Label>. It will turn your weapon skills into a Simon Says styled minigame, where you will have to press a highlighted skill 10 times, before the 30 second timer runs out. Pressing the wrong skill will knock you back and cancel the minigame, requiring you to start again.

During the minigame, three Avatars of Spite will spawn and fixate on the player reapiring the node. When they get close they will apply <Condition name="Poisoned"/> and explode knocking the player back, cancelling the minigame. These can either be dealt with by the rest of the party, using crowd control and killing them, or alternatively the player on the node can b e given or use their own source of <Boon name="Stability"/> to negate the knockback, allowing them to continue the game. The <Boon name="Stability"/> method allows multiple nodes to be completed at the same time.  
</GridItem>
<GridItem sm="4">
<GifPlayer sourceId="lonely-tower-astral-purifier" caption="Soloing an Astral Purifier Node with Stability"/>
</GridItem>
</Grid>

## Brothers <Item id="9443" disableText size="medium"/>
Once you have completed the Astral Purifier event, you can _/gg_ to respawn in the starting room. Leave the starting room, once again taking the _Mistlock Singularity_ if availible. However, this time turn left and move down the corridor. This time as well as Cerus's Despair attack (the falling red orbs) from before, you will also have to deal with Deimos's Grasping Hands, that apply <Condition name="Poisoned"/>, <Condition name="Torment"/>, and <Condition name="Crippled"/>. At the end of the corridor you will come to a single Astral Purifier node, which requires you to play the same minigame as before. Repairing this node will allow access to the room with the brothers Cerus and Deimos standing in. Both bosses will fixate and move towards the closest player to them, with the players gaining the <Label>Cerus's Focus</Label> and <Label>Deimos's Focus</Label> effects respectively. When the brothers are close together they will gain the effect <Label>Brothers United</Label> leading their attacks to deal more damage.

<Grid>
<GridItem>
<Achievement title="Brothers, Together">
Defeat Cerus and Deimos within 5 seconds of each other in the Lonely Tower fractal. 
</Achievement>
</GridItem>
<GridItem>
<Information>
Providing you can deal with the mechanics, the easiest strategy to kill the brothers quickly (and get the achievement) is to pull them together. By pulling both brothers together they again the <Label>Brothers United</Label> effect, which increases their outgoing damage.
</Information>
</GridItem>
</Grid>

### Cerus's Mechanics
<Grid>
<GridItem sm="4">
#### Despair
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Cerus will spawn an expanding AoE under players. When the AoE fills a red orb will drop from above. Standing in the red AoE left behind will apply <Effect name="Agony"/> and 5 stacks of <Condition name="Torment"/>.
</GridItem>
<GridItem sm="4">
#### Cry of Rage
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Cerus will repeatedly pummel the ground as a large expanding AoE fills the arena. When the AoE fills it will deal damage to all players in it. Additionally any player hit by the attack will grant a stack of the <Label>Empowered</Label> effect to Cerus, which increases his damage by 5% per stack.
</GridItem>
<GridItem sm="4">
#### Malicious Intent
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Cerus will tether himself to a player and draw out a Malicious Shadow, that will slowly walk towards Cerus. Once it reaches Cerus's hitbox, the Shadow will be consumed giving cerus 5 stacks of <Label>Empowered</Label>.
</GridItem>
</Grid>

### Deimos's Mechanics
<Grid>
<GridItem sm="4">
#### Grasping Hnads
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Grasping Hands will spawn under the player furthest away from Deimos. Standing in them applies apply <Condition name="Poisoned"/>, <Condition name="Torment"/>, and <Condition name="Crippled"/>. Any hands close to Deimos will get pulled in and consumed, giving deimos stacks of <Label>Devour</Label> for each hand consumed. <Label>Devour</Label> increases Deimos's outgoing damage by 2% per stack.
</GridItem>
<GridItem sm="4">
#### Rapid Decay
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Deimos will stop and swing his maces for 5 seconds, after the 5 seconds the closest player to Deimos, without <Label>Cerus's Focus</Label> will have an orange AoE spawned under them. Shrotly after the field becomes black and anyone who steps in it will expand the field and also be dealt heavy damage.
</GridItem>
<GridItem sm="4">
#### Annihilate
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Deimos will slam the ground creating a large AoE on the ground. This will then start a shockwave moving from the front to the back, launching anyone hit backwards.
</GridItem>
</Grid>

## Eparch <Item id="8886" disableText size="medium"/> <Item id="24664" disableText size="medium"/>
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

### Globules of Emotion

As Eparch carries out each attack, he will spawn Globules of Emotion. These can be collected by players giving different effects, some positive and some negative. Each attack has a corresponding emotion that it will spawn which can be seen in the table below. If you have stacks of a Globule of Emotion and go to collect a different type, each new Globule will remove a stack of the previous effect until you start to gain stacks of the new effect.

| Globule of Emotion (Colour)          | Boss Mechanic     | Player Attunement                                                                          | Boss Empowerment                                               |
|-----------------------|--------------|----------------------------------------------------------------------------------------|-----------------------------------------------------------|
| **Despair (Blue)**    | Rain of Despair | -3% Incoming Strike Damage, -3% Outgoing Strike Damage                                 | -3% Incoming Strike Damage, -3% Incoming Condition Damage |
| **Envy (Green)**      | Wave of Envy  | +5% Boon Duration, +5% Condition Duration, +5% Condition Damage, -50% Incoming Condition Damage | Boss attacks strip Boons                                  |
| **Gluttony (Orange)** | Spin Attack  | ~108.5 lifesteal, 100 Damage taken per second               | Heals boss                                                |
| **Malice (Purple)**   | Spike of Malice | +4% increased defiance break                                                           | Boss attacks inflict additional Conditions                |
| **Rage (Red)**        | Enraged Smash  | +5% Outgoing Strike Damage, +5% Incoming Strike Damage                                 | +5% Outgoing Strike Damage, +5% Outgoing Condition Damage |
| **Regret (Yellow)**   | Spawns Adds         | +2% Skill Recharge, 50 Damage taken on activation                                                  | 20 damage reflect                           |
| **Consumed**   | Consume (CC)         | -3% Health, -3% Outgoing Strike Damage, -3% Outgoing Condition Damage |                           |

With this in mind, it makes sense for the following roles to prioritise the following Globules of Emotion to maximise party damage:
- Healer - Takes Despair Globules. If there are no Condi DPS players, the healer can also take Envy Globules to cancel out the Despair stacks.
- Power DPS - One of the power DPS players wshould take Rage Globules. This will massively increase their damage and should make sure they do not get consumed by Eparch during CC. Commonly played builds for this are <Specialization name="Scrapper"/> or <Specialization name="Dragonhunter"/>
- Condi DPS - Takes Envy Globules. It is important to make sure they do not get consumed by Eparch during CC to prevent the boss from currupting the parties boons.
- Gluttony DPS - This is a special role that aims to maximise the amounts of hits on the boss to trigger the Lifesteal effect from Gluttony Globules. The current best choice for this is <Specialization name="Willbender"/> with <Item id="102245"/>.
- DPS / Booon DPS - The remaining players should pick up any remaining Globules if they spawn (Malice or Regret), or to pick up orbs for one of the other assgned roles if something goes wrong mid encounter.

### Consume
<Grid>
<GridItem sm="8">
During his rotation, Eparch will gain a defiance bar, then pull in and consume all Globules of Emotion left on the ground and gain their respective effects as per the table above. By breaking Eparchs Defiance Bar, you will remove some stacks of empowerment. It is important to make sure you have collected all Malice and Envy Globules before the CC phase to make the fight considerably easier.

Additionally, during this phase, Eparch will target one player and apply the <Label>Consume</Label> effect. This will start to remove any Emotion stacks the player has untill they reach zero or the defiance bar is broken. At zero stacks, Eparch will apply stacks of the <Label>Consumed</Label> effect, with each stat lowering the players attributes. To reduce the stacks and remove this effect, the player will have to collect Globules of Emotion.

Eparchs target fixation works as follows; The player who is furthest away in his line of site will be targeted. This means before Eparch is about to start his CC mechanic you want to make sure that a player without Rage, Envy, or Gluttony stacks is targeted to prevent the boss from becoming empowered, or your party losing a large potion of its outgoing damage modifiers.
</GridItem>
<GridItem sm="4">
<GifPlayer sourceId="lonely-tower-eparch-consume" caption="Throw firewood into the fire"/>
</GridItem>
</Grid> 

### Eparchs Attacks
<Grid>
<GridItem sm="4">
#### Rain of Despair
<GifPlayer sourceId="lonely-tower-eparch-despair" caption=""/>
Eparch will raise his greatsword in the air and spawn Globules of Despair. At the same time he will spawn Despair AoEs spiraling inwards from the edge of the arena to Eparchs hitbox. Standing in an AoE will apply <Effect name="Agony"/> and 5 stacks of <Condition name="Torment"/>.
</GridItem>
<GridItem sm="4">
#### Enraged Smash
<GifPlayer sourceId="lonely-tower-eparch-rage" caption=""/>
Eparch will leap into the air and slam his greatsword on the ground spawning Globules of Rage. At the same time fissues will spawn on the ground applying <Effect name="Agony"/> to anyone hit. Eparch will also create a shockwave that needs to be jumped or dodged. Failing to avoid the shockwave will cause players to be hit by a two second <Control name="Knockdown"/>.
</GridItem>
<GridItem sm="4">
#### Wave of Envy
<GifPlayer sourceId="lonely-tower-eparch-envy" caption=""/>
Eparch will raise his greatsword in the air and four arrows will apear from his hitbox. Shortly after Eparch will spin unleashing waves of envy in the direction of each arrow, spawning Globules of Envy. Anyone hit by this attack will have their boons corrupted. To avoid this make sure to dodge the waves.
</GridItem>
<GridItem sm="4">
#### Inhale
<GifPlayer sourceId="lonely-tower-eparch-gluttony" caption=""/>
Something
</GridItem>
<GridItem sm="4">
#### Spike of Malice
<GifPlayer sourceId="lonely-tower-eparch-malice" caption=""/>
Something
</GridItem>
<GridItem sm="4">
#### Spawn Adds
<GifPlayer sourceId="lonely-tower-eparch-regret" caption=""/>
Something
</GridItem>
</Grid>

<Divider text="Challenge Mode"/>
## Eparch CM <Item id="8886" disableText size="medium"/> <Item id="24664" disableText size="medium"/>
<Grid>
<GridItem>
<Achievement title="Secrets of the Tower ">
Accept the harbinger's challenge and defeat the final boss in the Lonely Tower fractal.
</Achievement>
</GridItem>
<GridItem>
<Achievement title="Wavering Ward">
Accept the harbinger's challenge and complete the Lonely Tower fractal without anyone in your group being defeated.

**Title:** Kryptis Exorcist
</Achievement>
</GridItem>
</Grid>
With Challenege mode enabled, the majority of the fractal plays out the same as the T4 version. The main difference is the Eparch encounter which gains the following changes:
- Split phases at 65% and 35%
- When successfully breaking Eparchs defiance bar, Eparch does not lose any aqquired Globule of Emotion Stacks
- Collecting Globules of Emotion will not reduce <Effect name="Consumed"/> stacks on players

The rest of the encounter is exactly the same as the T4 mode.

### Pre-fight Organisation

Before starting the encounter it is important to discuss two things:
1. Assign Orbs - The trick to having a clean CM run is to assign roles in the party to different Globules of Emotion to collect. By allocating these to certain builds you will maximise the parties damage output and prevent Eparch getting empowered by stacks of Emotion. With this in mind the most common Globule assignment is:
- Healer - Takes both Envy and Despair Globules. This will Cancel out the Despair stacks and prevent Eparch from getting Envy stacks and corrupting the parties boons.
- Power DPS - One of the power DPS players wshould take Rage Globules. This will massively increase their damage and should make sure they do not get consumed by Eparch during CC. Commonly played builds for this are <Specialization name="Scrapper"/> or <Specialization name="Dragonhunter"/>
- Gluttony DPS - This is a special role that aims to maximise the amounts of hits on the boss to trigger the Lifesteal effect from Gluttony Globules. The current best choice for this is <Specialization name="Willbender"/> with <Item id="102245"/>.
- DPS / Booon DPS - The remaining players should pick up any remaining Globules if they spawn (Malice or Regret), or to pick up orbs for one of the other assgned roles if something goes wrong mid encounter.

2. Decide on a Gluttony Strat - To make the split phases quick and painfree, you typically want your Gluttony player to start each split phase with 12 stacks of Gluttony. For most groups this means picking up two sets of orbs in the first phase and one set of orbs in the second phase (however slower groups will want to pick up two sets in both phases). Make sure to confirm this before starting so that the party knows to stop attacking to allow the second set of Gluttony Globules to spawn in the first phase and also in P2 if required.

### 100% - 65%

### 65% Split Phase
When reaching 65%, Eparch will leave the Arena and spawn 2 rifts Each rift will spawn either a Champion incarnation of Judgement, or a Champion Incarnation of Cruelty, along with some trash mobs. To close the rift, its associated Champion must be killed, to allow players to close the rift by channeling in a white AoE that spawns. Meanwhile Avatars of Spite will spawn and be drawn towards Eparch, who is floating above the arena. When the Aspects get close, they tether to Eparch giving him stacks of Globules of Emotion.

Typically groups will move to the North rift first. Once you reach the Champion make sure to CC it instantly. At this point let your Rage DPS and Gluttony DPS players go big and burst the Champion down as fast as possible. When killing the champions there are two main attacks to watch out for. The Champion incarnation of Judgement will spawn an orange expanding AoE. Anyone hit by this once it channels will have all of their boons transferred to the Champion. Meanwhile the Champion Incarnation of Cruelty will spawn walls that will <Control name="Knockback"/> any player who touches them. To negate this ensure you have a source of <Boon name="Stability"/>. Additionally both champions have other attacks that generally will <Control name="Knockback"/> players, but are well telegraphed and easily avoided.

While killing the first champion, keep an eye on the second rift. If Avatars of Spite have spawned and are getting closer to Eparch, you may need to send a player to either CC them and keep them back while the party finishes with the first rift, or to go kill them. This is typically only required in groups with low damage or missing Stacks or Rage and Gluttony Orbs going into the split phase.

Once the first champion has been killed, you can then interact with the rift to close it. Make sure to target the rift to preven being interrupted from channeling. You may want to send your Rage and Gluttony DPS players ahead with the support player to start fighting the second champion, however if aspects have spawned and are getting close to the middle, keep the Rage player back since they deal more damage to the rift. Once the rift has closed any Aspects from the rift wil despawn and you can safely move to the second rift and repeat the process
<Warning>
When closing the final rift, Avatars of Spite can take a couple of seconds to despawn meaning they can still tether to Eparch and give him stacks. To prevent this you may need to kill any aspects before closing the rift if they are close to the middle of the arena!
</Warning>

### 65% - 35%
This phase is a repeat of the first, however at either the start of the Phase or shortly into it (depending on pace) Eparch will gain another CC bar and start consuming stacks of emotion again. As in the first phase break the bar quickly and continue to DPS. This phase will be much faster due to players already starting the phase with stacks of Gluttony and Rage. Make sure to pay atention to Eparchs health and stop DPS to allow the Gluttony player to collect another set of Globules before phasing.

### 35% Split Phase
Once again this is essentially the same as the first split, however this time three rifts will spawn. This phase can get a bit hectic, especially if Gluttony stacks start to drop. Repeat the same process as the first phase, move to the North champion, CC it, Kill it, Send people ahead, remaining players closes the rift, and manage any Avatars of Spite in necessary, and repeat for the next two rifts. Sometimes a champion may get bored of waiting for yout party to walk to it and will come to you instead. If this is the case just swap to it once you have killed the champion you are currently attacking and make sure to pay attention to any Aspects spawning as they will not get cleaved down if you are away from the rift.

<Warning>
When closing the final rift, Avatars of Spite can take a couple of seconds to despawn meaning they can still tether to Eparch and give him stacks. To prevent this you may need to kill any aspects before closing the rift if they are close to the middle of the arena!
</Warning>

### 35% - 0%
Once again this phase is a repeat of the first and second phases, keep collecting Globules, insta CC Eparch when he gains a CC bar, and be careful of getting hit by Eparchs attacks if he has lots of Emotion stacks at this point. 
