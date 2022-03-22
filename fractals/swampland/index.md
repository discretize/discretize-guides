---
cycle: Night
date: 2022-03-22T23:58:09.496Z
title: Swampland
image: ./images/bloomhunger_spirit_onslaught.jpg
group: T4
api: 2892
bosses: 1
difficulties:
  - level: 77
    ar: 109
  - level: 89
    ar: 130
sigils:
  - id: 36053
  - id: 24868
consumables:
  - 78978
record:
  time: 3 min 01 sec
  by:
    - name: Invicta Luna
      tag: iV
  youtube:
    - id: zO5I1PKzSds
      name: Pineapple
      specialization: Guardian
    - id: lKBbJ6MKslE
      name: Tantor
      specialization: Guardian
    - id: PtANhScACaE
      name: Blackhawk
      specialization: Renegade
    - name: Delay
      specialization: Soulbeast
      id: GYiXAYsULHc
    - name: Roul
      specialization: Chronomancer
      id: pvUsltVLoJM
---

<Grid>
<GridItem sm="8">

## Running the wisps

Trigger the start event by walking to the three _Wisp Clefts_ in the South. Wait for three players to be ready at each of the randomly spawned Wisps, usually indicated by typing `ready` in chat. Count down to go and deliver the Wisps to the Clefts within 30 seconds while avoiding <Control name="Stun"/>, <Condition name="Immobile"/> and <Condition name="crippled"/> from the spike, wire and hunting traps on the ground.

Learn and practice to jump over the emerging walls, for nearly every wall there is an easy spot to skip over it.

The remaining two players can take the _Invigorator Rifle Prototypes_ from the ground and use `Skill 3` to grant <Boon name="Stability"/> to the Wisp runners. Note that it is possible to carry the Wisp from the farthest point without using any movement skills.

<Tabs>
<Tab specialization="renegade">

Use <Skill name="Impossible Odds"/> (<Skill name="Legendary Assassin Stance" disableText/>) for better mobility.
</Tab>

<Tab specialization="berserker">

Use <Skill id="14516"/> for better mobility. Also <Skill name="shake it off"/> comes in handy to cleanse conditions!
</Tab>

<Tab specialization="Weaver">

Equip <Skill id="5536"/> for mobility and <Skill id="5507"/> for a condition cleanse.
</Tab>

<Tab specialization="daredevil">

Use <Skill id="13038"/> or <Skill id="13002"/> for fast delivery.
</Tab>
</Tabs>

</GridItem>

<GridItem sm="4">

<MDImage src="images/the_three_wisp_clefts.jpg" caption="The three wisp clefts"/>

</GridItem>
</Grid>

---

## The Mossman

<Grid>
<GridItem sm="8">

In the passage, the Mossman is waiting to fight you. You can break his defiance bar while he is in <Effect name="Stealth"/> to force a reveal and make him <Effect name="Exposed"/>. Walk to the _Mistlock Singularity_ inside the Bloomhunger's lair to reset your cooldown and pre-stack some boons.

<Warning>

**Beware, there is a wisp that has <Effect name="Invulnerability"/> and can attack you, putting you in combat during pre-stack**!

</Warning>
</GridItem>

<GridItem sm="4">

<MDImage src="images/the_mossman.jpg" caption="The Mossman"/>

</GridItem>
</Grid>

---

<Grid>
<GridItem sm="8">

## Bloomhunger

Activate the encounter by placing the nearby Wisp into an empty Wisp Cleft. Bloomhunger (and all trash mobs) are only vulnerable inside the active Wisp Cleft area, additionally all players gain 100% increased endurance regeneration from it. The active area switches clockwise, move to the next position as soon as it decreases in size.

Bloomhunger gets <Boon name="Protection"/> from the flowers that start to fill up the battlefield and also inflict <Condition name="Poisoned"/> you, so cleave is appreciated for this fight.

When Bloomhunger casts _Poison Rain_, immediately break his defiance bar (especially at the start of the fight) and nuke him to 75%/50%/25% life. Avoid his _Leap_ and _Charge_ attacks to prevent being <Control name="Knockdown"/>ed.

### Spirit Onslaught <Label>75%, 50%</Label>

At 75% and 50% health, Bloomhunger will teleport to the middle and gain <Effect name="Invulnerability"/>. You will have to kill trash mobs inside the active Wisp Cleft to make him vulnerable again. Keep your pets and spirits close to yourself to prevent mobs from getting stuck. Kill the freshly spawned _Oakheart_ when you are out of mobs. Do not waste your time on Oakhearts while Bloomhunger is vulnerable.

Make sure to position yourself close to Bloomhunger before the phase ends to maximize the chance of him immediately jumping on you (and casting _Poison Rain_) instead of charging around.

### Running the wisps <Label>25%</Label>

Try to position yourself before Bloomhunger reaches 25% health. Again, he will teleport to the middle and become immune, but this time you have to carry four Wisps from northwest, northeast, southeast and southwest to their associated empty Wisp Cleft in the center area within 30 seconds. If you are near a Wisp before the phase begins, you can easily carry two Wisps before the time expires.

As soon as all four Wisp Clefts are activated, Bloomhunger gets vulnerable again and you can finish him off to complete the fractal.

<Tabs>
<Tab specialization="renegade">

Use <Item id="72872"/> to strip the boons from Bloomhunger with <Skill name="Darkrazor's Daring"/>.
</Tab>
<Tab specialization="Tempest">

Use <Specialization name="Tempest"/> for this fight and <Skill id="22572"/> for better cleave during the Spirit Onslaught phases.
</Tab>
<Tab specialization="Soulbeast">

Take <Skill id="12489"/> for pulsing condition cleanse! Great way the clean the huge stacks of <Condition name="Poisoned"/> at every phase. You can also take <Skill name="Bear stance"/> with the trait <Trait name="Leader of the Pack"/> to give the whole party condition cleanse.
</Tab>
<Tab specialization="Berserker">

Take Greatsword and <Skill name="Blood Reckoning"/> here for cleave!
</Tab>
</Tabs>

</GridItem>

<GridItem sm="4">

<MDImage src="images/bloomhunger.jpg" caption="Bloomhunger"/>

<MDImage src="images/bloomhunger_spirit_onslaught.jpg" caption="Bloomhunger during Spirit Onslaught"/>

</GridItem>
</Grid>
