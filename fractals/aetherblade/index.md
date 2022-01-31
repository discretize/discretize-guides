---
cycle: Day
potions:
  - id: 50082
  - id: 8887
    description: against the golems in the final room
date: 2022-01-31T15:38:02.821Z
title: Aetherblade
image: ./images/header.jpg
group: T4
api: 2948
bosses: 1
difficulties:
  - level: 96
    ar: 144
sigils:
  - id: 24615
  - id: 24868
  - id: 24672
    description: against the golems in the final room
record:
  time: 2 min 34 sec
  by:
    - name: Discretize
      tag: dT
  youtube:
    - id: PWoxS6xSSCc
      name: Seatek
      specialization: Renegade
    - id: yWlIQAVaSQA
      name: Delay
      specialization: Reaper
---

## Start (water tunnel) <Item id="50082" disableText/>

<Grid>
<GridItem sm="8">

You can stack <Effect name="Stealth"/> before entering the water to avoid that the mines explode. Clear the group of _Elite Aetherblades_ to open the door.

<Tabs>
<Tab specialization="thief">

Use the smoke field from <Skill id="13113"/> or <Skill name="Smoke Screen" profession="thief"/> or simply cast <Skill id="13117"/> to stack <Effect name="Stealth"/>.
</Tab>

<Tab specialization="ranger">

Use <Skill id="31568"/> from your Smokescale pet to stack <Effect name="Stealth"/> at the beginning.
</Tab>
<Tab specialization="Engineer">

<p>
<Skill id="30815"/> will provide <Effect name="Stealth"/> for the party, as well as a smoke field for the party to blast. You can also use <Skill id="5824"/> for a field to blast as well.
</p>

</Tab>
</Tabs>

</GridItem>

<GridItem sm="4">

<MDImage src="images/start.jpg" caption="Mines in the water tunnel"/>

</GridItem>
</Grid>

---

## Lasers <Item id="50082" disableText/>

<Grid>
<GridItem sm="9">

After the door opens, you enter a large area with two deathly laser puzzles.

The first one consists of a _moving laser square pattern_ and can be disabled by activating four consoles inside a small room at the end of it. Pressing a console applies <Condition name="Immobile"/> to you.

The second area is filled with _spinning lasers_. In exactly the same way as before, four consoles around the area have to be activated to disable the traps.

You don't need to kill a single mob and can bypass all traps with the following steps:

1.  One person (or more) teleports up to the first level and activates all four consoles using condition cleanses

2.  Everyone does `/gg` and resurrects immediately (you will spawn on the ramp up after the first console room)

3.  The team splits up to activate the second set of consoles (the spinning lasers won't be active if you're fast enough)

Speed is important here. Do not hesitate to `/gg` if you are certain the first console will be completed.

<Tabs>
<Tab specialization="Revenant">

<ProfessionVideo title="First puzzle skip" profession="Revenant" src="rePLyrDp3Pc"/>

To skip this part you are going to need a little jumping, along with damaging the Inquest with an AoE, non targetable skill like <Skill name="Shackling Wave"/>. **Once it comes down from the higher level**, you can use <Skill name="Phase Traversal"/> to reach the platform and go to the console room. Give yourself <Boon name="Resistance"/> with <Skill name="Pain Absorption"/> (<Skill name="Legendary Demon Stance" disableText/>) and disable the consoles.
</Tab>

<Tab specialization="elementalist">

<ProfessionVideo title="First puzzle skip" profession="Elementalist" src="OjUvCp2h_04" timestamp="45"/>

Teleport up to the first level with <Skill id="5536"/> and cast <Skill id="5507"/> to periodically clear <Condition name="Immobile"/> while activating the four consoles. Attune to x/<Skill id="5493" disableText/> for additional condition clear with <Skill id="5551"/>. <Specialization name="Revenant"/> can help giving <Boon name="Resistance"/> with <Skill name="Pain Absorption"/> (<Skill name="Legendary Demon Stance" disableText/>).

</Tab>

<Tab specialization="Guardian">

<ProfessionVideo title="First puzzle skip" profession="Guardian" src="MmJTsOhdQeo" timestamp="460"/>

Use <Skill name="Sword of Justice"/> upon the platform, then teleport to it with <Skill name="Merciful Intervention"/>. Equip conditions cleanses such as <Skill id="45460"/> or <Skill id="9187"/> and clear the consoles. The<Specialization name="Revenant"/> can help giving <Boon name="Resistance"/> with <Skill name="Pain Absorption"/> (<Skill name="Legendary Demon Stance" disableText/>).

</Tab>

<Tab specialization="Thief">

<ProfessionVideo title="First puzzle skip" profession="Thief" src="Alpgs_GaZV0" />

You can solo both the first and second room if you are fast enough. Use <Skill id="13002"/> or <Skill id="13025"/> to teleport and <Trait id="1964"/> or <Skill id="13062"/> as condition clears. <Specialization name="Revenant"/> can help giving <Boon name="Resistance"/> with <Skill name="Pain Absorption"/> (<Skill name="Legendary Demon Stance" disableText/>).

</Tab>
<Tab specialization="Necromancer">

Use <Skill id="10543"/> to teleport to the platform. Clear conditions with skills such as <Skill id="10685"/> or <Skill id="10609"/>. <Specialization name="Revenant"/> can help giving <Boon name="Resistance"/> with <Skill name="Pain Absorption"/> (<Skill name="Legendary Demon Stance" disableText/>).

</Tab>
</Tabs>

</GridItem>

<GridItem sm="3">

<MDImage src="images/moving_lasers.jpg" caption="The moving laser pattern"/>

<MDImage src="images/spinning_lasers.jpg" caption="The spinning lasers"/>

</GridItem>

</Grid>

---

## Breach the gate <Item id="50082" disableText/>

Kill the respawning enemies to fill the progress bar and open the gate. Avoid the dazing cannon shots and switch back your skills & traits if needed.

<Tabs>
<Tab specialization="Revenant">

You can <Skill name="Call to Anguish"/> most mobs to group them. If you have enough pulls in your group you should use <Skill name="Legendary Dwarf Stance"/> and <Skill name="Inspiring Reinforcement"/> to deny the <Control name="Daze"/>s from the air strikes constantly hitting you.
</Tab>

<Tab specialization="elementalist">

Stay in <Skill id="5492"/> after the last trash group for <Boon name="Might"/> stacking at Frizz.
</Tab>

<Tab specialization="Guardian">

You can use <Skill name="Binding Blade"/> and <TomeSkill name="Chapter 3: Heated Rebuke"/> to group the mobs.
</Tab>
<Tab specialization="Necromancer">

You can use <Skill name="spectral grasp"/> to group the mobs.
</Tab>
</Tabs>

---

<Grid>
<GridItem>

## Final room (Frizz) <Item id="8887" disableText/><Item id="24672" disableText/>

Talk to _Inspector Ellen Kiel_ to teleport your party into the final room. Stack <Boon name="Might"/> as soon as you are in.

Initially, Frizz and two Inquest approach. talk to Frizz to begin the fight. As soon as Frizz reaches 75%, he teleports to the middle and becomes invulnerable.

After about five seconds, the first _Aetherblade Golem_ wakes up and two _Small Lasers_ start spinning. You can jump over the small lasers by utilizing the elevated boxes around the arena.

When the first golem dies, the two _Small Lasers_ will disappear and two more _Aetherblade Golems_ wake up. _Large Lasers_ start spinning which you cannot completely bypass without <Effect name="Invulnerability"/>.

As soon as the two golems are dead, the two _Small Lasers_ will join the two _Large Lasers_ again and two final golems wake up. Kill the last golems to finish the fight.

If a golem walks through a laser, it powers up and blocks all attacks for a short time. Pay attention to their <Control name="Pull"/> attack, though it should not be a problem with high damage.
</GridItem>

<GridItem>

<MDImage src="images/frizz.jpg" caption="Frizz"/>

</GridItem>
</Grid>

<Tabs>
<Tab specialization="revenant">

Use <Skill name="Inspiring Reinforcement"/> in <Skill name="Legendary Dwarf Stance" disableText/> for <Boon name="Stability"/> against the _Lasers_ and _Small Lasers_.
</Tab>

<Tab specialization="Warrior">

Drop your banners in the very center of the arena. Using <Skill name="whirlwind attack"/> against the wall is very effective.
</Tab>

<Tab specialization="ranger">

Run an off-hand axe and use <Skill id="12638"/> to pull golems closer.
</Tab>

<Tab specialization="elementalist">

Use <Skill id="5697"/> against the golems next to a wall or box.
</Tab>
</Tabs>
