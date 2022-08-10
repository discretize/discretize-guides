---
title: Banner Berserker
hidden: false
archive: true
rating: Good
role: Power Damage
profession: Warrior
specialization: Berserker
hasBeginner: true
conditions:
  - name: Vulnerability
    uptime: 5 stacks
boons:
  - name: Might
    uptime: '12 stacks'
    variant: (using For Great Justice)
code: '[&DQIEHzMWEhenAAAAAAAAAKwACgCqAKIBwhKcAAAAAAAAAAAAAAAAAAAAAAA=]'
cmGuide: pug
classification:
  - 4
  - 4
  - 4
  - 2
  - 4
date: 2022-08-05T11:43:11.788Z
---

The <Specialization text="Banner Berserker" name="Berserker"/> is a strong build for <Specialization name="Warrior"/> in fractals. It has excellent defiance bar damage in <Skill name="Tremor"/> and <Skill name="Headbutt"/>, the build also has medium burst and excellent sustained damage. <Specialization name="Warrior"/> can provide half of the necessary <Boon name="Might"/> and <Boon name="Fury"/> to the group by using <Skill name="Forgreatjustice"/>. The <Specialization text="Banner Berserker" name="Berserker"/> excels at fighting larger groups of mobs due to extreme cleave with greatswords <Skill name="arcdivider" /> -> <Skill name="bloodreckoning" /> -> <Skill name="arcdivider" /> combo.

Unfortunately, this builds requires a lot of Assassin pieces or other runes than <Item name="scholar" /> due to receiving very little <Attribute name="Precision" /> from traits. This is also the reason why the <Specialization text="Banner Berserker" name="Berserker"/> is one of the classes that benefit a lot from higher <Attribute name="Agony Resistance" />.

Furthermore, the build is able to use damage modifying sigils like <Item name="Impact" type="Sigil"/> as well as slaying potions such as <Item name="Powerful Potion of Slaying Scarlets Armies"/>. As a <Specialization text="Banner Berserker" name="Berserker"/> your focus is to maintain your unique party buffs and instantly contribute to breaking defiance bars, all while making DPS players sweat nervously when they glance at their DPS meter.

<Beginner>

Before progressing to the advanced version of this page, we recommend acquiring an in-depth understanding of your CC skills and when to use them efficiently. You should be able to hit consistently high DPS, which you can verify with [arc-dps](https://www.deltaconnected.com/arcdps/). And finally, you should be able to execute the basic step-by-step rotation provided below without spending too much thought on it.

The advanced page provides a more complete overview of all the utilities the <Specialization name="Warrior"/> has to offer. If you ever feel like you are missing information feel free to already swap to the advanced page!

<Information>

Although this build lists 162 <Attribute name="Agony Resistance"/>, it is not a strict requirement! We recommend getting started with this build anyway - even if it might be suboptimal while being in Tier 1 or 2 fractals. Keep upgrading your <Attribute name="Agony Resistance"/> until you reach the suggested variant. In the beginning, it is much more important to learn about fractal mechanics and your skills rather than equipping optimal gear.

</Information>

</Beginner>

<Divider text="Equipment" />

<Beginner>
<CharacterWithAr>
<Character title="Eagle Runes" gear={{
  "profession": "Warrior",
  "weight": "Heavy",
  "gear": [
    "Berserker",
    "Assassin",
    "Berserker",
    "Assassin",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Assassin",
    "Berserker",
    "Assassin",
    "Assassin",
    "Assassin"
  ],
  "attributes": {
    "Health": 26322,
    "Armor": 2214,
    "Power": 3873,
    "Precision": 2361,
    "Toughness": 943,
    "Vitality": 1711,
    "Ferocity": 1940,
    "Condition Damage": 960,
    "Expertise": 0,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0,
    "Boon Duration": 0.162,
    "Critical Chance": 0.998095238095238,
    "Critical Damage": 2.7933333333333334,
    "Power Coefficient": 3079,
    "Power2 Coefficient": 0,
    "Burning Coefficient": 0.73,
    "Bleeding Coefficient": 0,
    "Poison Coefficient": 0,
    "Torment Coefficient": 0,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Siphon Base Coefficient": 139.75,
    "Effective Power": 27505.77697444861,
    "Power DPS": 32610.81528853572,
    "Power2 DPS": 0,
    "Siphon DPS": 139.75,
    "Bleeding Damage": 114.425,
    "Bleeding Stacks": 0,
    "Bleeding DPS": 0,
    "Burning Damage": 402.21250000000003,
    "Burning Stacks": 0.73,
    "Burning DPS": 293.61512500000003,
    "Confusion Damage": 139.49500000000003,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 130.95624999999998,
    "Poison Stacks": 0,
    "Poison DPS": 0,
    "Torment Damage": 169.9125,
    "Torment Stacks": 0,
    "Torment DPS": 0,
    "Damage": 33044.180413535716,
    "Effective Health": 115973946.26865673,
    "Survivability": 58959.8099993171,
    "Effective Healing": 390,
    "Healing": 390
  },
  "runeId": 24723,
  "runeName": "Eagle",
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
    "weapon1MainType": "Axe",
    "weapon1MainSigil1Id": 24615,
    "weapon1OffType": "Axe",
    "weapon1OffSigilId": 24868,
    "weapon2MainType": "Axe",
    "weapon2MainSigil1Id": 84505,
    "weapon2OffType": "Mace",
    "weapon2OffSigilId": 24639
  },
  "consumables": {
    "foodId": 91709,
    "utilityId": 77569
  },
  "skills": {
    "healId": 14401,
    "utility1Id": "",
    "utility2Id": "",
    "utility3Id": 30258,
    "eliteId": 30343
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
      "id": "jade-bot",
      "gw2id": 96613,
      "type": "Item"
    },
    {
      "id": "omnipotion",
      "gw2id": 79722,
      "type": "Item"
    }
  ]
}}>

Check the [gear optimizer](https://optimizer.discretize.eu/) for more gear variants!

</Character>
</CharacterWithAr>
</Beginner>

<Advanced>
<CharacterWithAr>
<Character title="Thief Runes" gear={{
  "profession": "Warrior",
  "weight": "Heavy",
  "gear": [
    "Assassin",
    "Assassin",
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
    "Health": 26532,
    "Armor": 2214,
    "Power": 4073,
    "Precision": 2362,
    "Toughness": 943,
    "Vitality": 1732,
    "Ferocity": 1736,
    "Condition Damage": 1060,
    "Expertise": 0,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0,
    "Boon Duration": 0.162,
    "Critical Chance": 0.9985714285714286,
    "Critical Damage": 2.6573333333333333,
    "Power Coefficient": 3079,
    "Power2 Coefficient": 0,
    "Burning Coefficient": 0.73,
    "Bleeding Coefficient": 0,
    "Poison Coefficient": 0,
    "Torment Coefficient": 0,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Siphon Base Coefficient": 139.75,
    "Effective Power": 28837.77696728606,
    "Power DPS": 34190.03283876541,
    "Power2 DPS": 0,
    "Siphon DPS": 139.75,
    "Bleeding Damage": 123.05,
    "Bleeding Stacks": 0,
    "Bleeding DPS": 0,
    "Burning Damage": 424.49375000000003,
    "Burning Stacks": 0.73,
    "Burning DPS": 309.8804375,
    "Confusion Damage": 149.41375000000002,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 139.58124999999998,
    "Poison Stacks": 0,
    "Poison DPS": 0,
    "Torment Damage": 182.85,
    "Torment Stacks": 0,
    "Torment DPS": 0,
    "Damage": 34639.66327626541,
    "Effective Health": 116899200.00000001,
    "Survivability": 59430.19827147942,
    "Effective Healing": 390,
    "Healing": 390
  },
  "runeId": 24818,
  "runeName": "Thief",
  "infusions": [
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131
  ],
  "weapons": {
    "weapon1MainType": "Axe",
    "weapon1MainSigil1Id": 24615,
    "weapon1OffType": "Axe",
    "weapon1OffSigilId": 24868,
    "weapon2MainType": "Axe",
    "weapon2MainSigil1Id": 84505,
    "weapon2OffType": "Mace",
    "weapon2OffSigilId": 24639
  },
  "consumables": {
    "foodId": 91709,
    "utilityId": 77569,
    "infusionId": 37131
  },
  "skills": {
    "healId": 14401,
    "utility1Id": "",
    "utility2Id": "",
    "utility3Id": 30258,
    "eliteId": 30343
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
      "id": "jade-bot",
      "gw2id": 96613,
      "type": "Item"
    },
    {
      "id": "omnipotion",
      "gw2id": 79722,
      "type": "Item"
    }
  ]
}}>

This build is the highest DPS variant assuming you have a high flanking uptime. If you cannot flank you will be better off running the <Item id="24836"/> or <Item id="24723"/> variant.

Check the [gear optimizer](https://optimizer.discretize.eu/) for more gear variants!

</Character>
<Character title="Scholar Runes" gear={{
  "profession": "Warrior",
  "weight": "Heavy",
  "gear": [
    "Assassin",
    "Assassin",
    "Berserker",
    "Assassin",
    "Assassin",
    "Assassin",
    "Berserker",
    "Assassin",
    "Assassin",
    "Assassin",
    "Assassin",
    "Assassin",
    "Assassin",
    "Assassin"
  ],
  "attributes": {
    "Health": 26412,
    "Armor": 2214,
    "Power": 3962,
    "Precision": 2362,
    "Toughness": 943,
    "Vitality": 1720,
    "Ferocity": 1949,
    "Condition Damage": 960,
    "Expertise": 0,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0,
    "Boon Duration": 0.162,
    "Critical Chance": 0.9985714285714286,
    "Critical Damage": 2.7993333333333332,
    "Power Coefficient": 3079,
    "Power2 Coefficient": 0,
    "Burning Coefficient": 0.73,
    "Bleeding Coefficient": 0,
    "Poison Coefficient": 0,
    "Torment Coefficient": 0,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Siphon Base Coefficient": 139.75,
    "Effective Power": 28206.888376327614,
    "Power DPS": 33442.05210270031,
    "Power2 DPS": 0,
    "Siphon DPS": 139.75,
    "Bleeding Damage": 114.425,
    "Bleeding Stacks": 0,
    "Bleeding DPS": 0,
    "Burning Damage": 402.21250000000003,
    "Burning Stacks": 0.73,
    "Burning DPS": 293.61512500000003,
    "Confusion Damage": 139.49500000000003,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 130.95624999999998,
    "Poison Stacks": 0,
    "Poison DPS": 0,
    "Torment Damage": 169.9125,
    "Torment Stacks": 0,
    "Torment DPS": 0,
    "Damage": 33875.41722770031,
    "Effective Health": 116370483.58208957,
    "Survivability": 59161.40497310095,
    "Effective Healing": 390,
    "Healing": 390
  },
  "runeId": 24836,
  "runeName": "Scholar",
  "infusions": [
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131
  ],
  "weapons": {
    "weapon1MainType": "Axe",
    "weapon1MainSigil1Id": 24615,
    "weapon1OffType": "Axe",
    "weapon1OffSigilId": 24868,
    "weapon2MainType": "Axe",
    "weapon2MainSigil1Id": 84505,
    "weapon2OffType": "Mace",
    "weapon2OffSigilId": 24639
  },
  "consumables": {
    "foodId": 91709,
    "utilityId": 77569,
    "infusionId": 37131
  },
  "skills": {
    "healId": 14401,
    "utility1Id": "",
    "utility2Id": "",
    "utility3Id": 30258,
    "eliteId": 30343
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
      "id": "jade-bot",
      "gw2id": 96613,
      "type": "Item"
    },
    {
      "id": "omnipotion",
      "gw2id": 79722,
      "type": "Item"
    }
  ]
}}>

This build should be used if you cannot benefit from the flanking bonus from <Item id="24818"/>. If you cannot maintain <Item id="24836"/> uptime or don't want to run as much Assassin gear, use the <Item id="24723"/> variant.

Check the [gear optimizer](https://optimizer.discretize.eu/) for more gear variants!

</Character>
<Character title="Eagle Runes" gear={{
  "profession": "Warrior",
  "weight": "Heavy",
  "gear": [
    "Berserker",
    "Assassin",
    "Berserker",
    "Assassin",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Assassin",
    "Berserker",
    "Assassin",
    "Assassin",
    "Assassin"
  ],
  "attributes": {
    "Health": 26412,
    "Armor": 2214,
    "Power": 3963,
    "Precision": 2361,
    "Toughness": 943,
    "Vitality": 1720,
    "Ferocity": 1949,
    "Condition Damage": 960,
    "Expertise": 0,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0,
    "Boon Duration": 0.162,
    "Critical Chance": 0.998095238095238,
    "Critical Damage": 2.7993333333333332,
    "Power Coefficient": 3079,
    "Power2 Coefficient": 0,
    "Burning Coefficient": 0.73,
    "Bleeding Coefficient": 0,
    "Poison Coefficient": 0,
    "Torment Coefficient": 0,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Siphon Base Coefficient": 139.75,
    "Effective Power": 28205.363996811364,
    "Power DPS": 33440.24480022417,
    "Power2 DPS": 0,
    "Siphon DPS": 139.75,
    "Bleeding Damage": 114.425,
    "Bleeding Stacks": 0,
    "Bleeding DPS": 0,
    "Burning Damage": 402.21250000000003,
    "Burning Stacks": 0.73,
    "Burning DPS": 293.61512500000003,
    "Confusion Damage": 139.49500000000003,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 130.95624999999998,
    "Poison Stacks": 0,
    "Poison DPS": 0,
    "Torment Damage": 169.9125,
    "Torment Stacks": 0,
    "Torment DPS": 0,
    "Damage": 33873.60992522417,
    "Effective Health": 116370483.58208957,
    "Survivability": 59161.40497310095,
    "Effective Healing": 390,
    "Healing": 390
  },
  "runeId": 24723,
  "runeName": "Eagle",
  "infusions": [
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131
  ],
  "weapons": {
    "weapon1MainType": "Axe",
    "weapon1MainSigil1Id": 24615,
    "weapon1OffType": "Axe",
    "weapon1OffSigilId": 24868,
    "weapon2MainType": "Axe",
    "weapon2MainSigil1Id": 84505,
    "weapon2OffType": "Mace",
    "weapon2OffSigilId": 24639
  },
  "consumables": {
    "foodId": 91709,
    "utilityId": 77569,
    "infusionId": 37131
  },
  "skills": {
    "healId": 14401,
    "utility1Id": "",
    "utility2Id": "",
    "utility3Id": 30258,
    "eliteId": 30343
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
      "id": "jade-bot",
      "gw2id": 96613,
      "type": "Item"
    },
    {
      "id": "omnipotion",
      "gw2id": 79722,
      "type": "Item"
    }
  ]
}}>

Check the [gear optimizer](https://optimizer.discretize.eu/) for more gear variants!

</Character>
</CharacterWithAr>
</Advanced>

<Divider text="Build" />

<Grid>
<GridItem sm="7">
<Traits traits1Id="4" traits1="Strength" traits1Selected="Peak Performance,Great Fortitude,Berserkers Power" traits2="Discipline" traits2Selected="Warriors Sprint,Destruction of the Empowered,Axe Mastery" traits3Id="18" traits3="Berserker" traits3Selected="Savage Instinct,Blood Reaction,Bloody Roar"/>

<Card title="Extra Weapons">

Absolutely mandatory: a greatsword for mobility and cleave.

<Advanced>

Nice to have:

- Axes with <Item name="Night" type="Sigil" disableText/>, <Item name="Serpent Slaying" type="Sigil" disableText/> and other slaying sigils.
- Warhorn for pre-stacking <Boon name="Might"/>.
- Sword for out of combat mobility.
- Rifle for Siax (coordinated).
- Torch (trade CC for DPS or a fire field).

</Advanced>

</Card>
</GridItem>

<GridItem sm="5">
<Card title="Situational Skills">

<Beginner>

|                                                           |                                                                                                    |
| --------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | --- |
| <Skill name="For Great Justice!" size="big" disableText/> | Whenever you notice less than 25 stacks of <Boon name="Might"/> on your buff bar.                  |
| <Skill name="bloodreckoning" size="big" disableText/>     | For double <Skill name="arcdivider"/> or the situational <Specialization name="Berserker"/> build. |
| <Skill name="Wild Blow" size="big" disableText/>          | 332 CC and 4s <Skill name="berserk"/> extension.                                                   |
| <Skill name="Battle Standard" size="big" disableText/>    | Can be used on Arkk if your <Specialization name="Renegade"/> is able to solo the CC bar.          |     |

</Beginner>

<Advanced>

|                                                           |                                                                                                                                                                                              |
| --------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <Skill name="For Great Justice!" size="big" disableText/> | Whenever you notice less than 25 stacks of <Boon name="Might"/> on your buff bar.                                                                                                            |
| <Skill name="Signet of fury" size="big" disableText/>     | Grants <Attribute name="Precision" text="180 Precision"/> passively; grants 360 <Attribute name="Precision"/> and <Attribute name="Ferocity"/> on use and fills up the entire adrenalin bar. |
| <Skill name="Signet of might" size="big" disableText/>    | Flat 180 power buff. Only take this when no other utility is needed.                                                                                                                         |
| <Skill name="Battle Standard" size="big" disableText/>    | Can be used on Arkk if your <Specialization name="Renegade"/> is able to solo the CC bar.                                                                                                    |
| <Skill name="onmymark" size="big" disableText/>           | Can be used to pull Krait from the side altars at the Nightmare CM fractal.                                                                                                                  |
| <Skill name="featherfootgrace" size="big" disableText/>   | Grants <Effect name="Superspeed"/> for skips.                                                                                                                                                |
| <Skill name="bloodreckoning" size="big" disableText/>     | For double <Skill name="arcdivider"/> or the situational <Specialization name="Berserker"/> build.                                                                                           |
| <Skill name="outrage" size="big" disableText/>            | Very strong in conjunction with <Skill name="headbutt"/> for <Skill name="berserk"/> extension.                                                                                              |
| <Skill name="Wild Blow" size="big" disableText/>          | 332 CC and 4s <Skill name="berserk"/> extension.                                                                                                                                             |
| <Skill name="bullscharge" size="big" disableText/>        | 300 CC, gives <Trait name="Peakperformance"/>.                                                                                                                                               |

</Advanced>

</Card>
</GridItem>
</Grid>

<Divider text="Details" />

<Grid>
<GridItem sm="8">

**How to deal damage:**

- Use <Skill name="decapitate"/> as often as possible. Three crits are required to gain a single <Skill name="decapitate"/>:
  1.  <Skill name="Cycloneaxe" /> and <Skill name="Throw axe" profession="warrior" />.
  2.  <Skill name="Dualstrike" /> and <Skill name="Throw axe" profession="warrior" />.
  3.  <Skill name="whirlingaxe" />.
- Get three <Skill name="decapitate"/> before pressing <Skill name="Whirling axe"/>.
- If the boss has a breakbar, make sure to use <Skill name="Tremor"/> to proc <Item name="severance"/>, then swap to Axe/Axe.

<Advanced>

- Only use <Skill name="Throw axe" profession="warrior"/> outside <Skill name="Berserk"/> to prevent its ammo count fully recharging.
- Interrupting your auto-attack chain to use <Skill name="Decapitate"/> or enter <Skill name="Berserk"/> is a DPS increase.
- Keep in mind that <Skill name="Crushing Blow"/> inflicts <Condition name="Vulnerability" count={10}/>! This can be often used with no DPS loss if you are on your mace set waiting to CC. Especially useful if you apply the <Condition name="Vulnerability"/> to adds for a quick burst. If the foe is disabled it even inflicts <Condition name="Vulnerability" count={20} />
- You must be in <Skill name="Berserk"/> mode for as many burn phases as possible for maximum DPS. Pay attention to your group's phase times and your <Skill name="Berserk"/> extensions. It is better for <Skill name="Berserk"/> to drop when the boss isn’t <Effect name="Exposed"/> if that means it will be back up right before another burst window.
- Think ahead when CC is needed and swap to Maces earlier to avoid losing invaluable <Skill name="Berserk"/> time.

</Advanced>

**Extra notes:**

- If your groups <Boon name="Might"/> is not 25, take <Skill name="Forgreatjustice"/>. It is a bigger DPS increase than <Skill name="signetofmight"/>!
- If you expect your party to be slow it can make sense to bring <Trait name="smashbrawler"/> and eat the initial <Control name="Stun"/> of <Skill name="headbutt"/>.
- Casting <Skill name="Mending"/> for <Trait name="Peak Performance"/> is only a DPS gain if you can’t be hitting something else, use it right before the start of DPS phases but only use it during if you need the heal.
- Entering <Skill name="Berserk"/> grants three stacks of <Trait name="Berserkers Power"/>, while <Skill name="Decapitate"/> only grants one. You will find <Trait name="Berserkers Power"/> starting to run low when out of <Skill name="Berserk"/>. Try to make sure you are in <Skill name="Berserk"/> for burn phases while also not delaying <Skill name="Berserk"/> where possible.

</GridItem>

<GridItem sm="4">
<Card title="CC skills">

|                              |            |
| ---------------------------- | ---------- |
| <Skill name="wildblow"/>     | 332 damage |
| <Skill name="headbutt"/>     | 300 damage |
| <Skill name="bullscharge"/>  | 300 damage |
| <Skill id="14502"/>          | 150 damage |
| <Skill name="skullgrinder"/> | 100 damage |
| <Skill id="14414"/>          | 300 damage |
| <Skill id="14415"/>          | 300 damage |
| <Skill id="14503"/>          | 100 damage |

**When to take Mace:**

- In fights with only one defiance bar, in the beginning, use Axe/Mace.
- In T4s and encounters that have defiance bars during the fight, use an offhand mace only.

</Card>
</GridItem>
</Grid>

<Divider text="Rotation / Skill usage" />

<Grid>
<GridItem xs="12" sm="6">
<Card title="Information">

Golem rotations out of the raid builds are generally suboptimal in fractals due to <Effect name="Exposed"/> and phases being much shorter compared to raids. The raid rotations are optimized for sustained DPS while in fractals a player needs the ability to adapt a rotation to the amount of time a group needs to finish a phase.  
For that reason, you find suggestions for pressing your axe skills in different estimated phase lengths here.

</Card>

<Advanced>

<Card title="Berserker openers">

<Video caption="by Decados [dT], edited by Vince [dT]" youtube="6z6ZvHxHXek"/>
</Card>
</Advanced>

</GridItem>

<GridItem xs="12" sm="6">

<Card title="Precasting">

<Beginner>

- Stack <Boon name="Might"/>: Use both charges of <Skill name="For Great Justice!"/>.
- If there is a defiance bar present immediately at the start of the fight, start on your Mace set - otherwise swap to it when necessary.
- With <Item name="Paralyzation" type="Sigil"/> you can deal 690 defiance bar damage with:
  - <Skill name="Tremor" />, you can precast it and cancel the aftercast animation.
  - <Skill name="Headbutt" /> with <Item name="Paralyzation" type="Sigil" /> for a total of 390 CC.

</Beginner>

<Advanced>

- Stack <Boon name="Might"/>:
  - Use both charges of <Skill name="For Great Justice!"/>.
  - Drop a fire field with <Skill name="Flames of War"/>.
  - Use <Skill name="Call of Valor"/> and <Skill id="14393"/> on offhand Warhorn to blast <Boon name="Might"/>.
- Precast damage skills:
  - (optional) <Skill name="Flames of War"/>
  - (optional) <Skill id="14393"/> for two stacks of a 25% damage modifier
  - Cast <Skill name="Mending"/> just before the boss becomes vulnerable.
- If there is a defiance bar present immediately at the start of the fight, start on your Mace set - otherwise swap to it when necessary.
- With <Item name="Paralyzation" type="Sigil"/> you can deal 690 defiance bar damage with:
  - <Skill name="Tremor" />, you can precast it and cancel the aftercast animation.
  - <Skill name="Headbutt" /> with <Item name="Paralyzation" type="Sigil" /> for a total of 390 CC.

</Advanced>

</Card>

</GridItem>

<GridItem xs="12" sm="6">

<Card title="Skill usage">

**Ultra short phases (3 seconds):**

- <Skill name="cycloneaxe" />, <Skill name="dualstrike" /> and <Skill name="decapitate" />.

or depending on the phase length:

- <Skill name="cycloneaxe" />, <Skill name="Throw axe" profession="warrior"/> and <Skill name="decapitate" />.
- <Skill name="dualstrike" />, <Skill name="Throw axe" profession="warrior"/> and <Skill name="decapitate" />.

**Short phases (6 seconds):**

- <Skill name="cycloneaxe" />, <Skill name="Throw axe" profession="warrior"/> and <Skill name="decapitate" />.
- <Skill name="dualstrike" />, <Skill name="Throw axe" profession="warrior"/> and <Skill name="decapitate" />.
- <Skill name="whirlingaxe" /> and <Skill name="decapitate" />.
- <Skill name="cycloneaxe" />, <Skill name="chop" /> and <Skill name="decapitate" />.

**Longer phases (>10 seconds):**

- <Skill name="dualstrike" />, <Skill name="Throw axe" profession="warrior" /> and <Skill name="decapitate" />.
- <Skill name="cycloneaxe" />, <Skill name="Throw axe" profession="warrior" /> and <Skill name="decapitate" />.
- <Skill name="whirlingaxe" /> and <Skill name="decapitate" />.
- <Skill name="cycloneaxe" />, <Skill name="chop" /> and <Skill name="decapitate" />.
- <Skill name="Throw axe" profession="warrior" />, <Skill name="dualstrike" /> and <Skill name="decapitate" />.

</Card>

</GridItem>

<GridItem xs="12" sm="6">
<Card title="Golem Rotation">

<Video youtube="NkoFpwfcxfw" caption="by TheCryophoenix.4587"/>
</Card>
</GridItem>
</Grid>
