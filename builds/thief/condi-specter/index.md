---
archive: false
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
classification:
  - 5
  - 4
  - 3
  - 2
  - 3
compositions: null
hidden: false
hasBeginner: true
specialization: Specter
code: "[&DQUcGywfRxcMAQAACwEAAC8BAAA+AQAADgEAAAAAAAAAAAAAAAAAAAAAAAA=]"
date: "2023-09-08T15:31:40.297Z "
title: Condi (Alac) Specter
rating: Good
role: Condi Damage
profession: Thief
conditions:
  - name: Vulnerability
    uptime: 20 stacks
  - name: Poisoned
  - name: Bleeding
  - name: Torment
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
<Character title="DPS" gear='{"attributes":{"profession":"Thief","specialization":"Specter","data":{"Health":16245,"Armor":2343,"Power":2923,"Precision":1633,"Toughness":1225,"Vitality":1533,"Ferocity":0,"Condition Damage":2767,"Expertise":944,"Concentration":225,"Healing Power":121,"Agony Resistance":150,"Condition Duration":0.7793333333333333,"Boon Duration":0.15,"Critical Chance":0.6014285714285714,"Critical Damage":1.5,"Power Coefficient":2620,"Power2 Coefficient":0,"Burning Coefficient":0,"Bleeding Coefficient":2.58,"Poison Coefficient":18.36,"Torment Coefficient":22.38,"Confusion Coefficient":0,"Flat DPS":0,"Poison Duration":0.33,"Outgoing Healing":0.2,"Torment Duration":0.15,"Effective Power":7322.628612857142,"NonCrit Effective Power":5629.697999999999,"Power DPS":7387.4805412728965,"Power2 DPS":0,"Siphon DPS":0,"Bleeding Damage":301.7720999999999,"Bleeding Stacks":4.59068,"Bleeding DPS":1385.3391440279995,"Burning Damage":898.6154249999998,"Burning Stacks":0,"Burning DPS":0,"Confusion Damage":319.566735,"Confusion Stacks":0,"Confusion DPS":0,"Poison Damage":425.9053679999999,"Poison Stacks":36.72,"Poison DPS":15639.245112959996,"Torment Damage":563.4151874999999,"Torment Stacks":43.17848,"Torment DPS":24327.411405164996,"Damage":48739.47620342589,"Effective Health":75745343.2835821,"Survivability":38508.054541729594,"Effective Healing":511.56,"Healing":511.56}},"armor":{"weight":"Medium","helmAffix":"Viper","helmRuneId":67339,"helmRune":"Trapper","helmRuneCount":6,"helmInfusionId":49431,"shouldersAffix":"Viper","shouldersRuneId":67339,"shouldersRune":"Trapper","shouldersRuneCount":6,"shouldersInfusionId":49431,"coatAffix":"Viper","coatRuneId":67339,"coatRune":"Trapper","coatRuneCount":6,"coatInfusionId":49431,"glovesAffix":"Viper","glovesRuneId":67339,"glovesRune":"Trapper","glovesRuneCount":6,"glovesInfusionId":49432,"leggingsAffix":"Viper","leggingsRuneId":67339,"leggingsRune":"Trapper","leggingsRuneCount":6,"leggingsInfusionId":49432,"bootsAffix":"Viper","bootsRuneId":67339,"bootsRune":"Trapper","bootsRuneCount":6,"bootsInfusionId":49432},"weapon":{"weapon1MainId":30695,"weapon1MainType":"Scepter","weapon1MainSigil1Id":48911,"weapon1MainAffix":"Viper","weapon1MainInfusion1Id":49432,"weapon1OffId":30687,"weapon1OffType":"Dagger","weapon1OffSigilId":24609,"weapon1OffAffix":"Viper","weapon1OffInfusionId":49432,"weapon2OffId":30693,"weapon2OffType":"Pistol","weapon2OffSigilId":24609,"weapon2OffAffix":"Viper","weapon2OffInfusionId":49432},"backAndTrinket":{"backItemAffix":"Viper","backItemInfusion1Id":49432,"amuletAffix":"Viper","ring1Affix":"Viper","ring1Infusion1Id":49432,"ring1Infusion2Id":49432,"ring1Infusion3Id":49432,"ring2Affix":"Viper","ring2Infusion1Id":49432,"ring2Infusion2Id":49432,"ring2Infusion3Id":49432,"accessory1Affix":"Viper","accessory1InfusionId":49432,"accessory2Affix":"Viper","accessory2InfusionId":49432},"consumables":{"foodId":95942,"utilityId":48917},"skills":{"healId":63292,"utility1Id":13026,"utility2Id":13055,"utility3Id":13037,"eliteId":13132},"assumedBuffs":{"value":[{"id":"might","type":"Boon"},{"id":"fury","type":"Boon"},{"id":"protection","type":"Boon"},{"id":"vulnerability","type":"Condition"},{"id":"reinforced-armor","type":"Text"},{"id":"jade-bot","gw2id":96613,"type":"Item"},{"id":"omnipotion","gw2id":79722,"type":"Item"}]},"traits":{"selection":[[1164,1292,1291],[1163,1277,1187],[2284,2290,2264]],"lines":[28,44,71]}}'>

  
The <Skill id="21778"/> is another option to support your party as it brings a tremendous amount of party healing.

If you do not need the extra CC you can remove the Pistol so your Dagger counts for both sets. This allows you to swap freely for <Item type="Sigil" name="Doom"/> and <Trait name="Quick Pockets"/>.

</Character>  
<Character title="Alac Specter 150 Agony Resistance" gear='{"attributes":{"profession":"Thief","specialization":"Specter","data":{"Health":23695,"Armor":2343,"Power":2178,"Precision":1234,"Toughness":1225,"Vitality":2315,"Ferocity":0,"Condition Damage":2753,"Expertise":783,"Concentration":624,"Healing Power":121,"Agony Resistance":150,"Condition Duration":0.672,"Boon Duration":0.41600000000000004,"Critical Chance":0.4114285714285714,"Critical Damage":1.5,"Power Coefficient":2620,"Power2 Coefficient":0,"Burning Coefficient":0,"Bleeding Coefficient":2.58,"Poison Coefficient":18.36,"Torment Coefficient":20.48,"Confusion Coefficient":0,"Flat DPS":0,"Poison Duration":0.33,"Outgoing Healing":0.2,"Torment Duration":0.35,"Effective Power":5057.764045714285,"NonCrit Effective Power":4194.8279999999995,"Power DPS":5102.557489322845,"Power2 DPS":0,"Siphon DPS":0,"Bleeding Damage":300.42389999999995,"Bleeding Stacks":4.31376,"Bleeding DPS":1295.956602864,"Burning Damage":895.1325749999997,"Burning Stacks":0,"Burning DPS":0,"Confusion Damage":318.151125,"Confusion Stacks":0,"Confusion DPS":0,"Poison Damage":424.11226199999993,"Poison Stacks":36.72,"Poison DPS":15573.402260639998,"Torment Damage":448.7098499999999,"Torment Stacks":40.96,"Torment DPS":18379.155455999997,"Damage":40351.07180882684,"Effective Health":110482358.20895524,"Survivability":56167.95028416636,"Effective Healing":511.56,"Healing":511.56}},"armor":{"weight":"Medium","helmAffix":"Viper","helmRuneId":67339,"helmRune":"Trapper","helmRuneCount":6,"helmInfusionId":49431,"shouldersAffix":"Viper","shouldersRuneId":67339,"shouldersRune":"Trapper","shouldersRuneCount":6,"shouldersInfusionId":49431,"coatAffix":"Viper","coatRuneId":67339,"coatRune":"Trapper","coatRuneCount":6,"coatInfusionId":49431,"glovesAffix":"Viper","glovesRuneId":67339,"glovesRune":"Trapper","glovesRuneCount":6,"glovesInfusionId":49432,"leggingsAffix":"Viper","leggingsRuneId":67339,"leggingsRune":"Trapper","leggingsRuneCount":6,"leggingsInfusionId":49432,"bootsAffix":"Viper","bootsRuneId":67339,"bootsRune":"Trapper","bootsRuneCount":6,"bootsInfusionId":49432},"weapon":{"weapon1MainId":30695,"weapon1MainType":"Scepter","weapon1MainSigil1Id":24583,"weapon1MainAffix":"Ritualist","weapon1MainInfusion1Id":49432,"weapon1OffId":30687,"weapon1OffType":"Dagger","weapon1OffSigilId":24609,"weapon1OffAffix":"Ritualist","weapon1OffInfusionId":49432,"weapon2OffId":30693,"weapon2OffType":"Pistol","weapon2OffSigilId":24609,"weapon2OffAffix":"Ritualist","weapon2OffInfusionId":49432},"backAndTrinket":{"backItemAffix":"Viper","backItemInfusion1Id":49432,"amuletAffix":"Ritualist","ring1Affix":"Ritualist","ring1Infusion1Id":49432,"ring1Infusion2Id":49432,"ring1Infusion3Id":49432,"ring2Affix":"Ritualist","ring2Infusion1Id":49432,"ring2Infusion2Id":49432,"ring2Infusion3Id":49432,"accessory1Affix":"Ritualist","accessory1InfusionId":49432,"accessory2Affix":"Ritualist","accessory2InfusionId":49432},"consumables":{"foodId":95942,"utilityId":77567},"skills":{"healId":63292,"utility1Id":13026,"utility2Id":13055,"utility3Id":13037,"eliteId":13132},"assumedBuffs":{"value":[{"id":"might","type":"Boon"},{"id":"fury","type":"Boon"},{"id":"protection","type":"Boon"},{"id":"vulnerability","type":"Condition"},{"id":"reinforced-armor","type":"Text"},{"id":"jade-bot","gw2id":96613,"type":"Item"},{"id":"omnipotion","gw2id":79722,"type":"Item"}]},"traits":{"selection":[[1164,1292,1291],[1163,1277,1187],[2284,2290,2289]],"lines":[28,44,71]}}'>

 This build can maintain <Boon name="Alacrity"/> solo. This setup aims to reach 40%bd for safe alac uptime with no precast in non-organized groups. Use the [gear optimizer](https://optimizer.discretize.eu/?s=TVPLpTL3v1) to adjust your gear if you need to change your <Attribute name="Boon Duration" /> or adjust stats.

The <Skill id="21778"/> is another option to support your party as it brings a tremendous amount of party healing.

If you do not need the extra CC you can remove the Pistol so your Dagger counts for both sets. This allows you to swap freely for <Item type="Sigil" name="Doom"/> and <Trait name="Quick Pockets"/>.

</Character> 
</CharacterWithAr>
</Beginner>

<Advanced>

<CharacterWithAr>  
<Character title="DPS" gear='{"attributes":{"profession":"Thief","specialization":"Specter","data":{"Health":16245,"Armor":2343,"Power":2923,"Precision":1633,"Toughness":1225,"Vitality":1533,"Ferocity":0,"Condition Damage":2857,"Expertise":944,"Concentration":225,"Healing Power":127,"Agony Resistance":150,"Condition Duration":0.7793333333333333,"Boon Duration":0.15,"Critical Chance":0.6014285714285714,"Critical Damage":1.5,"Power Coefficient":2620,"Power2 Coefficient":0,"Burning Coefficient":0,"Bleeding Coefficient":2.58,"Poison Coefficient":18.36,"Torment Coefficient":22.38,"Confusion Coefficient":0,"Flat DPS":0,"Poison Duration":0.33,"Outgoing Healing":0.2,"Torment Duration":0.15,"Effective Power":7322.628612857142,"NonCrit Effective Power":5629.697999999999,"Power DPS":7387.4805412728965,"Power2 DPS":0,"Siphon DPS":0,"Bleeding Damage":310.43909999999994,"Bleeding Stacks":4.59068,"Bleeding DPS":1425.1265675879997,"Burning Damage":921.0051749999999,"Burning Stacks":0,"Burning DPS":0,"Confusion Damage":328.66708499999993,"Confusion Stacks":0,"Confusion DPS":0,"Poison Damage":437.4324779999999,"Poison Stacks":36.72,"Poison DPS":16062.520592159995,"Torment Damage":579.6658124999999,"Torment Stacks":43.17848,"Torment DPS":25029.088691714995,"Damage":49904.216392735885,"Effective Health":75745343.2835821,"Survivability":38508.054541729594,"Effective Healing":513.72,"Healing":513.72}},"armor":{"weight":"Medium","helmAffix":"Viper","helmRuneId":67339,"helmRune":"Trapper","helmRuneCount":6,"helmInfusionId":37130,"shouldersAffix":"Viper","shouldersRuneId":67339,"shouldersRune":"Trapper","shouldersRuneCount":6,"shouldersInfusionId":37130,"coatAffix":"Viper","coatRuneId":67339,"coatRune":"Trapper","coatRuneCount":6,"coatInfusionId":37130,"glovesAffix":"Viper","glovesRuneId":67339,"glovesRune":"Trapper","glovesRuneCount":6,"glovesInfusionId":37130,"leggingsAffix":"Viper","leggingsRuneId":67339,"leggingsRune":"Trapper","leggingsRuneCount":6,"leggingsInfusionId":37130,"bootsAffix":"Viper","bootsRuneId":67339,"bootsRune":"Trapper","bootsRuneCount":6,"bootsInfusionId":37130},"weapon":{"weapon1MainId":30695,"weapon1MainType":"Scepter","weapon1MainSigil1Id":48911,"weapon1MainAffix":"Viper","weapon1MainInfusion1Id":37130,"weapon1OffId":30687,"weapon1OffType":"Dagger","weapon1OffSigilId":24609,"weapon1OffAffix":"Viper","weapon1OffInfusionId":37130,"weapon2OffId":30693,"weapon2OffType":"Pistol","weapon2OffSigilId":24609,"weapon2OffAffix":"Viper","weapon2OffInfusionId":37130},"backAndTrinket":{"backItemAffix":"Viper","backItemInfusion1Id":37130,"backItemInfusion2Id":37130,"amuletAffix":"Viper","ring1Affix":"Viper","ring1Infusion1Id":37130,"ring1Infusion2Id":37130,"ring1Infusion3Id":37130,"ring2Affix":"Viper","ring2Infusion1Id":37130,"ring2Infusion2Id":37130,"ring2Infusion3Id":37130,"accessory1Affix":"Viper","accessory1InfusionId":37130,"accessory2Affix":"Viper","accessory2InfusionId":37130},"consumables":{"foodId":95942,"utilityId":48917},"skills":{"healId":63292,"utility1Id":13026,"utility2Id":13055,"utility3Id":13037,"eliteId":13132},"assumedBuffs":{"value":[{"id":"might","type":"Boon"},{"id":"fury","type":"Boon"},{"id":"protection","type":"Boon"},{"id":"vulnerability","type":"Condition"},{"id":"reinforced-armor","type":"Text"},{"id":"jade-bot","gw2id":96613,"type":"Item"},{"id":"omnipotion","gw2id":79722,"type":"Item"}]},"traits":{"selection":[[1164,1292,1291],[1163,1277,1187],[2284,2290,2264]],"lines":[28,44,71]}}'>

If you do not need the extra CC you can remove the Pistol so your Dagger counts for both sets. This allows you to swap freely for <Item type="Sigil" name="Doom"/> and <Trait name="Quick Pockets"/> (note that the sigils will also proc from going in/out of shroud).

If healing isn't an issue, this is the perfect build to use <Item name="writofmasterfulmalice"/> over <Item name="tuningicicle"/>!

It's recommended to have a short bow for additional movement during downtime and <Boon name="might"/> blasts on the _Mistlock Singularity_.

</Character>
<Character title="Alac Specter 150 Agony Resistance" gear='{"attributes":{"profession":"Thief","specialization":"Specter","data":{"Health":23185,"Armor":2343,"Power":2229,"Precision":1258,"Toughness":1225,"Vitality":2262,"Ferocity":0,"Condition Damage":2844,"Expertise":783,"Concentration":600,"Healing Power":127,"Agony Resistance":150,"Condition Duration":0.672,"Boon Duration":0.4,"Critical Chance":0.4228571428571428,"Critical Damage":1.5,"Power Coefficient":2620,"Power2 Coefficient":0,"Burning Coefficient":0,"Bleeding Coefficient":2.58,"Poison Coefficient":18.36,"Torment Coefficient":20.48,"Confusion Coefficient":0,"Flat DPS":0,"Poison Duration":0.33,"Outgoing Healing":0.2,"Torment Duration":0.35,"Effective Power":5200.728274285712,"NonCrit Effective Power":4293.053999999999,"Power DPS":5246.787862390669,"Power2 DPS":0,"Siphon DPS":0,"Bleeding Damage":309.1871999999999,"Bleeding Stacks":4.31376,"Bleeding DPS":1333.7593758719997,"Burning Damage":917.7710999999997,"Burning Stacks":0,"Burning DPS":0,"Confusion Damage":327.35258999999996,"Confusion Stacks":0,"Confusion DPS":0,"Poison Damage":435.76745099999994,"Poison Stacks":36.72,"Poison DPS":16001.380800719997,"Torment Damage":461.8547999999999,"Torment Stacks":40.96,"Torment DPS":18917.572607999995,"Damage":41499.50064698266,"Effective Health":108104388.0597015,"Survivability":54959.017823945855,"Effective Healing":513.72,"Healing":513.72}},"armor":{"weight":"Medium","helmAffix":"Viper","helmRuneId":67339,"helmRune":"Trapper","helmRuneCount":6,"helmInfusionId":37130,"shouldersAffix":"Ritualist","shouldersRuneId":67339,"shouldersRune":"Trapper","shouldersRuneCount":6,"shouldersInfusionId":37130,"coatAffix":"Ritualist","coatRuneId":67339,"coatRune":"Trapper","coatRuneCount":6,"coatInfusionId":37130,"glovesAffix":"Ritualist","glovesRuneId":67339,"glovesRune":"Trapper","glovesRuneCount":6,"glovesInfusionId":37130,"leggingsAffix":"Ritualist","leggingsRuneId":67339,"leggingsRune":"Trapper","leggingsRuneCount":6,"leggingsInfusionId":37130,"bootsAffix":"Ritualist","bootsRuneId":67339,"bootsRune":"Trapper","bootsRuneCount":6,"bootsInfusionId":37130},"weapon":{"weapon1MainId":30695,"weapon1MainType":"Scepter","weapon1MainSigil1Id":24583,"weapon1MainAffix":"Ritualist","weapon1MainInfusion1Id":37130,"weapon1OffId":30687,"weapon1OffType":"Dagger","weapon1OffSigilId":24609,"weapon1OffAffix":"Viper","weapon1OffInfusionId":37130,"weapon2OffId":30693,"weapon2OffType":"Pistol","weapon2OffSigilId":24609,"weapon2OffAffix":"Viper","weapon2OffInfusionId":37130},"backAndTrinket":{"backItemAffix":"Ritualist","backItemInfusion1Id":37130,"backItemInfusion2Id":37130,"amuletAffix":"Viper","ring1Affix":"Ritualist","ring1Infusion1Id":37130,"ring1Infusion2Id":37130,"ring1Infusion3Id":37130,"ring2Affix":"Ritualist","ring2Infusion1Id":37130,"ring2Infusion2Id":37130,"ring2Infusion3Id":37130,"accessory1Affix":"Viper","accessory1InfusionId":37130,"accessory2Affix":"Viper","accessory2InfusionId":37130},"consumables":{"foodId":95942,"utilityId":77567},"skills":{"healId":63292,"utility1Id":13026,"utility2Id":13055,"utility3Id":13037,"eliteId":13132},"assumedBuffs":{"value":[{"id":"might","type":"Boon"},{"id":"fury","type":"Boon"},{"id":"protection","type":"Boon"},{"id":"vulnerability","type":"Condition"},{"id":"reinforced-armor","type":"Text"},{"id":"jade-bot","gw2id":96613,"type":"Item"},{"id":"omnipotion","gw2id":79722,"type":"Item"}]},"traits":{"selection":[[1164,1292,1291],[1163,1277,1187],[2284,2290,2289]],"lines":[28,44,71]}}'>
This build easily provides <Boon name="Alacrity" />. The setup aims to reach 40%bd for safe alacrity uptime with no precast in non-organized groups. Use the [gear optimizer](https://optimizer.discretize.eu/?s=TVPLpTL3v1) with the settings from the link to adjust your gear, adjust the desired boon duration number and your agony resist to get the optimal gear. Additionally, when it is <Instability name="Boon Overload"/>, you can also adjust your gear to play a much more offensive variation.

If you do not need the extra CC you can remove the Pistol so your Dagger counts for both sets. This allows you to swap freely for <Item type="Sigil" name="Doom"/> and <Trait name="Quick Pockets"/>.

It's recommended to have a short bow for additional movement during downtime and <Boon name="might"/> blasts on the _Mistlock Singularity_.This build can maintain <Boon name="Alacrity"/> solo. 
</Character>
<Character title="Alac Specter 222 Agony Resistance" gear='{"attributes":{"profession":"Thief","specialization":"Specter","data":{"Health":20545,"Armor":2451,"Power":2601,"Precision":1456,"Toughness":1333,"Vitality":1984,"Ferocity":0,"Condition Damage":2850,"Expertise":783,"Concentration":510,"Healing Power":127,"Agony Resistance":222,"Condition Duration":0.672,"Boon Duration":0.34,"Critical Chance":0.5171428571428571,"Critical Damage":1.5,"Power Coefficient":2620,"Power2 Coefficient":0,"Burning Coefficient":0,"Bleeding Coefficient":2.58,"Poison Coefficient":18.36,"Torment Coefficient":20.48,"Confusion Coefficient":0,"Flat DPS":0,"Poison Duration":0.33,"Outgoing Healing":0.2,"Torment Duration":0.35,"Effective Power":6304.846294285712,"NonCrit Effective Power":5009.525999999999,"Power DPS":6360.684363122282,"Power2 DPS":0,"Siphon DPS":0,"Bleeding Damage":309.76499999999993,"Bleeding Stacks":4.31376,"Bleeding DPS":1336.2518663999997,"Burning Damage":919.2637499999998,"Burning Stacks":0,"Burning DPS":0,"Confusion Damage":327.95928,"Confusion Stacks":0,"Confusion DPS":0,"Poison Damage":436.53592499999996,"Poison Stacks":36.72,"Poison DPS":16029.599165999998,"Torment Damage":462.72149999999993,"Torment Stacks":40.96,"Torment DPS":18953.07264,"Damage":42679.60803552227,"Effective Health":100210537.31343284,"Survivability":50945.87560418548,"Effective Healing":513.72,"Healing":513.72}},"armor":{"weight":"Medium","helmAffix":"Viper","helmRuneId":67339,"helmRune":"Trapper","helmRuneCount":6,"helmInfusionId":37130,"shouldersAffix":"Ritualist","shouldersRuneId":67339,"shouldersRune":"Trapper","shouldersRuneCount":6,"shouldersInfusionId":37130,"coatAffix":"Ritualist","coatRuneId":67339,"coatRune":"Trapper","coatRuneCount":6,"coatInfusionId":37130,"glovesAffix":"Ritualist","glovesRuneId":67339,"glovesRune":"Trapper","glovesRuneCount":6,"glovesInfusionId":37130,"leggingsAffix":"Ritualist","leggingsRuneId":67339,"leggingsRune":"Trapper","leggingsRuneCount":6,"leggingsInfusionId":37130,"bootsAffix":"Ritualist","bootsRuneId":67339,"bootsRune":"Trapper","bootsRuneCount":6,"bootsInfusionId":37130},"weapon":{"weapon1MainId":30695,"weapon1MainType":"Scepter","weapon1MainSigil1Id":24583,"weapon1MainAffix":"Viper","weapon1MainInfusion1Id":37130,"weapon1OffId":30687,"weapon1OffType":"Dagger","weapon1OffSigilId":24609,"weapon1OffAffix":"Viper","weapon1OffInfusionId":37130,"weapon2OffId":30693,"weapon2OffType":"Pistol","weapon2OffSigilId":24609,"weapon2OffAffix":"Viper","weapon2OffInfusionId":37130},"backAndTrinket":{"backItemAffix":"Viper","backItemInfusion1Id":37130,"backItemInfusion2Id":37130,"amuletAffix":"Viper","ring1Affix":"Viper","ring1Infusion1Id":37130,"ring1Infusion2Id":37130,"ring1Infusion3Id":37130,"ring2Affix":"Viper","ring2Infusion1Id":37130,"ring2Infusion2Id":37130,"ring2Infusion3Id":37130,"accessory1Affix":"Viper","accessory1InfusionId":37130,"accessory2Affix":"Viper","accessory2InfusionId":37130},"consumables":{"foodId":95942,"utilityId":77567},"skills":{"healId":63292,"utility1Id":13026,"utility2Id":13055,"utility3Id":13037,"eliteId":13132},"assumedBuffs":{"value":[{"id":"might","type":"Boon"},{"id":"fury","type":"Boon"},{"id":"protection","type":"Boon"},{"id":"vulnerability","type":"Condition"},{"id":"reinforced-armor","type":"Text"},{"id":"jade-bot","gw2id":96613,"type":"Item"},{"id":"omnipotion","gw2id":79722,"type":"Item"}]},"traits":{"selection":[[1164,1292,1291],[1163,1277,1187],[2284,2290,2289]],"lines":[28,44,71]}}'>

This build aims for the minimum <Attribute name="Boon Duration" /> required to maintain <Boon name="Alacrity" />. Use the [gear optimizer](https://optimizer.discretize.eu/?s=TVPLpTL3v1) with the settings from the link to adjust your gear, adjust the desired boon duration number and your agony resist to get the optimal gear. Additionally, when it is <Instability name="Boon Overload"/>.

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

### Situational Trait
<Trait id="1277"/> over <Trait id="1190"/> on <Instability name="No Pain, No Gain"/> days, or when boonstrip is needed.

### Alacrity Specter

This build can maintain <Boon name="Alacrity"/> solo. The minimum <Attribute name="Boon Duration" /> required is **34%**, but might make it hard to maintain alacrity uptime, which is why the general build suggests **40% uptime** You might need to adjust your gear using the [gear optimizer](https://optimizer.discretize.eu/?s=TVPLpTL3v1) with your <Attribute name="Agony Resistance" /> and desired <Attribute name="Boon Duration" />.

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
