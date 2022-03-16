---
title: Banner Bladesworn
hidden: false
rating: Good
role: Power Damage
profession: Warrior
specialization: BLadesworn
skills: null
traits: null
conditions: null
boons:
  - name: Might
    uptime: 12 Stacks
    variant: party
  - name: Fury
    uptime: 100&
    variant: party
code: "[&DQIEHzMWRCunAAAAAAAAAKwACgCqAKIBnACcAAAAAAAAAAAAAAAAAAAAAAA=]"
classification:
  - 3
  - 3
  - 3
  - 3
  - 3
date: 2022-03-16T21:23:58.496Z
---

<Warning>

This build guide is not complete, gear and sections may change regularly as we explore the new elite spec and spend more time playing it in fractals!

</Warning>

The <Specialization text="Power Bladesworn" name="Bladesworn"/> is a situationally strong build for <Specialization name="Warrior"/> in fractals. It has more initial burst than <Specialization text="Power Berserker" name="Berserker"/> thanks to <Skill name="Dragon Trigger" />, but loses most of its sustained damage in favour of short damage spikes. Unfortunately if enemies dont phase or die shortly after your burst, your damage drops off hard and you would be better playing <Specialization text="Power Berserker" name="Berserker"/>.

Besides providing the group with strong unique damage buffs through the stats of <Skill name="Banner of Strength"/> and <Skill name="Banner of Discipline"/>. <Specialization name="Warrior"/> can provide half of the necessary <Boon name="Might"/> and <Boon name="Fury"/> to the group by using <Skill name="Forgreatjustice"/>.

The <Specialization text="Power Bladesworn" name="Bladesworn"/> is one of the classes that benefit a lot from higher agony resistance due to not being able to crit cap by buffs and traits alone. Furthermore, the build is able to use damage modifying sigils like <Item name="Impact" type="Sigil"/> as well as slaying potions such as <Item name="Powerful Potion of Slaying Scarlets Armies"/>.

<Divider text="Equipment" />

<CharacterWithAr>
<Character title="162 AR + Scholar Rune" gear={{
  "profession": "Warrior",
  "weight": "Heavy",
  "gear": [
    "Assassin",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Assassin",
    "Assassin",
    "Assassin",
    "Assassin",
    "Assassin",
    "Berserker",
    "Berserker",
    "Berserker"
  ],
  "attributes": {
    "Health": 21732,
    "Armor": 2514,
    "Power": 4010,
    "Precision": 2575,
    "Toughness": 1243,
    "Vitality": 1252,
    "Ferocity": 2298,
    "Condition Damage": 900,
    "Expertise": 0,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0,
    "Boon Duration": 0.162,
    "Critical Chance": 1,
    "Critical Damage": 3.032,
    "Effective Power": 32183.513399152507,
    "Power DPS": 46434.972932855,
    "Bleeding Damage": 120.17499999999998,
    "Bleeding Stacks": 0,
    "Bleeding DPS": 0,
    "Burning Damage": 427.728125,
    "Burning Stacks": 0.54,
    "Burning DPS": 230.9731875,
    "Confusion Damage": 146.898125,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 138.35937499999997,
    "Poison Stacks": 0,
    "Poison DPS": 0,
    "Torment Damage": 178.36499999999998,
    "Torment Stacks": 0,
    "Torment DPS": 0,
    "Damage": 46665.946120355,
    "Effective Health": 108724871.64179106,
    "Survivability": 55274.46448489632,
    "Effective Healing": 390,
    "Healing": 390
  },
    "infusions": [
      49432, 49432, 49432, 49432, 49432, 49432, 49432,
      49432, 49432, 49432, 49432, 49432, 49432, 49432,
      49432, 49432, 49432, 49432
    ],
    "weight": "Heavy",
    "runeId": 24836,
    "runeName": "Scholar",
    "weapons": {
      "weapon1MainType": "Axe",
      "weapon1MainSigil1Id": 24615,
      "weapon1OffType": "Pistol",
      "weapon1OffSigilId": 24868
    },
    "consumables": {
      "foodId": 91805,
      "utilityId": 9443,
      "infusion": "Mighty +9 Agony Infusion"
    },
    "skills": {
      "heal": "Mending",
      "utility2": "Banner of Strength",
      "utility3": "Banner of Discipline",
      "elite": "Signet of Rage"
    },
    "assumedBuffs": [{"id": "Might", "type": "Boon"}, {"id": "Fury", "type": "Boon"}, {"gw2id": 1786, "type": "Trait"}, {"gw2id": 12497, "type": "Skill"}, {"gw2id": 14407, "type": "Skill"}, {"gw2id": 14405, "type": "Skill"}, {"gw2id": 14404, "type": "Skill"}]
  }}
>

This build is future proof for upgrading to higher <Attribute name="Agony Resistance"/> later without overwriting runes. However, most people would profit more from the <Item name="eagle" text="Eagle"/> rune build due to not relying on the <Item name="scholar" text="Scholar"/> buff. No <Trait name="Spotter"/> assumed.

</Character>
<Character title="162 AR + Eagle Rune" gear={{
  "profession": "Warrior",
  "weight": "Heavy",
  "gear": [
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Assassin",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker"
  ],
  "attributes": {
    "Health": 21742,
    "Armor": 2514,
    "Power": 4015,
    "Precision": 2570,
    "Toughness": 1243,
    "Vitality": 1253,
    "Ferocity": 2299,
    "Condition Damage": 900,
    "Expertise": 0,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0,
    "Boon Duration": 0.162,
    "Critical Chance": 0.9976190476190476,
    "Critical Damage": 3.0326666666666666,
    "Effective Power": 32179.29227973723,
    "Power DPS": 46428.882623094105,
    "Bleeding Damage": 120.17499999999998,
    "Bleeding Stacks": 0,
    "Bleeding DPS": 0,
    "Burning Damage": 427.728125,
    "Burning Stacks": 0.54,
    "Burning DPS": 230.9731875,
    "Confusion Damage": 146.898125,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 138.35937499999997,
    "Poison Stacks": 0,
    "Poison DPS": 0,
    "Torment Damage": 178.36499999999998,
    "Torment Stacks": 0,
    "Torment DPS": 0,
    "Damage": 46659.855810594105,
    "Effective Health": 108774901.49253733,
    "Survivability": 55299.89908110693,
    "Effective Healing": 390,
    "Healing": 390
  },
    "infusions": [
      37132, 49432, 49432, 49432, 49432, 49432, 49432,
      49432, 49432, 49432, 49432, 49432, 49432, 49432,
      49432, 49432, 49432, 49432
    ],
    "weight": "Heavy",
    "runeId": 24723,
    "runeName": "Eagle",
    "weapons": {
      "weapon1MainType": "Axe",
      "weapon1MainSigil1Id": 24615,
      "weapon1OffType": "Pistol",
      "weapon1OffSigilId": 24868
    },
    "consumables": {
      "foodId": 91805,
      "utilityId": 9443,
      "infusion": "Mighty +9 Agony Infusion"
    },
    "skills": {
      "heal": "Mending",
      "utility2": "Banner of Strength",
      "utility3": "Banner of Discipline",
      "elite": "Signet of Rage"
    },
    "assumedBuffs": [{"id": "Might", "type": "Boon"}, {"id": "Fury", "type": "Boon"}, {"gw2id": 1786, "type": "Trait"}, {"gw2id": 12497, "type": "Skill"}, {"gw2id": 14407, "type": "Skill"}, {"gw2id": 14405, "type": "Skill"}, {"gw2id": 14404, "type": "Skill"}]
  }}
>

Optionally 1 <Item id="37132"/>. Without that infusion the <Attribute name="Critical Chance"/> is at 99.76%. No <Trait name="Spotter"/> assumed.

</Character>
<Character title="222 AR" gear={{
  "profession": "Warrior",
  "weight": "Heavy",
  "gear": [
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Assassin",
    "Assassin",
    "Assassin",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker"
  ],
  "attributes": {
    "Health": 21832,
    "Armor": 2604,
    "Power": 4098,
    "Precision": 2575,
    "Toughness": 1333,
    "Vitality": 1262,
    "Ferocity": 2308,
    "Condition Damage": 900,
    "Expertise": 0,
    "Concentration": 333,
    "Healing Power": 0,
    "Agony Resistance": 222,
    "Condition Duration": 0,
    "Boon Duration": 0.222,
    "Critical Chance": 1,
    "Critical Damage": 3.038666666666667,
    "Effective Power": 32962.10204439076,
    "Power DPS": 47558.335140674695,
    "Bleeding Damage": 120.17499999999998,
    "Bleeding Stacks": 0,
    "Bleeding DPS": 0,
    "Burning Damage": 427.728125,
    "Burning Stacks": 0.54,
    "Burning DPS": 230.9731875,
    "Confusion Damage": 146.898125,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 138.35937499999997,
    "Poison Stacks": 0,
    "Poison DPS": 0,
    "Torment Damage": 178.36499999999998,
    "Torment Stacks": 0,
    "Torment DPS": 0,
    "Damage": 47789.308328174695,
    "Effective Health": 113135379.10447763,
    "Survivability": 57516.71535560632,
    "Effective Healing": 390,
    "Healing": 390
  },
    "infusions": [
      37132, 37131, 37131, 37131, 37131, 37131, 37131,
      37131, 37131, 37131, 37131, 37131, 37131, 37131,
      37131, 37131, 37131, 37131
    ],
    "weight": "Heavy",
    "runeId": 24836,
    "runeName": "Scholar",
    "weapons": {
      "weapon1MainType": "Axe",
      "weapon1MainSigil1Id": 24615,
      "weapon1OffType": "Pistol",
      "weapon1OffSigilId": 24868
    },
    "consumables": {
      "foodId": 91805,
      "utilityId": 9443,
      "infusion": "Mighty +9 Agony Infusion"
    },
    "skills": {
      "heal": "Mending",
      "utility2": "Banner of Strength",
      "utility3": "Banner of Discipline",
      "elite": "Signet of Rage"
    },
    "assumedBuffs": [{"id": "Might", "type": "Boon"}, {"id": "Fury", "type": "Boon"}, {"gw2id": 1786, "type": "Trait"}, {"gw2id": 12497, "type": "Skill"}, {"gw2id": 14407, "type": "Skill"}, {"gw2id": 14405, "type": "Skill"}, {"gw2id": 14404, "type": "Skill"}]
}}>

</Character>
</CharacterWithAr>

<Divider text="Build" />

<Grid>
<GridItem sm="7">
<Traits traits1Id="4" traits1="Strength" traits1Selected="Peak Performance,Great Fortitude,Berserkers Power" traits2="Discipline" traits2Selected="Warriors Sprint,Doubled Standards,Axe Mastery" traits3Id="68" traits3="Bladesworn" traits3Selected="Unseen Sword,Fierce as Fire,Unyielding Dragon"/>

<Card title="Extra Weapons">

- Axes and Pistols with <Item name="Night" type="Sigil" disableText/>, <Item name="Serpent Slaying" type="Sigil" disableText/> and other slaying sigils.
- Warhorn for pre-stacking <Boon name="Might"/>
- Greatsword for mobility and cleave.
- Torch (trade CC for DPS or a fire field).

</Card>
<Card title="DPS Skills">

If the encounter is short enough to precast Banners and swap to different skills, or you want to play without them, you can play the following skills:

<Skills
  unembossed
  heal="Mending"
  utility1="Signet of Might"
  utility2="Signet of Fury"
  utility3="Flow Stabilizer"
  elite="Signet of Rage"
/>

</Card>
</GridItem>

<GridItem sm="5">
<Card title="Situational Skills">

|                                                           |                                                                                                                                                                                              |
| --------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <Skill name="For Great Justice!" size="big" disableText/> | If your groups <Boon name="Might"/> is not 25, take <Skill name="Forgreatjustice"/>. It is a bigger DPS increase than <Skill name="signetofmight"/>!                                         |
| <Skill name="Signet of fury" size="big" disableText/>     | Grants <Attribute name="Precision" text="180 Precision"/> passively; grants 360 <Attribute name="Precision"/> and <Attribute name="Ferocity"/> on use and fills up the entire adrenaline bar. |
| <Skill name="Signet of might" size="big" disableText/>    | Flat 180 power buff. Only take this when no other utility is needed.                                                                                                                         |
| <Skill name="Battle Standard" size="big" disableText/>    | Can be used on Arkk if your <Specialization name="Renegade"/> is able to solo the CC bar.                                                                                                    |
| <Skill name="onmymark" size="big" disableText/>           | Can be used to pull Krait from the side altars at the Nightmare CM fractal.                                                                                                                  |
| <Skill name="featherfootgrace" size="big" disableText/>   | Grants <Effect name="Superspeed"/> for skips.                                                                                                                                                |
| <Skill name="bullscharge" size="big" disableText/>        | 300 CC, gives <Trait name="Peakperformance"/>.                                                                                                                                               |

</Card>
<Card title="CC skills">

|                             |            |
| --------------------------- | ---------- |
| <Skill name="bullscharge"/> | 300 damage |
| <Skill id="14502"/>         | 150 damage |
| <Skill id="14415"/>         | 300 damage |
| <Skill id="14503"/>         | 100 damage |

</Card>
</GridItem>
</Grid>

<Divider text="Rotation / Skill usage" />

<Grid>
<GridItem xs="12" sm="6">
<Card title="Information">

Golem rotations out of the raid builds are generally suboptimal in fractals due to <Effect name="Exposed"/> and phases being much shorter compared to raids. The raid rotations are optimized for sustained DPS while in fractals a player needs the ability to adapt a rotation to the amount of time a group needs to finish a phase.\
For that reason you can find a video with openers, that are efficient to use here.

- Casting <Skill name="Mending"/> for <Trait name="Peak Performance"/> is only a DPS gain if you can’t be hitting something else, use it right before the start of DPS phases but only use it during if you need the heal.
  
</Card>
</GridItem>

<GridItem xs="12" sm="6">

<Card title="Precasting">

- Stack <Boon name="Might"/>:
  - Use both charges of <Skill name="For Great Justice!"/>.
  - Drop a fire field with <Skill name="Flames of War"/>.
  - Use <Skill name="Call of Valor"/> and <Skill id="14393"/> on offhand Warhorn to blast <Boon name="Might"/>.
- Precast damage skills:
  - (optional) <Skill name="Flames of War"/>
  - (optional) <Skill id="14393"/> for two stacks of a 25% damage modifier
  - Cast <Skill name="Mending"/> immediately before the boss becomes vulnerable.

</Card>

</GridItem>

<GridItem xs="12" sm="6">

<Card title="Opener">

Start in <Skill name="Unsheathe Gunsaber"/>

1. Cyclone Trigger in <Skill name="Unsheathe Gunsaber"/> (Skill 4)
2. <Skill name="Sheathe Gunsaber" />
3. <Skill name="Dragons Roar" />
4. <Skill name="Cyclone Axe" />
5. <Skill name="Gunstinger" />
6. <Skill name="Chop" /> -> <Skill name="Double Chop" /> -> <Skill name="Triple Chop" />
7. <Skill name="Unsheathe Gunsaber" />
8. <Skill name="Dragon Trigger" />
9. Dragon Slash-Force in <Skill name="Dragon Trigger"/> (Skill 1) 

</Card>

</GridItem>

<GridItem xs="12" sm="6">
<Card title="Golem Rotation">

<Video youtube="" caption=""/>
</Card>
</GridItem>
</Grid>
