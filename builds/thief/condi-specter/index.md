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
date: "2023-04-13T19:14:59.700Z "
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

The **<Specialization text="Condi Specter" name="Specter"/>** is a high DPS condition build with great team support options. It offers large amounts of <Effect name="Barrier"/> for your party, some healing and a small amount of <Boon name="Might"/> and <Boon name="Swiftness"/> by targeting allied players.

<Advanced>

The value of this build comes from the pure damage that it will bring, which is inflated by the **<Specialization text="Condi Soulbeast" name="Soulbeast"/>**'s <Skill id="40498"/>, on top of Venom Skills which can be precast on the _Mistlock Singularity_, and cast again as soon as your allies have consumed them by attacking the target.

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
<Character title="DPS Specter" gear='{"attributes":{"profession":"Thief","specialization":"Specter","data":{"Health":16245,"Armor":2343,"Power":2923,"Precision":1633,"Toughness":1225,"Vitality":1460,"Ferocity":0,"Condition Damage":2495,"Expertise":1014,"Concentration":225,"Healing Power":0,"Agony Resistance":150,"Condition Duration":0.6759999999999999,"Boon Duration":0.15,"Critical Chance":0.6014285714285714,"Critical Damage":1.5,"Power Coefficient":2316,"Power2 Coefficient":0,"Burning Coefficient":0,"Bleeding Coefficient":2.43,"Poison Coefficient":18.2,"Torment Coefficient":20.65,"Confusion Coefficient":0,"Flat DPS":0,"Poison Duration":0.33,"Outgoing Healing":0.2,"Torment Duration":0.5,"Siphon Base Coefficient":113.75,"Effective Power":7345.440539999998,"NonCrit Effective Power":5647.235999999999,"Power DPS":6550.650862780129,"Power2 DPS":0,"Siphon DPS":129.4475,"Bleeding Damage":287.16824999999994,"Bleeding Stacks":4.07268,"Bleeding DPS":1169.5443884099998,"Burning Damage":865.8950625,"Burning Stacks":0,"Burning DPS":0,"Confusion Damage":339.44223750000003,"Confusion Stacks":0,"Confusion DPS":0,"Poison Damage":407.51466,"Poison Stacks":36.4,"Poison DPS":14833.533624,"Torment Damage":471.61991249999994,"Torment Stacks":41.3,"Torment DPS":19477.902386249996,"Damage":42161.07876144012,"Effective Health":94681679.10447764,"Survivability":48135.06817716199,"Effective Healing":468,"Healing":468}},"armor":{"weight":"Medium","helmAffix":"Viper","helmRuneId":44956,"helmRune":"Tormenting","helmRuneCount":6,"helmInfusionId":49431,"shouldersAffix":"Viper","shouldersRuneId":44956,"shouldersRune":"Tormenting","shouldersRuneCount":6,"shouldersInfusionId":49431,"coatAffix":"Viper","coatRuneId":44956,"coatRune":"Tormenting","coatRuneCount":6,"coatInfusionId":49431,"glovesAffix":"Viper","glovesRuneId":44956,"glovesRune":"Tormenting","glovesRuneCount":6,"glovesInfusionId":49432,"leggingsAffix":"Viper","leggingsRuneId":44956,"leggingsRune":"Tormenting","leggingsRuneCount":6,"leggingsInfusionId":49432,"bootsAffix":"Viper","bootsRuneId":44956,"bootsRune":"Tormenting","bootsRuneCount":6,"bootsInfusionId":49432},"weapon":{"weapon1MainId":30695,"weapon1MainType":"Scepter","weapon1MainSigil1Id":44944,"weapon1MainAffix":"Viper","weapon1MainInfusion1Id":49432,"weapon1OffId":30687,"weapon1OffType":"Dagger","weapon1OffSigilId":24609,"weapon1OffAffix":"Viper","weapon1OffInfusionId":49432,"weapon2OffId":30693,"weapon2OffType":"Pistol","weapon2OffSigilId":24639,"weapon2OffAffix":"Viper","weapon2OffInfusionId":49432},"backAndTrinket":{"backItemAffix":"Viper","backItemInfusion1Id":49432,"amuletAffix":"Viper","ring1Affix":"Viper","ring1Infusion1Id":49432,"ring1Infusion2Id":49432,"ring1Infusion3Id":49432,"ring2Affix":"Viper","ring2Infusion1Id":49432,"ring2Infusion2Id":49432,"ring2Infusion3Id":49432,"accessory1Affix":"Viper","accessory1InfusionId":49432,"accessory2Affix":"Viper","accessory2InfusionId":49432},"consumables":{"foodId":91878,"utilityId":77567},"skills":{"healId":63292,"utility1Id":13026,"utility2Id":13037,"utility3Id":13055,"eliteId":13132},"assumedBuffs":{"value":[{"id":"might","type":"Boon"},{"id":"fury","type":"Boon"},{"id":"protection","type":"Boon"},{"id":"vulnerability","type":"Condition"},{"id":"jade-bot","gw2id":96613,"type":"Item"},{"id":"omnipotion","gw2id":79722,"type":"Item"}]},"traits":{"selection":[[1164,1292,1291],[1163,1277,1187],[2275,2285,2264]],"lines":[28,44,71]}}'>
  
The <Skill id="21778"/> is a great option to support your party as it brings a tremendous amount of party healing.

If you do not need the extra CC you can remove the Pistol so your Dagger counts for both sets. This allows you to swap freely for <Item type="Sigil" name="Doom"/> and <Trait name="Quick Pockets"/>.

</Character>  
</CharacterWithAr>
</Beginner>
<Advanced>
<CharacterWithAr>  
<Character title="DPS/Alac Share" gear='{"attributes":{"profession":"Thief","specialization":"Specter","data":{"Health":16245,"Armor":2343,"Power":2923,"Precision":1633,"Toughness":1225,"Vitality":1460,"Ferocity":0,"Condition Damage":2585,"Expertise":1014,"Concentration":225,"Healing Power":0,"Agony Resistance":150,"Condition Duration":0.6759999999999999,"Boon Duration":0.15,"Critical Chance":0.6014285714285714,"Critical Damage":1.5,"Power Coefficient":2316,"Power2 Coefficient":0,"Burning Coefficient":0,"Bleeding Coefficient":2.43,"Poison Coefficient":18.2,"Torment Coefficient":20.65,"Confusion Coefficient":0,"Flat DPS":0,"Poison Duration":0.33,"Outgoing Healing":0.2,"Torment Duration":0.5,"Siphon Base Coefficient":113.75,"Effective Power":7345.440539999998,"NonCrit Effective Power":5647.235999999999,"Power DPS":6550.650862780129,"Power2 DPS":0,"Siphon DPS":129.4475,"Bleeding Damage":296.19975,"Bleeding Stacks":4.07268,"Bleeding DPS":1206.32679783,"Burning Damage":889.2264374999999,"Burning Stacks":0,"Burning DPS":0,"Confusion Damage":349.8284625,"Confusion Stacks":0,"Confusion DPS":0,"Poison Damage":419.52655500000003,"Poison Stacks":36.4,"Poison DPS":15270.766602,"Torment Damage":486.5218875,"Torment Stacks":41.3,"Torment DPS":20093.353953749996,"Damage":43250.545716360124,"Effective Health":94681679.10447764,"Survivability":48135.06817716199,"Effective Healing":468,"Healing":468}},"armor":{"weight":"Medium","helmAffix":"Viper","helmRuneId":44956,"helmRune":"Tormenting","helmRuneCount":6,"helmInfusionId":37130,"shouldersAffix":"Viper","shouldersRuneId":44956,"shouldersRune":"Tormenting","shouldersRuneCount":6,"shouldersInfusionId":37130,"coatAffix":"Viper","coatRuneId":44956,"coatRune":"Tormenting","coatRuneCount":6,"coatInfusionId":37130,"glovesAffix":"Viper","glovesRuneId":44956,"glovesRune":"Tormenting","glovesRuneCount":6,"glovesInfusionId":37130,"leggingsAffix":"Viper","leggingsRuneId":44956,"leggingsRune":"Tormenting","leggingsRuneCount":6,"leggingsInfusionId":37130,"bootsAffix":"Viper","bootsRuneId":44956,"bootsRune":"Tormenting","bootsRuneCount":6,"bootsInfusionId":37130},"weapon":{"weapon1MainId":30695,"weapon1MainType":"Scepter","weapon1MainSigil1Id":44944,"weapon1MainAffix":"Viper","weapon1MainInfusion1Id":37130,"weapon1OffId":30687,"weapon1OffType":"Dagger","weapon1OffSigilId":24609,"weapon1OffAffix":"Viper","weapon1OffInfusionId":37130,"weapon2OffId":30693,"weapon2OffType":"Pistol","weapon2OffSigilId":24639,"weapon2OffAffix":"Viper","weapon2OffInfusionId":37130},"backAndTrinket":{"backItemAffix":"Viper","backItemInfusion1Id":37130,"backItemInfusion2Id":37130,"amuletAffix":"Viper","ring1Affix":"Viper","ring1Infusion1Id":37130,"ring1Infusion2Id":37130,"ring1Infusion3Id":37130,"ring2Affix":"Viper","ring2Infusion1Id":37130,"ring2Infusion2Id":37130,"ring2Infusion3Id":37130,"accessory1Affix":"Viper","accessory1InfusionId":37130,"accessory2Affix":"Viper","accessory2InfusionId":37130},"consumables":{"foodId":91878,"utilityId":77567},"skills":{"healId":63292,"utility1Id":13026,"utility2Id":13037,"utility3Id":13055,"eliteId":13132},"assumedBuffs":{"value":[{"id":"might","type":"Boon"},{"id":"fury","type":"Boon"},{"id":"protection","type":"Boon"},{"id":"vulnerability","type":"Condition"},{"id":"jade-bot","gw2id":96613,"type":"Item"},{"id":"omnipotion","gw2id":79722,"type":"Item"}]},"traits":{"selection":[[1164,1292,1291],[1163,1277,1187],[2275,2285,2264]],"lines":[28,44,71]}}'>

The <Skill name="skelkvenom" /> is a great option to support your party as it brings a tremendous amount of party healing.

If you do not need the extra CC you can remove the Pistol so your Dagger counts for both sets. This allows you to swap freely for <Item type="Sigil" name="Doom"/> and <Trait name="Quick Pockets"/>.

If healing isn't an issue, this is the perfect build to use <Item name="writofmasterfulmalice"/> over <Item name="tuningicicle"/> ! <Skill name="signetofmalice"/> is also the strongest personal-healing ability you can bring to maintain your health over 90%, if you feel you don't need <Skill name="hideinshadows"/>.

It's recommended to have a short bow for additional movement during downtime and <Boon name="might"/> blasts on the _Mistlock Singularity_.
</Character>
<Character title="Condi Alac Specter" gear='{"attributes":{"profession":"Thief","specialization":"Specter","data":{"Health":28975,"Armor":2343,"Power":1750,"Precision":1000,"Toughness":1225,"Vitality":2733,"Ferocity":0,"Condition Damage":2749,"Expertise":1179,"Concentration":858,"Healing Power":0,"Agony Resistance":150,"Condition Duration":0.7859999999999999,"Boon Duration":0.5720000000000001,"Critical Chance":0.3,"Critical Damage":1.5,"Power Coefficient":920,"Power2 Coefficient":0,"Burning Coefficient":0,"Bleeding Coefficient":0,"Poison Coefficient":13.056000000000001,"Torment Coefficient":13.74,"Confusion Coefficient":0,"Flat DPS":0,"Poison Duration":0.53,"Outgoing Healing":0.2,"Torment Duration":0.2,"Siphon Base Coefficient":113.75,"Effective Power":3882.1124999999993,"NonCrit Effective Power":3375.7499999999995,"Power DPS":1375.2574123989216,"Power2 DPS":0,"Siphon DPS":129.22000000000003,"Bleeding Damage":300.50604999999996,"Bleeding Stacks":0,"Bleeding DPS":0,"Burning Damage":895.5302125,"Burning Stacks":0,"Burning DPS":0,"Confusion Damage":354.4232075,"Confusion Stacks":0,"Confusion DPS":0,"Poison Damage":424.259759,"Poison Stacks":26.112000000000002,"Poison DPS":11078.270827008,"Torment Damage":448.83007499999997,"Torment Stacks":27.28764,"Torment DPS":12247.513507773,"Damage":24830.26174717992,"Effective Health":168876679.10447764,"Survivability":85854.9461639439,"Effective Healing":468,"Healing":468}},"armor":{"weight":"Medium","helmAffix":"Ritualist","helmRuneId":24738,"helmRune":"Scavenging","helmRuneCount":6,"helmInfusionId":37130,"shouldersAffix":"Ritualist","shouldersRuneId":24738,"shouldersRune":"Scavenging","shouldersRuneCount":6,"shouldersInfusionId":37130,"coatAffix":"Ritualist","coatRuneId":24738,"coatRune":"Scavenging","coatRuneCount":6,"coatInfusionId":37130,"glovesAffix":"Ritualist","glovesRuneId":24738,"glovesRune":"Scavenging","glovesRuneCount":6,"glovesInfusionId":37130,"leggingsAffix":"Ritualist","leggingsRuneId":24738,"leggingsRune":"Scavenging","leggingsRuneCount":6,"leggingsInfusionId":37130,"bootsAffix":"Ritualist","bootsRuneId":24738,"bootsRune":"Scavenging","bootsRuneCount":6,"bootsInfusionId":37130},"weapon":{"weapon1MainId":30695,"weapon1MainType":"Scepter","weapon1MainSigil1Id":24583,"weapon1MainAffix":"Ritualist","weapon1MainInfusion1Id":37130,"weapon1OffId":30687,"weapon1OffType":"Dagger","weapon1OffSigilId":24609,"weapon1OffAffix":"Ritualist","weapon1OffInfusionId":37130,"weapon2OffId":30693,"weapon2OffType":"Pistol","weapon2OffSigilId":24639,"weapon2OffAffix":"Ritualist","weapon2OffInfusionId":37130},"backAndTrinket":{"backItemAffix":"Ritualist","backItemInfusion1Id":37130,"backItemInfusion2Id":37130,"amuletAffix":"Ritualist","ring1Affix":"Ritualist","ring1Infusion1Id":37130,"ring1Infusion2Id":37130,"ring1Infusion3Id":37130,"ring2Affix":"Ritualist","ring2Infusion1Id":37130,"ring2Infusion2Id":37130,"ring2Infusion3Id":37130,"accessory1Affix":"Ritualist","accessory1InfusionId":37130,"accessory2Affix":"Ritualist","accessory2InfusionId":37130},"consumables":{"foodId":91878,"utilityId":81079},"skills":{"healId":63292,"utility1Id":63323,"utility2Id":63276,"utility3Id":13037,"eliteId":13132},"assumedBuffs":{"value":[{"id":"might","type":"Boon"},{"id":"fury","type":"Boon"},{"id":"protection","type":"Boon"},{"id":"vulnerability","type":"Condition"},{"id":"jade-bot","gw2id":96613,"type":"Item"},{"id":"omnipotion","gw2id":79722,"type":"Item"}]},"traits":{"selection":[[1164,1292,1291],[1163,1277,1187],[2275,2285,2264]],"lines":[28,44,71]}}'>

This build runs <Attribute name="Boon Duration" text="57% Boon Duration"/> to be in line with the raid build. If you are confident to maintain <Boon name="Alacrity"/> you only need <Attribute name="Boon Duration" text="43% Boon Duration"/>. Use the [gear optimizer](https://optimizer.discretize.eu/) to adjust your gear. Additionally, when it is <Instability name="Boon Overload"/>, you can also adjust your gear to play a much more offensive variation.

If you do not need the extra CC you can remove the Pistol so your Dagger counts for both sets. This allows you to swap freely for <Item type="Sigil" name="Doom"/> and <Trait name="Quick Pockets"/>.

It's recommended to have a short bow for additional movement during downtime and <Boon name="might"/> blasts on the _Mistlock Singularity_.
</Character>  
</CharacterWithAr>
</Advanced>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Card title="Traits">
<Traits unembossed traits1="Trickery" traits1Selected="Thrill of the Crime,Pressure Striking,Quick Pockets" traits2="Deadly Arts" traits2Selected="Deadly Ambition,Panic Strike,Potent Poison" traits3="Specter" traits3Selected="Consume Shadows,Larcenous Torment,Strength of Shadows"/>

### No Pain, No Gain Variant

<Trait id="1277"/> over <Trait id="1190"/> on <Instability name="No Pain, No Gain"/> days, or when boonstrip is needed.
<Traits traits1="Trickery" traits1Selected="Thrill of the Crime,Bountiful Theft,Quick Pockets" unembossed/>

<Advanced>
### Alacrity Variants

Situationally <Specialization name="Specter"/> can be used as a <Boon name="Alacrity"/> source. Either on its own or sharing generation with another class.

#### Alac Share

Alac share specter is a very strong build to play, especially on Ensolyss and 100CM. It uses the same gear as <Specialization text="Condi DPS Specter" name="Specter"/>.

The DPS loss for the specter is well worth the DPS gain of taking a <Specialization text="Condi DPS Renegade" name="Renegade"/>, a <Specialization text="Staxe Mirage" name="Mirage"/> or another <Specialization text="Alac Share Specter" name="Specter"/> over a dedicated <Boon name="Alacrity"/> source!

<Traits traits1="Specter" traits1Selected="Consume Shadows,Traversing Dusk,Strength of Shadows" unembossed/>
<Skills heal="Well of Gloom" utility1="Well of Sorrow" utility2="Devourer Venom" utility3="Spider Venom" elite="Basilisk Venom" unembossed/>

#### Alacrity Specter

This build can maintain <Boon name="Alacrity"/> solo. You will need to adjust your gear using the [gear optimizer](https://optimizer.discretize.eu/) to gain at least 43% <Attribute name="Boon Duration"/> if you want to upkeep it permanantly.

<Traits traits1="Specter" traits1Selected="Consume Shadows,Traversing Dusk,Strength of Shadows" unembossed/>
<Skills heal="Well of Gloom" utility1="Well of Bounty" utility2="Well of Sorrow" utility3="Spider Venom" elite="Basilisk Venom" unembossed/>
</Advanced>

</Card>
</GridItem>
<GridItem sm="5">

<Card title="Situational Skills">

|                                                       |                                                                                                                                              |
| ----------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| <Skill id="13093" size="big" disableText/>            | A situational damage ability; take this over <Skill name="Thousand Needles"/> on moving targets.                                             |
| <Skill name="signetofmalice" size="big" disableText/> | Highest sustained healing.                                                                                                                   |
| <Skill name="skelkvenom" size="big" disableText/>     | Best party healing.                                                                                                                          |
| <Skill id="13020" size="big" disableText/>            | Taken over <Skill name="Prepare Thousand Needles"/> when extra CC is needed (particularly useful on MAMA).                                   |
| <Skill id="13082" size="big" disableText/>            | Taken for extra personal DPS, when CC isn't needed. Can also be precasted on the mistlock before swapping to <Skill name="Basilisk Venom"/>, |

</Card>

<Advanced>
<Card title="Useful skills for skips">

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

</Card>
</Advanced>

<Card title="CC Skills">

|                                            |                                                        |
| ------------------------------------------ | ------------------------------------------------------ |
| <Skill id="13132" size="big" disableText/> | 150 Defiance bar damage per ally (up to 750 CC).       |
| <Skill id="63275" size="big" disableText/> | 450 Defiance bar damage.                               |
| <Skill id="63155" size="big" disableText/> | Mind Shock (skill 5) does 150 Defiance bar damage.     |
| <Skill id="13020" size="big" disableText/> | 150 Defiance bar damage.                               |
| <Skill id="13012" size="big" disableText/> | 200 Defiance bar damage (260 with <Item id="24639"/>). |
| <Skill id="13019" size="big" disableText/> | <Condition name="Crippled"/> 15/s Defiance bar damage. |
| <Skill id="13093" size="big" disableText/> | <Condition name="Immobile"/> 50/s Defiance bar damage. |

</Card>

</GridItem>
</Grid>

<Divider text="Rotation / Skill usage"/>

<Grid>
<GridItem sm="7">

<Beginner>

<Card title="Step-by-Step Rotation">

**Step 1: Scepter 3 and F1**

In the first step, we will focus on spending our Initiative and gaining some of it back.

- The main skill we want to spend it on is <Skill name="Twilight Combo"/>.
- Besides that, we will just auto-attack on Scepter. Finishing auto-attack chains is not necessary.
- When low on Initiative, use <Skill name="Siphon"/> to gain back some through <Trait name="Kleptomaniac"/>. Be careful as this skill can cancel other skills you are currently casting.

**Step 2: Shadow Shroud**

Next up, we want to incorporate <Skill name="Enter Shadow Shroud"/>. This will be useful for gaining back Initiative instead of auto-attacking on Scepter for too long.

- When at low Initiative, use <Skill name="Enter Shadow Shroud"/> as soon as possible.
- This will trigger <Trait name="Quick Pockets"/> and give you back some Initiative (unless you recently weapon swapped before).
- Use Skills 2,4 and 5 off-cooldown in Shroud.
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

</Card>

<Card title="Improving Further">

Once you are comfortable with the above steps, you are already doing most of the full rotation and will be able to deal great damage.

There will be a few additional things on the advanced page to improve further but if you got here, you already know the most important things and these will have a smaller impact than what you learned so far.

The additional steps are:

- Using weapon swap more actively when not running a Pistol off-hand in order to maximize the efficiency of <Trait name="Quick Pockets"/> and <Item type="Sigil" name="Doom"/>.
- You can slightly shift the priority of certain skills to maximize their usage like casting <Skill name="Siphon"/> as soon as you go below 9 Initiative instead of when you run out of it.

</Card>

</Beginner>

<Advanced>
<Card title="Rotation">

There is no set rotation for <Specialization name="Specter" text="Condi Specter"/>, your rotation comes from skill priority. Your main aim when playing <Specialization name="Specter" text="Condi Specter"/> is to never have full Initiative, cast utility skills of cooldown and proc <Trait name="Quick Pockets"/> and <Item id="24609"/> as often as possible.

You should be casting your <Skill name="Skale Venom"/>, <Skill name="Spider Venom"/> and <Skill name="Thousand Needles"/> off cooldown (unless a phase is about to end).

On Scepter/Dagger you want to use:

- <Skill name="Twilight Combo"/>
- <Skill name="Shadow Bolt"/>, <Skill name="Double Bolt"/>, <Skill name="Triple Bolt"/>

You should also be weapon swapping off cooldown if you are not playing Pistol to make the best use of <Trait name="Quick Pockets"/> and <Item id="24609"/>

In <Skill name="Enter Shadow Shroud" text="Shadow Shorud"/> you want to use:

- Mind Shock (Skill 5)
- Eternal Night (Skill 4)
- Grasping Shadows (Skill 2)
- Haunt Shot (Skill 1)

</Card>
</Advanced>

</GridItem>

<GridItem sm="5">

<Beginner>
<Card title="Step-by-Step Video">

This video shows the step-by-step approach to the rotation listed on the left.

<Video youtube="HPwciFIKlAA" caption="by Ascers"/>

</Card>
</Beginner>

<Card title="Golem rotation">

<Beginner>

This video shows the full golem rotation. It optimizes the use of <Item type="Sigil" name="Doom"/> and <Trait name="Quick Pockets"/>.

</Beginner>

<Video youtube="7ZjQJmms_Dw" caption="by Incera"/>
</Card>

<Advanced>
<Card title="Precasting">

All Damaging Venom Skills should be casted on the _Mistlock Singularity_: <Skill name="Skale Venom"/>, <Skill name="Spider Venom"/> and <Skill name="Devourer Venom"/>. On stationary bosses which can be manually activated, instead of precasting <Skill name="Devourer Venom"/>, you can instead go to the spawn location and precast <Skill name="preparethousandneedles"/>. All you have to do then is to activate the Preparation when the boss becomes vulnerable, and cast it again as it will be off cooldown. This is possible on Skorvald, Artsariiv, Arkk, MAMA, and Ensolyss with the use of a <Item name="White Mantle Portal Device"/>, or on Siax without. It is also possible on the Sorrowful Spellcaster (Light & Dark Ai), but with a 1/4 chance of success.

- On 100CM, make sure to precast venoms on your <Skill id="13082"/> minions, as every boon and special ability effect currently on you will be stripped upon starting the encounter.
- Spam <Skill name="clusterbomb"/> for <Boon name="might"/> blasts on the _Mistlock Singularity_.

</Card>
</Advanced>
</GridItem>
</Grid>
