# Power Gaurdian (DPS)

Intro text bla bla

<Divider>
Equipment
</Divider>

<Grid>
<Column>
<Armor helmId="48075" helmRuneId="24836" helmRuneCount="6" helmAffix="Berserker" helmRune="Scholar" shouldersId="48077" shouldersRuneId="24836" shouldersRuneCount="6" shouldersAffix="Berserker" shouldersRune="Scholar" coatId="48073" coatRuneId="24836" coatRuneCount="6" coatAffix="Berserker" coatRune="Scholar" glovesId="48074" glovesRuneId="24836" glovesRuneCount="6" glovesAffix="Berserker" glovesRune="Scholar" leggingsId="48076" leggingsRuneId="24836" leggingsRuneCount="6" leggingsAffix="Berserker" leggingsRune="Scholar" bootsId="48072" bootsRuneId="24836" bootsRuneCount="6" bootsAffix="Berserker" bootsRune="Scholar"/>
</Column>

<Column>
<Weapons weapon1MainId="46762" weapon1MainSigil1Id="24615" weapon1MainSigil2Id="24554" weapon1MainType="Greatsword" weapon1MainAffix="Berserker" weapon1MainSigil1="Force" weapon1MainSigil2="Air" weapon2MainId="46769" weapon2MainSigil1Id="24615" weapon2MainType="Greatsword" weapon2MainAffix="Berserker" weapon2MainSigil1="Force" weapon2OffId="46775" weapon2OffSigilId="24554" weapon2OffType="Torch" weapon2OffAffix="Berserker" weapon2OffSigil="Air"/>
</Column>

<Column>
<Trinkets backItemId="49384" backItemStatId="584" backItemAffix="Berserker" accessory1Id="39233" accessory1Affix="Berserker" accessory2Id="39232" accessory2Affix="Berserker" amuletId="39273" amuletAffix="Berserker" ring1Id="75669" ring1Affix="Berserker" ring2Id="76024" ring2Affix="Berserker"/>

<Consumables foodId="41569" utilityId="77569" infusionId="37131"/>
</Column>
</Grid>

<Divider>
Build
</Divider>

<Grid>
<Column width="9">
<Traits traits1Id="16" traits1="Radiance" traits1Selected="574,565,1683" traits2Id="27" traits2="Zeal" traits2Selected="1898,1835,1955" traits3Id="42" traits3="Dragonhunter" traits3Selected="634,653,2017"/>
</Column>

<Column>
<Skills weapon1Skill1="" weapon1Skill2="" weapon1Skill3="" weapon1Skill4="" weapon1Skill5="" utilitySkill1="21664" utilitySkill2="30364" utilitySkill3="9168" utilitySkill4="9093" utilitySkill5="30273"/>

<Card>
<CardHeader>
Situational
</CardHeader>
<CardContent>
| | |
| -- | -- |
| <Skill id="9246" size="big" text="false"/> | A 1,200 range teleport (to an ally), sufficient for most blink spots. |
| <Skill id="9153" size="big" text="false"/> | Can be used where <Boon name="stability"/> or <Control name="stun"/> break needed. |
| <Skill id="9125" size="big" text="false"/> | Can be used for extra CC (200 damage) |
</CardContent>
</Card>
</Column>
</Grid>

<Divider>
Details
</Divider>

<Grid>
<Column width="9">
<Card>
<CardHeader>
Rotation
</CardHeader>
<CardContent>
* Start with Greatsword
* Make sure both your <Skill id="29887"/> and <Skill id="30364"/> are off cooldown, then get ready for Weapon Swap:
  * <Skill id="30364"/>
  * <Skill id="29887"/>
  * if swaping from Greatsword to Scepter:
    * <Skill id="9147"/> (skip on first swap)
    * <Skill id="9146"/>
    * <Skill id="30273"/> (if not under cooldown)
    * <Skill id="9168"/>
    * <Skill id="9081"/>
    * Weapon Swap
    * <Skill id="9090"/>
    * <Skill id="9104"/> => <Skill id="9089"/>
  * if Swapping from Scepter to Greatsword:
    * <Skill id="9168"/> (only if Icon states 2 uses left)
    * <Skill id="9104"/> => <Skill id="9089"/>
    * <Skill id="30273"/> (if not under cooldown)
    * <Skill id="9168"/>
    * <Skill id="9090"/>
    * Weapon Swap
    * <Skill id="9146"/>
    * <Skill id="9081"/>

* on Scepter:
  * Use <Skill id="9098"/> after <Skill id="9090"/> to cancel aftercast.
  * Use <Skill id="9104"/> => <Skill id="9089"/> and <Skill id="9104"/> off cooldown.
  * Your 4th <Skill id="9090"/> should be aligned with <Skill id="30364"/> and  <Skill id="29887"/> cooldowns.
* on Greatsword:
  * Make sure to finish Greatsword auto-attack chain before casting anything else.
  * When using <Skill id="9081"/> do not cast auto as it will interrupt the cast.
  * Use <Skill id="9146"/> and <Skill id="9081"/> off cooldown.
  * Your 2ed <Skill id="9146"/> should be aligned with <Skill id="30364"/> and  <Skill id="29887"/> cooldowns.
</CardContent>
</Card>
</Column>

<Column>
<Video videoId="BuTUNNlY_6Q" videoTitle="Small Hitbox: 31.4k DPS by Nightmare [SC]"/>

<Card>
<CardHeader>
CC skills
</CardHeader>
<CardContent>
| | |
| -- | -- |
| <Skill id="9093"/> | 300 damage |
| <Skill id="9226"/> | (after <Skill id="9147"/>) 150 damage |
| <Skill id="33134"/>| (after <Skill id="29887"/>) 150 damage |
| <Skill id="30273"/>| 150 damage |
</CardContent>
</Card>
</Column>
</Grid>
