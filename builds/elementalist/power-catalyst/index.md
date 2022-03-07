---
classification:
  - 3
  - 3
  - 3
  - 3
  - 3
Boons:
  - name: Quickness
    uptime: 100%
    variant: group
  - name: Might
    uptime: null
    variant: party
title: Power (Quick) Catalyst
hidden: false
rating: Good
profession: Elementalist
specialization: Catalyst
code: '[&DQYfHSkbQyb+GgAAvgEAAPgaAADuGgAAlwAAAAAAAAAAAAAAAAAAAAAAAAA=]'
date: 2022-03-07T21:07:02.427Z
role: Power Damage
conditions:
  - Burning
  - Chilled
  - Vulnerability
---

<Warning>

This build guide is not complete, gear and sections may chage regularly as we explore the new elite spec and spend more time playing it in fractals!

</Warning>

The <Specialization name="Catalyst" text="Power Catalyst"/> is currently one of the strongest DPS builds for fractals. <Specialization name="Catalyst" text="Power Catalyst"/> provides <Boon name="Quickness"/>, conjures, <Condition name="Vulnerability"/>, and additional <Boon name="Might"/> through placing fire fields and blasting them. Also it is very useful for some T4 skips like Aetherblade, Cliffside, Thaumanova Reactor etc. thanks to high mobility and <Skill id="5536"/>.

Unfortunately this build is pretty squishy and besides the healing skill does not have any defensive abilities to mitigate damage or cleanse conditions, so high awareness is required. Special care needs to be taken on fractals with <Instability name="We Bleed Fire"/>.

This build has one of the most harder rotations in game which makes it enjoyable to play if given some dedication. The build benefits heavily from slaying potions and sigils such as <Item id="50082"/> and <Item name="Serpent Slaying" type="Sigil"/>.

<Divider text="Equipment"/>

<CharacterWithAr>
<Character title="162 Agony Resistance" gear={{
  "profession": "Elementalist",
  "weight": "Light",
  "gear": [
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Dragon",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker"
  ],
  "attributes": {
    "Health": 14175,
    "Armor": 2410,
    "Power": 4434,
    "Precision": 2669,
    "Toughness": 1443,
    "Vitality": 1253,
    "Ferocity": 2188,
    "Condition Damage": 750,
    "Expertise": 0,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0,
    "Boon Duration": 0.162,
    "Critical Chance": 1.1147619047619048,
    "Critical Damage": 2.958666666666667,
    "Power Coefficient": 3804,
    "Burning Coefficient": 6.67,
    "Bleeding Coefficient": 5.78,
    "Poison Coefficient": 0,
    "Torment Coefficient": 0,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Burning Duration": 0.2,
    "Effective Power": 38445.32192049862,
    "Power DPS": 56313.4403487011,
    "Bleeding Damage": 118.38816773437502,
    "Bleeding Stacks": 5.78,
    "Bleeding DPS": 684.2836095046877,
    "Burning Damage": 436.8876786914063,
    "Burning Stacks": 8.004,
    "Burning DPS": 3496.848980246016,
    "Confusion Damage": 145.86482457421877,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 138.70852488281253,
    "Poison Stacks": 0,
    "Poison DPS": 0,
    "Torment Damage": 175.46186650781252,
    "Torment Stacks": 0,
    "Torment DPS": 0,
    "Damage": 60494.572938451805,
    "Effective Health": 67983582.08955225,
    "Survivability": 34562.06511924365,
    "Effective Healing": 390,
    "Healing": 390
  },
  "runeId": 24836,
  "runeName": "Scholar",
  "infusions": [
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432
  ],
  "weapons": {
    "weapon1MainType": "Hammer",
    "weapon1MainSigil1Id": 24615,
    "weapon1MainSigil2Id": 24868
  },
  "consumables": {
    "foodId": 91805,
    "utilityId": 9443,
    "infusion": "Mighty +9 Agony Infusion"
  },
  "skills": {
    "healId": 62827,
    "utility1Id": 5734,
    "utility2Id": 62698,
    "utility3Id": 62965,
    "eliteId": 5516
  },
  "assumedBuffs": [{"id": "Might", "type": "Boon"}, {"id": "Fury", "type": "Boon"}, {"gw2id": 1786, "type": "Trait"}, {"gw2id": 12497, "type": "Skill"}]
}}>

Check the [gear optimizer](https://optimizer.discretize.eu) for more gear variants!

The stat selection will not change with higher AR / <Trait name="Spotter"/> / <Skill name="Banner of Discipline"/>.

If you want to provide <Boon name="Quickness"/> using <Trait name="Sphere Specialist"/>, you can use the gear below. However, due to the conversion from <Attribute name="Agony Resistance"/> to <Attribute name="Concentration"/> it is more dps increase to play <Trait name="Empowered Empowerment"/> and use diviner gear to make up boon duration.

</Character>
</CharacterWithAr>

<Divider text="Build"/>

<Grid>
  
<GridItem sm="7">

<Traits traits1="Fire" traits1Selected="Burning Precision,Power Overwhelming,Persisting Flames" traits2="Air" traits2Selected="Ferocious Winds,Stormsoul,Bolt to the Heart" traits3="Catalyst" traits3Selected="Vicious Empowerment,Empowering Auras,Empowered Empowerment"/>

<Card title="Situational Traits">

|                                                     |                                                                                                                                                                       |
| --------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <Trait name="Fresh Air" size="big" disableText/>    | Will have a greater burst if playing <Specialization name="Catalyst" text="Quick Catalyst"/>                                                                          |
| <Trait name="Raging Storm" size="big" disableText/> | If you can't profit from <Trait name="Stormsoul"/> (e.g. Artsariiv, PuG Ensolyss).                                                                                    |
| <Trait name="One with Air" size="big" disableText/> | Useful for skipping with <Effect name="Superspeed"/>, especially in combination with <Item name="Executioner Axe Toy"/> or <Item name="Endless Choya Piñata Tonic"/>. |

</Card>

<Card title="Defiance Bar Damage">

|                                                                                                                        |                                          |
| ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------------- |
| <Skill name="Wind Storm" size="big" disableText/>                                                                      | 200 with <Control name="Knockdown"/>     |
| <Skill name="Shock Blast" size="big" disableText/>                                                                     | 150 with <Control name="Stun"/>          |
| <Skill name="Wind Blast" size="big" disableText/>                                                                      | 232 with <Control name="Launch"/>        |
| <Skill name="Deep Freeze" size="big" disableText/>                                                                     | 300 with <Control name="Stun"/>          |
| <Skill id="5547" size="big" disableText/>                                                                              | 200 with <Control name="Daze"/>          |
| <Skill id="5747" size="big" disableText/>                                                                              | 150 with <Control name="Pull"/>          |
| <Skill name="Chilling Crack" size="big" disableText/> <br/> <Skill name="Rain of Blows" size="big" disableText/> <br/> | 33 / s with <Condition name="Chilled"/>  |
| <Skill name="Crescent Wind" size="big" disableText/>                                                                   | 20 / s with <Condition name="Weakness"/> |

</Card>

</GridItem>

<GridItem sm="5">

<Card title="Swap Weapons">

- Hammers with <Item name="Night" type="Sigil"/>
- Hammers with <Item name="Serpent Slaying" type="Sigil"/>
- Hammers with slaying sigils (see [Cheat Sheet](/guides/cheat-sheet))
- A staff to precast <Skill name="Meteor Shower"/> on some encounters
- Weapons to precast <Boon name="Might"/>

</Card>

<Card title="Situational Skills">

|                                                                 |                                                                                                                                                                                                                                                                                                                                            |
| --------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Heal                                                            |                                                                                                                                                                                                                                                                                                                                            |
| <Skill name="Arcane Brilliance" size="big" disableText/>        | Take it for additional <Boon name="Might"/> from fire fields.                                                                                                                                                                                                                                                                              |
| <Skill name="Signet of Restoration" size="big" disableText/>    | Helps with keeping up <Item name="scholar"/> when burst heal is not needed.                                                                                                                                                                                                                                                                |
| Offensive                                                       |                                                                                                                                                                                                                                                                                                                                            |
| <Skill name="Conjure Lightning Hammer" size="big" disableText/> | Good on larger hitboxes and fast phase times instead of <Skill name="Shattering Ice"/>. **Precast that skill everywhere where it is possible for DPS increase.**                                                                                                                                                                           |
| <Skill name="Conjure Frostbow" size="big" disableText/>         | Precast it for <Specialization name="Renegade"/> for additional cc on encounters like Siax.                                                                                                                                                                                                                                                |
| Defensive                                                       |                                                                                                                                                                                                                                                                                                                                            |
| <Skill name="Arcane Shield" size="big" disableText/>            | Provides three blocks for things like the console in [Aetherblade Fractal](/fractals/aetherblade).                                                                                                                                                                                                                                         |
| <Skill name="Armor of Earth" size="big" disableText/>           | Another defensive utility skill granting <Boon name="Protection"/> and <Boon name="Stability"/>.                                                                                                                                                                                                                                           |
| <Skill name="Fortified Earth" size="big" disableText/>          | Strong defence against pulsing damage like the Heat Room in [Thaumanova Reactor Fractal](/fractals/thaumanova-reactor).                                                                                                                                                                                                                    |
| <Skill name="Conjure Earth Shield" size="big" disableText/>     | Precasted for additional cc on encounters like Artsariiv.                                                                                                                                                                                                                                                                                  |
| Utility                                                         |                                                                                                                                                                                                                                                                                                                                            |
| <Skill name="Lightning Flash" size="big" disableText/>          | A teleport with a range of 900 units. Very important skill for certain skips, especially in combination with <Item name="White Mantle Portal Device"/>, useful in fractals like [Cliffside Fractal](/fractals/cliffside), [Aetherblade Fractal](/fractals/aetherblade) and [Underground Facility Fractal](/fractals/underground-facility). |
| <Skill name="Arcane Wave" size="big" disableText/>              | Also Useful to generate <Boon name="Might"/> with a fire field.                                                                                                                                                                                                                                                                            |
| <Skill name="Invigorating Air" size="big" disableText/>         | Useful for skipping with <Effect name="Superspeed"/>, especially in combination with <Item name="executioneraxetoy"/> or <Item name="endlesschoyapiatatonic"/>.                                                                                                                                                                            |

</Card>

</GridItem>
</Grid>

<Divider text="Rotation / Skill usage"/>

<Grid>
<GridItem xs="12" sm="6">

<Card title="Information">

Golem rotations out of the raid builds are generally suboptimal in fractals due to <Effect name="Exposed"/> and phases being much shorter compared to raids. The raid rotations are optimized for sustained DPS while in fractals a player needs the ability to adapt a rotation to the amount of time a group needs to finish a phase.
</Card>

</GridItem>

<GridItem xs="12" sm="6">

<Card title="Precasting">

If a _Mistlock Singularity_ is present you should precast boons and particular effects for better group performance.

- Start on <Skill id="5492"/> and cast <Skill id="63458"/> to provide a fire field.
- Blast it using <Skill name="Molten End"/>, then attune to <Skill id="5495"/> and cast <Skill name="Ground Pound"/>, then attune to <Skill id="5494"/> and cast <Skill name="Shock Blast"/>.
- Precast <Skill id="5506"/> and <Skill id="5635"/>, and swap back to your regular utility skills
- Equip a staff and cast <Skill id="5516"/> while attuning to <Skill id="5492"/>.
- Take the _Mistlock Singularity_.

It is recommended to use separate precast templates to cast different utility and weapon skills.

</Card>

<Card title="Catalyst Rotation">

<Video caption="" youtube=""/>
</Card>

</GridItem>
</Grid>
