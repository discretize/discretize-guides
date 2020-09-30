---
title: 'Fractal Basics'
date: '2020-09-29'
image: './images/instabilities.jpg'
description: 'Get to know the meta 5-man team composition, learn about the /gg command and Mistlock Instabilities.'
hidden: 'false'
---

## Current fractal META

Please consult the [meta-page](guides/meta-explained) for more information about the current fractal META.

---

## Usage of `/gg`

<Grid>
<GridItem sm="8">
You can use the chat command `/gg` within fractals to immediately kill your character (dead, not downed). This can be used generously in fractal skips, as it allows the entire party to teleport to a checkpoint once one player activates it.

If everyone in the party is dead at the same time, cooldowns will reset for all players. Therefore it is advised for the entire group to use `/gg` at certain key positions to reset long cooldowns, like between Siax (2nd boss) and Ensolyss (3rd boss) in 99CM. Never resurrect as long as another player is still alive.

Note that the <Specialization name="Druid"/>'s <Skill id="31869"/> and <Skill name="Reapers Shroud"/> for <Specialization name="Reaper"/> will fully recharge after the resurrection.
</GridItem>
<GridItem sm="4">
<Image src="./images/gg.jpg" caption="A dead player"/>
</GridItem>
</Grid>

---

## Pre-stacking at Mistlock Singularity

<Grid>
<GridItem sm="12" md="6">
<Video caption="by Rubby [dT]" youtube="sMEBz5MJOk8"/>
</GridItem>
<GridItem sm="12" md="6">
After maxing the fractal masteries to level 4 you get access to _Mistlock Singularities_. Taking one of these will reset the cooldowns of all your skills! This allows you to precast certain skills before entering the battle without a penalty. It makes sense to precast <Boon name="Quickness"/> and <Boon name="Alacrity"/> and use blast finishers on certain Combo Fields. 

The most common applications are <Boon name="Might"/>-stacking using blast finishers inside a _Fire Field_ (3 stacks for 20 seconds with boon duration) and <Effect name="Stealth"/>-stacking inside a _Smoke Field_ (3 seconds).

Below is a list of frequently used blast finishers among all professions. Note that it is often required to swap to different weapons, make sure to swap back before you enter combat.
</GridItem>
</Grid>



---

### <Boon name="Might"/> stacking for groups using <Skill name="Moa Stance"/> from <Specialization name="Soulbeast"/>.
- <Specialization name="Renegade"/>: <Skill name="Renewing Wave"/> (Staff 4)
- <Specialization name="Firebrand"/>: <Skill name="Shield of Wrath"/> (Focus 5) and <Skill name="Mighty Blow"/> (Hammer 2)
- <Specialization name="Berserker"/>: <Skill id="14405"/> and <Skill id="14407"/> (Utility), <Skill id="14393"/> (Warhorn 4), <Skill id="14394"/> (Warhorn 5)
- <Specialization name="Weaver"/>: Use <Skill id="5692"/> (Scepter 2), <Skill id="5691"/> (Dagger 4) and <Skill id="5675"/> (Scepter 3) in <Skill id="5492" disableText/> / <Skill id="5492" disableText/>
- <Specialization name="Soulbeast"/>: Take the trait <Trait name="Leader of the Pack"/> and use <Skill name="Moa Stance"/> to make boons last longer, use <Skill id="12621"/> (Warhorn 5)


---


### Fire fields <Label><Boon name="Might"/> stacking</Label>

Below is a list of commonly used _Fire Field_ skills. **Make sure that everyone is back on their main weapon set before starting a fight.**

- <Specialization name="Elementalist"/>:
  - <Skill id="5548"/> (Staff 2, <Skill id="5492" disableText/>)
  - <Skill id="5691"/> (Dagger 4, <Skill id="5492" disableText/>)
  - <Skill id="5497"/> (Focus 4, <Skill id="5492" disableText/>)
  - <Skill id="29533"/> (Warhorn 5, <Skill id="5492" disableText/>, <Specialization disableText name="Tempest"/>)
- <Specialization name="Berserker"/>:
  - <Skill id="29940"/> (Torch 5)
- <Specialization name="Ranger"/>:
  - <Skill id="12504"/> (Torch 5)
- <Specialization name="Firebrand"/>:
  - <Skill id="44364"/> Skill 4 (Chapter 4: Scorched Aftermath)
  - <Skill id="9253"/>

---


<Grid>
<GridItem sm="12" md="6">
### Smoke fields <Label><Effect name="Stealth"/> stacking</Label>

Be careful not to aggro mobs with blasts or you will get <Effect name="Revealed"/>.
- <Specialization name="Thief"/>:
  - <Skill id="13113"/> (Pistol 5)
  - <Skill id="13065"/>
- <Specialization name="Ranger"/>:
  - <Skill id="31568"/> (Smokescale pet)
- <Specialization name="Engineer"/>:
  - <Skill id="5824"/> (Bomb kit)


</GridItem>
<GridItem sm="12" md="6">
#### Other skills that grant party <Effect name="Stealth"/>

- <Specialization name="Mesmer"/>:
  - <Skill id="10245"/>
  - <Skill id="10187"/>
  - Double any skill with <Skill id="29830"/> (<Specialization disableText name="Chronomancer"/>)
- <Specialization name="Thief"/>:
  - <Skill id="13117"/>

</GridItem>
</Grid>

---

## Mistlock Instabilities

Tier 4 fractals always have three Mistlock Instabilities active which add additional mechanics to the fights. The selection is random for each difficulty level and changes daily. More information can be found [in the official wiki](https://wiki.guildwars2.com/wiki/Fractals_of_the_Mists).

Below is a list of all current instabilities and their possible countermeasures.

| | |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <Instability name="Adrenaline Rush"/>  | When enraged, enemies deal 150% increased damage while they're low on health. Enemies deal 20% less damage when not enraged.     |
| <Instability name="Afflicted"/>   | Outgoing <Boon name="Resistance"/> duration is increased by 50%. Enemies apply random conditions. (<Condition name="Bleeding"/>, <Condition name="Burning"/>, <Condition name="Confusion"/>, <Condition name="Poisoned"/> and <Condition name="Torment"/>). Not necessary, although a good countermeasure is to have the <Specialization name="Firebrand"/> use <Skill id="45460"/> or blasting light fields.  |
| <Instability name="Flux Bomb"/>           |  This means that players in combat are randomly marked with Flux Bombs which leave a damaging and blinding AoE field behind. Do not place those inside the combat area, learn to dash away right before the field deploys. If you keep walking forward while marked you won't get any damage from the bomb. Flux bombs now apply to both allies and enemies. ***It is a little DPS increase to deploy it under the boss/mobs but it is not worth it blinding your team members!***                                    |
| <Instability name="Last Laugh"/>          | Enemies explode upon dying if not stunned. Stunned enemies apply protection and stability to nearby players. Each enemy killed explodes within a 180 radius 1.75 seconds after its death, dealing high damage and apply <Control name="Daze"/> to foes around it. Recognizable by a yellow zone after a mob's death. Stunned enemies apply <Boon name="Protection"/> and <Boon name="Stability"/> to nearby players.                                                                                                                               |
| <Instability name="Mists Convergence"/>   | Causes a set of effects from other fractals to spawn, including _The Mossman_, a deadly _Champion Rabbit_, _Veteran Jade Maw Tentacles_, an _air strike_ from the PvP map Skyhammer and the _cannon assault_ from Captain Mai Trin Fractal.                                                                                           |
| <Instability name="No Pain, No Gain"/>    | Enemies receive <Boon name="Protection"/>, <Boon name="Might"/> and <Boon name="Fury"/> when you hit them. Has a 20 second internal cooldown per enemy, <Specialization name="Renegade"/> can strip with <Skill name="Banish Enchantment"/> (<Skill name="Legendary Demon stance"/>) or <Specialization name="Reaper" text="Power Reaper"/> can strip with <Skill name="Well of Corruption"/> and weapon skills or <Skill name="Throw mine"/> from <Specialization name="Holosmith"/> or <Specialization name="Chronomancer"/> can strip with <Skill name="Phantasmal Disenchanter"/> or auto-attacks. Stripping an enemy boon will steal their life.   |
| <Instability name="Social Awkwardness"/>  | Players will be pushed away from one another. Make sure to not run around like a headless chicken! Find a good spot and stand still. |
| <Instability name="Toxic Trail"/>         | Enemies leave a trail of poison behind them which inflicts direct damage and the <Condition name="Poisoned"/> condition. Blocking a toxic-trail attack will absorb it and cleanse the condition. It can be very dangerous when fighting multiple mobs. Removes <Boon name="Aegis"/>.  |
| <Instability name="Fractal Vindicators"/> | Fractal Avengers are replaced by hard-hitting Fractal Vindicators. Those need to be killed as fast as possible to prevent further chaos.     |
| <Instability name="Hamstrung"/>   | The lower your health, the slower you move. Endurance regenerates 33% faster. Heal yourself to reduce Hamstrung stacks!      |
| <Instability name="Boon Overload"/> | Each boon on a player increases incoming strike damage by 5%. Outgoing boon duration is increased by 20%.    |
| <Instability name="Frailty"/> | Players are smaller and have 30% less health, but they move 25% faster.     |
| <Instability name="We Bleed Fire"/> | Enemies create flaming missiles when damaged. Incoming condition damage is reduced by 20%. It can be reflected for extra damage. In T4s <Specialization name="Renegade"/> should bring <Skill name="Legendary Centaur stance"/> and keep the bubble up in critical moments.    |
| <Instability name="Vengeance"/> | When enemies die, they enhance nearby foes with multiple boons, it does not apply to elite foes. Strip any enemy boon to inflict them with weakness.     |
| <Instability name="Outflanked"/> | Foes within 300 range do 300% more damage when attacking from behind, but do 25% less damage to you (their damage is reduced to 75%) when attacking from ahead.  |
| <Instability name="Stick Together"/> |   Take 60% increased damage when not within a range of 300 of an ally. Take 20% reduced damage when within a range of 300 of an ally.    |
| <Instability name="Sugar Rush"/> | Increases player movement speed and attack speed by 15%. Elite and lower enemies' movement speed and attack speed increases by 35%.      |
| <Instability name="Toxic Sickness"/> | Players are occasionally affected by the toxic vomit attack out of the Nightmare Fractal. Every player gets a cone AoE in front of him, aiming at a party member will deal lethal damage. Proper stacking and positioning nullifies this instability effectively.      |



<Divider text="What now?"/>
### Continue reading the basics of fractals like pre-stacking <Boon name="Might"/>, <Boon name="Fury"/> and other boons [here](/guides/blast-stacking) or if you already read that we recommend taking a look at what classes of meta compositions can do to break the Defiance bar [here!](/guides/cc-distribution)
