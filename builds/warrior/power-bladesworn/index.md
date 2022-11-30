---
title: Power Bladesworn
hidden: false
archive: false
rating: Good
role: Power Damage
profession: Warrior
specialization: BLadesworn
skills: null
traits: null
conditions:
  - name: Vulnerability
    uptime: 7 stacks
boons:
  - name: Quickness
    uptime: '33%'
    variant: Party
  - name: Might
    uptime: '3 Stacks '
    variant: Party
  - name: Might
    uptime: '8 Stacks '
    variant: Party (Using Empower Allies)
code: '[&DQIEHwsVRCumAAAA8hoAAP0aCgAAAKIB/BqcAAAAAAAAAAAAAAAAAAAAAAA=]'
classification:
  - 4
  - 5
  - 3
  - 3
  - 4
date: 2022-07-31T10:54:54.519Z
---

The <Specialization text="Power Bladesworn" name="Bladesworn"/> is a strong build for <Specialization name="Warrior"/> in fractals. It has more initial burst than <Specialization text="Power Berserker" name="Berserker"/> thanks to <Skill name="Dragon Trigger" />, but loses sustained damage in favor of short damage spikes. Along with this <Specialization text="Power Bladesworn" name="Bladesworn"/> provides a lot of boon support to a party, sharing <Boon name="Might"/> and <Boon name="Quickness"/> from traits along with optional utility skills like <Skill name="Forgreatjustice"/> which can carry a party with low boon uptime by providing 12 stacks of <Boon name="Might"/> (becomes 20 stacks, taking into account <Boon name="Might"/> from traits) and a high <Boon name="Fury"/> uptime.

The <Specialization text="Power Bladesworn" name="Bladesworn"/> is one of the harder builds to play in fractals dues to its quick rotation, relying on maintaining damage modifiers and your highest damaging skill locking you in place, requiring good positioning during fights. Furthermore, the build benefits from damage modifying sigils like <Item name="Impact" type="Sigil"/> as well as slaying potions such as <Item name="Powerful Potion of Slaying Scarlets Armies"/>.

<Divider text="Equipment" />

<Divider text="Build" />

<Grid>
<GridItem sm="7">
<Traits traits1Id="4" traits1="Strength" traits1Selected="Peak Performance,Great Fortitude,Berserkers Power" traits2="Tactics" traits2Selected="Leg Specialist,Warriors Cunning,Martial Cadence" traits3Id="68" traits3="Bladesworn" traits3Selected="Unseen Sword,Fierce as Fire,Unyielding Dragon"/>

<Card title="Extra Weapons">

- Axes and Pistols with <Item name="Night" type="Sigil" disableText/>, <Item name="Serpent Slaying" type="Sigil" disableText/> and other slaying sigils.
- Warhorn for pre-stacking <Boon name="Might"/>
- Torch (for a fire field).

</Card>
</GridItem>

<GridItem sm="5">
<Card title="Situational Skills">
If you need to swap a skill, you should first swap out <Skill id="68085"/>, however this is a significant DPS loss.
|                                                           |                                                                                                                                                                                   |
| --------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <Skill name="To The Limit" size="big" disableText/>       | Alternative heal for extra Flow generation.                                                      |
| <Skill name="For Great Justice!" size="big" disableText/> | If your groups <Boon name="Might"/> is not 25, take <Skill name="Forgreatjustice"/>. It is a bigger DPS increase than <Skill name="signetofmight"/>!                              |
| <Skill name="Signet of fury" size="big" disableText/>     | Grants <Attribute name="Precision" text="180 Precision"/> passively; grants 360 <Attribute name="Precision"/> and <Attribute name="Ferocity"/> on use as well as additional Flow. USed for extra burst in short phases |
| <Skill name="onmymark" size="big" disableText/>           | Can be used to pull Krait from the side altars at the Nightmare CM fractal.                                                                                                       |
| <Skill name="featherfootgrace" size="big" disableText/>   | Grants <Effect name="Superspeed"/> for skips.                                                                                                                                     |
| <Skill name="bannerofdefense" size="big" disableText/>        | Can be used to provide <Boon name="Aegis"/> to your party.                                                                                                                                    |

</Card>
<Card title="CC skills">

|                                   |                                                                                 |
| --------------------------------- | ------------------------------------------------------------------------------- |
| <Skill name="bullscharge"/>       | 300 damage                                                                      |
| <Skill id="14502"/>               | 150 damage                                                                      |
| <Skill name="Dragonslash-Force"/> | 50 damage per charge up to 10 charges (minimum 100 damage - maximum 500 damage) |

</Card>
</GridItem>
</Grid>

<Divider text="Rotation / Skill usage" />

<Grid>
<GridItem xs="12" sm="6">
<Card title="Information">

Golem rotations out of the raid builds are generally suboptimal in fractals due to <Effect name="Exposed"/> and phases being much shorter compared to raids. The raid rotations are optimized for sustained DPS while in fractals a player needs the ability to adapt a rotation to the amount of time a group needs to finish a phase.

- Casting <Skill name="Mending"/> for <Trait name="Peak Performance"/> is only a DPS gain if you can’t be hitting something else, use it right before the start of DPS phases but only use it during if you need the heal.
- <Skill name="Triggerguard"/> and <Skill name="Flicker Step"/> in <Skill name="Dragon Trigger"/> are used in the rotation, but should be saved to use to deal with mechanics if needed.

</Card>
</GridItem>

<GridItem xs="12" sm="6">

<Card title="Precasting">

- Stack <Boon name="Might"/>:
  - Use both charges of <Skill name="For Great Justice!"/>.
  - Use <Skill name="Call of Valor"/> and <Skill id="14393"/> on offhand Warhorn to blast <Boon name="Might"/>.
- Precast damage skills:
  - Cast <Skill name="Mending"/> and <Skill id="68085"/> immediately before the boss becomes vulnerable.
  - Precast <Trait name="Fierce as Fire"/> stacks using ammo skills.
  - Precast flow using <Skill name="Flow Stabilizer"/> and <Skill name="To the Limit"/>.
  - Use <Skill name="Tactical Reload"/> to reload precasted ammo and charge <Skill name="Dragon Trigger"/> quicker.

</Card>

</GridItem>

<GridItem xs="12" sm="6">

<Card title="Opener">

Make sure to cast <Skill name="Tactical Reload"/> and <Skill id="68085"/> before entering combat.

1. <Skill name="Dragons Roar"/> (Pistol 5)
2. <Skill name="Gunstinger"/> (Pistol 4)
3. <Skill name="Cyclone Axe" /> (Axe 2)
4. Charge <Skill name="Dragon Trigger"/>
5. <Skill name="Triggerguard"/> in <Skill name="Dragon Trigger"/> (Skill 4)
6. <Skill name="Dragon Slash-Force"/> in <Skill name="Dragon Trigger"/> (Skill 1)
7. <Skill name="Dragonspike Mine"/>
8. Charge <Skill name="Dragon Trigger"/>
9. <Skill name="Flicker Step"/> in <Skill name="Dragon Trigger"/> (Skill 5)
10. <Skill name="Triggerguard"/> in <Skill name="Dragon Trigger"/> (Skill 4)
11. <Skill name="Dragon Slash-Force"/> in <Skill name="Dragon Trigger"/> (Skill 1)

</Card>

</GridItem>

<GridItem xs="12" sm="6">
<Card title="Golem Rotation">

<Video youtube="yNXwsIXsakg" caption="by Evo"/>
</Card>
</GridItem>
</Grid>
