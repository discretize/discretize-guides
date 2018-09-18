---
title: 'Power Deadeye'
date: '2018-09-18'
group: 'Good Builds'
role: 'Damage'
profession: 'Thief'
specialization: 'Deadeye'
rating: 'Great'
benchmark:
  { small: { dps: 36939, by: 'Derpy Moa [SC]', youtube: 'WmvH1QH9xe0' } }
skills: [13132, 43390]
conditions: ['Vulnerability']
effects: ['Stealth']
---

The <Specialization name="Deadeye" prefix="power"/> is fine for meta groups, but it's lack of cleave and being hard to stay alive with makes it more off-meta in fractals. It has an extremely simple rotation and offers great mobility for skips, as well as endless party <Effect name="stealth"/> (though a <Specialization name="druid"/> fills this role perfectly).

<Divider text="Equipment"/>

<Grid>
<GridItem sm="4">
<Armor helmId="48087" helmRuneId="24836" helmRuneCount="6" helmAffix="Berserker" helmRune="Scholar" shouldersId="48089" shouldersRuneId="24836" shouldersRuneCount="6" shouldersAffix="Berserker" shouldersRune="Scholar" coatId="48085" coatRuneId="24836" coatRuneCount="6" coatAffix="Berserker" coatRune="Scholar" glovesId="48086" glovesRuneId="24836" glovesRuneCount="6" glovesAffix="Berserker" glovesRune="Scholar" leggingsId="48088" leggingsRuneId="24836" leggingsRuneCount="6" leggingsAffix="Berserker" leggingsRune="Scholar" bootsId="48084" bootsRuneId="24836" bootsRuneCount="6" bootsAffix="Berserker" bootsRune="Scholar"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainType="Dagger" weapon1MainAffix="Berserker" weapon1MainId="46760" weapon1MainSigil1="Force" weapon1MainSigil1Id="24615" weapon1OffType="Dagger" weapon1OffAffix="Berserker" weapon1OffId="46760" weapon1OffSigil="Impact" weapon1OffSigilId="24868"/>

<Card title="Alternative weapons">
* Dagger with <Item id="36053" text="false"/> / <Item id="24615" text="false"/> and slaying sigils  
  (<Item id="36054"/> doesn't stack anymore)
* A Shortbow to blast <Boon name="might"/>
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
<Traits title="" traits1Id="28" traits1="Dreadly Arts" traits1SelectedIds="1245,1292,1269" traits2Id="35" traits2="Critical Strikes" traits2SelectedIds="1268,1272,1904" traits3Id="58" traits3="Deadeye" traits3SelectedIds="2145,2160,2093"/>
</GridItem>

<GridItem sm="5">
<Skills healId="45088" utility1Id="41158" utility2Id="13064" utility3Id="13046" eliteId="13132"/>

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
1. <Skill id="43390"/> (F1)
2. <Skill id="13046"/> (Utility)
3. <Skill id="16432"/> (Dagger 5)
4. <Skill id="50481"/> (Dagger 1 in <Effect name="stealth"/>)
5. <Skill id="41158"/> (Utility)
6. **Autoattack chain 2x**
7. <Skill id="16432"/> (Dagger 5)
8. <Skill id="50481"/> (Dagger 1 in <Effect name="stealth" disableText/>)
9. **Autoattack chain 1x**
10. <Skill id="43390"/> (F2) 
11. <Skill id="43390"/> (F1, Repeat from here)
12. <Skill id="41158"/> (Utility)
13.  <Skill id="13046"/> (Utility)
14. <Skill id="16432"/> (Dagger 5)
15. <Skill id="50481"/> (Dagger 1 in <Effect name="stealth" disableText/>)
16. **Autoattack chain 2x**
17. <Skill id="13004"/> (Dagger 1)
18. <Skill id="16432"/> (Dagger 5)
19. <Skill id="50481"/> (Dagger 1 in <Effect name="stealth" disableText/>)
20. **Repeat from** `Step 11`

**After 25% some extra steps (look at the video)**

- <Skill id="13097"/> 2x (Dagger 2)
- <Skill id="43390"/> (F2 for <Effect name="stealth" disableText/>)
- <Skill id="50481"/> (Dagger 1 in <Effect name="stealth" disableText/>)

</Card>
</GridItem>
<GridItem sm="5">
<Card title="Notes">
* At `Step 11` F1 after an autoattack chain and F2 after an Autoattack chain while under Revealed / <Skill id="13046"/>
* From `Step 11` <Skill id="41158"/> when off cd, delay if in line with <Skill id="13046" disableText/> and <Skill id="50481"/>) 
</Card>
<Video youtube="WmvH1QH9xe0" title="Deadeye D/D 36.9k by Derpy Moa [SC]"/>  
<Card title="CC skills">
| | |
| -- | -- |
| <Skill id="13132"/> | 150 Defiance bar damage per ally |
</Card>
</GridItem>
</Grid>
