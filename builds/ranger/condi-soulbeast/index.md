---
title: Condi Soulbeast
rating: Meta
role: Condi Damage
profession: Ranger
skills:
  - 45717
  - 12498
  - 12508
  - 46432
classification:
  - 5
  - 4
  - 3
  - 2
  - 3
compositions:
  - name: _CRGB
    roles: DPS/CC/Quickness,DPS/CC/Quickness,DPS/Moa,DPS/Sun Spirit,DPS/Alacrity/CC
    composition: Firebrand,Firebrand,Soulbeast,Soulbeast,Renegade
specialization: Soulbeast
code: "[&DQQeLSE3Ny55AAAAAAAAAL8AAADpFgAALhYAADQlAAAAAAAAAAAAAAAAAAA=]"
date: 2022-03-28T17:42:00.313Z
conditions:
  - Bleeding
  - Poisoned
  - Burning
cmGuide: pug
benchmark:
  small:
    dps: 36197
    by: Eren
    youtube: WSuDmiuAwC8
---

<Warning>

This build is [META](/guides/meta-explained) in full condi groups. In power groups this build will fall massively behind <Specialization name="Soulbeast" text="Power Soulbeast"/> - the power damage counterpart.
</Warning>

Condi <Specialization name="Soulbeast"/> is a DPS build with high sustained damage and reasonable burst that also provides strong party buffs with <Skill name="Sun Spirit"/> and <Skill name="One Wolf Pack"/>, and crowd control (CC) skills. This build is mostly used for 100CM, for most other fractals, especially if your group are playing power builds, you will be better off playing the power variant found [here](/builds/ranger/power-soulbeast/).

This build is rather self sufficient due to:

- Boon extension by <Trait name="Essence of speed"/>, <Skill name="We heal as one"/>

- Good CC with <Skill id="46432"/> and <Skill name="Concussion Shot"/>

- High mobility via <Skill name="Instinctive Engage"/> and <Skill name="Quick Shot"/>

Overall this is a very well rounded build that is rewarding to play in both PuGs and organized teams alike.

<Divider text="Equipment"/>

<CharacterWithAr>
<Character title="Krait Runes" gear={{
  "profession": "Ranger",
  "weight": "medium",
  "gear": [
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper"
  ],
  "attributes": {
    "Health": 19472,
    "Armor": 2361,
    "Power": 2923,
    "Precision": 1976,
    "Toughness": 1243,
    "Vitality": 1355,
    "Ferocity": 150,
    "Condition Damage": 2732,
    "Expertise": 797,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0.5313333333333333,
    "Boon Duration": 0.162,
    "Critical Chance": 0.8147619047619048,
    "Critical Damage": 1.6,
    "Power Coefficient": 1591,
    "Burning Coefficient": 2.42,
    "Bleeding Coefficient": 27.82755714285714,
    "Poison Coefficient": 16.41,
    "Torment Coefficient": 0.16,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Bleeding Duration": 0.5,
    "Siphon Base Coefficient": 139.75,
    "Effective Power": 8223.37864866964,
    "Power DPS": 5037.888113220408,
    "Siphon DPS": 5037.888113220408,
    "Bleeding Damage": 384.81953999999996,
    "Bleeding Stacks": 55.65511428571428,
    "Bleeding DPS": 21417.175478076,
    "Burning Damage": 862.878375,
    "Burning Stacks": 3.705826666666667,
    "Burning DPS": 3197.6776921650003,
    "Confusion Damage": 341.298075,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 384.04359374999996,
    "Poison Stacks": 25.12918,
    "Poison DPS": 9650.700595190625,
    "Torment Damage": 432.1395,
    "Torment Stacks": 0.24501333333333336,
    "Torment DPS": 105.87993936000001,
    "Damage": 39549.07181801203,
    "Effective Health": 91489337.31343284,
    "Survivability": 46512.11861384486,
    "Effective Healing": 390,
    "Healing": 390
  },
  "runeId": 24762,
  "runeName": "Krait",
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
    "weapon1MainType": "Short Bow",
    "weapon1MainSigil1Id": 44944,
    "weapon1MainSigil2Id": 24560,
    "weapon2MainType": "Dagger",
    "weapon2MainSigil1Id": 44944,
    "weapon2OffType": "Torch",
    "weapon2OffSigilId": 24560
  },
  "consumables": {
    "foodId": 91878,
    "utilityId": 48917
  },
  "skills": {
    "healId": 31914,
    "utility1Id": 40498,
    "utility2Id": 12537,
    "utility3Id": 12498,
    "eliteId": 45717
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
}} >

If you do not have a Jade Bot Core: Tier 10, you will have slightly lower duration on your non-bleeding conditions but the build does not change!

</Character>

<Character title="Afflicted Runes" gear={{
  "profession": "Ranger",
  "weight": "medium",
  "gear": [
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper"
  ],
  "attributes": {
    "Health": 19472,
    "Armor": 2361,
    "Power": 2923,
    "Precision": 1976,
    "Toughness": 1243,
    "Vitality": 1355,
    "Ferocity": 150,
    "Condition Damage": 2632,
    "Expertise": 897,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0.798,
    "Boon Duration": 0.162,
    "Critical Chance": 0.8147619047619048,
    "Critical Damage": 1.6,
    "Power Coefficient": 1591,
    "Burning Coefficient": 2.42,
    "Bleeding Coefficient": 27.66755714285714,
    "Poison Coefficient": 16.25,
    "Torment Coefficient": 0,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Bleeding Duration": 0.2,
    "Poison Duration": 0.1,
    "Siphon Base Coefficient": 139.75,
    "Effective Power": 8223.37864866964,
    "Power DPS": 5037.888113220408,
    "Siphon DPS": 5037.888113220408,
    "Bleeding Damage": 357.44481499999995,
    "Bleeding Stacks": 55.27977917142857,
    "Bleeding DPS": 19759.470439172135,
    "Burning Damage": 805.0715,
    "Burning Stacks": 4.35116,
    "Burning DPS": 3502.9949079400003,
    "Confusion Damage": 317.28445,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 357.41703125,
    "Poison Stacks": 30.8425,
    "Poison DPS": 11023.634786328124,
    "Torment Damage": 401.34075,
    "Torment Stacks": 0,
    "Torment DPS": 0,
    "Damage": 39463.738246660665,
    "Effective Health": 91489337.31343284,
    "Survivability": 46512.11861384486,
    "Effective Healing": 390,
    "Healing": 390
  },
  "runeId": 24687,
  "runeName": "Afflicted",
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
    "weapon1MainType": "Short Bow",
    "weapon1MainSigil1Id": 44950,
    "weapon1MainSigil2Id": 24560,
    "weapon2MainType": "Dagger",
    "weapon2MainSigil1Id": 44950,
    "weapon2OffType": "Torch",
    "weapon2OffSigilId": 24560
  },
  "consumables": {
    "foodId": 91876,
    "utilityId": 48917
  },
  "skills": {
    "healId": 31914,
    "utility1Id": 40498,
    "utility2Id": 12537,
    "utility3Id": 12498,
    "eliteId": 45717
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
}} >

This builds damage depends on the amount of <Specialization name="Soulbeast" text="Condi Soulbeasts"/> in the party. The build deals similar DPS with 2 <Specialization name="Soulbeast" text="Condi Soulbeasts"/>, and outperforms the Krait build if you have 3 <Specialization name="Soulbeast" text="Condi Soulbeasts"/> in the party. If you are going to be on your own run the Krait rune setup!

This build uses the Jade Bot Core: Tier 10 in combination with 14 <Item name="Spiteful +9 Agony Infusion"/> to cap Bleeding duration. If you do not have the Jade Core, run all 18 <Item name="Spiteful +9 Agony Infusion"/>.

</Character> 
</CharacterWithAr>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1Id="33" traits1="Wilderness Survival" traits1SelectedIds="1099,1101,1701" traits2Id="30" traits2="Skirmishing" traits2SelectedIds="1069,1846,1912" traits3Id="55" traits3="Soulbeast" traits3SelectedIds="2071,2161,2128"/>
</GridItem>

<GridItem sm="5">
<Card title="Situational Skills">

|                                                       |                                                                                                                                                                                                                                                                                     |
| ----------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <Skill name="Sun Spirit" size="big" disableText/>     | Your standard 3rd utility. Provides a partywide damage increase by causing you and allies to periodically inflict <Condition name="Burning"/>.                                                                                                                                      |
| <Skill name="Moa Stance" size="big" disableText/>     | A replacement for <Skill name="Sun Spirit"/>, this allows your <Specialization name="Renegade"/> to lower their boon duration and deal substantially more DPS! Alternatively if you have more than one <Specialization name="Soulbeast"/>, one can drop <Skill name="Sun Spirit"/>. |
| <Skill name="Vipers Nest" size="big" disableText/>    | A replacement for <Skill name="Sun Spirit"/>. Only taken if you do not need to provide <Skill name="Sun Spirit"/> or <Skill name="Moa Stance"/>.                                                                                                                                    |
| <Skill name="Bear stance" size="big" disableText/>    | Area condi cleanse, also for allies if you play <Trait name="leaderofthepack"/>.                                                                                                                                                                                                    |
| <Skill name="Healing Spring" size="big" disableText/> | Area condi cleanse, taken if you are playing <Trait name="Oppressivesuperiority"/> or your party needs a long lasting condi cleanse. Very useful on 100CM!                                                                                                                          |

</Card>
<Card title="Pets">

|                                            |                                                                                                                                                                                                                                                                                                               |
| ------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <Skill id="46432" size="big" disableText/> | [Warthog](https://wiki.guildwars2.com/wiki/Juvenile_Warthog) - Best CDPS pet that also brings CC, also this is the pet you use in <Skill id="42944"/>.                                                                                                                                                        |
| <Skill id="45479" size="big" disableText/> | [Bristleback](https://wiki.guildwars2.com/wiki/Juvenile_Bristleback) - Used to precast some extra Bleeding. Is also the best CDPS pet for when there are multiple targets. Only take Bristleback if you can consistently get 5+ hits from <Skill name="Rain of Spikes"/> without delaying the skill too much. |
| <Skill id="44514" size="big" disableText/> | [Lynx](https://wiki.guildwars2.com/wiki/Juvenile_Lynx) - Best single target CDPS pet. Taken if you don't need the CC from Warthog                                                                                                                                                                             |

</Card>
</GridItem>
</Grid>

<Divider text="Further information"/>

<Grid>
<GridItem sm="7">
<Card title="Situational Traits">

|                                                         |                                                                                                                                |
| ------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| <Trait name="Essence of Speed" size="big" disableText/> | Take this instead of <Trait name="Predators Cunning"/> if boon uptime in your party is bad and you want some extra generation. |

</Card>

<Card title="Off-hand Dagger">

Running an off-hand Dagger is similar DPS to Torch providing you can flank permanently and your group can't make use of the fire field from <Skill name="Bonfire"/>. It also has the benefit of having an evade through using <Skill id="12478"/>.

</Card>
<Card title="Swap Weapons">

- A <Item id="75325"/> (selected attribute does not matter!) to blast might when prestacking boons.
- A weapon set to precast <Item id="24609"/> and <Item id="24599"/> before getting into fight.

</Card>
</GridItem>

<GridItem sm="5">

<Card title="Defiance Bar Damage">

|                                            |                                                                                   |
| ------------------------------------------ | --------------------------------------------------------------------------------- |
| <Skill id="46432" size="big" disableText/> | 300 damage (F2 in <Skill id="42944"/>)                                            |
| <Skill id="12508" size="big" disableText/> | 200 damage (Shortbow 5)                                                           |
| <Skill id="12507" size="big" disableText/> | 50/s <Condition name="Immobile"/>, 15/s <Condition name="Crippled"/> (Shortbow 4) |
| <Skill id="12490" size="big" disableText/> | 33/s <Condition name="Chilled"/>, 20/s <Condition name="Weakness"/> (Axe 3)       |

</Card>
</GridItem>
</Grid>

<Divider text="Rotation / Skill usage"/>

<Grid>
<GridItem sm="6">
<Card title="Information">

When playing <Specialization name="Soulbeast" text="Condi Soulbeast"/> in 100CM, <Trait name="Light on your Feet"/> is much more attractive choice than <Trait name="Quickdraw"/> which is used in raids. The reason being that Ai moves around far too much for you to be able to benefit from using skills like <Skill name="Bonfire"/> twice in most cases. Also with some strategic dodging during movement and downtime you can keep a very high <Trait name="Light on your Feet"/> uptime especially during your bursts which leads to very high DPS.

The rotation in general is very simple, just keep rotating between your Shortbow and Dagger/Torch set using your utility skills as often as you can. When you get to the point of auto attacking use your <Skill id="42944"/> skills to fill.
</Card>
<Card title="Shortbow Golem Rotation">

1.  <Skill name="Vipers Nest"/>
2.  <Skill name="One Wolf Pack"/>
3.  <Skill name="Poison Volley"/>
4.  <Skill name="Crippling Shot"/>
5.  <Skill name="Concussion Shot"/>
6.  `Weapon Swap`
7.  <Skill name="Vulture Stance"/> + <Skill name="Sharpening Stone"/>
8.  <Skill name="Double Arc"/>
9.  <Skill name="Throw Torch"/>
10. <Skill name="Bonfire"/>
11. <Skill id="44514"/>
12. <Skill name="Primal Cry"/>
13. `Autoattack chain x2`
14. <Skill name="Double Arc"/>
15. `Autoattack chain x3`
16. <Skill name="Double Arc"/>
17. <Skill name="Throw Torch"/>
18. `Weapon Swap`
19. <Skill name="Poison Volley"/>
20. <Skill name="Crippling Shot"/>
21. `Autoattack`
22. <Skill id="44514"/>
23. `Autoattack`
24. <Skill name="Concussion Shot"/>
25. <Skill name="Poison Volley"/>
26. `Autoattack`
27. <Skill name="Primal Cry"/>
28. `Autoattack`
29. <Skill name="Poison Volley"/>
30. `Autoattack`
31. <Skill name="Crippling Shot"/>
32. Repeat from `Step 5`

</Card>
</GridItem>

<GridItem sm="6">
<Card title="Shortbow Golem Rotation">

<Video youtube="iKKWM4F3ayg" caption="by Eren"/>
</Card>
<Card title="Precasting">

When precasting in fractals we want to stack as many useful boons with as much duration as possible, these being <Boon name="Might"/>, <Boon name="Fury"/>, <Boon name="Quickness"/>, <Boon name="Alacrity"/> and <Boon name="Swiftness"/>. We can also cast useful unique effects, for a <Specialization name="Soulbeast" text="Condi Soulbeast"/> this means your stances such as <Skill name="Vulture Stance"/>, <Skill name="Moa Stance"/> and <Skill name="One Wolf Pack"/>.

As a <Specialization name="Soulbeast" text="Condi Soulbeast"/> there are also multiple skills and traits that can be quickly prestacked for extra condis and damage at the start of fights. These aren't necessary to do and depending on the encounter not all are possible, but if you have the time and can make use of them they are worth to use.

### **Stances**

As a <Specialization name="Soulbeast" text="Condi Soulbeast"/> we have three important stances to share with <Trait name="Leader of the Pack"/> when precasting.

**<Skill name="Moa Stance"/> -** This will increase your party members boon duration by 66%, which when added to the conversion from <Item id="74185"/> means your party will have close to 100% boon duration without even swapping gear. This means any boons your party stacks duration will be close to doubled.

**<Skill name="Vulture Stance"/> -** This will help your party stack some initial condis and some initial <Boon name="Might"/> at the start of the fight and should be the last thing you cast before taking the _Mistlock Singularity_.

### **Boons**

**<Boon name="Might"/> -** Before starting fights we want to have 25 stacks of <Boon name="Might"/>, the standard way of this in fractals is from blasting a fire field. If no one else in your party will provide one you can use <Skill name="Bonfire"/> on torch. in the fire field we want to use blast finishers which each one will give 3 stacks of <Boon name="Might"/> for 20 seconds (not accounting for boon duration). Our main blast is from <Skill name="Call of the Wild"/> which can be used twice and also gives 6 stacks of might for 10 seconds along with the blast (again not accounting for boon duration).

**<Boon name="Fury"/> and <Boon name="Swiftness"/> -** We can provide these boons again by using <Skill name="Call of the Wild"/>. These boons stack up to 30 seconds, so by blasting twice with Warhorn and under the effect of <Skill name="Moa Stance"/>, we can provide the maximum duration for our party.

### **Traits**

**<Trait name="Poison Master"/> -** If you can get into combat before precasting you can use <Skill id="40588"/> (Merged F3) to proc <Trait name="Poison Master"/> for some extra <Condition name="poisoned" text ="Poison"/> stacks on your opener

**<Trait name="Light on your Feet"/> -** Stacks in duration by dodging and using <Skill name="Quick Shot"/>. This will increase you condi duration which means if you are playing with <Item id="24687"/> means your <Condition name="Poisoned"/> duration will be capped. It will also increase your strike damage (power) for a bit of extra damage.

### **Skills**

**<Skill name="Sharpening Stone"/> -** Used for some additional <Condition name="Bleeding"/> at the start of the fight. If you use a second time while you still have charges left, the original charges will be overwritten.

**<Skill name="Sharpen Spines"/> -** Can be precasted by merging with Bristleback for extra bleeding at the start of the fight. This stacks in intensity so you can use the skill after taking the mistlock giving you 10 stacks of <Condition name="Bleeding"/>.

**<Skill name="Crippling Shot"/> -** Can be precasted giving you the effect _Blood Thirst_ lasting for 11 seconds. When you have this effect and are merged your next 3 attacks will inflict 1 stack of <Condition name="Bleeding"/> lasting for 12 seconds.

**<Skill name="Double Arc"/> -** Can be precasted giving you the effect _Poisonous Strike_ lasting for 7 seconds. When you have this effect and are merged your next 2 attacks will inflict 1 stack of <Condition name="poisoned" text ="Poison"/> lasting for 6 seconds. This skill can be used twice giving you 3 charges.
</Card>

</GridItem>
</Grid>
