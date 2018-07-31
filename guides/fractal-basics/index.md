---
title: "Fractal Basics"
date: "2018-04-17"
image: "./images/instabilities.jpg"
description: "Get to know the meta 5-man team composition, learn about the /gg command and Mistlock Instabilities."
---

## Team Composition

The current "meta" group setup for fractals consists of the following builds:

|                                       |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <Specialization name="chronomancer"/> | The Chronomancer's role consists of providing 100% <Boon name="quickness"/> uptime, good <Boon name="alacrity"/> uptime, strong utilities in terms of heavy crowd control, reflects, shared <Boon name="aegis"/>, <Skill id="10197" profession="mesmer"/> skips, group <Effect name="stealth"/> and medium power DPS. It is by far the most important profession in the team offering a combination of abilities like no other profession does.<br/>The <Specialization name="chronomancer" prefix="boon"/> is even capable of providing every single boon in the game which has great synergy with traits like <Trait id="1511" profession="elementalist"/>. |
| <Specialization name="warrior"/>      | The Warrior is still essential to any team, providing strong party buffs in the form of <Skill id="14405" profession="warrior"/>, <Skill id="14407" profession="warrior"/> and <Trait id="1482" profession="warrior"/>. The currently favored build is the <Specialization prefix="banner" name="warrior"/> setup with CC, boonstrip capabilities and good burst DPS.                                                                                                                                                                                                                                                                                        |
| <Specialization name="weaver"/>       | The Weaver is the typical damage dealer. Its main purpose is to deal as much damage as possible while providing minor utilities with AoE <Condition name="blind"/>, <Skill id="5536" profession="elementalist"/> and <Boon name="might"/> pre-stacking. Ideally you want as many Weaver as possible in your party. Good groups usually go with 2 Weavers and one Power Soulbeast ( for extra CC and <Skill id="12497" profession="ranger"/> ) .                                                                                                                                                                                                     |
| <Specialization name="druid"/>        | The Druid significantly buffs the group's damage output with <Skill id="12493" profession="ranger"/>, <Skill id="12497" profession="ranger"/>, <Skill id="31582" profession="ranger"/>, 25x <Boon name="might"/>, <Boon name="fury"/> and <Trait id="1016" profession="ranger"/> while also providing party heals and condition cleanses. If required, it can even provide permanent <Boon name="protection"/> and <Boon name="stability"/> when needed.                                                                                                                                                                                                                  |
| <Specialization name="Soulbeast"/>        | The Power Soulbeast takes over the Druid's or 3rd DPS's place in the party, buffs the group's damage output with <Skill id="12497" profession="ranger"/> while also providing extra CC. If required, it can even provide condition cleanse, damage boost if really needed with <Trait id="2128"/>, mostly recommended in some of the T4 fractals where too many mobs are in one place, for example the Molten Effigy encounter in the Molten Boss fractal, after these encounters switch back to <Trait id="2143"/>.                                                                                                                                                                                                                 |

The only interchangeable slots in the prevailing team composition are the two/three DPS slots ( depends if you run with Druid or not), which may be swapped with any other profession. While condition-based team setups are perfectly viable, power setups tend to outperform them in fractals due to <Item id="24868"/> and Slaying Potions like <Item id="50082"/>. Fights are also shorter than in raids and power classes usually benefit more from the additional precision from the <Item id="79722"/>.

---

## Usage of `/gg`

<Grid>
<Column>
You can use the chat command `/gg` within fractals to immediately kill your character (dead, not downed). This can be used generously in fractal skips, as it allows the entire party to teleport to a checkpoint once one player activates it.
If everyone in the party is dead at the same time, cooldowns will reset for all players. Therefore it is advised for the entire group to use `/gg` at certain key positions to reset long cooldowns, like between Siax (2nd boss) and Ensolyss (3rd boss) in 99CM. Never resurrect as long as another player is still alive.

Note that the Druid's <Skill id="31869"/> will fully recharge after the resurrection.
</Column>
<Column width="6" compact>
<Image src="./images/gg.jpg" title="A dead player" compact/>
</Column>
</Grid>

---

## Mistlock Instabilities

Tier 4 fractals always have three Mistlock Instabilities active which add additional mechanics to the fights. The selection is fixed for each difficulty level and specified in the top panel of each fractal guide.

Below is a list of all current instabilities and their possible countermeasures.

|                                           |                                                                                                                                                                                                                                                                                                                                       |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <Instability name="Adrenaline Rush"/>     | Enemies deal 50% more damage below 10% health. This also enhances special boss abilities, so be sure to finish mobs off quickly.                                                                                                                                                                                                      |
| <Instability name="Afflicted"/>           | Enemies apply random damaging conditions (<Condition name="bleeding"/>, <Condition name="burning"/>, <Condition name="confusion"/>, <Condition name="poison"/> and <Condition name="torment"/>). A good countermeasure is to have the <Specialization name="druid"/> use <Skill id="12489"/> in combination with <Trait id="1075"/>.  |
| <Instability name="Flux Bomb"/>           | Causes players in combat to be randomly marked with Flux Bombs which leave a damaging and blinding AoE field behind. Do not place those inside the combat area, learn to dash away right before the field deploys. If you keep walking forward while marked you wont get any damage from the bomb.                                    |
| <Instability name="Last Laugh"/>          | Each enemy killed explodes within a 180 radius 1.75 seconds after its death, dealing high damage and apply <Control name="daze"/> to foes around it. Recognizable by a yellow zone after a mob's death.                                                                                                                                   |
| <Instability name="Mists Convergence"/>   | Causes a set of effects from other fractals to spawn, including _The Mossman_, a deadly _Champion Rabbit_, _Veteran Jade Maw Tentacles_, an _air strike_ from the PvP map Skyhammer and the _cannon assault_ from Captain Mai Trin Fractal.                                                                                           |
| <Instability name="No Pain, No Gain"/>    | Enemies receive <Boon name="protection"/>, <Boon name="might"/> and <Boon name="fury"/> when you hit them. Has a 20 second internal cooldown per enemy, conveniently lining up with the Mesmer's <Skill id="10267"/>.                                                                                                                 |
| <Instability name="Social Awkwardness"/>  | Players receive 1 stack of <Effect name="agony"/> and 10% health damage when they attack enemies while an ally is within a 44 unit range. This is the most annoying instability and active in almost all relevant T4 fractals. Spread out to prevent killing each other, but stay in melee range to keep benefiting from group buffs. |
| <Instability name="Toxic Trail"/>         | Enemies leave a trail of poison behind them which inflicts direct damage and the <Condition name="poison"/> condition. Can be very dangerous when fighting multiple mobs.                                                                                                                                                             |
| <Instability name="Fractal Vindicators"/> | Fractal Avengers are replaced by hard-hitting Fractal Vindicators. Those need to be killed as fast as possible to prevent further chaos.                                                                                                                                                                                              |
| <Instability name="Hamstrung"/>           | The lower your health, the slower you move. Heal yourself!                                                                                                                                                                                                                                                                            |
