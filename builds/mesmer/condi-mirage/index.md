---
title: Staxe Mirage
rating: Good
role: Condi Damage
profession: Mesmer
classification:
  - 5
  - 4
  - 3
  - 2
  - 3
specialization: Mirage
code: '[&DQQeLSE3Ny55AAAAAAAAAL8AAADpFgAALhYAADQlAAAAAAAAAAAAAAAAAAA=]'
date: 2022-01-12T02:05:45.106Z
Boons:
  - name: Might
    uptime: 25 Stacks
    variant: party
  - name: Alacrity
    uptime: 55%
    variant: party
conditions:
  - name: Torment
  - name: Confusion
  - name: Bleeding
cmGuide: ''
hidden: true
archive: false
---

<Warning>

This build is strong in full condi groups ([team comps](/guides/effective-comp)). In power groups this build will fall massively behind <Specialization name="Soulbeast" text="Power Soulbeast"/> - the power damage counterpart.
</Warning>

Insert introduction here

<Divider text="Equipment"/>

<CharacterWithAr>
<Character title="Staxe Mirage" gear='{"attributes":{"profession":"Mesmer","specialization":"Mirage","data":{"Health":20522,"Armor":2192,"Power":2923,"Precision":1633,"Toughness":1225,"Vitality":1460,"Ferocity":0,"Condition Damage":2803,"Expertise":1198,"Concentration":475,"Healing Power":0,"Agony Resistance":150,"Condition Duration":0.9986666666666666,"Boon Duration":0.31666666666666665,"Critical Chance":0.6014285714285714,"Critical Damage":1.5,"Clone Critical Chance":0.3514285714285714,"Phantasm Critical Chance":0.3514285714285714,"Phantasm Critical Damage":1.5,"Power Coefficient":1670,"Power2 Coefficient":0,"Burning Coefficient":0,"Bleeding Coefficient":14.467571428571429,"Poison Coefficient":0.7,"Torment Coefficient":19.97,"Confusion Coefficient":6.18,"Flat DPS":0,"Siphon Base Coefficient":139.75,"Effective Power":5702.981785714286,"NonCrit Effective Power":4384.5,"Power DPS":3667.3005707134607,"Power2 DPS":0,"Siphon DPS":139.75,"Bleeding Damage":309.0425,"Bleeding Stacks":28.915852761904763,"Bleeding DPS":8936.227427170954,"Burning Damage":918.8806249999999,"Burning Stacks":0,"Burning DPS":0,"Confusion Damage":364.336375,"Confusion Stacks":12.351759999999999,"Confusion DPS":4500.195463269999,"Poison Damage":327.73,"Poison Stacks":1.3990666666666665,"Poison DPS":458.5161186666666,"Torment Damage":461.61375,"Torment Stacks":39.91337333333333,"Torment DPS":18424.56193955,"Damage":36126.55151937108,"Effective Health":89520843.78109454,"Survivability":45511.35931931598,"Effective Healing":390,"Healing":390}},"armor":{"weight":"Light","helmAffix":"Viper","helmRuneId":24848,"helmRune":"Nightmare","helmRuneCount":6,"helmInfusionId":37130,"shouldersAffix":"Viper","shouldersRuneId":24848,"shouldersRune":"Nightmare","shouldersRuneCount":6,"shouldersInfusionId":37130,"coatAffix":"Viper","coatRuneId":24848,"coatRune":"Nightmare","coatRuneCount":6,"coatInfusionId":37130,"glovesAffix":"Viper","glovesRuneId":24848,"glovesRune":"Nightmare","glovesRuneCount":6,"glovesInfusionId":37130,"leggingsAffix":"Viper","leggingsRuneId":24848,"leggingsRune":"Nightmare","leggingsRuneCount":6,"leggingsInfusionId":37130,"bootsAffix":"Viper","bootsRuneId":24848,"bootsRune":"Nightmare","bootsRuneCount":6,"bootsInfusionId":86113},"weapon":{"weapon1MainId":76158,"weapon1MainType":"Axe","weapon1MainSigil1Id":44944,"weapon1MainAffix":"Viper","weapon1MainInfusion1Id":86113,"weapon1OffId":30693,"weapon1OffType":"Pistol","weapon1OffSigilId":24615,"weapon1OffAffix":"Viper","weapon1OffInfusionId":86113,"weapon2MainId":30698,"weapon2MainType":"Staff","weapon2MainSigil1Id":44944,"weapon2MainAffix":"Viper","weapon2MainInfusion1Id":86113,"weapon2MainInfusion2Id":86113,"weapon2MainSigil2Id":24615},"backAndTrinket":{"backItemAffix":"Viper","backItemInfusion1Id":86113,"backItemInfusion2Id":86113,"amuletAffix":"Viper","ring1Affix":"Viper","ring1Infusion1Id":86113,"ring1Infusion2Id":86113,"ring1Infusion3Id":86113,"ring2Affix":"Viper","ring2Infusion1Id":86113,"ring2Infusion2Id":86113,"ring2Infusion3Id":86113,"accessory1Affix":"Viper","accessory1InfusionId":86113,"accessory2Affix":"Viper","accessory2InfusionId":86113},"consumables":{"foodId":91878,"utilityId":77567},"skills":{"healId":21750,"utility1Id":10234,"utility2Id":10232,"utility3Id":41065,"eliteId":45449},"assumedBuffs":{"value":[{"id":"might","type":"Boon"},{"id":"fury","type":"Boon"},{"id":"protection","type":"Boon"},{"id":"vulnerability","type":"Condition"},{"id":"jade-bot","gw2id":96613,"type":"Item"},{"id":"omnipotion","gw2id":79722,"type":"Item"}]},"traits":{"selection":[[670,669,671],[700,1889,1950],[2110,2098,2070]],"lines":[45,1,59]}}'>

This build uses 5 <Item name="Malign +9 Agony Infusion"/> and 13 <Item name="Spiteful +9 Agony Infusion"/>. However you can also run 11 <Item name="Malign +9 Agony Infusion"/> and 7 <Item name="Spiteful +9 Agony Infusion"/> with <Item id="91876"/>, giving you the same stats. 
  
</Character>
</CharacterWithAr>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1Id="1" traits1="Dueling" traits1SelectedIds="700,1889,1950" traits2Id="45" traits2="Chaos" traits2SelectedIds="670,669,671" traits3Id="59" traits3="Mirage" traits3SelectedIds="2110,2098,2070"/>
</GridItem>

<GridItem sm="5">
<Card title="Situational Skills">

|                                                   |                                                                                                                                                                                                                                                                                     |
| ------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <Skill name="Sun Spirit" size="big" disableText/> | Your standard 3rd utility. Provides a partywide damage increase by causing you and allies to periodically inflict <Condition name="Burning"/>.                                                                                                                                      |
| <Skill name="Moa Stance" size="big" disableText/> | A replacement for <Skill name="Sun Spirit"/>, this allows your <Specialization name="Renegade"/> to lower their boon duration and deal substantially more DPS! Alternatively if you have more than one <Specialization name="Soulbeast"/>, one can drop <Skill name="Sun Spirit"/>. |

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

1. something
2. something else

</Card>
</GridItem>

<GridItem sm="6">
<Card title="Shortbow Golem Rotation">

<Video youtube="iKKWM4F3ayg" caption="by Eren"/>
</Card>

<Card title="Precasting">

</Card>

</GridItem>
</Grid>
