---
title: Power Willbender
hidden: false
rating: Good
role: Power Damage
profession: Guardian
specialization: Willbender
skills: null
conditions:
  - Vulnerability
  - Blinded
  - Crippled
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
code: "[&DQEQLio6QSYmDwAA3hoAAEgBTAH+ABYB6Ro3AQAAAAAAAAAAAAAAAAAAAAA=]"
classification:
  - 3
  - 3
  - 3
  - 3
  - 3
date: 2022-03-20T15:47:20.783Z
---

<Warning>

This build guide is not complete, gear and sections may change regularly as we explore the new elite spec and spend more time playing it in fractals!

</Warning>

<Specialization name="Willbender" text="Power Willbender"/> has great burst options and deals high consistent damage while providing medium defiance bar damage and <Condition name="Vulnerability"/>. The build offers a unique party wide offensive buff by sharing <Skill name="bane signet"/> for 216 <Attribute name="Power"/> and also strong on-demand defensive support with <Skill id="62532"/> and other useful skills such as <Skill id="9251"/> and <Skill name="standyourground"/>. It benefits from slaying potions and slaying sigils such as <Item id="50082"/> and <Item name="Serpent Slaying" type="Sigil"/>.

<Divider text="Equipment"/>

<CharacterWithAr>  
<Character title="162 AR (No Banner)" gear={{
  "profession": "Guardian",
  "weight": "Heavy",
  "gear": [
    "Berserker",
    "Assassin",
    "Assassin",
    "Berserker",
    "Assassin",
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
    "Health": 11645,
    "Armor": 2514,
    "Power": 3988,
    "Precision": 2364,
    "Toughness": 1243,
    "Vitality": 1000,
    "Ferocity": 1556,
    "Condition Damage": 750,
    "Expertise": 0,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0,
    "Boon Duration": 0.162,
    "Critical Chance": 0.9995238095238095,
    "Critical Damage": 2.5373333333333337,
    "Power Coefficient": 3361,
    "Burning Coefficient": 1.92,
    "Bleeding Coefficient": 0,
    "Poison Coefficient": 0,
    "Torment Coefficient": 0,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Effective Power": 32425.958877010824,
    "Power DPS": 41965.209004864606,
    "Bleeding Damage": 96.3125,
    "Bleeding Stacks": 0,
    "Bleeding DPS": 0,
    "Burning Damage": 355.421875,
    "Burning Stacks": 1.92,
    "Burning DPS": 682.41,
    "Confusion Damage": 118.665625,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 112.84375,
    "Poison Stacks": 0,
    "Poison DPS": 0,
    "Torment Damage": 142.74375,
    "Torment Stacks": 0,
    "Torment DPS": 0,
    "Damage": 42647.61900486461,
    "Effective Health": 58259761.19402986,
    "Survivability": 29618.58728725463,
    "Effective Healing": 390,
    "Healing": 390
  },
    "runeId": 24836,
    "runeName": "Scholar",
    "infusions": [
      37131, 37131, 37131, 37131, 37131, 37131, 37131,
      37131, 37131, 37131, 37131, 37131, 37131, 37131,
      37131, 37131, 37131, 37131
    ],
    "weapons": {
      "weapon1MainType": "Sword",
      "weapon1MainSigil1": "Force",
      "weapon1OffType": "Focus",
      "weapon1OffSigil": "Impact",
      "weapon2MainType": "Greatsword",
      "weapon2MainSigil1": "Force",
      "weapon2MainSigil2": "Impact"
    },
    "consumables": {
      "foodId": 91805,
      "utilityId": 9443,
      "infusion": "Mighty +9 Agony Infusion"
    },
    "skills": {
      "heal": "Litany of Wrath",
      "utility1": "Whirling Light",
      "utility2": "Sword of Justice",
      "utility3": "Bane Signet",
      "eliteId": 62561
    },
    "assumedBuffs": [{"id": "Might", "type": "Boon"}, {"id": "Fury", "type": "Boon"}, {"gw2id": 1786, "type": "Trait"}, {"gw2id": 12497, "type": "Skill"}, {"gw2id": 9093, "type": "Skill"}]
  }}
>

This build assumes you have neither <Skill name="Banner of Discipline"/> nor <Trait name="Spotter"/>.

If you cannot maintain good <Boon name="resolution"/> uptime during your bursts, you may want to play with <Trait name="Healers resolution"/>. By playing this trait you will lose <Attribute name="Precision"/> so will need to adjust your gear to [Crit Cap](/guides/crit-cap/).

Check the [gear optimizer](https://optimizer.discretize.eu/) for more gear variants!

</Character>

<Character title="162 AR (Banner)" gear={{
  "profession": "Guardian",
  "weight": "Heavy",
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
    "Dragon",
    "Berserker",
    "Berserker"
  ],
  "attributes": {
    "Health": 11915,
    "Armor": 2514,
    "Power": 4055,
    "Precision": 2371,
    "Toughness": 1243,
    "Vitality": 1027,
    "Ferocity": 1568,
    "Condition Damage": 750,
    "Expertise": 0,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0,
    "Boon Duration": 0.162,
    "Critical Chance": 1.002857142857143,
    "Critical Damage": 2.5453333333333332,
    "Power Coefficient": 3361,
    "Burning Coefficient": 1.92,
    "Bleeding Coefficient": 0,
    "Poison Coefficient": 0,
    "Torment Coefficient": 0,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Effective Power": 33084.227304123226,
    "Power DPS": 42817.13052335702,
    "Bleeding Damage": 96.3125,
    "Bleeding Stacks": 0,
    "Bleeding DPS": 0,
    "Burning Damage": 355.421875,
    "Burning Stacks": 1.92,
    "Burning DPS": 682.41,
    "Confusion Damage": 118.665625,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 112.84375,
    "Poison Stacks": 0,
    "Poison DPS": 0,
    "Torment Damage": 142.74375,
    "Torment Stacks": 0,
    "Torment DPS": 0,
    "Damage": 43499.54052335702,
    "Effective Health": 59610567.16417911,
    "Survivability": 30305.321384941082,
    "Effective Healing": 390,
    "Healing": 390
  },
    "runeId": 24836,
    "runeName": "Scholar",
    "infusions": [
      37131, 37131, 37131, 37131, 37131, 37131, 37131,
      37131, 37131, 37131, 37131, 37131, 37131, 37131,
      37131, 37131, 37131, 37131
    ],
    "weapons": {
      "weapon1MainType": "Sword",
      "weapon1MainSigil1": "Force",
      "weapon1OffType": "Focus",
      "weapon1OffSigil": "Impact",
      "weapon2MainType": "Greatsword",
      "weapon2MainSigil1": "Force",
      "weapon2MainSigil2": "Impact"
    },
    "consumables": {
      "foodId": 91805,
      "utilityId": 9443,
      "infusion": "Mighty +9 Agony Infusion"
    },
    "skills": {
      "heal": "Litany of Wrath",
      "utility1": "Whirling Light",
      "utility2": "Sword of Justice",
      "utility3": "Bane Signet",
      "eliteId": 62561
    },
    "assumedBuffs": [{"id": "Might", "type": "Boon"}, {"id": "Fury", "type": "Boon"}, {"gw2id": 1786, "type": "Trait"}, {"gw2id": 12497, "type": "Skill"}, {"gw2id": 1016, "type": "Trait"}, {"gw2id": 9093, "type": "Skill"}]
}}>

This build assumes you have either <Skill name="Banner of Discipline"/> or <Trait name="Spotter"/>.

If you cannot maintain good <Boon name="resolution"/> uptime during your bursts, you may want to play with <Trait name="Healers resolution"/>. By playing this trait you will lose <Attribute name="Precision"/> so will need to adjust your gear to [Crit Cap](/guides/crit-cap/).

Check the [gear optimizer](https://optimizer.discretize.eu/) for more gear variants!

</Character>

<Character title="222 AR (No Banner)" gear={{
  "profession": "Guardian",
  "weight": "Heavy",
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
    "Health": 11645,
    "Armor": 2604,
    "Power": 4066,
    "Precision": 2374,
    "Toughness": 1333,
    "Vitality": 1000,
    "Ferocity": 1556,
    "Condition Damage": 750,
    "Expertise": 0,
    "Concentration": 333,
    "Healing Power": 0,
    "Agony Resistance": 222,
    "Condition Duration": 0,
    "Boon Duration": 0.222,
    "Critical Chance": 1.0042857142857144,
    "Critical Damage": 2.5373333333333337,
    "Power Coefficient": 3361,
    "Burning Coefficient": 1.92,
    "Bleeding Coefficient": 0,
    "Poison Coefficient": 0,
    "Torment Coefficient": 0,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Effective Power": 33069.70887074973,
    "Power DPS": 42798.34097596836,
    "Bleeding Damage": 96.3125,
    "Bleeding Stacks": 0,
    "Bleeding DPS": 0,
    "Burning Damage": 355.421875,
    "Burning Stacks": 1.92,
    "Burning DPS": 682.41,
    "Confusion Damage": 118.665625,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 112.84375,
    "Poison Stacks": 0,
    "Poison DPS": 0,
    "Torment Damage": 142.74375,
    "Torment Stacks": 0,
    "Torment DPS": 0,
    "Damage": 43480.75097596837,
    "Effective Health": 60345432.835820906,
    "Survivability": 30678.91857438785,
    "Effective Healing": 390,
    "Healing": 390
  },
    "runeId": 24836,
    "runeName": "Scholar",
    "infusions": [
      37131, 37131, 37131, 37131, 37131, 37131, 37131,
      37131, 37131, 37131, 37131, 37131, 37131, 37131,
      37131, 37131, 37131, 37131
    ],
    "weapons": {
      "weapon1MainType": "Sword",
      "weapon1MainSigil1": "Force",
      "weapon1OffType": "Focus",
      "weapon1OffSigil": "Impact",
      "weapon2MainType": "Greatsword",
      "weapon2MainSigil1": "Force",
      "weapon2MainSigil2": "Impact"
    },
    "consumables": {
      "foodId": 91805,
      "utilityId": 9443,
      "infusion": "Mighty +9 Agony Infusion"
    },
    "skills": {
      "heal": "Litany of Wrath",
      "utility1": "Whirling Light",
      "utility2": "Sword of Justice",
      "utility3": "Bane Signet",
      "eliteId": 62561
    },
    "assumedBuffs": [{"id": "Might", "type": "Boon"}, {"id": "Fury", "type": "Boon"}, {"gw2id": 1786, "type": "Trait"}, {"gw2id": 12497, "type": "Skill"}, {"gw2id": 9093, "type": "Skill"}]
}}>

This build assumes you have neither <Skill name="Banner of Discipline"/> nor <Trait name="Spotter"/>.

If you cannot maintain good <Boon name="resolution"/> uptime during your bursts, you may want to play with <Trait name="Healers resolution"/>. By playing this trait you will lose <Attribute name="Precision"/> so will need to adjust your gear to [Crit Cap](/guides/crit-cap/).

Check the [gear optimizer](https://optimizer.discretize.eu/) for more gear variants!

</Character>

<Character title="222 AR (Banner)" gear={{
  "profession": "Guardian",
  "weight": "Heavy",
  "gear": [
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Dragon",
    "Dragon",
    "Dragon",
    "Berserker",
    "Berserker",
    "Dragon",
    "Berserker",
    "Berserker"
  ],
  "attributes": {
    "Health": 13745,
    "Armor": 2604,
    "Power": 3993,
    "Precision": 2366,
    "Toughness": 1333,
    "Vitality": 1210,
    "Ferocity": 1635,
    "Condition Damage": 750,
    "Expertise": 0,
    "Concentration": 333,
    "Healing Power": 0,
    "Agony Resistance": 222,
    "Condition Duration": 0,
    "Boon Duration": 0.222,
    "Critical Chance": 1.0004761904761905,
    "Critical Damage": 2.59,
    "Power Coefficient": 3361,
    "Burning Coefficient": 1.92,
    "Bleeding Coefficient": 0,
    "Poison Coefficient": 0,
    "Torment Coefficient": 0,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Effective Power": 33150.0773960285,
    "Power DPS": 42902.35276397836,
    "Bleeding Damage": 96.3125,
    "Bleeding Stacks": 0,
    "Bleeding DPS": 0,
    "Burning Damage": 355.421875,
    "Burning Stacks": 1.92,
    "Burning DPS": 682.41,
    "Confusion Damage": 118.665625,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 112.84375,
    "Poison Stacks": 0,
    "Poison DPS": 0,
    "Torment Damage": 142.74375,
    "Torment Stacks": 0,
    "Torment DPS": 0,
    "Damage": 43584.76276397836,
    "Effective Health": 71227820.8955224,
    "Survivability": 36211.398523397256,
    "Effective Healing": 390,
    "Healing": 390
  },
    "infusions": [
      37131, 37131, 37131, 37131, 37131, 37131, 37131,
      37131, 37131, 37131, 37131, 37131, 37131, 37131,
      37131, 37131, 37131, 37131
    ],
    "weight": "Heavy",
    "runeId": 24836,
    "runeName": "Scholar",
    "weapons": {
      "weapon1MainType": "Sword",
      "weapon1MainSigil1Id": 24615,
      "weapon1OffType": "Focus",
      "weapon1OffSigilId": 24868,
      "weapon2MainType": "Greatsword",
      "weapon2MainSigil1Id": 24615,
      "weapon2MainSigil2Id": 24868
    },
    "consumables": {
      "foodId": 91805,
      "utilityId": 9443,
      "infusion": "Mighty +9 Agony Infusion"
    },
    "skills": {
      "heal": "Litany of Wrath",
      "utility1": "Whirling Light",
      "utility2": "Sword of Justice",
      "utility3": "Bane Signet",
      "eliteId": 62561
    },
    "assumedBuffs": [{"id": "Might", "type": "Boon"}, {"id": "Fury", "type": "Boon"}, {"gw2id": 1786, "type": "Trait"}, {"gw2id": 12497, "type": "Skill"}, {"gw2id": 1016, "type": "Trait"}, {"gw2id": 9093, "type": "Skill"}]
}}>

This build assumes you have either <Skill name="Banner of Discipline"/> or <Trait name="Spotter"/>.

If you cannot maintain good <Boon name="resolution"/> uptime during your bursts, you may want to play with <Trait name="Healers resolution"/>. By playing this trait you will lose <Attribute name="Precision"/> so will need to adjust your gear to [Crit Cap](/guides/crit-cap/).

Check the [gear optimizer](https://optimizer.discretize.eu/) for more gear variants!

</Character>  
</CharacterWithAr>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1Id="16" traits1="Radiance" traits1SelectedIds="566,565,579" traits2Id="42" traits2="Zeal" traits2SelectedIds="634,653,2017" traits3Id="65" traits3="Willbender" traits3SelectedIds="2190,2197,2201"/>

<Card title="Virtues">

If you can reliably upkeep <Boon name="Aegis"/>, and you dont gain value from sharing <Skill name="Bane Signet"/> through <Trait name="Perfect Inscriptions"/>. You can drop the Radiance traitline for Virtues for more personal damage. Please note you will need to adjust your gear potentially to crit cap! Check the [gear optimizer](https://optimizer.discretize.eu) for more gear variants!

<Traits unembossed traits1="Virtues" traits1Selected="Unscathed Contender,Inspiring Virtue,Permeating Wrath"/>

</Card>

<Card title="CC skills">

|                                               |                                                     |
| --------------------------------------------- | --------------------------------------------------- |
| <Skill id="9093"/>                            | 300 damage                                          |
| <Skill id="9226"/> (after <Skill id="9147"/>) | 150 damage                                          |
| <Skill name="chainsoflight"/>                 | 250 damage                                          |
| <Skill name="hammerofwisdom"/>                | 200 damage                                          |
| <Skill name="sanctuary"/>                     | 750 damage                                          |
| <Skill name="Heavens Palm"/>                  | 400 damage (Knockdown) <br/> 150 damage (Knockback) |

</Card>
</GridItem>

<GridItem sm="5">
<Card title="Situational Skills">
If you need to use a different skill you can swap <Skill name="Whirling Light"/> without losing much damage.
|                                                        |                                                                                                                                 |
| ------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------- |
| <Skill id="9246" size="big" disableText/>              | A 1,200 range teleport to an ally.                                                                                              |
| <Skill name="Hallowed Ground" size="big" disableText/> | When <Boon name="Stability"/> is needed. Also useful for precasting a fire field and <Boon name="Resolution"/> at the mistlock. |
| <Skill name="Advance" size="big" disableText/>         | When extra <Boon name="Aegis"/> is needed.                                                                                      |
| <Skill id="9153" size="big" disableText/>              | When <Boon name="Stability"/> or a stunbreak is needed.                                                                         |
| <Skill id="9125" size="big" disableText/>              | Deals an additional 200 defiance bar damage.                                                                                    |
| <Skill id="9251" size="big" disableText/>              | A stationary reflect lasting for 10 seconds.                                                                                    |
| <Skill id="9247" size="big" disableText/>              | A 1200 range teleport to an enemy.                                                                                              |
| <Skill name="Purging flames" size="big" disableText/>  | Cleanses conditions.                                                                                                            |
| <Skill name="Sanctuary" size="big" disableText/>       | Huge CC and projectile destruction.                                                                                             |
| <Skill name="renewed focus" size="big" disableText/>   | Recharges all virtue skills, grants <Effect name="Invulnerability"/> for 3 seconds.                                             |

</Card>
</GridItem>
</Grid>

<Divider text="Details"/>

As a <Specialization name="Willbender" text="Power Willbender"/> it is important to play <Trait name="perfectinscriptions"/> to be able to use the <Skill name="Banesignet"/> for 300 CC while also sharing the 216 <Attribute name="Power"/> buff with your allies. This enables everyone to deal more damage during critical parts of the fight when the boss is <Effect name="exposed"/>.

Generally it is important to apply <Boon name="Resolution"/> when you are about to burst for the <Trait name="retribution"/> modifier. Thanks to <Trait name="healersresolution"/> your heal skill applies long lasting <Trait name="retribution"/>. Since <Skill name="litanyofwrath"/> has a low cooldown it lines up well with your burst. You can also trigger a <Skill id="13677"/> by losing health below the 75% threshold to trigger <Trait id="648"/>, however you need to be careful to not die.

<Divider text="Rotation / Skill Usage"/>

<Grid>
<GridItem xs="12" sm="6">
<Card title="Information">

Golem rotations out of the raid builds are generally suboptimal in fractals due to <Effect name="Exposed"/> and phases being much shorter compared to raids. The raid rotations are optimized for sustained DPS while in fractals a player needs the ability to adapt their rotation to the amount of time a group needs to finish a phase.\
For that reason you will find some general notes for skill usage here.
</Card>

<Card title="Precasting">

If you have a Mistlock Singularity present you can use these skills for precasts:

1.  Cast <Skill name="litany of wrath"/> for <Boon name="Resolution"/>
2.  Use <Skill name="Save yourselves"/> or <Skill name="hallowedground"/>
3.  Blast a fire field with <Skill name="Holy Strike"/>
4.  Use <Skill name="Feelmywrath"/>
5.  Use <Skill name="banesignet"/>
6.  Take mistlock
7.  Blast a fire field with <Skill name="Holy Strike"/> again

</Card>
</GridItem>

<GridItem xs="12" sm="6">
<Card title="Notes on skill usage:">

- Always start on sword
- Delay swapping to GS until the CC-bar is about to be broken. This is especially important at Ensolyss without instant CC.
- Always cast your <Skill name="whirlingwrath"/> inside the hitbox to get the additional hits. Ideal with adds around.
- Always cast your <Skill name="bindingblade"/> inside the hitbox to get the additional hits when adds are present. Can be abused at **Artsariiv**, **Arkk**, **Siax** and **Ensolyss**.
- Don't interrupt your GS auto-attack chain.
- In certain scenarios (precasting symbols, starting with <Skill name="onewolfpack"/>) it can be beneficial to get your <Skill name="Rushing Justice"/> out first.
- Don't waste your key skills on meaningless adds.

</Card>
</GridItem>

<GridItem xs="12" sm="6">
<Card title="Golem Rotation">

**Rotation:**

This is just a suggested opener. Depending on the encounter and the length of the phase you will want to start on different weapons and use different skills. <Specialization name="Willbender" text="Power Willbender"/> plays very similarly to <Specialization name="Dragonhunter" text="Power Dragonhunter"/>, if you need some ideas you can use the [Dragonhunter CM Guide](/cm-guides/guardian/power-dragonhunter/).

1.  <Skill name="banesignet" profession="guardian"/>
2.  <Skill name="Symbol of Blades" profession="guardian"/> (Sword 2)
3.  <Skill name="Shield of Wrath" profession="guardian"/> (Focus 5)
4.  <Skill name="Sword of Justice" profession="guardian"/>
5.  <Skill name="Ray of Judgment" profession="guardian"/> (Focus 4)
6.  <Skill name="Rushing Justice" profession="guardian"/> (F1)
7.  <Skill name="Zealotsdefense" profession="guardian"/> (Sword 3)
8.  **Weapon Swap**
9. <Skill name="Symbol of Resolution" profession="guardian"/> (GS 4)
10. <Skill name="Whirling Wrath" profession="guardian"/> (GS 2)
11. <Skill name="Whirling Light" profession="guardian"/>
12. <Skill name="Sword of Justice" profession="guardian"/>
13. <Skill name="Sword of Justice" profession="guardian"/>
14. <Skill name="Leap of Faith" profession="guardian"/> (GS 3)
15. <Skill name="Binding Blade" profession="guardian"/> (GS 5)
16. If the phase lasts longer than this, continue with the [SC rotation](https://snowcrows.com/builds/guardian/willbender/power-willbender).

</Card>
</GridItem>

<GridItem xs="12" sm="6">
<Card title="Golem Rotation">

<Video youtube="" caption=""/>
</Card>
</GridItem>
</Grid>

<Divider text="Underwater combat"/>

It is very much recommended to play <BuildLink build="Condi Firebrand" specialization="Firebrand"/> since it provides much better DPS compared to the <Specialization text="Power Willbender" name="Willbender"/>. If you still want to play <Specialization text="Power Willbender" name="Willbender"/> for whatever reason follow these rough guidelines.

- Open with <Skill name="refraction"/> for <Boon name="resolution"/>
- Cast <Skill name="purify"/> and swap to spear. Camp spear now.
- Priority list:
  1.  <Skill name="Zealots flurry"/> (Spear 2)
  2.  <Skill name="Symbol of spears"/> (Spear 4)
  3.  <Skill name="brilliance"/> (Spear 3)
