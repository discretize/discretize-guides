---
title: 'Molten Boss'
date: '2018-04-17'
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

## Start area <Item id="50082" text="false"/>

<Grid>
<GridItem>
Skip the first two bridges, you can use <Effect name="stealth"/> but since it is difficult to reapply just stay together while moving.

You will reach an area with two _Molten Protectors_, drag them with you to the next group of mobs where you can't proceed. Kill everything there and the bridge to the Molten Effigy will come down.

Note that the Molten Protectors cast a zone which grants enemies inside <Effect name="invulnerability"/> (recognizable by an electric beam). Therefore, killing and controlling the Molten Protectors is your highest priority throughout the entire fractal.

<Tabs>
    <Tab specialization="spellbreaker">As a lot of boons are present in this fractal, Spellbreaker is the recommended build for warriors.</Tab>
</Tabs>
</GridItem>
<GridItem sm="4">
<Image src="./images/start.jpg" caption="The long way down" compact/>
</GridItem>
</Grid>

---

## <Boss/> Molten Effigy <Item id="50082" text="false"/>

Stack <Boon name="might"/> before moving on to the Molten Effigy.

There is another single Molten Protector which needs to be focused before switching to the boss. Use interrupts or reflects against the Effigy's _Firestorm_ attack, pay attention to the _Charge_ (large arrow) and _Shockwave_ attacks and cleave mobs around if possible.

The moment you killed the Effigy, you can continue to the next trash group. All following groups of mobs are progress-blocking, clear them to make it to the final area. Molten Protectors have the highest priority and Smoke Shamans are second to them (they apply <Effect name="stealth"/> to surrounding enemies). You can `/gg` once directly before the end boss if necessary.

<Image src="./images/molten_effigy.jpg" caption="The Molten Effigy"/>

---

## <Boss red/> Molten Berserker & Molten Firestorm <Item id="50082" text="false"/>

When you walk onto the end boss area, a group-wide <Effect name="agony"/> effect will be applied and put you in combat. As soon as it ends, use the small time before boss starts to stack <Boon name="might"/>.

Kill the _Molten Firestorm_ first and pay attention to the AoEs and _Shockwave_ attack. Reflects are useful here as well (especially if you're running without a healer). The _Molten Berserker_ will heal to full health after his comrade is dead, kill him afterwards to finish the fractal.

Do not walk into the hitboxes of the two bosses to prevent them from moving out of damaging fields.

<Image src="./images/endboss.jpg" caption="The Molten Berserker & Molten Firestorm"/>
