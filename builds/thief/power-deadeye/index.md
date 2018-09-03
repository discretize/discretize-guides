---
title: 'Power Deadeye'
date: '2018-09-01'
group: 'Good Builds'
role: 'Damage'
profession: 'Thief'
specialization: 'Deadeye'
rating: 'Great'
benchmark: { small: { dps: 36939, by: 'Derpy Moa [SC]', youtube: 'WmvH1QH9xe0' } }
skills: [13132, 43390]
conditions: ['Vulnerability']
effects: ['Stealth']
---
The <Specialization name="Deadeye" prefix="power"/> is fine for meta groups, but it's lack of cleave and being hard to stay alive with  makes it more off-meta in fractals. It has an extremely simple rotation and offers great mobility for skips, as well as endless party <Effect name="stealth"/> (though a <Specialization name="druid"/> fills this role perfectly).

<Divider text="Equipment"/>

<Grid>
<GridItem>
<Armor helmId="48087" helmRuneId="24836" helmRuneCount="6" helmAffix="Berserker" helmRune="Scholar" shouldersId="48089" shouldersRuneId="24836" shouldersRuneCount="6" shouldersAffix="Berserker" shouldersRune="Scholar" coatId="48085" coatRuneId="24836" coatRuneCount="6" coatAffix="Berserker" coatRune="Scholar" glovesId="48086" glovesRuneId="24836" glovesRuneCount="6" glovesAffix="Berserker" glovesRune="Scholar" leggingsId="48088" leggingsRuneId="24836" leggingsRuneCount="6" leggingsAffix="Berserker" leggingsRune="Scholar" bootsId="48084" bootsRuneId="24836" bootsRuneCount="6" bootsAffix="Berserker" bootsRune="Scholar"/>
</GridItem>

<GridItem>
<Weapons weapon1MainType="Dagger" weapon1MainAffix="Berserker" weapon1MainId="46760" weapon1MainSigil1="Force" weapon1MainSigil1Id="24615" weapon1OffType="Dagger" weapon1OffAffix="Berserker" weapon1OffId="46760" weapon1OffSigil="Impact" weapon1OffSigilId="24868"/>

<Card>
<Card title="Alternative weapons">
* Dagger with <Item id="36053" text="false"/> / <Item id="24615" text="false"/> and slaying sigils  
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
<Traits title="" traits1Id="28" traits1="Dreadly Arts" traits1Selected="1245,1292,1269" traits2Id="35" traits2="Critical Strikes" traits2Selected="1268,1272,1904" traits3Id="58" traits3="Deadeye" traits3Selected="2145,2160,2093"/>
</GridItem>

<GridItem>
<Skills heal="45088" utility1="41158" utility2="13064" utility3="13046" elite="13132"/>

<Card>
<Card title="Situational">
| | |
| -- | -- |
| <Skill id="13117" size="big" text="false"/> | Group stealth. |
| <Skill id="13065" size="big" text="false"/> | Drop it to blast <Effect name="stealth"/> for skips or destroy projectiles. |
| <Skill id="13002" size="big" text="false"/> | 1200 range teleport, use it again to teleport back. |
| <Skill id="13044" size="big" text="false"/> | 3 seconds AoE <Effect name="stealth"/> (also another blast). |
</Card>
</GridItem>
</Grid>

<Divider text="Details"/>

<Grid>
<GridItem sm="7">
<Card title="Rotation">
  
**Opener**  
* <Skill id="43390"/> (F1)
* <Skill id="13046"/> (Utility)
* <Skill id="16432"/> (Dagger 5)
* <Skill id="50481"/> (Dagger 1 in <Effect name="stealth"/>)
* <Skill id="41158"/> (Utility)
* Autoattack chain 2x
* <Skill id="16432"/> (Dagger 5)
* <Skill id="50481"/> (Dagger 1 in <Effect name="stealth"/>)
* Autoattack chain 1x
* <Skill id="43390"/> (F2)
  
**Repeat from here**
* <Skill id="43390"/> (F1 after an autoattack chain and F2 after an Autoattack chain while under Revealed / <Skill id="13046"/>)
* <Skill id="41158"/> (Utility when off cd, delay if in line with <Skill id="13046"/> and <Skill id="50481"/>)
* <Skill id="13046"/> (Utility)
* <Skill id="16432"/> (Dagger 5)
* <Skill id="50481"/> (Dagger 1 in <Effect name="stealth"/>)
* Autoattack chain 2x
* <Skill id="13004"/> (Dagger 1)
* <Skill id="16432"/> (Dagger 5)
* <Skill id="50481"/> (Dagger 1 in <Effect name="stealth"/>)
* **Repeat**

**After 25% some extra steps (look at the video)**
* <Skill id="13097"/> 2x (Dagger 2)
* <Skill id="43390"/> (F2 for <Effect name="stealth"/>)
* <Skill id="50481"/> (Dagger 1 in <Effect name="stealth"/>)

</Card>
</GridItem>

<GridItem>
<Card title="CC skills">
| | |
| -- | -- |
| <Skill id="13132"/> | 150 Defiance bar damage per ally |
</Card>
<Video videoId="WmvH1QH9xe0" videoTitle="Deadeye D/D 36.9k by Derpy Moa [SC]"/>
</GridItem>
</Grid>
