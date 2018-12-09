---
title: 'Power Daredevil'
date: '2018-09-18'
rating: 'Great'
role: 'Damage'
profession: 'Thief'
specialization: 'Daredevil'
benchmark:
  { small: { dps: 35366, by: 'Derpy Moa [SC]', youtube: 'POHMLGFY3xU' } }
skills: [13132, 13014, 13044, 13065, 13025]
traits: [2047]
conditions: ['Vulnerability', 'Crippled', 'Blind', 'Weakness']
effects: ['Stealth']
---

<Specialization name="Daredevil" text="Power Daredevil"/> has decent DPS and provides excellent crowd control. Furthermore, it adds some <Condition name="Vulnerability"/>, has plenty sources for <Effect name="stealth"/> and has a simplistic rotation.

However, it is highly susceptible to melee unfriendly Instabilities since you are constantly moving and relies on many unique conditions on their target.

The build benefits from slaying potions such as <Item id="50082"/> and <Item name="Impact" type="Sigil"/>.

<Divider text="Equipment"/>

<Grid>
<GridItem sm="4">
<Armor weight="Medium" helmId="48087" helmRuneId="24836" helmRuneCount="6" helmAffix="Berserker" helmRune="Scholar" shouldersId="48089" shouldersRuneId="24836" shouldersRuneCount="6" shouldersAffix="Berserker" shouldersRune="Scholar" coatId="48085" coatRuneId="24836" coatRuneCount="6" coatAffix="Berserker" coatRune="Scholar" glovesId="48086" glovesRuneId="24836" glovesRuneCount="6" glovesAffix="Berserker" glovesRune="Scholar" leggingsId="48088" leggingsRuneId="24836" leggingsRuneCount="6" leggingsAffix="Berserker" leggingsRune="Scholar" bootsId="48084" bootsRuneId="24836" bootsRuneCount="6" bootsAffix="Berserker" bootsRune="Scholar"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainId="46773" weapon1MainSigil1Id="24615" weapon1MainSigil2Id="24868" weapon1MainType="Staff" weapon1MainAffix="Berserker" weapon1MainSigil1="Force" weapon1MainSigil2="Impact"/>

<Card title="Alternative weapons">
* Staff with <Item id="36053" disableText/> / <Item id="24615" disableText/> and slaying sigils  
  (<Item id="36054"/> doesn't stack anymore)
* A shortbow to stack <Boon name="might"/>, <Effect name="Stealth"/> and to skip
</Card>
</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemId="49390" backItemAffix="Berserker" accessory1Id="39233" accessory1Affix="Berserker" accessory2Id="39232" accessory2Affix="Berserker" amuletId="39273" amuletAffix="Berserker" ring1Id="75669" ring1Affix="Berserker" ring2Id="76024" ring2Affix="Berserker"/>

<Consumables foodId="41569" utilityId="67530" infusionId="37131"/>
</GridItem>
</Grid>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits title="" traits1Id="28" traits1="Dreadly Arts" traits1SelectedIds="1276,1292,1269" traits2Id="35" traits2="Critical Strikes" traits2SelectedIds="1268,1272,1904" traits3Id="7" traits3="Daredevil" traits3SelectedIds="1933,1884,2047"/>
</GridItem>

<GridItem sm="5">
<Skills healId="30400" utility1Id="13037" utility2Id="30868" utility3Id="13046" eliteId="13132"/>

<Card title="Situational">
| | |
| -- | -- |
| <Skill id="13117" size="big" disableText/> | Group stealth. |
| <Skill id="13065" size="big" disableText/> | Use it to blast <Effect name="stealth"/> for skips or destroy projectiles. |
| <Skill id="13002" size="big" disableText/> | 1200 range teleport, use it again to teleport back. |
| <Skill id="13044" size="big" disableText/> | 3 seconds AoE <Effect name="stealth"/> (also another blast). |
</Card>
</GridItem>
</Grid>

<Divider text="Details"/>

<Grid>
<GridItem sm="7">
<Card title="Rotation">
(Before fight, lose endurance)
1. **Dodge** 
2. <Skill id="13014"/> (F1 mid Dodge)
3. <Skill id="29911"/> 2x (Staff 2)
4. <Skill id="13046"/> (Utility mid Staff 2)
5. <Skill id="30868"/> => <Skill id="30693"/> (Utility)
6. **Dodge (Repeat from here)**
7. <Skill id="29911"/> (Staff 2)
8. <Skill id="30614"/> => <Skill id="30135" disableText/> => <Skill id="30434" disableText/>
9. **Repeat from** `Step 6`

You can also activate <Skill id="13046"/> for the last few attacks of a fight.
</Card>
</GridItem>

<GridItem sm="5">
<Card title="CC skills">
| | |
| -- | -- |
| <Skill id="30693"/> | 200 damage |
| <Skill id="13132"/> | 150 Defiance bar damage per ally |
</Card>

<Video youtube="POHMLGFY3xU" title="Daredevil Staff 35.3k by Derpy Moa [SC]"/>
</GridItem>
</Grid>
