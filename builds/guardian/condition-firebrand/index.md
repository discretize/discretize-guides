---
title: "Condition Firebrand"
date: "2018-05-16"
group: "Good Builds"
role: "Damage"
profession: "Guardian"
specialization: "Firebrand"
benchmark: { small: { dps: 34005, by: "Nightmare [SC]", youtube: "00-DS9GbzeE" }}
skills: [41714, 9187, 44364, 9154, 29965, 40915]
traits: [571]
boons: ["Quickness", "Might", "Fury", "Retaliation", "Protection", "Swiftness", "Regeneration", "Vigor", "Aegis", "Stability", "Resistance"]
conditions: ["Burning", "Immobile", "Crippled"]
---

The <Specialization name="firebrand" prefix="condition"/> was hit hard by nerfs, but still a good condition class to play in fractals. Offers so much support it really helps players with little experience in fractals. Has everything from reflects, CC to condition cleanse and boonspam.

This is the Viper alternative of the build. Ideally Griveing stats would be the best for fractals (short fights, strong bursts needed), but since Grieving is only acquireable through raids I went with Viper so everyone can use the build, even if they do not raid. So if you want to go with high-end build go with full Grieving (armor,weapons,trinkets).

<Divider>
Equipment
</Divider>

<Grid>
<Column>
<Armor helmId="74412" helmRuneId="83502" helmRuneCount="6" helmAffix="Viper" helmRune="Renegade" shouldersId="72557" shouldersRuneId="83502" shouldersRuneCount="6" shouldersAffix="Viper" shouldersRune="Renegade" coatId="76377" coatRuneId="83502" coatRuneCount="6" coatAffix="Viper" coatRune="Renegade" glovesId="76776" glovesRuneId="83502" glovesRuneCount="6" glovesAffix="Viper" glovesRune="Renegade" leggingsId="77143" leggingsRuneId="83502" leggingsRuneCount="6" leggingsAffix="Viper" leggingsRune="Renegade" bootsId="72548" bootsRuneId="83502" bootsRuneCount="6" bootsAffix="Viper" bootsRune="Renegade"/>
</Column>

<Column>
<Weapons weapon1MainId="76688" weapon1MainSigil1Id="24624" weapon1MainSigil2Id="" weapon1MainType="Scepter" weapon1MainAffix="Viper" weapon1MainSigil1="Smoldering" weapon1MainSigil2="" weapon1OffId="76271" weapon1OffSigilId="44950" weapon1OffType="Torch" weapon1OffAffix="Viper" weapon1OffSigil="Malice" weapon2MainId="77122" weapon2MainSigil1Id="24624" weapon2MainType="Axe" weapon2MainAffix="Viper" weapon2MainSigil1="Smoldering" weapon2OffId="" weapon2OffSigilId="" weapon2OffType="" weapon2OffAffix="" weapon2OffSigil=""/>

<Card>
<CardHeader>
Alternative weapons
</CardHeader>
<CardContent>
- Hammer for <Boon name="might"/> stacking
</CardContent>
</Card>
</Column>

<Column>
<Trinkets backItemId="79830" backItemStatId="1113" backItemAffix="Viper" accessory1Id="80002" accessory1StatId="1113" accessory1Affix="Viper" accessory2Id="79745" accessory2StatId="1113" accessory2Affix="Viper" amuletId="79980" amuletStatId="1113" amuletAffix="Viper" ring1Id="80793" ring1StatId="1113" ring1Affix="Viper" ring2Id="79710" ring2StatId="1113" ring2Affix="Viper"/>

<Consumables foodId="84550" utilityId="77567" infusionId="37130"/>
</Column>
</Grid>

<Divider>
Build
</Divider>

<Grid>
<Column width="9">
<Traits traits1Id="16" traits1="Radiance" traits1Selected="574,565,579" traits2Id="42" traits2="Zeal" traits2Selected="634,1556,2017" traits3Id="62" traits3="Firebrand" traits3Selected="2086,2116,2159"/>
<Card>
<CardHeader>
Rotation
</CardHeader>
<CardContent>
* Start on Axe:
  * Cast <Skill id="40624"/>
  * Use <Skill id="9104"/> => <Skill id="9089"/>
* Swap to Scepter:
  * Use <Skill id="9098"/> after <Skill id="9090"/> to cancel the aftercast
* Use F1 (<Skill id="44364"/> ):
  * Skill 2 4 5 1 1 1 2 1
* Back on scepter  
  * <Skill id="9090"/>
  * <Skill id="9154"/>
  * <Skill id="9104"/> => <Skill id="9089"/>
  * <Skill id="9089"/> if <Trait id="567"/> procs
  * <Skill id="9090"/>
* Use F1 (<Skill id="44364"/> ): (repeat from here)
  * Skill 2 4 5 1 1 1 2 1
* Back on scepter  
  * <Skill id="9090"/>
   * <Skill id="9104"/> => <Skill id="9089"/>
  * <Skill id="9089"/> if <Trait id="567"/> procs
  * <Skill id="9098"/> until <Skill id="9090"/> is on cooldown
* Repeat until <Skill id="9154"/> is off cooldown
  
* Use the following skills up to 1 stack (do not use the initial stack until the end of fight) in combination with a symbol:
  * <Skill id="46148"/>
  * <Skill id="40915"/>
</CardContent>
</Card>
</Column>


<Column>
<Skills weapon1Skill1="" weapon1Skill2="" weapon1Skill3="" weapon1Skill4="" weapon1Skill5="" utilitySkill1="41714" utilitySkill2="46148" utilitySkill3="40915" utilitySkill4="9151" utilitySkill5="9154"/>
<Card>
<CardHeader>
Situational
</CardHeader>
<CardContent>
| | |
| -- | -- |
| <Skill id="29965" size="big" text="false"/> | If your group struggles with <Boon name="quickness"/>. |
| <Skill id="45460" size="big" text="false"/> | Extra group cleanse. |
| <Skill id="43357" size="big" text="false"/> | When group <Boon name="stability"/> is needed. |
| <Skill id="9246" size="big" text="false"/> | A 1,200 range teleport to an ally. |
| <Skill id="9153" size="big" text="false"/> | Can be used where <Boon name="stability"/> or stunbreak is needed. |
| <Skill id="9251" size="big" text="false"/> | A stationary reflect lasting for 10 seconds. |
</CardContent>
</Card>
<Video videoId="3D5AodiyTdk" videoTitle="Large Hitbox: 31.8k DPS by Nightmare [SC]"/>
<Card>
<CardHeader>
CC skills
</CardHeader>
<CardContent>
| | |
| -- | -- |
| F1 Skill 3 | 150 damage |
| <Skill id="45402"/> | 150 damage |
| <Skill id="9093"/> | 300 damage |
</CardContent>
</Card>
</Column>
</Grid>
