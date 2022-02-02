---
title: Condi Willbender
rating: Good
role: Condi Damage
profession: Guardian
specialization: Willbender
skills:
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
classification:
  - 3
  - 3
  - 3
  - 3
  - 3
code: ''
date: 2022-01-11T02:29:01.849Z
hidden: true
---

<Warning>

This build guide is not complete, gear and sections may chage regularly as we explore the new elite spec and spend more time playing it in fractals!

</Warning>

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
    "Health": 12810,
    "Armor": 2514,
    "Power": 2909,
    "Precision": 2085,
    "Toughness": 1243,
    "Vitality": 1000,
    "Ferocity": 300,
    "Condition Damage": 2927,
    "Expertise": 451,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0.30066666666666664,
    "Boon Duration": 0.162,
    "Critical Chance": 0.8666666666666666,
    "Critical Damage": 1.7,
    "Burning Duration": 0.7,
    "Maximum Health": 0.10000000000000009,
    "Resolution Duration": 0.25,
    "Effective Power": 8852.398263000001,
    "Power DPS": 9254.625061241817,
    "Bleeding Damage": 333.48375,
    "Bleeding Stacks": 1.4827599999999999,
    "Bleeding DPS": 494.47636514999994,
    "Burning Damage": 1134.654328125,
    "Burning Stacks": 29.3,
    "Burning DPS": 33245.3718140625,
    "Confusion Damage": 392.7875625,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 352.89,
    "Poison Stacks": 0,
    "Poison DPS": 0,
    "Torment Damage": 498.20062500000006,
    "Torment Stacks": 1.7298866666666668,
    "Torment DPS": 861.8306185125001,
    "Damage": 43856.303858966814,
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
    "weapon1MainId": 30699,
    "weapon1MainSigil1Id": 48911,
    "weapon1OffId": 30700,
    "weapon1OffSigil1Id": 44944,
    "weapon2MainId": 30695,
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
    "utility3Id": 9151,
    "eliteId": 62561
  }
}} 
>

If you need to swap a utility out, <Skill name="Signet of Fire"/> is a minor dps increase and should be swapped out when other skills suit the encounter better.
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
| <Skill id="9246" size="big" disableText/>              | A 1,200 range teleport to an ally.                                                  |
| <Skill name="Hallowed Ground" size="big" disableText/> | When <Boon name="Stability"/> is needed.                                            |
| <Skill id="9153" size="big" disableText/>              | When <Boon name="Stability"/> or a stunbreak is needed.                             |
| <Skill id="9125" size="big" disableText/>              | Deals an additional 200 defiance bar damage.                                        |
| <Skill id="9251" size="big" disableText/>              | A stationary reflect lasting for 10 seconds.                                        |
| <Skill id="9247" size="big" disableText/>              | A 1200 range teleport to an enemy.                                                  |
| <Skill name="Purging flames" size="big" disableText/>  | Cleanses conditions.                                                                |
| <Skill name="Sanctuary" size="big" disableText/>       | Huge CC and projectile destruction.                                                 |
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

**Make sure to only press <Skill id="9089"/> three times (twice to throw the projectile and once to activate the skill initially) or you will cancel a wasted cast! Never interrupt your axe auto attack chain! Keep <Skill name="purgingflames"/> on cooldown!**
</Warning>

1.  <Skill name="Rushing Justice"/> (F1)
2.  <Skill id="9104"/> (Torch 4)
3.  <Skill name="Symbol of Blades"/> (Sword 2)
4.  _Weapon Swap_
5.  <Skill name="Purging Flames"/>
6.  <Skill name="Whirling Light"/>
7.  <Skill name="Symbol of Punishment"/> (Scepter 2)
8.  <Skill name="Cleansing Flame"/> (Torch 5)
9.  <Skill id="9089"/> x2 (Torch 4)
10. <Skill name="Orb of Wrath"/> (Scepter 1)
11. <Skill name="Rushing Justice"/> (F1)
12. <Skill name="Orb of Wrath"/> (Scepter 1)
13. <Skill id="9104"/> (Torch 4)
14. <Skill id="9089"/> (Torch 4)
15. <Skill name="Symbol of Punishment"/> (Scepter 2)
16. _Weapon Swap_
17. <Skill name="Symbol of Blades"/> (Sword 2)
18. <Skill name="Zealots Defence"/> (Sword 3)
19. <Skill id="9089"/> (Torch 4)
20. <Skill name="Cleansing Flame"/> (Torch 5)
21. <Skill name="Symbol of Blades"/> (Sword 2)
22. <Skill name="Rushing Justice"/> (F1)
23. <Skill name="Purging Flames"/>
24. <Skill name="Whirling Light"/>
25. <Skill id="9104"/> -> <Skill id="9089"/> (Torch 4)
26. <Skill name="Sword of Wrath"/> -> <Skill name="Sword Arc"/> -> <Skill name="Sword Wave"/> (Sword 1)
27. <Skill name="Zealots Defence"/> (Sword 3)
28. <Skill name="Symbol of Blades"/> (Sword 2)

Repeat from step 7.

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
3.  Use <Skill name="Feelmywrath"/>
4.  Take the _Mistlock Singularity_
5.  Use <Skill name="Feelmywrath"/> again

</Card>
</GridItem>
</Grid>
