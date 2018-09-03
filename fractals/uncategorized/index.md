---
title: 'Uncategorized'
date: '2018-04-17'
image: './images/header.jpg'
group: 'T4'
api: 2939
bosses: 3
difficulties: [{ level: 79, ar: 113 }, { level: 91, ar: 134 }]
record:
  {
    time: '3:16',
    by: { name: 'Happens', tag: 'hP' },
    youtube:
      [
        { id: 'fMB69jScHWg', name: 'Never Moa', specialization: 'Tempest' },
        { id: '1HptYqPzPZE', name: 'Midnightz', specialization: 'Tempest' },
      ],
  }
cycle: 'Day'
potions: [{ id: 8887, description: 'for Old Tom and the Raving Asura' }]
sigils:
  [
    { id: 24868 },
    { id: 24615 },
    { id: 24672, description: 'for Old Tom and the Raving Asura' },
  ]
consumables: [78978, 49940, 8764, 8801]
---

<Grid>
<GridItem>
## Start

**Option 1 (recommended):** The whole party stacks <Effect name="stealth"/> and skips together until the holding area. If a single Harpy spawned immediately at the begin, you can kill it before stealthing.

**Option 2:** The <Specialization name="mesmer"/> (or anyone with a <Item id="78978"/>) skips alone and teleports the team to the holding area.

## Holding Area

Stack <Boon name="might"/> before destroying the _Power Generator_, then kill the Rabbit, the Bandit Saboteur, the Flame Legion Fire Shaman and finally the Ettin. Try to keep all mobs together on the Flame Legion Fire Shaman to maximize cleave damage, but do not get caught in the Ettin's _Massive Smash_ attack. Reflects are strong here as well, especially against the Fire Shaman's projectiles.

<Tabs>
<Tab specialization="elementalist">
If positioned correctly, you can <Skill id="5697"/> against the wall.
</Tab>
</Tabs>
</GridItem>

<GridItem sm="5">
<Tabs>
<Tab specialization="mesmer">
You can give easy party <Effect name="stealth"/> with <Skill id="10245"/> and <Trait id="674"/> at the cost of a elite skill slot.
</Tab>

<Tab specialization="thief">
Use the smoke field from <Skill id="13113"/> or <Skill id="14184"/> or simply cast <Skill id="13117"/> to stack <Effect name="stealth"/>.    
        <Skill id="14184"/> is also useful against the Holding Area bosses.
</Tab>

<Tab specialization="ranger">
Use <Skill id="31568"/> from your Smokescale pet to stack <Effect name="stealth"/>.
</Tab>
</Tabs>

<Image src="./images/harpies_jp.jpg" caption="Harpies protect their jumping puzzle"/>
</GridItem>
</Grid>

---

<Grid>
<GridItem>
## Pulsing Orbs

Walk past the three Harpies (no <Effect name="stealth"/> needed) and run up the ramp towards Old Tom. You can dodge through or reflect the pulsing orbs and even skip the last part by walking on the left wall.
</GridItem>

<GridItem sm="4">
<Image src="./images/pulsing_orbs.jpg" caption="The ramp up" compact/>
</GridItem>

<GridItem>
## Old Tom <Item id="8887" disableText/><Item id="24672" disableText/>

Stack <Boon name="might"/> before Old Tom and simply nuke him down. Be careful with <Effect name="agony"/> and try to let Pets and Illusions soak the green projectiles when his defiance bar is not broken.

<Image src="./images/old_tom.jpg" caption="Old Tom"/>
</GridItem>
<GridItem>
<Tabs>
<Tab specialization="mesmer">
**Pro tip**: Immediately after the holding area, use <Item id="49940"/> and <Skill id="10200"/> up to the upper level from below. Take [this shortcut](https://youtu.be/xFfz0Erv-5c?t=34s) to the Raving Asura and place a portal before jumping down and killing Old Tom. Open the portal afterwards and don't forget to trigger the "Reach the top" checkpoint to prevent the fractal from bugging.    
        **Actually, anyone can do this and trigger the checkpoint.**
</Tab>

<Tab specialization="ranger">
A <Skill id="12489"/> traited with <Trait id="1075"/> almost nullifies the Poison from the green projectiles, it also helps against <Instability name="Afflicted"/>.
</Tab>

<Tab specialization="guardian">
You can use <Skill id="30783"/> to bypass the jumping puzzle.    
        Other skills that work are <Skill id="9080"/>, <Skill id="14366"/> or <Skill id="45230"/> but those require some aiming.
</Tab>
</Tabs>
</GridItem>
</Grid>

---

## Raving Asura <Item id="8887" disableText/><Item id="24672" disableText/>

<Grid>
<GridItem>
If noone did a portal to above, stack <Effect name="stealth"/> before the Harpies and jump to the top. As soon as someone reaches the top level, you can safely use `/gg` and resurrect at the checkpoint there. Use reflects against the *Lightning Bolts* from the Raving Asura (or let others soak them) and kill the four golems to finish the fractal.

Note that the golems are resistent to pulls since a recent patch.
</GridItem>
<GridItem sm="5">
<Image src="./images/raving_asura.jpg" caption="The Raving Asura and his entourage" compact/>
</GridItem>
</Grid>
