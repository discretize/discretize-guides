---
title: Condi Willbender
hidden: false
archive: false
rating: Good
role: Condi Damage
profession: Guardian
specialization: Willbender
skills: null
conditions:
  - name: Burning
  - name: Vulnerability
    uptime: 12 stacks (using Sword of Justice)
boons:
  - name: Might
    uptime: 2 stacks
    variant: party
code: '[&DQEQGi4XQSUmDwAA2BoAAEwBTAFIAUgB6RoAAAAAAAAAAAAAAAAAAAAAAAA=]'
classification:
  - 3
  - 4
  - 3
  - 2
  - 3
date: 2022-04-29T09:41:26.581Z
---

The <Specialization name="Willbender" text="Condition Willbender"/> is a strong build for guardian. It has high damage, CC, and mobility making it a strong choice for all groups. It also can easily slot more supportive utility skills allowing you to provide yourself and your party with <Boon name="Stability"/>, <Boon name="Aegis"/> and reflects.

<Divider text="Equipment"/>

<CharacterWithAr> 
<Character title="162 Agony Resistance" gear={{
  "profession": "Guardian",
  "weight": "Heavy",
  "gear": [
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Sinister",
    "Sinister",
    "Viper",
    "Sinister",
    "Sinister",
    "Sinister",
    "Viper",
    "Viper"
  ],
  "attributes": {
    "Health": 14460,
    "Armor": 2514,
    "Power": 2909,
    "Precision": 2085,
    "Toughness": 1243,
    "Vitality": 1150,
    "Ferocity": 300,
    "Condition Damage": 2947,
    "Expertise": 451,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0.30066666666666664,
    "Boon Duration": 0.162,
    "Critical Chance": 0.8666666666666666,
    "Critical Damage": 1.7,
    "Power Coefficient": 2715,
    "Burning Coefficient": 14.65,
    "Bleeding Coefficient": 1.14,
    "Poison Coefficient": 0,
    "Torment Coefficient": 1.33,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Burning Duration": 0.7,
    "Maximum Health": 0.10000000000000009,
    "Resolution Duration": 0.25,
    "Effective Power": 10976.97384612,
    "Power DPS": 11475.735075939852,
    "Bleeding Damage": 603.91575,
    "Bleeding Stacks": 1.4827599999999999,
    "Bleeding DPS": 895.46211747,
    "Burning Damage": 2053.206478125,
    "Burning Stacks": 29.3,
    "Burning DPS": 60158.949809062506,
    "Confusion Damage": 711.2093625,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 638.847,
    "Poison Stacks": 0,
    "Poison DPS": 0,
    "Torment Damage": 902.2286250000001,
    "Torment Stacks": 1.7298866666666668,
    "Torment DPS": 1560.7532686725003,
    "Damage": 74090.90027114486,
    "Effective Health": 72343164.17910449,
    "Survivability": 36778.426120541175,
    "Effective Healing": 390,
    "Healing": 390
  },
  "runeId": 24765,
  "runeName": "Balthazar",
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
      "weapon1MainType": "Sword",
      "weapon1MainSigil1Id": 48911,
      "weapon1OffType": "Torch",
      "weapon1OffSigilId": 44944,
      "weapon2MainType": "Scepter",
      "weapon2MainSigil1Id": 24605
    },
  "consumables": {
      "foodId": 91878,
      "utility": "toxic-focusing-crystal",
      "infusion": "Malign +9 Agony Infusion"
  },
  "skills": {
    "healId": 62622,
    "utility1Id": 62565,
    "utility2Id": 9187,
    "eliteId": 62561
  },
  "assumedBuffs": [{ "type": "Item", "gw2id": 79722 }, { "type": "Item", "gw2id": 96613 }, {"id": "Might", "type": "Boon"}, {"id": "Fury", "type": "Boon"}, {"gw2id": 1786, "type": "Trait"}, {"gw2id": 9151, "type": "Skill"}, {"id": "jade-bot-per-tier", "value": 10, "type": "Text"}]
}} 
>

Many different gear variations can be run on this build that varies damage-wise in certain situations. Overall when considering <Effect name="Exposed"/> and the fact you can share gear with <Specialization name="Firebrand" text ="Condi Firebrand"/> makes the setup below the best option for fractals. If you want to optimize for different situations you can use our [gear optimizer](https://optimizer.discretize.eu/).

This build also makes use of a <Item id="96613"/> gaining <Attribute name="Condition Damage"/> from <Trait name="Power of the Virtuous"/>. Removing this does not change the gear!

If you need to swap a utility out, <Skill name="Signet of Wrath"/> is a minor DPS increase and should be swapped out when other skills suit the encounter better.
You will want the following weapons to swap to during fractal runs:

- Greatsword for pulling adds in Nightmare CM after MAMA and some T4s
- A staff for <Boon name="Might"/> pre-stacking.
- Greatsword can also be run as an alternative to Sword offering extra cleave and a useful leap

</Character> 
</CharacterWithAr>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1="Radiance" traits1Selected="Right-Hand Strength,Radiant Fire,Amplified Wrath" traits2="Virtues" traits2Selected="masterofconsecrations,inspiringvirtue,permeatingwrath" traits3="Willbender" traits3Selected="Searing Pact,Restorative Virtues,Tyrants Momentum"/>

<Card title="Defiance Bar Damage">

|                                               |                                                                                |
| --------------------------------------------- | ------------------------------------------------------------------------------ |
| <Skill name="Hammer of Wisdom"/>              | 200 damage                                                                     |
| <Skill name="Sanctuary"/>                     | 1050 damage over 7 seconds (thanks to <Trait name="Master of Consecrations"/>) |
| <Skill name="Chains of light"/>               | <Condition name="Immobile"/> 50/s                                              |
| <Skill name="Heavens Palm"/>                  | 400 damage (Knockdown) <br/> 150 damage (Knockback)                            |
| <Skill id="9226"/> (after <Skill id="9147"/>) | 150 damage                                                                     |

</Card>
</GridItem>

<GridItem sm="5">
<Card title="Situational Skills">

|                                                         |                                                                                     |
| ------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| <Skill name="Sword of Justice" size="big" disableText/> | Used as a source of <Condition name="Vulnerability"/>                               |
| <Skill name="Sanctuary" size="big" disableText/>        | Huge CC and projectile destruction.                                                 |
| <Skill name="Signet of Wrath" size="big" disableText/>  | Taken as a 3rd utility if no other skill is needed.                                 |
| <Skill id="9246" size="big" disableText/>               | A 1,200 range teleport to an ally.                                                  |
| <Skill name="Hallowed Ground" size="big" disableText/>  | When <Boon name="Stability"/> is needed.                                            |
| <Skill id="9153" size="big" disableText/>               | When <Boon name="Stability"/> or a stunbreak is needed.                             |
| <Skill name="Advance" size="big" disableText/>          | When <Boon name="Aegis"/> is needed.                                                |
| <Skill id="9125" size="big" disableText/>               | Deals an additional 200 defiance bar damage.                                        |
| <Skill id="9251" size="big" disableText/>               | A stationary reflect lasting for 10 seconds.                                        |
| <Skill id="9247" size="big" disableText/>               | A 1200 range teleport to an enemy.                                                  |
| <Skill name="renewed focus" size="big" disableText/>    | Recharges all virtue skills, grants <Effect name="Invulnerability"/> for 3 seconds. |

</Card>
</GridItem>
</Grid>

<Divider text="Rotation / Skill usage"/>

<Grid>
<GridItem sm="6">
<Card title="Skill Priority">

In general for fractals there is no set rotation for <Specialization name="Willbender" text="Condi Willbender"/>. Instead, you want to adapt your rotation depending on phase length and cooldowns. You can use the skill priority list below to see what your most important skills are. In general though make sure to prioritise using <Skill name="Rushing Justice"/> to maintain <Skill id="62618"/> and aim for maximum uptime of <Trait name="lethal tempo"/>.

1. <Skill name="Rushing Justice"/>
2. <Skill name="Purging Flames"/>
3. <Skill name="Symbol of Punishment"/>
4. <Skill name="Whirling Light"/>
5. <Skill name="Zealot's Flame"/>, <Skill name="Zealot's Fire"/>
6. <Skill name="Symbol of Blades"/>
7. <Skill name="Rushing Justice"/> with <Skill id="62618"/> already active
8. <Skill name="Zealot's Defense"/>
9. <Skill name="Cleansing Flame"/>
10. <Skill name="Sword of Wrath"/>, <Skill name="Sword Arc"/>, <Skill name="Sword Wave"/>
11. <Skill name="Orb of Wrath"/>

</Card>
<Card title="Precasting">

1.  Use <Skill name="hallowedground"/>
2.  Blast a fire field with <Skill name="holystrike"/> and/or <Skill name="Hammer of Wisdom"/>
3.  Take the _Mistlock Singularity_

You can also precast stacks of <Trait name="lethal tempo"/> using your virtue skills, but this can be tricky due to them being movement abilities.
</Card>
</GridItem>

<GridItem sm="6">
<Card title="Golem rotation">

<Video youtube="x76DgzoGCnA" caption="Sword rotation by Support Hero"/>

Please note the setup used in this benchmark is optimized for raids, it is fine to be used in fractals and is only a small DPS loss compared to the setup listed on this page.

<Video youtube="mCOEGlJkRJ0" caption="Greatsword rotation by [CnD] DaedDee"/>

Please note the setup used in this benchmark is optimized for raids, it is fine to be used in fractals and is only a small DPS loss compared to the setup listed on this page.

</Card>
</GridItem>
</Grid>
