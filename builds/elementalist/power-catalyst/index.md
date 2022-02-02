---
title: Power (Quick) Catalyst
rating: Good
role: Power Damage
profession: Elementalist
specialization: Catalyst
code: ''
classification:
  - 3
  - 3
  - 3
  - 3
  - 3
date: 2022-01-12T02:17:12.062Z
conditions:
  - Burning
  - Chilled
  - Vulnerability
Boons:
  - name: Quickness
    uptime: 100%
    variant: group
  - name: Might
    uptime:
    variant: party
hidden: true
---

<Warning>

This build guide is not complete, gear and sections may chage regularly as we explore the new elite spec and spend more time playing it in fractals!

</Warning>

The <Specialization name="Catalyst" text="Power Catalyst"/> is currently one of the strongest DPS builds for fractals. <Specialization name="Catalyst" text="Power Catalyst"/> provides <Boon name="Quickness"/>, conjures, <Condition name="Vulnerability"/>, and additional <Boon name="Might"/> through placing fire fields and blasting them. Also it is very useful for some T4 skips like Aetherblade, Cliffside, Thaumanova Reactor etc. thanks to high mobility and <Skill id="5536"/>.

Unfortunately this build is pretty squishy and besides the healing skill does not have any defensive abilities to mitigate damage or cleanse conditions, so high awareness is required. Special care needs to be taken on fractals with <Instability name="We Bleed Fire"/>.

This build has one of the most harder rotations in game which makes it enjoyable to play if given some dedication. The build benefits heavily from slaying potions and sigils such as <Item id="50082"/> and <Item name="Serpent Slaying" type="Sigil"/>.

<Divider text="Equipment"/>

<CharacterWithAr>

<Character title="DPS Catalyst 162 Agony Resistance" gear={{
  "profession": "Elementalist",
  "weight": "Light",
  "gear": [
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
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
    "Health": 13645,
    "Armor": 2410,
    "Power": 4449,
    "Precision": 2696,
    "Toughness": 1443,
    "Vitality": 1200,
    "Ferocity": 2172,
    "Condition Damage": 750,
    "Expertise": 0,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0,
    "Boon Duration": 0.162,
    "Critical Chance": 1.1276190476190475,
    "Critical Damage": 2.9480000000000004,
    "Burning Duration": 0.2,
    "Effective Power": 38436.30749393017,
    "Power DPS": 56300.23631378913,
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
    "Damage": 60481.368903539835,
    "Effective Health": 65441691.542288564,
    "Survivability": 33269.79742871813,
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
  }
}}>

Check the [gear optimizer](https://optimizer.discretize.eu) for more gear variants!

</Character>

<Character title="Quick Catalyst 162 Agony Resistance" gear={{
  "profession": "Elementalist",
  "weight": "Light",
  "gear": [
    "Berserker",
    "Berserker",
    "Diviner",
    "Berserker",
    "Berserker",
    "Diviner",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Diviner",
    "Diviner",
    "Diviner"
  ],
  "attributes": {
    "Health": 13645,
    "Armor": 2410,
    "Power": 4352,
    "Precision": 2551,
    "Toughness": 1443,
    "Vitality": 1200,
    "Ferocity": 2019,
    "Condition Damage": 750,
    "Expertise": 0,
    "Concentration": 758,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0,
    "Boon Duration": 0.5053333333333333,
    "Critical Chance": 1.0585714285714287,
    "Critical Damage": 2.846,
    "Burning Duration": 0.2,
    "Effective Power": 36297.40327570908,
    "Power DPS": 53167.2399155939,
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
    "Damage": 57348.3725053446,
    "Effective Health": 65441691.542288564,
    "Survivability": 33269.79742871813,
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
  }
}}>

Check the [gear optimizer](https://optimizer.discretize.eu) for more gear variants!

</Character>

<Character title="Quick Catalyst 222 Agony Resistance" gear={{
  "profession": "Elementalist",
  "weight": "Light",
  "gear": [
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Diviner",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Diviner",
    "Diviner",
    "Diviner"
  ],
  "attributes": {
    "Health": 13645,
    "Armor": 2500,
    "Power": 4371,
    "Precision": 2669,
    "Toughness": 1533,
    "Vitality": 1200,
    "Ferocity": 2048,
    "Condition Damage": 750,
    "Expertise": 0,
    "Concentration": 752,
    "Healing Power": 0,
    "Agony Resistance": 222,
    "Condition Duration": 0,
    "Boon Duration": 0.5013333333333333,
    "Critical Chance": 1.1147619047619048,
    "Critical Damage": 2.865333333333333,
    "Burning Duration": 0.2,
    "Effective Power": 36703.52136213809,
    "Power DPS": 53762.108302492605,
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
    "Damage": 57943.24089224331,
    "Effective Health": 67885572.13930349,
    "Survivability": 34512.23799659557,
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
  }
}}>

Check the [gear optimizer](https://optimizer.discretize.eu) for more gear variants!

</Character>

</CharacterWithAr>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1="Fire" traits1Selected="Burning Precision,Power Overwhelming,Persisting Flames" traits2="Air" traits2Selected="Ferocious Winds,Stormsoul,Bolt to the Heart" traits3="Catalyst" traits3Selected="Vicious Empowerment,Empowering Auras,Empowered Empowerment"/>
<Card title="Situational Traits">

|                                                          |                                                                                                                                                                       |
| -------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <Trait name="Sphere Specialist" size="big" disableText/> | If you need extra boon duration from your Jade Sphere (With this trait you can play the DPS gear)                                                                     |
| <Trait name="Raging Storm" size="big" disableText/>      | If you can't profit from <Trait name="Stormsoul"/> (e.g. Artsariiv, PuG Ensolyss).                                                                                    |
| <Trait name="One with Air" size="big" disableText/>      | Useful for skipping with <Effect name="Superspeed"/>, especially in combination with <Item name="Executioner Axe Toy"/> or <Item name="Endless Choya Pinata Tonic"/>. |

</Card>
<Card title="Defiance Bar Damage">

|                                                                                                                                                                           |                                          |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------- |
| <Skill name="Wind Storm" size="big" disableText/>                                                                                                                         | 200 with <Control name="Knockdown"/>     |
| <Skill name="Shock Blast" size="big" disableText/>                                                                                                                        | 150 with <Control name="Stun"/>          |
| <Skill name="Wind Blast" size="big" disableText/>                                                                                                                         | 232 with <Control name="Launch"/>        |
| <Skill name="Deep Freeze" size="big" disableText/>                                                                                                                        | 300 with <Control name="Stun"/>          |
| <Skill name="Magnetic Surge" size="big" disableText/>                                                                                                                     | 200 with <Control name="Daze"/>          |
| <Skill name="Magnetic Shield" size="big" disableText/>                                                                                                                    | 150 with <Control name="Pull"/>          |
| <Skill name="Chilling Crack" size="big" disableText/> <br/> <Skill name="Rain of Blows" size="big" disableText/> <br/> <Skill name="Twin Strike" size="big" disableText/> | 33 / s with <Condition name="Chilled"/>  |
| <Skill name="Crescent Wind" size="big" disableText/>                                                                                                                      | 20 / s with <Condition name="Weakness"/> |

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
| Utility                                                         | Another defensive utility skill granting a block and some barrier.                                                                                                                                                                                                                                                                         |
| <Skill name="Lightning Flash" size="big" disableText/>          | A teleport with a range of 900 units. Very important skill for certain skips, especially in combination with <Item name="White Mantle Portal Device"/>, useful in fractals like [Cliffside Fractal](/fractals/cliffside), [Aetherblade Fractal](/fractals/aetherblade) and [Underground Facility Fractal](/fractals/underground-facility). |
| <Skill name="Arcane Wave" size="big" disableText/>              | Also Useful to generate <Boon name="Might"/> with a fire field.                                                                                                                                                                                                                                                                            |
| <Skill name="Invigorating Air" size="big" disableText/>         | Useful for skipping with <Effect name="Superspeed"/>, especially in combination with <Item name="Executioner Axe Toy"/> or <Item name="Endless Choya Pinata Tonic"/>.                                                                                                                                                                      |

</Card>
</GridItem>
</Grid>

<Divider text="Rotation / Skill usage"/>

<Grid>
<GridItem xs="12" sm="6">
<Card title="Information">

Golem rotations out of the raid builds are generally suboptimal in fractals due to <Effect name="Exposed"/> and phases being much shorter compared to raids. The raid rotations are optimized for sustained DPS while in fractals a player needs the ability to adapt a rotation to the amount of time a group needs to finish a phase.\
For that reason you can find a video with openers, that are efficient to use here.
</Card>

<Card title="Catalyst Rotation">

<Video caption="" youtube=""/>
</Card>
</GridItem>

<GridItem xs="12" sm="6">
<Card title="Precasting">

If a _Mistlock Singularity_ is present you should precast boons and particular effects for better group performance.

</Card>
</GridItem>

<GridItem xs="12" sm="12">
<Card title="Rotation (Bolt to the Heart)">

This is very wrong, borrowed a kind of loop from one of Rouls benchmarks just to see if the skills are working.

</Card>

<Grid>
<GridItem sm="2">
<Skill name="Air Attunement" size="large" disableText/>
</GridItem>

<GridItem sm="10">

1.  <Skill name="Hurricane of Pain"/>

2.  <Skill id="63439"/>

3.  <Skill name="Grand Finale"/>

4.  <Skill name="Wind Slam"/> x 2

5.  <Skill name="Shock Blast"/>

</GridItem>

<GridItem sm="2">
<Skill name="Fire Attunement" size="large" disableText/>
</GridItem>

<GridItem sm="10">

1.  <Skill name="Triple Sear"/>

2.  <Skill name="Firestorm"/>

3.  <Skill name="Surging Flames"/>

4.  <Skill id="63458"/>

5.  <Skill name="Singeing Strike"/>

6.  <Skill name="Relentless Fire"/>

7.  <Skill name="Singeing Strike"/> x3

8.  <Skill name="Molten End"/>

9.  <Skill id="63458"/>

</GridItem>

<GridItem sm="2">
<Skill name="Water Attunement" size="large" disableText/>
</GridItem>

<GridItem sm="10">

1.  <Skill name="Rain of Blows"/>

2.  <Skill name="Cleansing Typhoon"/>

3.  <Skill name="Shattering Ice"/>

4.  <Skill name="Crashing Font"/>

</GridItem>

<GridItem sm="2">
<Skill name="Earth Attunement" size="large" disableText/>
</GridItem>

<GridItem sm="10">

1.  <Skill name="Ground Pound"/>

2.  <Skill name="Whirling Stones"/>

</GridItem>
</Grid>
</GridItem>
</Grid>
