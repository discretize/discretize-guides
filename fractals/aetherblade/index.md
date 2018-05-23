---
title: "Aetherblade"
date: "2018-04-17"
image: "./images/header.jpg"
group: "T4"
api: 2948
bosses: 1
difficulties: [{ level: 96, ar: 143 }]
record: { time: "3:10", by: { name: "Happens", tag: "hP" }, youtube: [{ id: "VkfhMuvB4a0", name: "Guts", specialization: "Chronomancer" }]}
cycle: "Day"
potions: [{ id: 50082}, { id: 8887, description: "against the golems in the final room" }]
sigils: [{ id: 24615 }, { id: 24868 }, { id: 24672, description: "against the golems in the final room" }]
---

## Start (Water tunnel) <Item id="50082" text="false"/>

<Grid>
<Column>
You can stack <Effect name="stealth"/> before entering the water to cheat the exploding mines.    
Clear the group of *Elite Aetherblades* to open the door.

<Tips>
    <Tip specialization="thief">Use the smoke field from <Skill id="13113"/> or <Skill id="14184"/> or simply cast <Skill id="13117"/> to stack <Effect name="stealth"/>.</Tip>
    <Tip specialization="ranger">Use <Skill id="31568"/> from your Smokescale pet to stack <Effect name="stealth"/> at the beginning.</Tip>
</Tips>
</Column>

<Column width="5" compact>
<Image src="./images/start.jpg" title="Mines in the water tunnel" compact/>
</Column>
</Grid>

---

## Lasers <Item id="50082" text="false"/>

<Grid>
<Column>
After the door opens, you enter a large area with two deathly laser puzzles.

The first one consists of a _moving laser square pattern_ and can be disabled by activating four consoles inside a small room at the end of it. Pressing a console applies <Condition name="immobile"/> to you.

The second area is filled with _spinning lasers_. In exactly the same way as before, four consoles around the area have to be activated to disable the traps.

You don't need to kill a single mob and can bypass all traps with the following steps:

1. One person (or more) teleports up to the first level and activates all four consoles using condition cleanses
2. Everyone does `/gg` and resurrects immediately (you will spawn on the ramp up after the first console room)
3. The team splits up to activate the second set of consoles (the spinning lasers won't be active if you're fast enough)

<Tips>
    <Tip specialization="mesmer">Use <Skill id="29578"/> to teleport up and cast <Skill id="30305"/> or any Shatter skill with <Trait id="740"/> to remove <Condition name="immobile"/>.</Tip>
    <Tip specialization="elementalist">Teleport up to the first level with <Skill id="5536"/> and cast <Skill id="5507"/> to periodically clear <Condition name="immobile"/> while activating the four consoles.</Tip>
    <Tip specialization="daredevil">You can solo both the first and second room if you are fast enough. Use <Skill id="13002"/> or <Skill id="13025"/> to teleport and <Trait id="1964"/> or <Skill id="13062"/> as condition clears.</Tip>
</Tips>
</Column>

<Column width="6" compact>
<Image src="./images/moving_lasers.jpg" title="The moving laser pattern"/>
<Image src="./images/spinning_lasers.jpg" title="The spinning lasers"/>
</Column>
</Grid>

---

## Breach the gate <Item id="50082" text="false"/>

<Grid>
<Column>
Kill the respawning enemies to fill the progress bar and open the gate. Avoid the dazing cannon shots and switch back your skills & traits if needed.
</Column>

<Column>
<Tips>
    <Tip specialization="mesmer">Trait <Trait id="751"/> to use <Skill id="10363"/> more often.</Tip>
    <Tip specialization="elementalist">Stay in <Skill id="5492"/> after the last trash group for <Boon name="might"/> stacking at Frizz.</Tip>
</Tips>
</Column>
</Grid>

---

## <Boss red/> Final room (Frizz) <Item id="8887" text="false"/><Item id="24672" text="false"/>

<Grid>
<Column>
Talk to *Inspector Ellen Kiel* to teleport your party into the final room. Stack <Boon name="might"/> as soon as you are in.

Initially, there are Frizz and two Inquest enemies to fight. As soon as Frizz reaches 75%, he teleports to the middle and becomes invulnerable.

After about five seconds, the first _Aetherblade Golem_ wakes up and two _Small Lasers_ start spinning. You can jump over the small lasers by utilizing the elevated boxes around.

When the first golem dies, the two _Small Lasers_ will disappear and two more _Aetherblade Golems_ wake up. _Large Lasers_ start spinning which you cannot bypass without <Effect name="invulnerability"/>.

As soon as the two golems are dead, the two _Small Lasers_ will join the two large lasers again and two final golems wake up. Kill those to finish the fight.

If a golem walks through a laser, he powers up and blocks all attacks for a short time. Pay attention to their <Control name="pull"/> attack, though it should not be a problem with high damage.
</Column>

<Column compact>
<Image src="./images/frizz.jpg" title="Frizz"/>

<Tips>
    <Tip specialization="mesmer">Use <Skill id="10363"/> and <Skill id="30359"/> to grab the golems together. <Skill id="10192"/> makes yourself immune against both the small and large lasers.</Tip>
    <Tip specialization="ranger">Run an offhand axe and use <Skill id="12638"/> to pull golems closer.</Tip>
</Tips>
</Column>
</Grid>
