---
title: 'Thaumanova Reactor'
date: '2018-09-12'
image: './images/header.jpg'
group: 'T4'
api: 2967
bosses: 2
difficulties: [{ level: 84, ar: 122 }, { level: 97, ar: 145 }]
record:
  {
    time: '2:43',
    by: { name: 'Discretize', tag: 'dT' },
    youtube:
      [
        { id: 'QCele6YZeow', name: 'Metagame', specialization: 'Chronomancer' },
        { id: 'KP5bbAK9Dqs', name: 'Nimajeb', specialization: 'Warrior' },
        { id: '8jPj3qhxSek', name: 'Xarlor', specialization: 'Weaver' },
        { id: 'VErPFTieTk8', name: 'Hyperiel', specialization: 'Weaver' },
        { id: '4xRc7pEAfv8', name: 'The Way To God', specialization: 'Weaver' },
      ],
  }
cycle: 'Day'
sigils: [{ id: 24615 }, { id: 24868 }]
consumables: [78978, 49940]
---

<Grid>
<GridItem sm="8">
## Start
Activate the *Detonator* and wait for the <Specialization name="mesmer"/> to open a portal (in this case, stack <Boon name="might"/> in the vestibule) or walk up to the *Elite Flame Legion Fire Shaman*. Kill him, `/gg` to reset your cooldowns and split up to disable the four colliders.

<Tabs>
<Tab specialization="chronomancer">
Lay down a <Skill id="10197"/>, cast <Skill id="29578"/> with <Skill id="10200"/>, teleport up to the central area and open the portal.
</Tab>
</Tabs>
</GridItem>

<GridItem sm="4">
<Image src="./images/fire_shaman.jpg" caption="The Elite Flame Legion Fire Shaman"/>
</GridItem>
</Grid>

---

<Grid>
<GridItem sm="4">
<Image src="./images/turret_room.jpg" caption="Golems patrol in the turret room"/>
</GridItem>

<GridItem sm="8">
## Turret room <Label>South</Label>
This should be done by two support classes (usually the <Specialization name="warrior"/> and the <Specialization name="druid"/>). Learn the timing of the turret shots and jump or dodge over them. You can also take a *Safety Shield* from the beginning and use it to block shots for a short duration.

One person activates the console to the left <Label circular>1</Label> to grant the other person short access to the console at the right <Label circular>2</Label>.

Activating <Label circular>2</Label> enables short access to the two final consoles at <Label circular>3</Label>. You can bypass the <Condition name="immobile"/> from triggering them by standing exactly in the middle and pressing both buttons at the same time.
</GridItem>
</Grid>

---

<Grid>
<GridItem sm="8">
## Researcher Dormitories <Label>East</Label>
**Both DPS** should do this area immediately after the Elite Flame Legion Fire Shaman. Remember to destroy the Unstable Portals as well. Finishing this event in time will grant you a 10% damage boost for the endboss.

<Tabs>
<Tab specialization="elementalist">
Stack <Boon name="might"/> before the door opens and use <Skill id="5697"/> against the walls.
</Tab>
</Tabs>
</GridItem>

<GridItem sm="4">
<Image src="./images/researcher_dormitories.jpg" caption="The Researcher Dormitories"/>
</GridItem>
</Grid>

---

<Grid>
<GridItem sm="4">
<Image src="./images/superheated_room.jpg" caption="The Superheated Room"/>
</GridItem>

<GridItem sm="8">
## Superheated Room <Label>West</Label>
This is usually solo'ed by the <Specialization name="mesmer"/> using <Skill id="29578"/>, <Skill id="29830"/>, <Skill id="10200"/>, dodge jumps and heals from <Skill id="10213"/> and <Trait id="740"/> but other classes can do it as well.

[Search YouTube](https://www.youtube.com/results?search_query=heatroom+solo) for class-specific guides.
</GridItem>
</Grid>

---

<Grid>
<GridItem>
## Ooze Room: Subject 6 <Label>Northwest</Label>
Gather at Subject 6 after finishing the other three colliders. During the fight, small and large (at 75%/50/25% health) Oozes will spawn and move toward it slowly, restoring its health when they reach it. Subject 6 also has a easily distinguishable *Shield Form*, hitting him then will give him stacks of *Overload*. Reaching 20 stacks results in a party wipe.

There are two main tactics for killing it:

**Option 1 (easy):** Everyone goes AFK until Subject 6 blocks for the first time. After the blocking is over, nuke him without killing any Oozes.  
Requires high damage and you may have to wait a while as the blocking occurs at random times.

**Option 2 (coordinated):** The team nukes from the beginning ignoring the Oozes, but refrains from using crowd control effects and breaking his defiance bar. If Subject 6 starts blocking, immediately break the defiance bar using **unblockable** CC skills to bypass the Overload mechanic.
</GridItem>

<GridItem>
<Image src="./images/subject_6_block.jpg" caption="Subject 6 in block mode"/>

<Tabs>
<Tab specialization="warrior">
Equip <Skill id="14404"/> to make your CC skills unblockable.
</Tab>

<Tab specialization="thief">
Share <Skill id="13132"/> with 5 allies to deal 750 unblockable defiance bar damage.
</Tab>
</Tabs>
</GridItem>
</Grid>

---

## Thaumanova Anomaly

<Grid>
<GridItem sm="8">
After all four colliders are disabled, use `/gg` to reset any cooldowns and resurrect directly at the Thaumanova Anomaly console. Activate it to teleport up and stack <Boon name="might"/>.    
During the fight, try to stack as much as possible on one or two adjacent platforms but don't die from <Instability name="Social Awkwardness"/> (present on both difficulties).

Alternate the special _Hex Shield_ skill between players for her _Gaze_ attack (the beam dissolving the platforms) and the _Cosmic Instability_ debuff (occuring after 50% health). The _Flux Bomb_ debuff will also cause nearby platforms to disappear.
</GridItem>

<GridItem sm="4">
<Tabs>
<Tab specialization="chronomancer">
You can freely cast *Hex Shield* during <Skill id="29830"/> for an extra safe spot.
</Tab>
</Tabs>
</GridItem>
</Grid>

<Image src="./images/thaumanova_anomaly.jpg" caption="The Thaumanova Anomaly"/>
