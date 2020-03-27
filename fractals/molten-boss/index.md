---
title: 'Molten Boss'
date: '2018-09-12'
image: './images/header.jpg'
group: 'T4'
api: 2966
bosses: 2
difficulties: [{ level: 90, ar: 132 }]
cycle: 'Day'
potions: [{ id: 50082 }]
sigils: [{ id: 24615 }, { id: 24868 }]
consumables: [78978, 49940, 8764, 8801]
record:
  {
    time: '4:24',
    by: { name: 'Discretize', tag: 'dT' },
    youtube:
      [
        { id: '1IwsZyYrjmA', name: 'Metagame', specialization: 'Chronomancer' },
        { id: 'uS1gDsdXrh8', name: 'Nimajeb', specialization: 'Spellbreaker' },
        { id: '1DiIqiNB69A', name: 'Hyperiel', specialization: 'Holosmith' },
        { id: '-0eOZUOaYz8', name: 'Xarlor', specialization: 'Weaver' },
        { id: 'uOLhW3wIVoU', name: 'Hutselflutsje', specialization: 'Weaver' },
      ],
  }
---

## Start area <Item id="50082" disableText/>

<Grid>
<GridItem sm="8">
Skip the first two bridges, you can use <Effect name="stealth"/> but since it is difficult to reapply just stay together while moving.
**You can use <Item id="78978"/> to skip the entire first part, video below.**


You will reach an area with two _Molten Protectors_, drag them with you to the next group of mobs where you can't proceed. Kill everything there and the bridge to the Molten Effigy will come down.

Note that the _Molten Protectors_ cast a zone which grants enemies inside <Effect name="invulnerability"/> (recognizable by an electric beam). Therefore, killing and controlling the Molten Protectors is your highest priority throughout the entire fractal.

</GridItem>

<GridItem sm="4">
<Image src="./images/start.jpg" caption="The long way down"/>
</GridItem>
</Grid>

<GridItem sm="12">
<Tabs>
<Tab specialization="Revenant">
<Video title="Revenant skip" youtube="vn2UvjuDW1M"/>  
</Tab>

<Tab specialization="Guardian">
<Video title="Guardian skip" timestamp="364" youtube="MmJTsOhdQeo"/>
</Tab>

<Tab specialization="Thief">
<Video title="Thief skip" timestamp="172"  youtube="Alpgs_GaZV0"/>
</Tab>
</Tabs>
</GridItem>

---

## Molten Effigy <Item id="50082" disableText/>

Stack <Boon name="might"/> if possible before moving on to the Molten Effigy. **<Specialization name="Revenant"/> take <Skill name="Legendary Demon Stance"/> for <Skill name="Banish Enchantment"/> to remove <Boon name="Protection"> from the _Molten Effigy_**.

There is another single Molten Protector which needs to be focused before switching to the _Molten Effigy_. **<Specialization name="Revenant"/> use <Skill name="Banish Enchantment"/> (<Skill name="Legendary Demon Stance" disableText/>) and remove <Boon name="Protection"/> from the _Molten Effigy_**. Use interrupts or reflects against the Effigy's _Firestorm_ attack, pay attention to the _Charge_ (large arrow) and _Shockwave_ attacks and cleave mobs around if possible.

The moment you killed the Effigy you can `/gg` if necessary so you don't have to take the Mistlock Singularity (this prevents the problem where you can't take the Mistlock Singularity due to being in fight), then you can continue to the next trash group. All following groups of mobs are progress-blocking, clear them to make it to the final area. Molten Protectors have the highest priority (because they cast AoE <Effect name="invulnerability"/>) and Smoke Shamans are second to them (they apply <Effect name="stealth"/> to surrounding enemies). You can `/gg` once directly before the end boss if necessary.

<Image src="./images/molten_effigy.jpg" caption="The Molten Effigy"/>

---

## Molten Berserker & Molten Firestorm <Item id="50082" disableText/>

When you walk onto the end boss area, a group-wide <Effect name="agony"/> effect will be applied and put you in combat. As soon as it ends, use the small time (4-5 seconds) before boss starts to stack <Boon name="might"/>.

Kill the _Molten Firestorm_ first and pay attention to the AoEs and _Shockwave_ attack. Reflects are useful here as well (especially if you're running without a healer). The _Molten Berserker_ will heal to full health after his comrade is dead, kill him afterwards to finish the fractal.

Do not walk into the hitboxes of the two bosses to prevent them from moving out of damaging fields.

## Advanced tactics for Molten Berserker & Molten Firestorm:

You enter the arena after killing the group of mobs before the bridge, before anyone enters the arena place a <Item id="78978"/> at the Mistlock Singularity and open at the respawn place (entering the arena teleports everyone in), then you all `/gg` fast, revive and take the portal to the Mistlock Singularity. It only works well if you know where you respawn.

After entering the arena again you kill the _Molten Firestorm_, then use `/gg` the moment it's dead, this resets your cooldowns (after `/gg` the boss progress doesn't reset so you do not have to worry) and you go back into the arena and kill the _Molten Berserker_.

<Image src="./images/endboss.jpg" caption="The Molten Berserker & Molten Firestorm"/>
