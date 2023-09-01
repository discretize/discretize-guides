---
title: Condi (Alac) Specter
hidden: false
archive: false
hasBeginner: true
rating: Good
role: Condi Damage
profession: Thief
specialization: Specter
conditions:
  - name: Vulnerability
    uptime: 20 stacks
  - name: Poisoned
  - name: Bleeding
  - name: Torment
boons:
  - name: Fury
    uptime: 75%
    variant: party
  - name: Might
    uptime: 5 stacks
    variant: party
  - name: Swiftness
    uptime: 75%
    variant: party
code: "[&DQUcGywfRxcMAQAACwEAAC8BAAA+AQAADgEAAAAAAAAAAAAAAAAAAAAAAAA=]"
classification:
  - 5
  - 4
  - 3
  - 2
  - 3
compositions: null
date: "2023-09-01T15:14:59.996Z "
cmGuide: ""
---
 
<Advanced> 
<Warning>
<Specialization text="Condi Specter" name="Specter"/> is a very strong build, especially in fractal CMs. However, like all condi thief builds it does suffer from a lack of cleave damage, which is important in T4s. We suggest that you also consider gearing <BuildLink build="Power Daredevil" specialization="Daredevil"/> to swap to on certain sections of T4 fractals where cleave is important and power damage is more suited to the boss. By swapping between both builds and also learning skips, you can carry your party and vastly speed up a fractal clear.
</Warning>
</Advanced>

The **<Specialization text="Condi Specter" name="Specter"/>** is a high DPS condition build with great CC and some party healing. 

<Advanced>

The value of this build comes from the pure damage that it will bring and the massive amount of CC offered by <Skill name="basiliskvenom" />. Venom Skills can be precast on the _Mistlock Singularity_, and cast again as soon as your allies have consumed them by attacking the target, this is required for this build to perform well.

</Advanced>

<Beginner>

The beginner version of this guide will focus on the most important utility options and try to teach a slightly simplified rotation step-by-step while giving some notes on what you can do to optimize in the future.

The advanced page provides a more complete overview of the utilities the <Specialization name="Thief"/> has to offer. Once you can execute the step-by-step rotation provided below without spending too much thought on it and are confident with the utility options provided here, head over and check out the advanced page for some extra information. Feel free to swap to the advanced page early if you feel like you are missing some information on additional (less common) utility skills or trait swaps.

<Information>

Although this build lists 150 <Attribute name="Agony Resistance"/>, it is not a strict requirement! We recommend getting started with this build anyway - even if it might be suboptimal while being in Tier 1 or 2 fractals. Keep upgrading your <Attribute name="Agony Resistance"/> until you reach the suggested variant. In the beginning, it is much more important to learn about fractal mechanics and your skills rather than equipping optimal gear. 

</Information>
</Beginner>

<Beginner>
<CharacterWithAr>  
<Character title="DPS" gear='{"attributes":{"profession":"Thief","specialization":"Specter","data":{"Health":13995,"Armor":2118,"Power":2923,"Precision":1633,"Toughness":1000,"Vitality":1297,"Ferocity":0,"Condition Damage":2857,"Expertise":944,"Concentration":0,"Healing Power":127,"Agony Resistance":0,"Condition Duration":0.7793333333333333,"Boon Duration":0,"Critical Chance":0.6014285714285714,"Critical Damage":1.5,"Power Coefficient":2620,"Power2 Coefficient":0,"Burning Coefficient":0,"Bleeding Coefficient":2.58,"Poison Coefficient":18.096,"Torment Coefficient":22.2,"Confusion Coefficient":0,"Flat DPS":0,"Poison Duration":0.48,"Outgoing Healing":0.2,"Effective Power":6467.181344999998,"NonCrit Effective Power":4972.022999999999,"Power DPS":6524.457113554099,"Power2 DPS":0,"Siphon DPS":0,"Bleeding Damage":274.17285,"Bleeding Stacks":4.59068,"Bleeding DPS":1258.6398190379998,"Burning Damage":813.4111125000001,"Burning Stacks":0,"Burning DPS":0,"Confusion Damage":290.27139750000003,"Confusion Stacks":0,"Confusion DPS":0,"Poison Damage":386.330553,"Poison Stacks":36.192,"Poison DPS":13982.075374176,"Torment Damage":511.94784375000006,"Torment Stacks":39.5012,"Torment DPS":20222.554165537502,"Damage":41987.7264723056,"Effective Health":44240910.4477612,"Survivability":22491.566063935537,"Effective Healing":513.72,"Healing":513.72}},"armor":{"weight":"Medium","helmAffix":"Viper","helmRuneId":67339,"helmRune":"Trapper","helmRuneCount":6,"helmInfusionId":37130,"shouldersAffix":"Viper","shouldersRuneId":67339,"shouldersRune":"Trapper","shouldersRuneCount":6,"shouldersInfusionId":37130,"coatAffix":"Viper","coatRuneId":67339,"coatRune":"Trapper","coatRuneCount":6,"coatInfusionId":37130,"glovesAffix":"Viper","glovesRuneId":67339,"glovesRune":"Trapper","glovesRuneCount":6,"glovesInfusionId":37130,"leggingsAffix":"Viper","leggingsRuneId":67339,"leggingsRune":"Trapper","leggingsRuneCount":6,"leggingsInfusionId":37130,"bootsAffix":"Viper","bootsRuneId":67339,"bootsRune":"Trapper","bootsRuneCount":6,"bootsInfusionId":37130},"weapon":{"weapon1MainId":30695,"weapon1MainType":"Scepter","weapon1MainSigil1Id":48911,"weapon1MainAffix":"Viper","weapon1MainInfusion1Id":37130,"weapon1OffId":30687,"weapon1OffType":"Dagger","weapon1OffSigilId":24609,"weapon1OffAffix":"Viper","weapon1OffInfusionId":37130,"weapon2OffId":30693,"weapon2OffType":"Pistol","weapon2OffSigilId":24609,"weapon2OffAffix":"Viper","weapon2OffInfusionId":37130},"backAndTrinket":{"backItemAffix":"Viper","backItemInfusion1Id":37130,"backItemInfusion2Id":37130,"amuletAffix":"Viper","ring1Affix":"Viper","ring1Infusion1Id":37130,"ring1Infusion2Id":37130,"ring1Infusion3Id":37130,"ring2Affix":"Viper","ring2Infusion1Id":37130,"ring2Infusion2Id":37130,"ring2Infusion3Id":37130,"accessory1Affix":"Viper","accessory1InfusionId":37130,"accessory2Affix":"Viper","accessory2InfusionId":37130},"consumables":{"foodId":97422,"utilityId":48917},"skills":{"healId":63292,"utility1Id":13026,"utility2Id":13055,"utility3Id":13037,"eliteId":13132},"assumedBuffs":{"value":[{"id":"might","type":"Boon"},{"id":"fury","type":"Boon"},{"id":"protection","type":"Boon"},{"id":"vulnerability","type":"Condition"},{"id":"reinforced-armor","type":"Text"},{"id":"jade-bot","gw2id":96613,"type":"Item"}]},"traits":{"selection":[[1164,1292,1291],[1163,1277,1187],[2284,2290,2264]],"lines":[28,44,71]}}'>

  
The <Skill id="21778"/> is another option to support your party as it brings a tremendous amount of party healing.

If you do not need the extra CC you can remove the Pistol so your Dagger counts for both sets. This allows you to swap freely for <Item type="Sigil" name="Doom"/> and <Trait name="Quick Pockets"/>.

</Character>  
<Character title="150 AR 42%BD ALAC" gear='{"attributes":{"profession":"Thief","specialization":"Specter","data":{"Health":23295,"Armor":2343,"Power":2218,"Precision":1256,"Toughness":1225,"Vitality":2273,"Ferocity":0,"Condition Damage":2831,"Expertise":783,"Concentration":602,"Healing Power":127,"Agony Resistance":150,"Condition Duration":0.672,"Boon Duration":0.4013333333333333,"Critical Chance":0.4219047619047619,"Critical Damage":1.5,"Power Coefficient":1900,"Power2 Coefficient":0,"Burning Coefficient":0,"Bleeding Coefficient":2.05,"Poison Coefficient":16.016,"Torment Coefficient":18.94,"Confusion Coefficient":0.99,"Flat DPS":0,"Poison Duration":0.33,"Outgoing Healing":0.2,"Torment Duration":0.35,"Effective Power":5168.999887142857,"NonCrit Effective Power":4268.541,"Power DPS":3781.7095824302764,"Power2 DPS":0,"Siphon DPS":0,"Bleeding Damage":307.69547499999993,"Bleeding Stacks":3.4276,"Bleeding DPS":1054.6570101099996,"Burning Damage":913.82476875,"Burning Stacks":0,"Burning DPS":0,"Confusion Damage":325.78417125,"Confusion Stacks":1.65528,"Confusion DPS":539.2640229867,"Poison Damage":433.76433799999995,"Poison Stacks":32.032,"Poison DPS":13894.339274815997,"Torment Damage":459.6187124999999,"Torment Stacks":37.88,"Torment DPS":17410.356829499997,"Damage":36680.32671984297,"Effective Health":108617283.58208957,"Survivability":55219.7679624248,"Effective Healing":513.72,"Healing":513.72}},"armor":{"weight":"Medium","helmAffix":"Viper","helmRuneId":67339,"helmRune":"Trapper","helmRuneCount":6,"helmInfusionId":37130,"shouldersAffix":"Viper","shouldersRuneId":67339,"shouldersRune":"Trapper","shouldersRuneCount":6,"shouldersInfusionId":37130,"coatAffix":"Viper","coatRuneId":67339,"coatRune":"Trapper","coatRuneCount":6,"coatInfusionId":37130,"glovesAffix":"Viper","glovesRuneId":67339,"glovesRune":"Trapper","glovesRuneCount":6,"glovesInfusionId":37130,"leggingsAffix":"Viper","leggingsRuneId":67339,"leggingsRune":"Trapper","leggingsRuneCount":6,"leggingsInfusionId":37130,"bootsAffix":"Viper","bootsRuneId":67339,"bootsRune":"Trapper","bootsRuneCount":6,"bootsInfusionId":37130},"weapon":{"weapon1MainId":30695,"weapon1MainType":"Scepter","weapon1MainSigil1Id":24609,"weapon1MainAffix":"Ritualist","weapon1MainInfusion1Id":37130,"weapon1OffId":30687,"weapon1OffType":"Dagger","weapon1OffSigilId":24583,"weapon1OffAffix":"Ritualist","weapon1OffInfusionId":37130,"weapon2OffId":30693,"weapon2OffType":"Pistol","weapon2OffSigilId":24583,"weapon2OffAffix":"Ritualist","weapon2OffInfusionId":37130},"backAndTrinket":{"backItemAffix":"Ritualist","backItemInfusion1Id":37130,"backItemInfusion2Id":37130,"amuletAffix":"Ritualist","ring1Affix":"Ritualist","ring1Infusion1Id":37130,"ring1Infusion2Id":37130,"ring1Infusion3Id":37130,"ring2Affix":"Ritualist","ring2Infusion1Id":37130,"ring2Infusion2Id":37130,"ring2Infusion3Id":37130,"accessory1Affix":"Ritualist","accessory1InfusionId":37130,"accessory2Affix":"Viper","accessory2InfusionId":37130},"consumables":{"foodId":95942,"utilityId":81079},"skills":{"healId":63292,"utility1Id":13026,"utility2Id":13055,"utility3Id":13037,"eliteId":13132},"assumedBuffs":{"value":[{"id":"might","type":"Boon"},{"id":"fury","type":"Boon"},{"id":"protection","type":"Boon"},{"id":"vulnerability","type":"Condition"},{"id":"reinforced-armor","type":"Text"},{"id":"jade-bot","gw2id":96613,"type":"Item"},{"id":"omnipotion","gw2id":79722,"type":"Item"}]},"traits":{"selection":[[1164,1292,1291],[1163,1277,1187],[2284,2290,2289]],"lines":[28,44,71]}}'>

 This build can maintain <Boon name="Alacrity"/> solo. You might need to adjust your gear using the [gear optimizer](https://optimizer.discretize.eu/?s=TVPLpTL3v1) with your appropriate AR to gain at least 40% <Attribute name="Boon Duration"/> if you want to upkeep it permanantly.
. 

The <Skill id="21778"/> is another option to support your party as it brings a tremendous amount of party healing.

If you do not need the extra CC you can remove the Pistol so your Dagger counts for both sets. This allows you to swap freely for <Item type="Sigil" name="Doom"/> and <Trait name="Quick Pockets"/>.

</Character> 
</CharacterWithAr>
</Beginner>

<Advanced>

<CharacterWithAr>  
<Character title="DPS" gear='{"attributes":{"profession":"Thief","specialization":"Specter","data":{"Health":13995,"Armor":2118,"Power":2923,"Precision":1633,"Toughness":1000,"Vitality":1297,"Ferocity":0,"Condition Damage":2857,"Expertise":944,"Concentration":0,"Healing Power":127,"Agony Resistance":0,"Condition Duration":0.7793333333333333,"Boon Duration":0,"Critical Chance":0.6014285714285714,"Critical Damage":1.5,"Power Coefficient":2620,"Power2 Coefficient":0,"Burning Coefficient":0,"Bleeding Coefficient":2.58,"Poison Coefficient":18.096,"Torment Coefficient":22.2,"Confusion Coefficient":0,"Flat DPS":0,"Poison Duration":0.48,"Outgoing Healing":0.2,"Effective Power":6467.181344999998,"NonCrit Effective Power":4972.022999999999,"Power DPS":6524.457113554099,"Power2 DPS":0,"Siphon DPS":0,"Bleeding Damage":274.17285,"Bleeding Stacks":4.59068,"Bleeding DPS":1258.6398190379998,"Burning Damage":813.4111125000001,"Burning Stacks":0,"Burning DPS":0,"Confusion Damage":290.27139750000003,"Confusion Stacks":0,"Confusion DPS":0,"Poison Damage":386.330553,"Poison Stacks":36.192,"Poison DPS":13982.075374176,"Torment Damage":511.94784375000006,"Torment Stacks":39.5012,"Torment DPS":20222.554165537502,"Damage":41987.7264723056,"Effective Health":44240910.4477612,"Survivability":22491.566063935537,"Effective Healing":513.72,"Healing":513.72}},"armor":{"weight":"Medium","helmAffix":"Viper","helmRuneId":67339,"helmRune":"Trapper","helmRuneCount":6,"helmInfusionId":37130,"shouldersAffix":"Viper","shouldersRuneId":67339,"shouldersRune":"Trapper","shouldersRuneCount":6,"shouldersInfusionId":37130,"coatAffix":"Viper","coatRuneId":67339,"coatRune":"Trapper","coatRuneCount":6,"coatInfusionId":37130,"glovesAffix":"Viper","glovesRuneId":67339,"glovesRune":"Trapper","glovesRuneCount":6,"glovesInfusionId":37130,"leggingsAffix":"Viper","leggingsRuneId":67339,"leggingsRune":"Trapper","leggingsRuneCount":6,"leggingsInfusionId":37130,"bootsAffix":"Viper","bootsRuneId":67339,"bootsRune":"Trapper","bootsRuneCount":6,"bootsInfusionId":37130},"weapon":{"weapon1MainId":30695,"weapon1MainType":"Scepter","weapon1MainSigil1Id":48911,"weapon1MainAffix":"Viper","weapon1MainInfusion1Id":37130,"weapon1OffId":30687,"weapon1OffType":"Dagger","weapon1OffSigilId":24609,"weapon1OffAffix":"Viper","weapon1OffInfusionId":37130,"weapon2OffId":30693,"weapon2OffType":"Pistol","weapon2OffSigilId":24609,"weapon2OffAffix":"Viper","weapon2OffInfusionId":37130},"backAndTrinket":{"backItemAffix":"Viper","backItemInfusion1Id":37130,"backItemInfusion2Id":37130,"amuletAffix":"Viper","ring1Affix":"Viper","ring1Infusion1Id":37130,"ring1Infusion2Id":37130,"ring1Infusion3Id":37130,"ring2Affix":"Viper","ring2Infusion1Id":37130,"ring2Infusion2Id":37130,"ring2Infusion3Id":37130,"accessory1Affix":"Viper","accessory1InfusionId":37130,"accessory2Affix":"Viper","accessory2InfusionId":37130},"consumables":{"foodId":97422,"utilityId":48917},"skills":{"healId":63292,"utility1Id":13026,"utility2Id":13055,"utility3Id":13037,"eliteId":13132},"assumedBuffs":{"value":[{"id":"might","type":"Boon"},{"id":"fury","type":"Boon"},{"id":"protection","type":"Boon"},{"id":"vulnerability","type":"Condition"},{"id":"reinforced-armor","type":"Text"},{"id":"jade-bot","gw2id":96613,"type":"Item"}]},"traits":{"selection":[[1164,1292,1291],[1163,1277,1187],[2284,2290,2264]],"lines":[28,44,71]}}'>

If you do not need the extra CC you can remove the Pistol so your Dagger counts for both sets. This allows you to swap freely for <Item type="Sigil" name="Doom"/> and <Trait name="Quick Pockets"/> (note that the sigils will also proc from going in/out of shroud).

If healing isn't an issue, this is the perfect build to use <Item name="writofmasterfulmalice"/> over <Item name="tuningicicle"/>!

It's recommended to have a short bow for additional movement during downtime and <Boon name="might"/> blasts on the _Mistlock Singularity_.

</Character>
<Character title="150 AR 40%BD ALAC" gear='{"attributes":{"profession":"Thief","specialization":"Specter","data":{"Health":23175,"Armor":2343,"Power":2230,"Precision":1257,"Toughness":1225,"Vitality":2261,"Ferocity":0,"Condition Damage":2741,"Expertise":783,"Concentration":601,"Healing Power":121,"Agony Resistance":150,"Condition Duration":0.672,"Boon Duration":0.4006666666666667,"Critical Chance":0.42238095238095236,"Critical Damage":1.5,"Power Coefficient":1940,"Power2 Coefficient":0,"Burning Coefficient":0,"Bleeding Coefficient":2.1,"Poison Coefficient":16.446,"Torment Coefficient":19.48,"Confusion Coefficient":1.02,"Flat DPS":0,"Poison Duration":0.33,"Outgoing Healing":0.2,"Torment Duration":0.35,"Effective Power":5197.987439285714,"NonCrit Effective Power":4291.634999999999,"Power DPS":3882.978680097915,"Power2 DPS":0,"Siphon DPS":0,"Bleeding Damage":299.03522499999997,"Bleeding Stacks":3.5112000000000005,"Bleeding DPS":1049.9724820200001,"Burning Damage":891.45245625,"Burning Stacks":0,"Burning DPS":0,"Confusion Damage":316.69090874999995,"Confusion Stacks":1.7054400000000003,"Confusion DPS":540.0973434186,"Poison Damage":422.24620550000003,"Poison Stacks":32.892,"Poison DPS":13888.522191306003,"Torment Damage":446.62833749999993,"Torment Stacks":38.96,"Torment DPS":17400.640029,"Damage":36762.21072584252,"Effective Health":108057761.19402987,"Survivability":54935.313265902325,"Effective Healing":511.56,"Healing":511.56}},"armor":{"weight":"Medium","helmAffix":"Ritualist","helmRuneId":67339,"helmRune":"Trapper","helmRuneCount":6,"helmInfusionId":49432,"shouldersAffix":"Ritualist","shouldersRuneId":67339,"shouldersRune":"Trapper","shouldersRuneCount":6,"shouldersInfusionId":49432,"coatAffix":"Ritualist","coatRuneId":67339,"coatRune":"Trapper","coatRuneCount":6,"coatInfusionId":49432,"glovesAffix":"Ritualist","glovesRuneId":67339,"glovesRune":"Trapper","glovesRuneCount":6,"glovesInfusionId":49432,"leggingsAffix":"Ritualist","leggingsRuneId":67339,"leggingsRune":"Trapper","leggingsRuneCount":6,"leggingsInfusionId":49432,"bootsAffix":"Ritualist","bootsRuneId":67339,"bootsRune":"Trapper","bootsRuneCount":6,"bootsInfusionId":49432},"weapon":{"weapon1MainId":30695,"weapon1MainType":"Scepter","weapon1MainSigil1Id":24609,"weapon1MainAffix":"Viper","weapon1MainInfusion1Id":49432,"weapon1OffId":30687,"weapon1OffType":"Dagger","weapon1OffSigilId":24583,"weapon1OffAffix":"Viper","weapon1OffInfusionId":49432,"weapon2OffId":30693,"weapon2OffType":"Pistol","weapon2OffSigilId":24583,"weapon2OffAffix":"Viper","weapon2OffInfusionId":49432},"backAndTrinket":{"backItemAffix":"Viper","backItemInfusion1Id":49432,"backItemInfusion2Id":49432,"amuletAffix":"Ritualist","ring1Affix":"Viper","ring1Infusion1Id":49432,"ring1Infusion2Id":49432,"ring1Infusion3Id":49432,"ring2Affix":"Viper","ring2Infusion1Id":49432,"ring2Infusion2Id":49432,"ring2Infusion3Id":49432,"accessory1Affix":"Ritualist","accessory1InfusionId":49432,"accessory2Affix":"Ritualist","accessory2InfusionId":49432},"consumables":{"foodId":95942,"utilityId":81079},"skills":{"healId":63292,"utility1Id":13026,"utility2Id":13055,"utility3Id":13037,"eliteId":13132},"assumedBuffs":{"value":[{"id":"might","type":"Boon"},{"id":"fury","type":"Boon"},{"id":"protection","type":"Boon"},{"id":"vulnerability","type":"Condition"},{"id":"reinforced-armor","type":"Text"},{"id":"jade-bot","gw2id":96613,"type":"Item"},{"id":"omnipotion","gw2id":79722,"type":"Item"}]},"traits":{"selection":[[1164,1292,1291],[1163,1277,1187],[2284,2290,2289]],"lines":[28,44,71]}}'>

This build easily provides <Boon name="Alacrity" />. Use the [gear optimizer](https://optimizer.discretize.eu/?s=TVPLpTL3v1) with the settings from the link to adjust your gear, adjust the desired boon duration number and your agony resist to get the optimal gear. Additionally, when it is <Instability name="Boon Overload"/>, you can also adjust your gear to play a much more offensive variation.

If you do not need the extra CC you can remove the Pistol so your Dagger counts for both sets. This allows you to swap freely for <Item type="Sigil" name="Doom"/> and <Trait name="Quick Pockets"/>.

It's recommended to have a short bow for additional movement during downtime and <Boon name="might"/> blasts on the _Mistlock Singularity_.
</Character>  
</CharacterWithAr>
</Advanced>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
### Traits
<Traits traits1Id="44" traits1="Trickery" traits1SelectedIds="1163,1190,1187" traits2Id="28" traits2="Deadly Arts" traits2SelectedIds="1164,1292,1291" traits3Id="71" traits3="Specter" traits3SelectedIds="2284,2290,2264"/>

<Traits traits1="Trickery" traits1Selected="Thrill of the Crime,Pressure Striking,Quick Pockets" traits2="Deadly Arts" traits2Selected="Deadly Ambition,Panic Strike,Potent Poison" traits3="Specter" traits3Selected="Consume Shadows,Larcenous Torment,Strength of Shadows"/>

### No Pain, No Gain Variant

<Trait id="1277"/> over <Trait id="1190"/> on <Instability name="No Pain, No Gain"/> days, or when boonstrip is needed.
<Traits traits1Id="44" traits1="Trickery" traits1SelectedIds="1163,1277,1187" unembossed/>

### Alacrity Specter

This build can maintain <Boon name="Alacrity"/> solo. You will need to adjust your gear using the [gear optimizer](https://optimizer.discretize.eu/?s=TVPLpTL3v1) with your appropriate AR to gain at least 40% <Attribute name="Boon Duration"/> if you want to upkeep it permanantly.

<Trait name="shadestep" /> is currently bugged and provides more alacrity to your allies than it does to yourself. 2 seconds (before <Attribute name="Boon Duration" />) of <Boon name="Alacrity" /> is applied to your allies, only 1.25 seconds is applied to yourself.

<Boon name="Alacrity" /> is applied to allies around your _Tethered Ally_ via your _Shroud Skills_.

<Traits traits1Id="71" traits1="Specter" traits1SelectedIds="2284,2290,2289" unembossed/>

### Defiance Bar Damage

| Skill               | Damage                                                 |
| ------------------- | ------------------------------------------------------ |
| <Skill id="13132"/> | 150 Defiance bar damage per ally (up to 750 CC).       |
| <Skill id="63275"/> | 450 Defiance bar damage.                               |
| <Skill id="63155"/> | Mind Shock (skill 5) does 150 Defiance bar damage.     |
| <Skill id="13020"/> | 150 Defiance bar damage.                               |
| <Skill id="13012"/> | 200 Defiance bar damage (260 with <Item id="24639"/>). |
| <Skill id="13019"/> | <Condition name="Crippled"/> 15/s Defiance bar damage. |
| <Skill id="13093"/> | <Condition name="Immobile"/> 50/s Defiance bar damage. |

</GridItem>
<GridItem sm="5">

### Situational Skills

|                                                       |                                                                                                                                              |
| ----------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| <Skill id="13093" size="big" disableText/>            | A situational damage ability; take this over <Skill name="Thousand Needles"/> on moving targets.                                             |
| <Skill name="signetofmalice" size="big" disableText/> | Highest sustained healing.                                                                                                                   |
| <Skill name="skelkvenom" size="big" disableText/>     | Best party healing.                                                                                                                          |
| <Skill id="13020" size="big" disableText/>            | Taken over <Skill name="Prepare Thousand Needles"/> when extra CC is needed (particularly useful on MAMA).                                   |
| <Skill id="13082" size="big" disableText/>            | Taken for extra personal DPS, when CC isn't needed. Can also be precasted on the mistlock before swapping to <Skill name="Basilisk Venom"/>, |

<Advanced>
**Useful Skills for Skips**

|                                            |                                                                                                           |
| ------------------------------------------ | --------------------------------------------------------------------------------------------------------- |
| <Skill id="13117" size="big" disableText/> | Group stealth. Keep in mind, if you leave the AoE before it ends, you will be revealed for a long period. |
| <Skill id="13065" size="big" disableText/> | Used for a smoke field to blast <Effect name="Stealth"/> for skips.                                       |
| <Skill id="13044" size="big" disableText/> | 3 seconds AoE <Effect name="Stealth"/> (also another blast).                                              |
| <Skill id="13064" size="big" disableText/> | 1200 range shadowstep, useful for some skips.                                                             |
| <Skill id="13002" size="big" disableText/> | 1200 range teleport, use it again to teleport back.                                                       |
| <Skill id="13038" size="big" disableText/> | One way portal, useful if you don't have <Item id="78978"/>.                                              |
| <Skill id="13025" size="big" disableText/> | 900 range shadowstep, useful for some skips.                                                              |
| <Skill id="13041" size="big" disableText/> | Used as a blast finisher to stack <Effect name="Stealth"/>.                                               |

</Advanced>
</GridItem>
</Grid>

<Divider text="Rotation / Skill usage"/>

<Grid>
<GridItem sm="7">

<Beginner>

### Step-by-Step Rotation

**Step 1: Scepter 3 and F1**

In the first step, we will focus on spending our Initiative and gaining some of it back.

- The main skill we want to spend it on is <Skill name="Twilight Combo"/>.
- Besides that, we will just auto-attack on Scepter. Finishing auto-attack chains is not necessary.
- When low on Initiative, use <Skill name="Siphon"/> to gain back some through <Trait name="Kleptomaniac"/>. Be careful as this skill can cancel other skills you are currently casting.

**Step 2: Shadow Shroud**

Next up, we want to incorporate <Skill name="Enter Shadow Shroud"/>. This will be useful for gaining back Initiative instead of auto-attacking on Scepter for too long.

- When at low Initiative, use <Skill name="Enter Shadow Shroud"/> as soon as possible.
- This will trigger <Trait name="Quick Pockets"/> and give you back some Initiative (unless you recently weapon swapped before).
- Use Skills 2 and 4 off-cooldown in Shroud.
  There are 2 options to track how long you want to stay in Shroud:

1. Leave Shroud when your Initiative is almost full.
2. Leave Shroud after the 3rd time casting skill 2 (if you entered at 0-1 Initiative) or after casting 2 additional auto-attacks after the 2nd time (if you entered at 3-4 initiative).

The 2nd way is more future-proof due to being independent of <Trait name="Quick Pockets"/> timings if you have to swap to Pistol during the fight or when you move on to using the 2nd Dagger to trigger <Trait name="Quick Pockets"/> at different times.

**Step 3: Venoms**

The first utility skills we will incorporate will be the venoms, namely <Skill name="Spider Venom"/> and <Skill name="Skale Venom"/>.

- Venoms give a buff to ourselves and 4 allies that will make the next attacks inflict various conditions. It will count towards your damage and scale with your stats.
- This also means they will be a lot more effective in a real fight "with allies" compared to the golem.
- Use these skills off-cooldown. They are instant-casts and can therefore be used while casting other skills.
- Use <Skill name="Basilisk Venom"/> whenever its CC is needed. This one does have a cast-time though.
- If a Mistlock Singularity is present, you can even precast them there before taking the singularity to reset your skills and use them again once the first ones are used up. This will ensure massive burst damage at the start of the fight.

**Step 4: Thousand Needles**

Lastly, you have <Skill name="Prepare Thousand Needles"/>.

- Using this skill will place a trap on the ground that will take 3 seconds until you can use it again to trigger the trap dealing damage and inflicting conditions in the area.
- Use it off-cooldown unless you know the boss will move soon. You can place it on the boss's location before the boss becomes attackable. The cooldown will start when you first place it, not when you trigger it.
- Due to its stationary nature, this skill can easily get wasted on bosses that move around a lot. You can consider <Skill name="Devourer Venom"/> as an alternative to enemies that move around a lot. In that case, use it like the other 2 venoms in step 3.

</Beginner>

<Advanced>
### Rotation

There is no set rotation for <Specialization name="Specter" text="Condi Specter"/>, your rotation comes from skill priority. Your main aim when playing <Specialization name="Specter" text="Condi Specter"/> is to never have full Initiative, cast utility skills of cooldown and proc <Trait name="Quick Pockets"/> and <Item id="24609"/> as often as possible.

You should be casting your <Skill name="Skale Venom"/>, <Skill name="Spider Venom"/> and <Skill name="Thousand Needles"/> off cooldown (unless a phase is about to end).

On Scepter/Dagger you want to use:

- <Skill name="Twilight Combo"/> (Scepter 3)
- <Skill name="Shadow Bolt"/>, <Skill name="Double Bolt"/>, <Skill name="Triple Bolt"/> (Auto attack chain)

You should also be weapon swapping off cooldown if you are not playing Pistol to make the best use of <Trait name="Quick Pockets"/> and <Item id="24609"/>

In <Skill name="Enter Shadow Shroud" text="Shadow Shroud"/> you want to use:

- <Skill name="Eternal Night"/> (Shroud 4)
- <Skill name="Grasping Shadows"/> (Shroud 2)
- <Skill name="Haunt Shot"/> (Shroud 1)

</Advanced>

</GridItem>

<GridItem sm="5">

<Beginner>
### Step-by-Step Video

This video shows the step-by-step approach to the rotation listed on the left.

<Video youtube="HPwciFIKlAA" caption="by Ascers"/>

</Beginner>

### Golem Rotation

<Beginner>

This video shows the full golem rotation. It optimizes the use of <Item type="Sigil" name="Doom"/> and <Trait name="Quick Pockets"/>.

</Beginner>

<Video youtube="CvCn4vQbDuw" caption="by Incera"/>
<Advanced>
<Card title="Precasting">

All Damaging Venom Skills should be casted on the _Mistlock Singularity_: <Skill name="Skale Venom"/>, <Skill name="Spider Venom"/> and <Skill name="Devourer Venom"/>. On stationary bosses which can be manually activated, instead of precasting <Skill name="Devourer Venom"/>, you can instead go to the spawn location and precast <Skill name="preparethousandneedles"/>. All you have to do then is to activate the Preparation when the boss becomes vulnerable, and cast it again as it will be off cooldown. This is possible on Skorvald, Artsariiv, Arkk, MAMA, and Ensolyss with the use of a <Item name="White Mantle Portal Device"/>, or on Siax without. It is also possible on the Sorrowful Spellcaster (Light & Dark Ai), but with a 1/4 chance of success.

- On 100CM, make sure to precast venoms on your <Skill id="13082"/> minions, as every boon and special ability effect currently on you will be stripped upon starting the encounter. 
- Spam <Skill name="clusterbomb"/> for <Boon name="might"/> blasts on the _Mistlock Singularity_.

</Card>
</Advanced>
<Beginner>
<Card title="Improving Further">

Once you are comfortable with the above steps, you are already doing most of the full rotation and will be able to deal great damage.

There will be a few additional things on the advanced page to improve further but if you got here, you already know the most important things and these will have a smaller impact than what you learned so far.

The additional steps are:

- Using weapon swap more actively when not running a Pistol off-hand in order to maximize the efficiency of <Trait name="Quick Pockets"/> and <Item type="Sigil" name="Doom"/>.
- You can slightly shift the priority of certain skills to maximize their usage like casting <Skill name="Siphon"/> as soon as you go below 9 Initiative instead of when you run out of it.

</Card>
</Beginner>
</GridItem>
</Grid>
