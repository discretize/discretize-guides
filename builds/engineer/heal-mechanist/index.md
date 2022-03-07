---
title: Heal Alacrity Mechanist
rating: Good
role: Support
author: Parpage.9867
profession: Engineer
specialization: Mechanist
traits: []
conditions:
  - Burning
  - Confusion
  - Vulnerability
boons:
  - name: Alacrity
    uptime: 100%
    variant: party
  - name: Might
    uptime: 25 Stacks
    variant: Party
  - name: Fury
    uptime: 100%
    variant: Party
  - name: Regeneration
    uptime: 100%
    variant: Party
  - name: Vigor
    uptime: 100%
    variant: Party
  - name: Protection
    variant: Party
    uptime: On Demand
  - name: Stability
    uptime: On Demand
    variant: party
  - name: Aegis
    variant: party
    uptime: On Demand
code: '[&DQMvOR0nRiqEAAAAiAAAAJUBAAALGwAACRsAAAAAAAAAAAAAAAAAAAAAAAA=]'
classification:
  - 3
  - 3
  - 3
  - 3
  - 3
date: 2022-03-07T22:45:44.556Z
---

<Warning>

This build guide is not complete, gear and sections may chage regularly as we explore the new elite spec and spend more time playing it in fractals!

</Warning>

<Warning>

This build is very common in PuGs. It is part of a composition called PuG Meta. More info about this composition can be found [here](/guides/meta-explained). This build provides a high amount of boons and a lot of safety to the group via its healing. It therefore shines most in less experienced groups as well as when you have bad instabilities.

</Warning>

The <Specialization name="Mechanist" text="Heal Alacrity Mechanist" /> provides permanent <Boon name="Might" />, <Boon name="Alacrity" />, <Boon name="Fury" />, <Boon name="Regeneration" /> and <Boon name="Vigor" />, as well as some <Boon name="Protection" />. It also has access to a small amount of <Boon name="Aegis" />, <Boon name="Stability" /> througt <Skill id="63293"/>.

It offers a large of healing thanks to <Skill name="Med Kit"/>, <Skill name="Super Elixir"/>, permanent <Boon name="Regeneration"/> and <Boon name="Vigor"/> that you get from <Skill name="Energizing Slam"/>. Whenever you use a Jade Golem skill it pumps out as well a small amount of healing when traited with <Trait name="Soothing Detonation"/>. You can also provide a huge amount of barrier with <Skill id="63141"/>, <Skill name ="Barrier Signet"/> and <Skill name="Barrier Blast"/> making it nearly permanent.

<Divider text="Equipment"/>

<CharacterWithAr> 
<Character title="Heal Alacrity Mechanist" gear={{
  "profession": "Engineer",
  "weight": "medium",
  "gear": [
    "Harrier",
    "Harrier",
    "Harrier",
    "Harrier",
    "Harrier",
    "Harrier",
    "Minstrel",
    "Minstrel",
    "Minstrel",
    "Minstrel",
    "Minstrel",
    "Minstrel",
    "Minstrel",
    "Minstrel"
  ],
  "attributes": {
    "Health": 20182,
    "Armor": 3140,
    "Power": 2189,
    "Precision": 1225,
    "Toughness": 2022,
    "Vitality": 1426,
    "Ferocity": 150,
    "Condition Damage": 750,
    "Expertise": 0,
    "Concentration": 1276,
    "Healing Power": 1597,
    "Agony Resistance": 150,
    "Condition Duration": 0,
    "Boon Duration": 1.0006666666666666,
    "Critical Chance": 0.35714285714285715,
    "Critical Damage": 1.6,
    "Power Coefficient": 3000,
    "Burning Coefficient": 0,
    "Bleeding Coefficient": 0,
    "Poison Coefficient": 0,
    "Torment Coefficient": 0,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Outgoing Healing": 0.5535000000000001,
    "Effective Power": 3820.977678571429,
    "Power DPS": 4413.913375323175,
    "Bleeding Damage": 96.3125,
    "Bleeding Stacks": 0,
    "Bleeding DPS": 0,
    "Burning Damage": 355.421875,
    "Burning Stacks": 0,
    "Burning DPS": 0,
    "Confusion Damage": 118.665625,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 112.84375,
    "Poison Stacks": 0,
    "Poison DPS": 0,
    "Torment Damage": 142.74375,
    "Torment Stacks": 0,
    "Torment DPS": 0,
    "Damage": 4413.913375323175,
    "Effective Health": 135023980.73870477,
    "Survivability": 68644.62671006852,
    "Effective Healing": 1350.1468499999999,
    "Healing": 1350.1468499999999
  },
  "runeId": 24842,
  "runeName": "Monk",
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
    "weapon1MainType": "Mace",
    "weapon1MainSigil1Id": 74326,
    "weapon1OffType": "Shield",
    "weapon1offSigil1": "Paralyzation"
  },
  "consumables": {
    "foodId": 91690,
    "utilityId": 67528,
    "Infusion": "Healing +9 Agony Infusion"
  },
  "skills": {
    "healId": 5802,
    "utility1Id": 5838,
    "utility2Id": 5933,
    "utility3Id": 63262,
    "eliteId": 30800
  },
  "assumedBuffs": [
    {
      "id": "might",
      "type": "Boon"
    },
    {
      "id": "fury",
      "type": "Boon"
    },
    {
      "id": "protection",
      "type": "Boon"
    },
    {
      "id": "vulnerability",
      "type": "Condition"
    },
    {
      "id": "assassinsPresence",
      "gw2id": 1786,
      "type": "Trait"
    }
  ]
  }}
>
Note that this build variant is optimized for 150 agony resistance. If you have more Agony Resistance, feel free to swap out more Harrier pieces but make sure you are maintaining as close to 100% <Attribute name="boon duration"/> as possible. Check the [gear optimizer](https://optimizer.discretize.eu/) for more gear variants!
</Character>
</CharacterWithAr>

<Divider text="Default Build"/>

<Traits
  traits1="Inventions"
  traits1Selected="Over Shield, Soothing Detonation, Medical DIspersion Field"
  traits2="Alchemy"
  traits2Selected="Health Insurance, Comeback Cure, HGH"
  traits3="Mechanist"
  traits3Selected="Mech Arms: High-Impact Drivers, Mech Frame: Channeling Conduits, Mech Core: Barrier Engine"
/>

<Divider text="Situational Traits and Skills"/>
<Grid>
<GridItem sm="6">
<Card title="Common Utility Skills">

|                                                               |                                                                                                                     |
| ------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| <Skill name="Personal Battering Ram" size="big" disableText/> | Used to provide CC if no other utility is needed                                                                    |
| <Skill name="Shift Signet" size="big" disableText/>           | Allows extra mobility when running through trash mobs and provides a useful stunbreak                               |
| <Skill name="Thumper Turret" size="big" disableText/>         | Deals a large amount of CC. If using <Trait name="Experimental Turrets"/> will also share <Boon name="Protection"/> |
| <Skill name="Flame Turret" size="big" disableText/>           | If using <Trait name="Experimental Turrets"/> can be placed to share <Boon name="Might"/>                           |
| <Skill name="Rifle Turret" size="big" disableText/>           | If using <Trait name="Experimental Turrets"/> can be placed to share <Boon name="Fury"/>                            |
| <Skill name="Net Turret" size="big" disableText/>             | If using <Trait name="Experimental Turrets"/> can be placed to share <Boon name="Swiftness"/>                       |
| <Skill name="Rocket Turret" size="big" disableText/>          | If using <Trait name="Experimental Turrets"/> can be placed to share <Boon name="Resolution"/>                      |
| <Skill name="Tool Kit" size="big" disableText/>               | Has access to a block with <Skill id="5998"/> and a pull with <Skill id="5996"/>                                    |
| <Skill name="Throw Mine" size="big" disableText/>             | Can be used for some emergency boonstrip                                                                            |
| <Skill name="Overclock Signet" size="big" disableText/>       | Can be used to resummon your mech if <Skill name="Crash Down"/> is on cooldown                                      |

</Card>

</GridItem>

<GridItem sm="6">

<Card title="Situational Traits">

|                                                               |                                                                                                                        |
| ------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| <Trait name="Experimental Turrets" size="big" disableText/>   | Taken if you are running turret skills. Grant boons depending on the deployed skills.                                  |
| <Trait name="Purity of Purpose" size="big" disableText/>      | Useful on condi heavy and boonstrip heavy encounters to mass condi cleans and generate boons.                          |
| <Trait name="Gyroscopic Aceleration" size="big" disableText/> | In the <Specialization name="Scrapper"/> traitline. Useful to give <Effect name="superspeed"/> for movement and skips. |

</Card>

<Card title="Defiance Bar Damage">

| Skill                                  | Defiance Bar Damage                      |
| -------------------------------------- | ---------------------------------------- |
| <Skill name="Rocket Fist Prototype"/>  | 100 damage                               |
| <Skill name="Magnetic Inversion  "/>   | 150 damage                               |
| <Skill name="Throw Shield"/>           | 100 damage                               |
| <Skill name="Thump"/>                  | 232 damage (hits twice if not destroyed) |
| <Skill name="Personal Battering Ram"/> | 232 damage                               |
| <Skill name="Endothermic Shell"/>      | <Condition name="Chilled"/> 33/s damage  |
| <Skill name="Glob Shot"/>              | <Condition name="Crippled"/> 20/s damage |

</Card>
</GridItem>
</Grid>

<Divider text="Skill Explanations"/>

<Grid>
<GridItem sm="6">
<Card title="Mace">

- <Skill name="Barrier Blast" /> generates <Effect name="Barrier"/> in a 240 radius around you
- <Skill name="Energizing Slam" /> grants <Boon name="Regeneration"/> and <Boon name="Vigor"/> to allies, while applying some <Condition name="Vulnerability"/> to enemies.
- <Skill name="Rocket Fist Prototype" /> can be used for CC.

</Card>
</GridItem>

<GridItem sm="6">
<Card title="Shield">

- <Skill name="Magnetic Shield" /> offers projectile reflection and some CC when released though <Skill name="Magnetic Inversion  "/>.
- <Skill name="Static Shield" /> can be used as a long block which CCs any enemies attacking you. After the block is over it will cc with <Skill name="Throw Shield"/>.

</Card>
</GridItem>
</Grid>
