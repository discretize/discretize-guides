---
title: Condi Soulbeast
hidden: false
archive: false
hasBeginner: true
rating: Meta
role: Condi Damage
profession: Ranger
specialization: Soulbeast
conditions:
  - name: Vulnerability
    uptime: 10 stacks
  - name: Bleeding
  - name: Poisoned
  - name: Burning
code: "[&DQQeLSE3Ny55AAAAAAAAAL8AAADpFgAALhYAADQlAAAAAAAAAAAAAAAAAAA=]"
cmGuide: pug
classification:
  - 5
  - 4
  - 3
  - 2
  - 3
date: "2023-04-07T14:16:30.100Z "
---
<Warning>

This build is strong in full condi groups ([team comps](/guides/effective-comp)), especially on Ensolyss, 100CM and some T4 bosses. In power groups and other bosses this build will fall massively behind <BuildLink specialization="Soulbeast" build="Power Soulbeast"/> - the power damage counterpart.

</Warning>

Condi <Specialization name="Soulbeast"/> is a DPS build with high sustained damage that also provides strong party buffs with <Skill name="Sun Spirit"/>, <Skill name="One Wolf Pack"/>, and crowd control (CC) skills. This build is mostly used for 100CM, for most other fractals, especially if your group is playing power builds, you will be better off playing the power variant found [here](/builds/ranger/power-soulbeast/).

This build is rather self sufficient due to:

- Boon extension by <Trait name="Essence of speed"/>, <Skill name="We heal as one"/>
- Good CC with <Skill id="46432"/> and <Skill name="Concussion Shot"/>
- High mobility via <Skill name="Instinctive Engage"/> and <Skill name="Quick Shot"/>

Overall this is a very well-rounded build that is rewarding to play in both PuGs and organized teams alike.

<Beginner>

This guide will focus on the Shortbow + Dagger/Dagger variant of the build with <Trait name="Light on your Feet"/> which is frequently played in fractals. There are some alternatives for specific situations with slightly varying rotations. Once you can execute the step-by-step rotation provided below without spending too much thought on it and are confident with the utility options, check out the advanced page for extra information. Feel free to swap to the advanced page early if you feel like you are missing some information on additional (less common) utility skills, trait swaps, or other weapon variants.

</Beginner>

<Divider text="Equipment"/>

<Beginner>

<CharacterWithAr>
<Character title="Condi Soulbeast" gear='{"attributes":{"profession":"Ranger","specialization":"Soulbeast","data":{"Health":21722,"Armor":2343,"Power":2923,"Precision":1733,"Toughness":1225,"Vitality":1580,"Ferocity":0,"Condition Damage":2737,"Expertise":727,"Concentration":225,"Healing Power":0,"Agony Resistance":150,"Condition Duration":0.4846666666666667,"Boon Duration":0.15,"Critical Chance":0.7490476190476191,"Critical Damage":1.5,"Power Coefficient":1517,"Power2 Coefficient":0,"Burning Coefficient":0,"Bleeding Coefficient":25.354023809523806,"Poison Coefficient":15.98,"Torment Coefficient":0,"Confusion Coefficient":0,"Flat DPS":0,"Bleeding Duration":0.35,"Poison Duration":0.5,"Effective Power":7768.035831324402,"NonCrit Effective Power":5651.4378124999985,"Power DPS":4537.585812906861,"Power2 DPS":0,"Siphon DPS":0,"Bleeding Damage":369.96094625,"Bleeding Stacks":46.516182349206346,"Bleeding DPS":17209.170837849928,"Burning Damage":829.38228125,"Burning Stacks":0,"Burning DPS":0,"Confusion Damage":328.10666875,"Confusion Stacks":0,"Confusion DPS":0,"Poison Damage":369.1803125,"Poison Stacks":31.714973333333333,"Poison DPS":11708.543766129167,"Torment Damage":415.4566875,"Torment Stacks":0,"Torment DPS":0,"Damage":33455.300416885955,"Effective Health":101282877.61194031,"Survivability":51491.04098217606,"Effective Healing":390,"Healing":390}},"armor":{"weight":"Medium","helmAffix":"Viper","helmRuneId":72912,"helmRune":"Thorns","helmRuneCount":6,"helmInfusionId":49431,"shouldersAffix":"Viper","shouldersRuneId":72912,"shouldersRune":"Thorns","shouldersRuneCount":6,"shouldersInfusionId":49431,"coatAffix":"Viper","coatRuneId":72912,"coatRune":"Thorns","coatRuneCount":6,"coatInfusionId":49431,"glovesAffix":"Viper","glovesRuneId":72912,"glovesRune":"Thorns","glovesRuneCount":6,"glovesInfusionId":49432,"leggingsAffix":"Viper","leggingsRuneId":72912,"leggingsRune":"Thorns","leggingsRuneCount":6,"leggingsInfusionId":49432,"bootsAffix":"Viper","bootsRuneId":72912,"bootsRune":"Thorns","bootsRuneCount":6,"bootsInfusionId":49432},"weapon":{"weapon1MainId":30686,"weapon1MainType":"Short Bow","weapon1MainSigil1Id":24612,"weapon1MainAffix":"Viper","weapon1MainInfusion1Id":49432,"weapon1MainInfusion2Id":49432,"weapon1MainSigil2Id":24560,"weapon2MainId":30687,"weapon2MainType":"Dagger","weapon2MainSigil1Id":24612,"weapon2MainAffix":"Viper","weapon2MainInfusion1Id":49432,"weapon2OffId":30687,"weapon2OffType":"Dagger","weapon2OffSigilId":24560,"weapon2OffAffix":"Viper","weapon2OffInfusionId":49432},"backAndTrinket":{"backItemAffix":"Viper","backItemInfusion1Id":49432,"amuletAffix":"Viper","ring1Affix":"Viper","ring1Infusion1Id":49432,"ring1Infusion2Id":49432,"ring1Infusion3Id":49432,"ring2Affix":"Viper","ring2Infusion1Id":49432,"ring2Infusion2Id":49432,"ring2Infusion3Id":49432,"accessory1Affix":"Viper","accessory1InfusionId":49432,"accessory2Affix":"Viper","accessory2InfusionId":49432},"consumables":{"foodId":96578,"utilityId":48917},"skills":{"healId":31914,"utility1Id":12496,"utility2Id":12537,"utility3Id":40498,"eliteId":45717},"assumedBuffs":{"value":[{"id":"might","type":"Boon"},{"id":"fury","type":"Boon"},{"id":"protection","type":"Boon"},{"id":"vulnerability","type":"Condition"},{"id":"jade-bot","gw2id":96613,"type":"Item"},{"id":"omnipotion","gw2id":79722,"type":"Item"}]},"traits":{"selection":[[1069,1846,1888],[1606,970,1066],[2071,2161,2128]],"lines":[30,32,55]}}'>

If you do not have a Jade Bot Core: Tier 10, you will have a slightly lower duration on your non-bleeding conditions but the build does not change!

</Character>
</CharacterWithAr>

</Beginner>

<Advanced>

<CharacterWithAr>
<Character title="Condi Soulbeast" gear='{"attributes":{"profession":"Ranger","specialization":"Soulbeast","data":{"Health":21722,"Armor":2343,"Power":2923,"Precision":1733,"Toughness":1225,"Vitality":1580,"Ferocity":0,"Condition Damage":2807,"Expertise":747,"Concentration":225,"Healing Power":0,"Agony Resistance":150,"Condition Duration":0.498,"Boon Duration":0.15,"Critical Chance":0.7490476190476191,"Critical Damage":1.5,"Power Coefficient":1517,"Power2 Coefficient":0,"Burning Coefficient":0,"Bleeding Coefficient":25.354023809523806,"Poison Coefficient":15.98,"Torment Coefficient":0,"Confusion Coefficient":0,"Flat DPS":0,"Bleeding Duration":0.35,"Poison Duration":0.5,"Effective Power":7768.035831324402,"NonCrit Effective Power":5651.4378124999985,"Power DPS":4537.585812906861,"Power2 DPS":0,"Siphon DPS":0,"Bleeding Damage":378.30503374999995,"Bleeding Stacks":46.85423599999999,"Bleeding DPS":17725.19333131046,"Burning Damage":845.58946875,"Burning Stacks":0,"Burning DPS":0,"Confusion Damage":335.32148125000003,"Confusion Stacks":0,"Confusion DPS":0,"Poison Damage":377.0225,"Poison Stacks":31.92804,"Poison DPS":12037.589460899999,"Torment Damage":424.86731249999997,"Torment Stacks":0,"Torment DPS":0,"Damage":34300.36860511732,"Effective Health":101282877.61194031,"Survivability":51491.04098217606,"Effective Healing":390,"Healing":390}},"armor":{"weight":"Medium","helmAffix":"Viper","helmRuneId":72912,"helmRune":"Thorns","helmRuneCount":6,"helmInfusionId":37130,"shouldersAffix":"Viper","shouldersRuneId":72912,"shouldersRune":"Thorns","shouldersRuneCount":6,"shouldersInfusionId":37130,"coatAffix":"Viper","coatRuneId":72912,"coatRune":"Thorns","coatRuneCount":6,"coatInfusionId":37130,"glovesAffix":"Viper","glovesRuneId":72912,"glovesRune":"Thorns","glovesRuneCount":6,"glovesInfusionId":37130,"leggingsAffix":"Viper","leggingsRuneId":72912,"leggingsRune":"Thorns","leggingsRuneCount":6,"leggingsInfusionId":37130,"bootsAffix":"Viper","bootsRuneId":72912,"bootsRune":"Thorns","bootsRuneCount":6,"bootsInfusionId":37130},"weapon":{"weapon1MainId":30686,"weapon1MainType":"Short Bow","weapon1MainSigil1Id":24612,"weapon1MainAffix":"Viper","weapon1MainInfusion1Id":86113,"weapon1MainInfusion2Id":86113,"weapon1MainSigil2Id":24560,"weapon2MainId":30687,"weapon2MainType":"Dagger","weapon2MainSigil1Id":24612,"weapon2MainAffix":"Viper","weapon2MainInfusion1Id":86113,"weapon2OffId":30687,"weapon2OffType":"Dagger","weapon2OffSigilId":24560,"weapon2OffAffix":"Viper","weapon2OffInfusionId":86113},"backAndTrinket":{"backItemAffix":"Viper","backItemInfusion1Id":37130,"backItemInfusion2Id":37130,"amuletAffix":"Viper","ring1Affix":"Viper","ring1Infusion1Id":37130,"ring1Infusion2Id":37130,"ring1Infusion3Id":37130,"ring2Affix":"Viper","ring2Infusion1Id":37130,"ring2Infusion2Id":37130,"ring2Infusion3Id":37130,"accessory1Affix":"Viper","accessory1InfusionId":86113,"accessory2Affix":"Viper","accessory2InfusionId":86113},"consumables":{"foodId":96578,"utilityId":48917},"skills":{"healId":31914,"utility1Id":12496,"utility2Id":12537,"utility3Id":40498,"eliteId":45717},"assumedBuffs":{"value":[{"id":"might","type":"Boon"},{"id":"fury","type":"Boon"},{"id":"protection","type":"Boon"},{"id":"vulnerability","type":"Condition"},{"id":"jade-bot","gw2id":96613,"type":"Item"},{"id":"omnipotion","gw2id":79722,"type":"Item"}]},"traits":{"selection":[[1069,1846,1888],[1606,970,1066],[2071,2161,2128]],"lines":[30,32,55]}}'>

This build uses the Jade Bot Core: Tier 10 in combination with 14 <Item name="Malign +9 Agony Infusion"/> and 4 <Item name="Spiteful +9 Agony Infusion"/>.

</Character>
<Character title="Hybrid Soulbeast" gear='{"attributes":{"profession":"Ranger","specialization":"Soulbeast","data":{"Health":22022,"Armor":2493,"Power":3073,"Precision":1883,"Toughness":1375,"Vitality":1610,"Ferocity":910,"Condition Damage":2657,"Expertise":748,"Concentration":225,"Healing Power":0,"Agony Resistance":150,"Condition Duration":0.49866666666666665,"Boon Duration":0.15,"Critical Chance":0.9704761904761905,"Critical Damage":2.1066666666666665,"Power Coefficient":4165.924,"Power2 Coefficient":0,"Burning Coefficient":1.84,"Bleeding Coefficient":26.57812933333333,"Poison Coefficient":5.9704,"Torment Coefficient":0.35,"Confusion Coefficient":0,"Flat DPS":0,"Bleeding Duration":0.5,"Siphon Base Coefficient":139.75,"Effective Power":13912.556219096941,"NonCrit Effective Power":6708.099715624999,"Power DPS":22317.54018270512,"Power2 DPS":0,"Siphon DPS":139.75,"Bleeding Damage":386.212565375,"Bleeding Stacks":53.12082116088888,"Bleeding DPS":20515.92861537348,"Burning Damage":868.8752718750001,"Burning Stacks":2.757546666666667,"Burning DPS":2395.9641097080003,"Confusion Damage":342.746633125,"Confusion Stacks":0,"Confusion DPS":0,"Poison Damage":308.792575,"Poison Stacks":8.947639466666665,"Poison DPS":2762.964631083626,"Torment Damage":433.65733125,"Torment Stacks":0.5245333333333333,"Torment DPS":227.467725485,"Damage":48359.61526435523,"Effective Health":109255414.92537315,"Survivability":55544.186540606584,"Effective Healing":390,"Healing":390}},"armor":{"weight":"Medium","helmAffix":"Viper","helmRuneId":24762,"helmRune":"Krait","helmRuneCount":6,"helmInfusionId":37130,"shouldersAffix":"Viper","shouldersRuneId":24762,"shouldersRune":"Krait","shouldersRuneCount":6,"shouldersInfusionId":37130,"coatAffix":"Viper","coatRuneId":24762,"coatRune":"Krait","coatRuneCount":6,"coatInfusionId":37130,"glovesAffix":"Viper","glovesRuneId":24762,"glovesRune":"Krait","glovesRuneCount":6,"glovesInfusionId":37130,"leggingsAffix":"Viper","leggingsRuneId":24762,"leggingsRune":"Krait","leggingsRuneCount":6,"leggingsInfusionId":37130,"bootsAffix":"Viper","bootsRuneId":24762,"bootsRune":"Krait","bootsRuneCount":6,"bootsInfusionId":37130},"weapon":{"weapon1MainId":76158,"weapon1MainType":"Axe","weapon1MainSigil1Id":24605,"weapon1MainAffix":"Viper","weapon1MainInfusion1Id":86113,"weapon1OffId":30700,"weapon1OffType":"Torch","weapon1OffSigilId":24560,"weapon1OffAffix":"Viper","weapon1OffInfusionId":86113,"weapon2MainId":30687,"weapon2MainType":"Dagger","weapon2MainSigil1Id":44944,"weapon2MainAffix":"Viper","weapon2MainInfusion1Id":86113,"weapon2OffId":76158,"weapon2OffType":"Axe","weapon2OffSigilId":24560,"weapon2OffAffix":"Viper","weapon2OffInfusionId":86113},"backAndTrinket":{"backItemAffix":"Viper","backItemInfusion1Id":37130,"backItemInfusion2Id":37130,"amuletAffix":"Viper","ring1Affix":"Viper","ring1Infusion1Id":37130,"ring1Infusion2Id":86113,"ring1Infusion3Id":86113,"ring2Affix":"Viper","ring2Infusion1Id":86113,"ring2Infusion2Id":86113,"ring2Infusion3Id":86113,"accessory1Affix":"Viper","accessory1InfusionId":86113,"accessory2Affix":"Viper","accessory2InfusionId":86113},"consumables":{"foodId":91878,"utilityId":48917},"skills":{"healId":31914,"utility1Id":12633,"utility2Id":12537,"utility3Id":40498,"eliteId":45717},"assumedBuffs":{"value":[{"id":"might","type":"Boon"},{"id":"fury","type":"Boon"},{"id":"protection","type":"Boon"},{"id":"vulnerability","type":"Condition"},{"id":"jade-bot","gw2id":96613,"type":"Item"},{"id":"omnipotion","gw2id":79722,"type":"Item"}]},"traits":{"selection":[[1069,1846,1888],[1606,970,1066],[2071,2161,2128]],"lines":[30,32,55]}}'>

This build uses the Jade Bot Core: Tier 10 in combination with 9 <Item name="Malign +9 Agony Infusion"/> and 9 <Item name="Spiteful +9 Agony Infusion"/>. However you can also run 15 <Item name="Malign +9 Agony Infusion"/> and 3 <Item name="Spiteful +9 Agony Infusion"/> with <Item id="91876"/>, giving you the same stats.

This build is mainly used on 100CM, although can preform well on other fights as well. On 100CM it can preform slightly better than <Specialization name="Soulbeast" text="Condi Soulbeast"/> with a more engaging rotation, however mistakes will tank your damage and can be very punishing, especially in less experienced groups.

If you need to drop a utiltiy skill <Skill name="Sic Em"/> should be replaced and you will want to use either [Warthog](https://wiki.guildwars2.com/wiki/Juvenile_Warthog) or [Bristleback](https://wiki.guildwars2.com/wiki/Juvenile_Bristleback) as your pet.

</Character>
</CharacterWithAr>

</Advanced>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Card title="Traits">
<Tabs>
<Tab title="Condi Soulbeast">
<Traits traits1Id="33" traits1="Wilderness Survival" traits1SelectedIds="1099,1101,1701" traits2Id="30" traits2="Skirmishing" traits2SelectedIds="1069,1846,1912" traits3Id="55" traits3="Soulbeast" traits3SelectedIds="2071,2161,2128" unembossed/>
</Tab>
<Tab title="Hybrid Soulbeast">
<Traits traits1Id="32" traits1="Beastmastery" traits1SelectedIds="1606,970,1066" traits2Id="30" traits2="Skirmishing" traits2SelectedIds="1069,1846,1888" traits3Id="55" traits3="Soulbeast" traits3SelectedIds="2071,2161,2128" unembossed/>
</Tab>
</Tabs>
</Card>

<Beginner>

<Card title="Defiance Bar Damage">

|                                                   |                                                                                   |
| ------------------------------------------------- | --------------------------------------------------------------------------------- |
| <Skill id="46432" size="big" disableText/>        | 300 damage (F2 in <Skill id="42944"/>)                                            |
| <Skill id="12508" size="big" disableText/>        | 200 damage (Shortbow 5)                                                           |
| <Skill name="Spike Trap" size="big" disableText/> | 232 damage (Shortbow 5)                                                           |
| <Skill id="12507" size="big" disableText/>        | 50/s <Condition name="Immobile"/>, 15/s <Condition name="Crippled"/> (Shortbow 4) |
| <Skill id="12490" size="big" disableText/>        | 33/s <Condition name="Chilled"/>, 20/s <Condition name="Weakness"/> (Axe 3)       |

</Card>

</Beginner>

</GridItem>

<GridItem sm="5">
<Card title="Situational Skills">

|                                                       |                                                                                                                                                                                   |
| ----------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <Skill name="Moa Stance" size="big" disableText/>     | A replacement for <Skill name="Vipers Nest"/>, this allows boon providers such as <Specialization name="Renegade"/> to lower their boon duration and deal substantially more DPS! |
| <Skill name="Dolyak Stance" size="big" disableText/>  | Can be used to share <Boon name="Stability"/>.                                                                                                                                    |
| <Skill name="Spike Trap" size="big" disableText/>     | Can be taken to for extra CC, while being used in rotation for <Condition name="Bleeding"/> stacks.                                                                               |
| <Skill name="Bear stance" size="big" disableText/>    | A party-wide condi cleanse through <Trait name="leaderofthepack"/>.                                                                                                               |
| <Skill name="Healing Spring" size="big" disableText/> | Area condi cleanse, taken if your party needs a long lasting condi cleanse. Very useful on 100CM!                                                                                 |

</Card>
<Card title="Pets">

[Warthog](https://wiki.guildwars2.com/wiki/Juvenile_Warthog) - Best CDPS pet that also brings CC, also this is the pet you use in <Skill id="42944"/>.

<Advanced>

[Bristleback](https://wiki.guildwars2.com/wiki/Juvenile_Bristleback) - Used to precast some extra Bleeding. Is also the best CDPS pet for when there are multiple targets. Only take Bristleback if you can consistently get 5+ hits from <Skill name="Rain of Spikes"/> without delaying the skill too much.

</Advanced>

[Lynx](https://wiki.guildwars2.com/wiki/Juvenile_Lynx) - Best single target CDPS pet. Taken if you don't need the CC from Warthog

</Card>
</GridItem>
</Grid>

<Advanced>

<Divider text="Further information"/>

<Grid>
<GridItem sm="7">
<Card title="Situational Traits">

|                                                         |                                                                                                                                |
| ------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| <Trait name="Essence of Speed" size="big" disableText/> | Take this instead of <Trait name="Predators Cunning"/> if boon uptime in your party is bad and you want some extra generation. |

</Card>

<Card title="Swap Weapons">

- A <Item id="75325"/> (selected attribute does not matter!) to blast might when prestacking boons.
- A weapon set to precast <Item id="24609"/> and <Item id="24599"/> before getting into fight.

</Card>
</GridItem>

<GridItem sm="5">

<Card title="Defiance Bar Damage">

|                                                   |                                                                                   |
| ------------------------------------------------- | --------------------------------------------------------------------------------- |
| <Skill id="46432" size="big" disableText/>        | 300 damage (F2 in <Skill id="42944"/>)                                            |
| <Skill id="12508" size="big" disableText/>        | 200 damage (Shortbow 5)                                                           |
| <Skill name="Spike Trap" size="big" disableText/> | 232 damage                                                                        |
| <Skill id="12507" size="big" disableText/>        | 50/s <Condition name="Immobile"/>, 15/s <Condition name="Crippled"/> (Shortbow 4) |
| <Skill id="12490" size="big" disableText/>        | 33/s <Condition name="Chilled"/>, 20/s <Condition name="Weakness"/> (Axe 3)       |

</Card>
</GridItem>
</Grid>

</Advanced>

<Divider text="Rotation / Skill usage"/>

<Advanced>
<Grid>
<GridItem sm="6">
<Card title="Information">

The rotation in general is very simple, just keep rotating between your Shortbow and Dagger/Dagger set using your utility skills as often as you can. When you get to the point of auto-attacking use your <Skill id="42944"/> skills to fill.

Your rotation will not line up in a perfect loop so each weaponswap your cooldowns will be slightly different. In general aim to use 3x <Skill name="Double Arc"/> per Dagger loop and 3x <Skill name="Poison Volley"/> per Shortbow loop.
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
9.  <Skill name="Stalkers Strike"/>
10. <Skill name="Crippling Talon"/>
11. <Skill id="44514"/>
12. <Skill name="Primal Cry"/>
13. <Skill name="Crippling Talon"/>
14. <Skill name="Double Arc"/>
15. <Skill name="Stalkers Strike"/>
16. <Skill name="Double Arc"/>
17. <Skill name="Crippling Talon"/>
18. `Weapon Swap`
19. <Skill name="Poison Volley"/>
20. <Skill name="Crippling Shot"/>
21. <Skill name="Vipers Nest"/>
22. <Skill id="44514"/>
23. <Skill name="Poison Volley"/>
24. <Skill name="Primal Cry"/>
25. <Skill name="Crippling Shot"/>
26. <Skill name="Concussion Shot"/>
27. <Skill name="Poison Volley"/>
28. Repeat from `Step 6`

</Card>
</GridItem>

<GridItem sm="6">
<Card title="Shortbow Golem Rotation">

<Video youtube="9IcCtFB28gc" caption="by Umbra"/>
</Card>
<Card title="Precasting">

When precasting in fractals we want to stack as many useful boons with as much duration as possible, these being <Boon name="Might"/>, <Boon name="Fury"/>, <Boon name="Quickness"/>, <Boon name="Alacrity"/> and <Boon name="Swiftness"/>. We can also cast useful unique effects, for a <Specialization name="Soulbeast" text="Condi Soulbeast"/> this means your stances such as <Skill name="Vulture Stance"/>, <Skill name="Moa Stance"/> and <Skill name="One Wolf Pack"/>.

As a <Specialization name="Soulbeast" text="Condi Soulbeast"/> there are also multiple skills and traits that can be quickly pre-stacked for extra condis and damage at the start of fights. These aren't necessary to do and depending on the encounter, not all are possible, but if you have the time and can make use of them they are worth using.

### **Stances**

As a <Specialization name="Soulbeast" text="Condi Soulbeast"/> we have three important stances to share with <Trait name="Leader of the Pack"/> when precasting.

**<Skill name="Moa Stance"/> -** This will increase your party members' boon duration by 66%, which when added to the conversion from <Item id="74185"/> means your party will have close to 100% boon duration without even swapping gear. This means any boons your party stacks duration will be close to double.

**<Skill name="Vulture Stance"/> -** This will help your party stack some initial condis and some initial <Boon name="Might"/> at the start of the fight and should be the last thing you cast before taking the _Mistlock Singularity_.

### **Boons**

**<Boon name="Might"/> -** Before starting fights we want to have 25 stacks of <Boon name="Might"/>, the standard way of this in fractals is by blasting a fire field. If no one else in your party will provide one you can use <Skill name="Bonfire"/> on a torch. In the fire field, we want to use blast finishers which each one will give 3 stacks of <Boon name="Might"/> for 20 seconds (not accounting for boon duration). Our main blast is from <Skill name="Call of the Wild"/> which can be used twice and also gives 6 stacks of might for 10 seconds along with the blast (again not accounting for boon duration).

**<Boon name="Fury"/> and <Boon name="Swiftness"/> -** We can provide these boons again by using <Skill name="Call of the Wild"/>. These boons stack up to 30 seconds, so by blasting twice with Warhorn and under the effect of <Skill name="Moa Stance"/>, we can provide the maximum duration for our party.

### **Traits**

**<Trait name="Poison Master"/> -** If you can get into combat before precasting you can use <Skill id="40588"/> (Merged F3) to proc <Trait name="Poison Master"/> for some extra <Condition name="poisoned" text ="Poison"/> stacks on your opener

**<Trait name="Light on your Feet"/> -** Stacks in duration by dodging and using <Skill name="Quick Shot"/>. This will increase your condi duration which means if you are playing with <Item id="24687"/> means your <Condition name="Poisoned"/> duration will be capped. It will also increase your strike damage (power) for a bit of extra damage.

### **Skills**

**<Skill name="Sharpening Stone"/> -** Used for some additional <Condition name="Bleeding"/> at the start of the fight. If you use a second time while you still have charges left, the original charges will be overwritten.

**<Skill name="Sharpen Spines"/> -** Can be precasted by merging with Bristleback for extra bleeding at the start of the fight. This stacks in intensity so you can use the skill after taking the mistlock giving you 10 stacks of <Condition name="Bleeding"/>.

**<Skill name="Crippling Shot"/> -** Can be precasted giving you the effect _Blood Thirst_ lasting for 11 seconds. When you have this effect and are merged your next 3 attacks will inflict 1 stack of <Condition name="Bleeding"/> lasting for 12 seconds.

**<Skill name="Double Arc"/> -** Can be precasted giving you the effect _Poisonous Strike_ lasting for 7 seconds. When you have this effect and are merged your next 2 attacks will inflict 1 stack of <Condition name="poisoned" text ="Poison"/> lasting for 6 seconds. This skill can be used twice giving you 3 charges.
</Card>

</GridItem>
</Grid>
</Advanced>

<Beginner>

<Grid>
<GridItem xs="12" sm="7">
<Card title="Step-by-Step Rotation">

**Step 1: Weapon Rotation**

The highest priority skills are your weapon skills, namely skills 2,4, and 5 on both sets. The weapon skill rotation will be the backbone of your rotation and you will not want to interrupt it for any other skill. Any further steps will introduce more skills to fill the gaps between your weapon skills, so it is a good idea to spend some time practicing this step.

The weapon rotation is:

1. Start on Shortbow and use <Skill name="Poison Volley"/>, <Skill name="Crippling Shot"/> and <Skill name="Concussion Shot"/>.
2. Swap to Dagger/Dagger and use <Skill name="Double Arc"/>, <Skill name="Stalkers Strike"/> and <Skill name="Crippling Talon"/>.
3. Keep using these skills off-cooldown. Your 3rd <Skill name="Double Arc"/> and depending on the cooldown, 3rd <Skill name="Crippling Talon"/>, should come back at the same time. Use them and swap back to Shortbow.
4. Use <Skill name="Poison Volley"/>, <Skill name="Crippling Shot"/> and <Skill name="Concussion Shot"/> off-cooldown (with this priority) until you used <Skill name="Poison Volley"/> 3 times.
5. Repeat step 2.

**Step 2: Beastmode Skills**

Your <Skill name="Beastmode"/> skills will fill some gaps in your weapon rotation. Use them off-cooldown but do not interrupt or delay your weapon rotation for them. The priority depends on the Pet you are using.

For Lynx, the priority is:

1. <Skill id="44514"/>
2. <Skill id="40588"/>

For Warthog, the priority is:

1. <Skill id="46432"/>
2. <Skill id="41406"/>
3. <Skill id="40588"/>

Keep in mind that <Skill id="46432"/> is also a CC skill, so delay it for break bars if necessary but try not to delay it for too long if possible.

**Step 3: Utility Skills**

Next up, we want to incorporate our Utility Skills. These will generally also be used off-cooldown with a higher priority than the <Skill name="Beastmode"/> skills.

- <Skill name="One Wolf Pack"/> is your highest priority utility skill. Use it off-cooldown but don't waste it in split phases. Make sure everyone is in your range and can attack the boss when you cast it.
- When running <Skill name="Vipers Nest"/>, use it off-cooldown but make sure to not use it right before the boss moves.
- <Skill name="Sharpening Stone"/> and <Skill name="Vulture Stance"/> are instant-cast so you can use them off-cooldown, even while casting other skills. Make sure to be in the range of your allies when using <Skill name="Vulture Stance"/>.

**Step 4: Easy Precasts**

Lastly, we will look at some easy precasts you can (almost) always do with low effort but a good reward:

1. <Skill name="Double Arc"/>, <Skill name="Crippling Shot"/> and <Skill name="Sharpening Stone"/> all provide a boost to your next attacks after being used. You can use these before the fight if you do not get into combat by doing so (no other enemies around). This becomes even more efficient if a Mistlock Singularity is present to reset the skill cooldowns.
2. If a Mistlock Singularity is present, you can cast your Stances as well, namely <Skill name="One Wolf Pack"/> and <Skill name="Vulture Stance"/>.

</Card>
</GridItem>
<GridItem xs="12" sm="5">

<Card title="Shortbow Golem Rotation">

This video shows the full rotation on the golem.

<Video youtube="9IcCtFB28gc" caption="by Umbra"/>

</Card>
<Card title="Improving Further">

Once you are comfortable with the above steps, you are doing the full rotation and will be able to deal great damage.

There will be a few additional things on the advanced page to improve further but if you got here, you already know the most important things and these will have a smaller impact than what you learned so far.

Most of the additional steps will be extra precasts to have a higher damage spike or help with providing boons for your party at the Mistlock Singularity.

</Card>
</GridItem>
</Grid>
</Beginner>
