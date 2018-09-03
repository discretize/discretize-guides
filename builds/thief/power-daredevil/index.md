---
title: 'Power Daredevil'
date: '2018-07-01'
rating: 'Good'
role: 'Damage'
profession: 'Thief'
specialization: 'Daredevil'
benchmark: { small: { dps: 34815, by: 'Ramirez [SC]', youtube: 'v503BIZmaME' } }
skills: [13132, 13014, 13044, 13065, 13025]
traits: [2047]
conditions: ['Vulnerability', 'Crippled', 'Blind', 'Weakness']
effects: ['Stealth']
---

The <Specialization name="thief"/> profession is really behind the other power based builds like <Specialization name="dragonhunter" prefix="power"/> and <Specialization name="weaver" prefix="power"/> dps wise, but if you really have nothing else it is fine for off-meta groups. It has a very simple rotation and offers great mobility for skips, as well as endless party <Effect name="stealth"/> (though even a <Specialization name="druid"/> fills this role perfectly).

While <Specialization name="deadeye" prefix="power"/> is more efficient in raids, <Specialization name="daredevil" prefix="power"/> is better in fractals.

<Divider text="Equipment"/>

<Grid>
<GridItem>
<Armor helmId="48087" helmRuneId="24836" helmRuneCount="6" helmAffix="Berserker" helmRune="Scholar" shouldersId="48089" shouldersRuneId="24836" shouldersRuneCount="6" shouldersAffix="Berserker" shouldersRune="Scholar" coatId="48085" coatRuneId="24836" coatRuneCount="6" coatAffix="Berserker" coatRune="Scholar" glovesId="48086" glovesRuneId="24836" glovesRuneCount="6" glovesAffix="Berserker" glovesRune="Scholar" leggingsId="48088" leggingsRuneId="24836" leggingsRuneCount="6" leggingsAffix="Berserker" leggingsRune="Scholar" bootsId="48084" bootsRuneId="24836" bootsRuneCount="6" bootsAffix="Berserker" bootsRune="Scholar"/>
</GridItem>

<GridItem>
<Weapons weapon1MainId="46773" weapon1MainSigil1Id="24615" weapon1MainSigil2Id="24868" weapon1MainType="Staff" weapon1MainAffix="Berserker" weapon1MainSigil1="Force" weapon1MainSigil2="Impact"/>

<Card title="Alternative weapons">
* Staff with <Item id="36053" disableText/> / <Item id="24615" disableText/> and slaying sigils  
  (<Item id="36054"/> doesn't stack anymore)
* A Shortbow to blast <Boon name="might"/>
</Card>
</GridItem>

<GridItem>
<Trinkets backItemId="49384" backItemStatId="584" backItemAffix="Berserker" accessory1Id="39233" accessory1Affix="Berserker" accessory2Id="39232" accessory2Affix="Berserker" amuletId="39273" amuletAffix="Berserker" ring1Id="75669" ring1Affix="Berserker" ring2Id="76024" ring2Affix="Berserker"/>

<Consumables foodId="41569" utilityId="67530" infusionId="37131"/>
</GridItem>
</Grid>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits title="" traits1Id="28" traits1="Dreadly Arts" traits1Selected="1276,1292,1269" traits2Id="35" traits2="Critical Strikes" traits2Selected="1268,1272,1904" traits3Id="7" traits3="Daredevil" traits3Selected="1933,1884,2047"/>
</GridItem>

<GridItem>
<Skills heal="30400" utility1="13037" utility2="30868" utility3="13046" elite="13132"/>

<Card title="Situational">
| | |
| -- | -- |
| <Skill id="13117" size="big" disableText/> | Group stealth. |
| <Skill id="13065" size="big" disableText/> | Drop it to blast <Effect name="stealth"/> for skips or destroy projectiles. |
| <Skill id="13002" size="big" disableText/> | 1200 range teleport, use it again to teleport back. |
| <Skill id="13044" size="big" disableText/> | 3 seconds AoE <Effect name="stealth"/> (also another blast). |
</Card>
</GridItem>
</Grid>

<Divider text="Details"/>

<Grid>
<GridItem sm="7">
<Card title="Rotation">
* Dodge
* <Skill id="30868"/> => <Skill id="30693"/> (repeat from here)
* <Skill id="29911"/> (Staff 2)
* <Skill id="30614"/> => <Skill id="30135"/> (Staff 1)
* <Skill id="29911"/> (Staff 2)
* <Skill id="30614"/> => <Skill id="30135"/> (Staff 1)
* Dodge
* <Skill id="30434"/> (Staff 1)
* <Skill id="29911"/> (Staff 2)
* <Skill id="30614"/> => <Skill id="30135"/> => <Skill id="30434"/>
* <Skill id="29911"/> (Staff 2)
* <Skill id="30614"/> => <Skill id="30135"/> (Staff 1)
* Dodge
* <Skill id="30434"/> (Staff 1)
* <Skill id="29911"/> (Staff 2)
* <Skill id="30614"/> => <Skill id="30135"/> => <Skill id="30434"/>
* <Skill id="29911"/> (Staff 2)
* <Skill id="30614"/> => <Skill id="30135"/> (Staff 1)
* Dodge
* <Skill id="30434"/> (Staff 1)
* Repeat

You can also activate <Skill id="13046"/> for the last few attacks of a fight.
</Card>
</GridItem>

<GridItem>
<Card title="CC skills">
| | |
| -- | -- |
| <Skill id="30693"/> | 200 damage |
| <Skill id="13132"/> | 150 Defiance bar damage per ally |
</Card>
<Video youtube="v503BIZmaME" title="Daredevil Staff 34.8k by Ramirez [SC]"/>
</GridItem>
</Grid>
