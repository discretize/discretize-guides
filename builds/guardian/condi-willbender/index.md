---
title: Condi Willbender
hidden: false
rating: Good
role: Condi Damage
profession: Guardian
specialization: Willbender
skills: null
conditions:
  - Burning
  - Vulnerability
  - Crippled
  - Bleeding
boons:
  - name: Quickness
    uptime: ~10%
    variant: group
  - name: Quickness
    uptime: ~25%
    variant: self
  - name: Might
    uptime: 2 stacks
    variant: party
code: "[&DQEQGi4XQSUmDwAA2BoAAEwBTAFIAUgB6RoAAAAAAAAAAAAAAAAAAAAAAAA=]"
classification:
  - 3
  - 3
  - 3
  - 3
  - 3
date: 2022-03-02T21:42:04.592Z
---

<Warning>

This build guide is not complete, gear and sections may chage regularly as we explore the new elite spec and spend more time playing it in fractals!

</Warning>

<Specialization name="Willbender" text="Condition Willbender"/> is a strong build for guardian. It has high damage, CC and mobility making it a strong choice for all groups. It alsocan easily slot more supportive utility skills allowing you to provide yourself and your party wwith <Boon name="Stability"/>, <Boon name="Aegis"/> and reflects easily.

<Divider text="Equipment"/>

<CharacterWithAr> 
<Character title="162 Agony Resistance" gear={{
  "profession": "Guardian",
  "weight": "Heavy",
  "gear": [
    "Grieving",
    "Sinister",
    "Grieving",
    "Sinister",
    "Grieving",
    "Sinister",
    "Viper",
    "Grieving",
    "Viper",
    "Viper",
    "Viper",
    "Sinister",
    "Grieving",
    "Grieving"
  ],
  "attributes": {
    "Health": 12810,
    "Armor": 2514,
    "Power": 2973,
    "Precision": 2075,
    "Toughness": 1243,
    "Vitality": 1000,
    "Ferocity": 615,
    "Condition Damage": 2770,
    "Expertise": 225,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0.15,
    "Boon Duration": 0.162,
    "Critical Chance": 0.8619047619047618,
    "Critical Damage": 1.91,
    "Power Coefficient": 2715,
    "Burning Coefficient": 14.65,
    "Bleeding Coefficient": 1.14,
    "Poison Coefficient": 0,
    "Torment Coefficient": 1.33,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Burning Duration": 0.8500000000000001,
    "Maximum Health": 0.10000000000000009,
    "Resolution Duration": 0.25,
    "Effective Power": 10047.60000315,
    "Power DPS": 10504.133233943878,
    "Bleeding Damage": 317.5875,
    "Bleeding Stacks": 1.3109999999999997,
    "Bleeding DPS": 416.3572124999999,
    "Burning Damage": 1087.42921875,
    "Burning Stacks": 29.3,
    "Burning DPS": 31861.676109375003,
    "Confusion Damage": 374.506875,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 336.99375,
    "Poison Stacks": 0,
    "Poison DPS": 0,
    "Torment Damage": 474.35624999999993,
    "Torment Stacks": 1.5294999999999999,
    "Torment DPS": 725.5278843749999,
    "Damage": 43507.69444019388,
    "Effective Health": 64088238.805970155,
    "Survivability": 32581.717745790622,
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
      "foodId": "91878",
      "utility": "toxic-focusing-crystal",
      "infusion": "Malign +9 Agony Infusion"
  },
  "skills": {
    "healId": 62622,
    "utility1Id": 62565,
    "utility2Id": 9187,
    "eliteId": 62561
  }
}} 
>

This is the optimal gear setup but at a minimal DPS loss you can also use the same gear as <BuildLink build="Condi Firebrand" specialization="Firebrand"/>.

If you need to swap a utility out, <Skill name="Signet of Wrath"/> is a minor dps increase and should be swapped out when other skills suit the encounter better.
You will want the following weapons to swap to durning fractal runs:

- Greatsword for pulling adds in Nightmare CM after MAMA and some T4s
- A staff for <Boon name="Might"/> pre-stacking.

</Character> 
</CharacterWithAr>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1="Radiance" traits1Selected="Right-Hand Strength,Radiant Fire,Amplified Wrath" traits2="Virtues" traits2Selected="masterofconsecrations,inspiringvirtue,permeatingwrath" traits3="Willbender" traits3Selected="Searing Pact,Restorative Virtues,Tyrants Momentum"/>

<Card title="Defiance Bar Damage">

|                                  |                                                                                |
| -------------------------------- | ------------------------------------------------------------------------------ |
| <Skill name="Hammer of Wisdom"/> | 200 damage                                                                     |
| <Skill name="Sanctuary"/>        | 1050 damage over 7 seconds (thanks to <Trait name="Master of Consecrations"/>) |
| <Skill name="Chains of light"/>  | <Condition name="Immobile"/> 50/s                                              |
| <Skill name="Heavens Palm"/>     | 400 damage (Knockdown) <br/> 150 damage (Knockback)                            |

</Card>
</GridItem>

<GridItem sm="5">
<Card title="Situational Skills">

|                                                        |                                                                                     |
| ------------------------------------------------------ | ----------------------------------------------------------------------------------- |
| <Skill name="Sword of Justice" size="big" disableText/>| Used as a source of <Condition name="Vulnerability"/>            |
| <Skill name="Sanctuary" size="big" disableText/>       | Huge CC and projectile destruction.                                                 |
| <Skill name="Signet of Wrath" size="big" disableText/> | Taken as a 3rd utility if no other skill is needed.                                   |
| <Skill id="9246" size="big" disableText/>              | A 1,200 range teleport to an ally.                                                  |
| <Skill name="Hallowed Ground" size="big" disableText/> | When <Boon name="Stability"/> is needed.                                            |
| <Skill id="9153" size="big" disableText/>              | When <Boon name="Stability"/> or a stunbreak is needed.                             |
| <Skill name="Advance" size="big" disableText/>         | When <Boon name="Aegis"/> is needed.                             |
| <Skill id="9125" size="big" disableText/>              | Deals an additional 200 defiance bar damage.                                        |
| <Skill id="9251" size="big" disableText/>              | A stationary reflect lasting for 10 seconds.                                        |
| <Skill id="9247" size="big" disableText/>              | A 1200 range teleport to an enemy.                                                  |
| <Skill name="renewed focus" size="big" disableText/>   | Recharges all virtue skills, grants <Effect name="Invulnerability"/> for 3 seconds. |

</Card>
</GridItem>
</Grid>

<Divider text="Details"/>

<Divider text="Rotation / Skill usage"/>

<Grid>
<GridItem sm="6">
<Card title="Rotation">

<Warning>

**Make sure to only press <Skill id="9089"/> three times (twice to throw the projectile and once to activate the skill initially) or you will cancel a wasted cast! Keep <Skill name="Rushing Justice"/> (F1) on cooldown!**
</Warning>

1.  <Skill name="Rushing Justice"/> (F1)
2.  <Skill id="9104"/> (Torch 4)
3.  <Skill name="Symbol of Punishment"/> (Scepter 2)
4.  _Weapon Swap_
5.  <Skill name="Symbol of Blades"/> (Sword 2)
6.  <Skill name="Purging Flames"/>
7.  <Skill name="Whirling Light"/>
8.  <Skill id="9089"/> x2 (Torch 4)
9.  <Skill name="Zealot's Defense"/> (Sword 3)

</Card>
</GridItem>

<GridItem sm="6">
<Card title="Golem rotation">

<Video youtube="" caption=""/>
</Card>

<Card title="Precasting">

<Warning>

The most important part is to get the precast of Ashes of the Just right! You have to start the fight quickly to not lose the stacks since they only last 10 seconds!
</Warning>

1.  Use <Skill name="hallowedground"/>
2.  Blast a fire field with <Skill name="holystrike"/> and/or <Skill name="Hammer of Wisdom"/>
4.  Take the _Mistlock Singularity_


</Card>
</GridItem>
</Grid>
