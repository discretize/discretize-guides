---
title: Power Dragonhunter
hidden: false
archive: false
hasBeginner: true
rating: Meta
role: Power Damage
profession: Guardian
specialization: Dragonhunter
conditions:
  - name: Vulnerability
    uptime: 25 stacks
boons:
  - name: Fury
    uptime: 80%
    variant: group
code: "[&DQEQLio6GzkmDwAAihIAAEgBTAH+ABYBiRI3AQAAAAAAAAAAAAAAAAAAAAA=]"
cmGuide: static
classification:
  - 3
  - 4
  - 3
  - 2
  - 4
date: 2022-05-04T08:07:50.682Z
---

The <Specialization name="Dragonhunter"/> is a good and easy to play build for fractals. It has great burst options and deals high consistent damage while providing medium defiance bar damage and high <Condition name="Vulnerability"/>. The build offers a unique party wide offensive buff by sharing <Skill name="bane signet"/> for 216 <Attribute name="Power"/> and also strong on-demand defensive support with <Skill id="30039"/> and other useful skills such as <Skill id="9251"/> and <Skill name="standyourground"/>.

The <Specialization name="Dragonhunter" text="Power Dragonhunter"/> has access to blocks with <Skill name="Shieldofwrath"/>, <Skill name="shieldofcourage"/> and a very strong heal skill (<Skill name="litanyofwrath"/>) that makes the player invincible for 6 seconds. It also benefits from slaying potions and slaying sigils such as <Item id="50082"/> and <Item name="Serpent Slaying" type="Sigil"/>.

Unfortunately, the <Specialization name="Dragonhunter"/> is relying on fast CC to capitalize on the immediate high burst damage. Playing this build in slower groups therefore might not be as rewarding as the condi builds of <Specialization name="Guardian"/>. Sharing <Skill name="bane signet"/> with a party that can't capitalize on the unique buff might also be frustrating.

<Beginner>

Before progressing to the advanced version of this page, we recommend acquiring an in-depth understanding of your CC skills and when to use them efficiently. You should be able to hit consistently high DPS, which you can verify with [arc-dps](https://www.deltaconnected.com/arcdps/). And finally, you should be able to execute the basic step-by-step rotation provided below without spending too much thought on it.

The advanced page provides a more complete overview of all the utilities the <Specialization name="Guardian"/> has to offer. If you ever feel like you are missing information feel free to already swap to the advanced page!

<Information>

Although this build lists 162 <Attribute name="Agony Resistance"/>, it is not a strict requirement! We recommend getting started with this build anyway - even if it might be suboptimal while being in Tier 1 or 2 fractals. Keep upgrading your <Attribute name="Agony Resistance"/> until you reach the suggested variant. In the beginning, it is much more important to learn about fractal mechanics and your skills rather than equipping optimal gear.

</Information>

</Beginner>

<Divider text="Equipment"/>

<CharacterWithAr>  
<Character title="162 AR (No Banner)" gear={{
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
    "Assassin",
    "Assassin",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker"
  ],
  "attributes": {
    "Health": 13995,
    "Armor": 2514,
    "Power": 3761,
    "Precision": 2365,
    "Toughness": 1243,
    "Vitality": 1235,
    "Ferocity": 1555,
    "Condition Damage": 750,
    "Expertise": 0,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0,
    "Boon Duration": 0.162,
    "Critical Chance": 1,
    "Critical Damage": 2.5366666666666666,
    "Power Coefficient": 3361,
    "Burning Coefficient": 1.92,
    "Bleeding Coefficient": 0,
    "Poison Coefficient": 0,
    "Torment Coefficient": 0,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Siphon Base Coefficient": 139.75,
    "Effective Power": 33639.14067555104,
    "Power DPS": 43535.29141722258,
    "Siphon DPS": 139.75,
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
    "Damage": 44357.45141722258,
    "Effective Health": 77796417.91044776,
    "Survivability": 39550.797107497594,
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
    "weapon1MainType": "Greatsword",
    "weapon1MainSigil1Id": 24615,
    "weapon1MainSigil2Id": 24868,
    "weapon2MainType": "Sword",
    "weapon2MainSigil1Id": 24615,
    "weapon2OffType": "Focus",
    "weapon2OffSigilId": 24868
  },
  "consumables": {
    "foodId": 91805,
    "utilityId": 9443,
    "infusion": "Mighty +9 Agony Infusion"
  },
  "skills": {
    "healId": 21664,
    "utility1Id": 9168,
    "utility2Id": 30364,
    "utility3Id": 9093,
    "eliteId": 29965
  },
  "assumedBuffs": [{ "type": "Item", "gw2id": 79722 }, { "type": "Item", "gw2id": 96613 }, 
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
      "id": "frostSpirit",
      "gw2id": 12497,
      "type": "Skill"
    },
    {
      "id": "jade-bot-base",
      "type": "Text"
    },
    {
      "id": "jade-bot-per-tier",
      "type": "Text"
    },
    {
      "id": "assassinsPresence",
      "gw2id": 1786,
      "type": "Trait"
    }
  ]
}}>

This build assumes you have neither <Skill name="Banner of Discipline"/> nor <Trait name="Spotter"/>. Start here if you don't know what to do.

If you cannot maintain good <Boon name="resolution"/> uptime during your bursts, you may want to play with <Trait name="Healers resolution"/>. By playing this trait you will lose <Attribute name="Precision"/> so will need to adjust your gear to [Crit Cap](/guides/crit-cap/).

Check the [gear optimizer](https://optimizer.discretize.eu/) for more gear variants!

</Character>
<Character advanced title="162 AR (Banner)" gear={{
   "profession":"Guardian",
   "weight":"Heavy",
   "gear":[
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
   "attributes":{
      "Health":14265,
      "Armor":2514,
      "Power":3832,
      "Precision":2370,
      "Toughness":1243,
      "Vitality":1262,
      "Ferocity":1567,
      "Condition Damage":750,
      "Expertise":0,
      "Concentration":243,
      "Healing Power":0,
      "Agony Resistance":162,
      "Condition Duration":0,
      "Boon Duration":0.162,
      "Critical Chance":1.0023809523809524,
      "Critical Damage":2.5446666666666666,
      "Power Coefficient":3361,
      "Burning Coefficient":1.92,
      "Bleeding Coefficient":0,
      "Poison Coefficient":0,
      "Torment Coefficient":0,
      "Confusion Coefficient":0,
      "Flat DPS":0,
      "Siphon Base Coefficient":139.75,
      "Effective Power":34382.27098304175,
      "Power DPS":44497.03995918496,
      "Siphon DPS":139.75,
      "Bleeding Damage":96.3125,
      "Bleeding Stacks":0,
      "Bleeding DPS":0,
      "Burning Damage":355.421875,
      "Burning Stacks":1.92,
      "Burning DPS":682.41,
      "Confusion Damage":118.665625,
      "Confusion Stacks":0,
      "Confusion DPS":0,
      "Poison Damage":112.84375,
      "Poison Stacks":0,
      "Poison DPS":0,
      "Torment Damage":142.74375,
      "Torment Stacks":0,
      "Torment DPS":0,
      "Damage":45319.19995918496,
      "Effective Health":53129200,
      "Survivability":27010.269445856633,
      "Effective Healing":390,
      "Healing":390
   },
   "runeId":24836,
   "runeName":"Scholar",
   "infusions":[
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
   "weapons":{
      "weapon1MainType":"Greatsword",
      "weapon1MainSigil1Id":24615,
      "weapon1MainSigil2Id":24868,
      "weapon2MainType":"Sword",
      "weapon2MainSigil1Id":24615,
      "weapon2OffType":"Focus",
      "weapon2OffSigilId":24868
   },
   "consumables":{
      "foodId":91805,
      "utilityId":9443,
      "infusion": "Mighty +9 Agony Infusion"
   },
   "skills":{
      "healId":21664,
      "utility1Id":9168,
      "utility2Id":30364,
      "utility3Id":9093,
      "eliteId":29965
   },
   "assumedBuffs":[
      {
         "id":"might",
         "type":"Boon"
      },
      {
         "id":"fury",
         "type":"Boon"
      },
      {
         "id":"vulnerability",
         "type":"Condition"
      },
      {
         "id":"spotter",
         "gw2id":1016,
         "type":"Trait"
      },
      {
         "id":"frostSpirit",
         "gw2id":12497,
         "type":"Skill"
      },
      {
         "id":"jade-bot-base",
         "type":"Text"
      },
      {
         "id":"jade-bot-per-tier",
         "type":"Text"
      },
      {
         "id":"assassinsPresence",
         "gw2id":1786,
         "type":"Trait"
      }
   ]
}}>

This build assumes you have either <Skill name="Banner of Discipline"/> or <Trait name="Spotter"/>.

If you cannot maintain good <Boon name="resolution"/> uptime during your bursts, you may want to play with <Trait name="Healers resolution"/>. By playing this trait you will lose <Attribute name="Precision"/> so will need to adjust your gear to [Crit Cap](/guides/crit-cap/).

Check the [gear optimizer](https://optimizer.discretize.eu/) for more gear variants!

</Character>

<Character advanced title="222 AR (No Banner)" gear={{
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
      "utility1": "Procession of Blades",
      "utility2": "Sword of Justice",
      "utility3": "Bane Signet",
      "elite": "Dragons Maw"
    },
    "assumedBuffs": [{ "type": "Item", "gw2id": 79722 }, { "type": "Item", "gw2id": 96613 }, {"id": "Might", "type": "Boon"}, {"id": "Fury", "type": "Boon"}, {"gw2id": 1786, "type": "Trait"}, {"gw2id": 12497, "type": "Skill"}, {"gw2id": 9093, "type": "Skill"}]
}}>

This build assumes you have neither <Skill name="Banner of Discipline"/> nor <Trait name="Spotter"/>.

If you cannot maintaingood <Boon name="resolution"/> uptime during your bursts, you may want to play with <Trait name="Healers resolution"/>. By playing this trait you will lose <Attribute name="Precision"/> so will need to adjust your gear to [Crit Cap](/guides/crit-cap/).

Check the [gear optimizer](https://optimizer.discretize.eu/) for more gear variants!

</Character>

<Character advanced title="222 AR (Banner)" gear={{
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
      "utility1": "Procession of Blades",
      "utility2": "Sword of Justice",
      "utility3": "Bane Signet",
      "elite": "Dragons Maw"
    },
    "assumedBuffs": [{ "type": "Item", "gw2id": 79722 }, { "type": "Item", "gw2id": 96613 }, {"id": "Might", "type": "Boon"}, {"id": "Fury", "type": "Boon"}, {"gw2id": 1786, "type": "Trait"}, {"gw2id": 12497, "type": "Skill"}, {"gw2id": 1016, "type": "Trait"}, {"gw2id": 9093, "type": "Skill"}]
}}>

This build assumes you have either <Skill name="Banner of Discipline"/> or <Trait name="Spotter"/>.

If you cannot maintain good <Boon name="resolution"/> uptime during your bursts, you may want to play with <Trait name="Healers resolution"/>. By playing this trait you will lose <Attribute name="Precision"/> so will need to adjust your gear to [Crit Cap](/guides/crit-cap/).

Check the [gear optimizer](https://optimizer.discretize.eu/) for more gear variants!

</Character>  
</CharacterWithAr>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1Id="16" traits1="Radiance" traits1SelectedIds="566,565,579" traits2Id="42" traits2="Zeal" traits2SelectedIds="634,653,2017" traits3Id="27" traits3="Dragonhunter" traits3SelectedIds="1898,1835,1955"/>

<Advanced>

<Card title="Virtues">

If you can reliably upkeep <Boon name="Aegis"/>, and you don't gain value from sharing <Skill name="Bane Signet"/> through <Trait name="Perfect Inscriptions"/>. You can drop the Radiance trait line for Virtues for more personal damage. Please note you will need to adjust your gear potentially to crit cap! Check the [gear optimizer](https://optimizer.discretize.eu) for more gear variants!

<Traits unembossed traits1="Virtues" traits1Selected="Unscathed Contender,Inspiring Virtue,Permeating Wrath"/>

</Card>

</Advanced>
  
<Card title="CC skills">

|                                                 |            |
| ----------------------------------------------- | ---------- |
| <Skill id="9093"/>                              | 300 damage |
| <Skill id="9226"/> (after <Skill id="9147"/>)   | 150 damage |
| <Skill id="33134"/> (after <Skill id="29887"/>) | 150 damage |
| <Skill id="30273"/>                             | 150 damage |
| <Skill name="chainsoflight"/>                   | 250 damage |
| <Skill name="hammerofwisdom"/>                  | 200 damage |
| <Skill name="sanctuary"/>                       | 750 damage |

</Card>
</GridItem>

<GridItem sm="5">
<Card title="Situational Skills">

<Beginner>

You should drop <Skill name="Swordofjustice"/> first.

|                                                   |                                                                                          |
| ------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| <Skill id="9153" size="big" disableText/>         | When <Boon name="Stability"/> or a stunbreak is needed.                                  |
| <Skill id="9125" size="big" disableText/>         | Deals an additional 200 defiance bar damage.                                             |
| <Skill id="9251" size="big" disableText/>         | A stationary reflect lasting for 10 seconds.                                             |
| <Skill name="dragonsmaw" size="big" disableText/> | When you are certain no extra <Boon name="Quickness"/> or <Boon name="Fury"/> is needed. |
| <Skill name="Sanctuary" size="big" disableText/>  | Huge CC and projectile destruction.                                                      |

</Beginner>

<Advanced>

|                                                        |                                                                                                                                |
| ------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ |
| <Skill id="9246" size="big" disableText/>              | A 1,200 range teleport to an ally.                                                                                             |
| <Skill name="Hallowed Ground" size="big" disableText/> | When <Boon name="Stability"/> is needed. Also useful for precasting a fire field and <Boon name="resolution"/> at the mistlock |
| <Skill name="Advance" size="big" disableText/>         | When <Boon name="Aegis"/> is needed.                                                                                           |
| <Skill id="9153" size="big" disableText/>              | When <Boon name="Stability"/> or a stunbreak is needed.                                                                        |
| <Skill id="9125" size="big" disableText/>              | Deals an additional 200 defiance bar damage.                                                                                   |
| <Skill id="9251" size="big" disableText/>              | A stationary reflect lasting for 10 seconds.                                                                                   |
| <Skill name="feelmywrath" size="big" disableText/>     | When <Boon name="Quickness"/> or <Boon name="Fury"/> is needed.                                                                |
| <Skill id="9247" size="big" disableText/>              | A 1200 range teleport to an enemy.                                                                                             |
| <Skill name="Purging flames" size="big" disableText/>  | Cleanses conditions.                                                                                                           |
| <Skill name="Sanctuary" size="big" disableText/>       | Huge CC and projectile destruction.                                                                                            |
| <Skill name="testoffaith" size="big" disableText/>     | Can be precasted for a bit of extra damage.                                                                                    |
| <Skill name="renewed focus" size="big" disableText/>   | Recharges all virtue skills, grants <Effect name="Invulnerability"/> for 3 seconds.                                            |

</Advanced>

</Card>
</GridItem>
</Grid>

<Advanced>
<Divider text="Details"/>

As a <Specialization name="Dragonhunter" text="Power Dragonhunter"/> it is important to play <Trait name="perfectinscriptions"/> to be able to use the <Skill name="Banesignet"/> for 300 CC while also sharing the 216 <Attribute name="Power"/> buff with your allies. This enables everyone to deal more damage during critical parts of the fight when the boss is <Effect name="exposed"/>.

Generally it is important to apply <Boon name="Resolution"/> when you are about to burst for the <Trait name="retribution"/> modifier. Thanks to <Trait name="healersresolution"/> your heal skill applies long lasting <Trait name="retribution"/>. Since <Skill name="litanyofwrath"/> and <Skill name="processionofblades"/> have almost the same cooldown they will line up well (<Skill name="processionofblades"/> has a slightly shorter cooldown thanks to <Trait name="piercinglight"/>). You can also trigger a <Skill id="13677"/> by losing health below the 75% threshold to trigger <Trait id="648"/>, however you need to be careful to not die.

</Advanced>

<Divider text="Rotation / Skill Usage"/>

<Grid>

<GridItem xs="12" sm="7">

<Advanced>

<Card title="Information">

Golem rotations out of the raid builds are generally suboptimal in fractals due to <Effect name="Exposed"/> and phases being much shorter compared to raids. The raid rotations are optimized for sustained DPS while in fractals a player needs the ability to adapt their rotation to the amount of time a group needs to finish a phase.\
For that reason, you will find some general notes for skill usage here.
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

<Card title="Notes on skill usage:">

- Always start on the sword
- Delay swapping to GS until the CC-bar is about to be broken. This is especially important at Ensolyss without instant CC.
- Always cast your <Skill name="whirlingwrath"/> inside the hitbox to get the additional hits. Ideal with adds around.
- Always cast your <Skill name="bindingblade"/> inside the hitbox to get the additional hits when adds are present. Can be abused at **Artsariiv**, **Arkk**, **Siax**, and **Ensolyss**.
- Don't interrupt your GS auto-attack chain.
- In certain scenarios (precasting traps, starting with <Skill name="onewolfpack"/>) it can be beneficial to get your <Skill name="spearofjustice"/> out first.
- Don't waste your key skills on meaningless adds.

</Card>

</Advanced>

<Beginner>

<Card title="Step-by-Step Rotation">

**Step 0: Bane Signet**

The <Skill name="Bane Signet"/> grants you a passive boost to your <Attribute name="Power"/>. Its active effect (when clicked) will inflict a high amount of CC (300 CC) on your target and share the passive with your allies for 10 seconds through <Trait name="Perfect Inscriptions"/>. Therefore, you want to do the following:

- If a Mistlock Singularity is present, cast <Skill name="Bane Signet"/> there to share its buff right before you run into the fight, then take the singularity.
- If a boss starts with a break bar, you should cast <Skill name="Bane Signet"/> at the start to help with breaking the bar while also sharing its passive to your allies to enhance their burst damage as well.
- If a boss does not get a break bar early into the fight, you can use <Skill name="Bane Signet"/> before the fight starts to share the passive and start right with your burst when the boss spawns.

**Step 1: Greatsword Skills**

The first step consists of using <Skill name="Symbol of Resolution"/>, <Skill name="Whirling Wrath"/> and <Skill name="Binding Blade"/> off-cooldown (in this order of priority if multiple come up at the same time).

- <Skill name="Symbol of Resolution"/> and <Skill name="Whirling Wrath"/> are your 2 biggest damaging weapon skills on the Greatsword.
- Make sure to be in the hitbox of the enemy whenever possible for <Skill name="Whirling Wrath"/>. <Skill name="Whirling Wrath"/> deals additional damage when casted inside a hitbox.
- <Skill name="Binding Blade"/> will deal more damage if you are in the hitbox while there are extra enemies around.

**Step 2: Trap + F1 Combo**

Next up, it is time to incorporate <Skill name="Spear of Justice"/> and <Skill name="Procession of Blades"/>.

- Try to always wait until both skills are up again and then cast <Skill name="Procession of Blades"/> first, followed by <Skill name="Spear of Justice"/>.
- Using <Skill name="Spear of Justice"/> will tether you to your target making you deal increased damage while it is active due to <Trait name="Big Game Hunter"/>.
- Your trap <Skill name="Procession of Blades"/> deals high damage and you therefore should always cast it while being tethered to your target.
- If you kill certain enemies, your <Skill name="Spear of Justice"/> will reset due to <Trait name="Renewed Justice"/>. Wait until you get your trap back to cast both of them unless the boss will phase or die before this happens.

The opener at this step looks like this:

1. <Skill name="Procession of Blades"/>
2. <Skill name="Spear of Justice"/>
3. <Skill name="Symbol of Resolution"/>
4. <Skill name="Whirling Wrath"/>
5. <Skill name="Binding Blade"/>

**Step 3: Sword of Justice**

Now it is time to incorporate another strong utility skill, <Skill name="Sword of Justice"/>.

- <Skill name="Sword of Justice"/> has 3 maximum charges. It summons a sword that will deal damage and inflict <Condition name="Vulnerability"/> on nearby enemies while it is active.
- Its recharge time aligns with the cooldown of <Skill name="Spear of Justice"/> so we will always use 1 charge right before we cast our Trap + F1. This will enhance the burst damage further.
- The other charges may be used between other skill casts in our opener or any time we do not have another skill ready to use as we should always get one charge back when our F1 comes back up for our burst due to them having the same cooldown. Try to use them while tethered to an enemy with <Skill name="Spear of Justice"/> for the extra damage.

**Step 4: Sword skills**

This last step will not contribute much to your consistent DPS but can increase your burst by a good amount which is especially important in fights with shorter phases. We will use <Skill name="Symbol of Blades"/> and <Skill name="Zealots Defense"/> at the start of the fight, then swap to Greatsword and do our regular rotation.

The opener should now look like this:

1. <Skill name="Sword of Justice"/>
2. <Skill name="Procession of Blades"/>
3. <Skill name="Spear of Justice"/>
4. <Skill name="Symbol of Blades"/>
5. <Skill name="Zealots Defense"/>
6. Swap to Greatsword
7. <Skill name="Symbol of Resolution"/>
8. <Skill name="Whirling Wrath"/>
9. <Skill name="Binding Blade"/>

</Card>

<Card title="Improving Further">

Once you are comfortable with the above steps, you are already doing most of the full rotation and will be able to deal great burst damage and good consistent damage.

There will be a few additional things on the advanced page to improve further but if you got here, you already know the most important things and these will have a smaller impact than what you learned so far.

The additional steps are:

- Incorporate your Focus skills into the rotation, namely <Skill name="Ray of Judgment"/> and <Skill name="Shield of Wrath"/>.
- Weapon swap more often on fights with long phases, usually after using <Skill name="Whirling Wrath"/>/<Skill name="Zealots Defense"/> twice on the respective weapon set.
- Precasts: You can cast lasting skills such as <Skill name="Symbol of Blades"/> before the fight starts to get your damage up earlier and have 1 less cast in your opener.

</Card>

</Beginner>

</GridItem>

<GridItem xs="12" sm="5">

<Advanced>
<Card title="Standard Opener">

**Rotation:**

1.  <Skill name="banesignet" profession="guardian"/>
2.  <Skill name="Symbol of Blades" profession="guardian"/> (Sword 2)
3.  <Skill name="Shield of Wrath" profession="guardian"/> (Focus 5)
4.  <Skill name="Sword of Justice" profession="guardian"/>
5.  <Skill name="Procession of Blades " profession="guardian"/>
6.  <Skill name="spearofjustice" profession="guardian"/> (F1)
7.  <Skill name="Zealotsdefense" profession="guardian"/> (Sword 3)
8.  <Skill name="Ray of Judgment" profession="guardian"/> (Focus 4)
9.  **Weapon Swap**
10. <Skill name="Symbol of Resolution" profession="guardian"/> (GS 4)
11. <Skill name="Whirling Wrath" profession="guardian"/> (GS 2)
12. <Skill name="Sword of Justice" profession="guardian"/>
13. <Skill name="Dragons Maw" profession="guardian"/>
14. <Skill name="Sword of Justice" profession="guardian"/>
15. <Skill name="Leap of Faith" profession="guardian"/> (GS 3)
16. <Skill name="Binding Blade" profession="guardian"/> (GS 5)
17. If the phase lasts longer than this, continue with the SC rotation.

</Card>
</Advanced>

<Beginner>

<Card title="Step-by-Step Video">

This video shows the step-by-step approach to the rotation listed on the left.

<Video youtube="03nlPL24KWE" caption="by Ascers"/>

</Card>

</Beginner>

<Card title="Golem Rotation">

This video shows the full rotation on the golem. It will slightly vary from the step-by-step version. It also uses the raid setup so numbers will not be comparable.

<Video youtube="faIaiHFG1qI" caption="by Nagy"/>
</Card>
</GridItem>

</Grid>

<Divider text="Underwater combat"/>

It is very much recommended to play <BuildLink build="Condi Firebrand" specialization="Firebrand"/> since it provides much better DPS compared to the <Specialization text="Power Dragonhunter" name="Dragonhunter"/>. If you still want to play <Specialization text="Power Dragonhunter" name="Dragonhunter"/> for whatever reason follow these rough guidelines.

- Open with <Skill name="refraction"/> for <Boon name="resolution"/>
- Cast <Skill name="purify"/> and swap to spear. Camp spear now.
- Priority list:
  1.  <Skill name="Zealots flurry"/> (Spear 2)
  2.  <Skill name="Symbol of spears"/> (Spear 4)
  3.  <Skill name="brilliance"/> (Spear 3)
