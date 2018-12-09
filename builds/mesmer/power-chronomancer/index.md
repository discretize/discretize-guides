---
title: 'Power Chronomancer'
date: '2018-09-18'
rating: 'Great'
role: 'Damage'
profession: 'Mesmer'
specialization: 'Chronomancer'
benchmark:
  { small: { dps: 33536, by: 'Van Gherwen [SC]', youtube: 'T0LrKV_TLQg' } }
skills: [10267, 10186, 10197, 10200, 10302, 29830, 30359, 29519]
traits: [1852]
conditions: ['Vulnerability']
effects: ['Stealth']
---

The <Specialization text="Power Chronomancer" name="chronomancer"/> is a good DPS option for fights without a lot of target switching. It does high burst damage and does not suffer from smaller hitboxes while periodically removing boons with <Skill id="10267"/> and applying 10-15x <Condition name="vulnerability"/>.

In addition, a <Specialization name="chronomancer"/> has access to <Skill id="29830"/>, enabling the usage of strong utility skills like <Skill id="29519"/>, <Skill id="34326"/> and <Skill id="10197"/> and <Skill name="Mass Invisibility"/> twice in a row.

As Focus is used as a main weapon, <Skill id="10363"/> can <Control name="pull"/> trash mobs together and CC skills like <Skill id="30359"/>, <Skill id="10287"/> and <Skill id="10341"/> can break any defiance bar.

The build unfolds its full strength in fights with medium to long interphases, it excels at encounters like Arkk ([Shattered Observatory Fractal](https://discretize.eu/fractals/shattered-observatory)) but is not as good on short-lived fights with target switching like MAMA ([Nightmare Fractal](https://discretize.eu/fractals/nightmare)).

It benefits heavily from slaying potions such as <Item id="50082"/> and <Item name="Impact" type="Sigil"/>.

<Divider text="Equipment (150 AR and Spotter)"/>

<Grid>
<GridItem sm="4">
<Armor weight="Light" helmAffix="Assassin" helmId="48135" helmRune="Scholar" helmRuneId="24836" helmRuneCount="6" shouldersAffix="Assassin" shouldersId="48137" shouldersRune="Scholar" shouldersRuneId="24836" shouldersRuneCount="6" coatAffix="Assassin" coatId="48133" coatRune="Scholar" coatRuneId="24836" coatRuneCount="6" glovesAffix="Assassin" glovesId="48134" glovesRune="Scholar" glovesRuneId="24836" glovesRuneCount="6" leggingsAffix="Berserker" leggingsId="48088" leggingsRune="Scholar" leggingsRuneId="24836" leggingsRuneCount="6" bootsAffix="Berserker" bootsId="48084" bootsRune="Scholar" bootsRuneId="24836" bootsRuneCount="6"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainType="Sword" weapon1MainAffix="Assassin" weapon1MainId="47059" weapon1MainSigil1="Force" weapon1MainSigil1Id="24615" weapon1OffType="Focus" weapon1OffAffix="Berserker" weapon1OffId="46761" weapon1OffSigil="Impact" weapon1OffSigilId="24868" weapon2OffType="Sword" weapon2OffAffix="Berserker" weapon2OffId="46774" weapon2OffSigil="Impact" weapon2OffSigilId="24868"/>

<Card title="Swap Weapons">
* Weapons with <Item id="36053"/>/<Item id="24615"/> (<Item id="36054"/> doesn't stack anymore)
* Torch for <Boon name="might"/> stacking
</Card>
</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemAffix="Berserker" backItemId="49390" accessory1Affix="Berserker" accessory1Id="39232" accessory2Affix="Berserker" accessory2Id="39233" amuletAffix="Berserker" amuletId="39273" ring1Affix="Berserker" ring1Id="75669" ring2Affix="Berserker" ring2Id="76024"/>

<Consumables foodId="41569" utilityId="77569" infusionId="37131"/>
</GridItem>
</Grid>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1Id="1" traits1="Dueling" traits1SelectedIds="701,708,692" traits2Id="24" traits2="Illusions" traits2SelectedIds="721,729,733" traits3Id="40" traits3="Chronomancer" traits3SelectedIds="1995,1978,1890"/>

<Card title="Situational Elite Skills">
| | |
| -- | -- |
| <Skill id="29519" size="big" disableText/> | The best CC skill out there in case <Skill id="30359"/> is not enough. |
| <Skill id="10245" size="big" disableText/> | Useful for party skipping. Provides 15 seconds of <Effect name="stealth"/> with <Trait id="674"/> and <Skill id="29830"/>. |
| <Skill id="10311" size="big" disableText/> | If you need additional <Boon name="quickness"/>. |
</Card>
</GridItem>

<GridItem sm="5">
<Skills healId="21750" utility1Id="10267" utility2Id="10341" utility3Id="10211" eliteId="30359"/>

<Card title="Situational">
| | |
| -- | -- |
| <Trait id="729" size="big" disableText/> | Minor DPS loss but increases your personal <Boon name="quickness"/> uptime. |
| <Skill id="30525" size="big" disableText/> | Alternative to <Skill id="10211"/> with more cleave damage. |
| <Skill id="34326" size="big" disableText/> | One of the strongest reflect skills, protecting everyone inside from projectiles for 6 seconds. |
| <Skill id="10197" size="big" disableText/> | Party escort service. |
| <Skill id="10200" size="big" disableText/> | A 1200 range teleport. It breaks <Control name="stun"/> on use, which means it gets executed even if there is no valid path your mouse target - keep this in mind. |
| <Skill id="29578" size="big" disableText/> | Enables you to use key utilities twice. If you use <Skill id="29830"/> at the end of the cast, you get a "free" mimic and can do stuff like triple <Skill id="10200"/> without the need for any illusions. |
</Card>
</GridItem>
</Grid>

<Divider text="Details"/>

<Grid>
<GridItem>
<Card title="Skill priority">
1. Cast your phantasms whenever ready
    * <Skill id="10174"/>
    * <Skill id="10267"/>
    * <Skill id="10341"/>
    * <Skill id="10282"/>
2. Use <Skill id="21750"/> to recharge them all
    * If available, cast <Skill id="29830"/> during the aftercast - this way, all phantasms are recharged but <Skill id="21750" disableText/> does not go on cooldown
3. Use <Skill id="10211"/> but always keep one charge except at the end of the fight (if possible during <Skill id="29830"/>)
4. Use <Skill id="10191"/> and <Skill id="10190"/> whenever you have three illusions up
5. Use <Skill id="10334"/> and <Skill id="30525"/> off recharge
6. <Skill id="30359"/> can be used for additional DPS if no CC is needed

Apart from doing DPS, you have access to a wide range of utilities like <Skill id="29519"/> or <Skill id="34326"/> which can all be used twice with <Skill id="29830"/> if needed. Cast <Skill id="10173"/> to quickly get up another illusion.
</Card>

<Video youtube="T0LrKV_TLQg" title="Small Hitbox: 33.5k DPS by Van Gherwen [SC]"/>
</GridItem>

<GridItem>
<Card title="Written Opener">
1. Start on Sword/Focus with <Skill id="10282"/>
2. Swap to Sword/Sword and use <Skill id="10174"/>, <Skill id="10267"/> and <Skill id="10341"/>
3. Cast <Skill id="10173"/> to get another illusion
4. Cast <Skill id="21750"/> and use <Skill id="29830"/> during the aftercast
5. <Skill id="10212"/>, <Skill id="10191"/> and <Skill id="10190"/>
6. <Skill id="10174"/>, <Skill id="10267"/> and <Skill id="10341"/>
7. Start <Skill id="10334"/> (<Skill id="30747" disableText/> ends)
8. <Skill id="10212"/>
9. <Skill id="10174"/>, <Skill id="10267"/> and <Skill id="10341"/>
10. <Skill id="21750"/>
11. <Skill id="10174"/> and <Skill id="10267"/>
12. Swap to Sword/Focus
13. <Skill id="10282"/> and <Skill id="10341"/>
14. <Skill id="30359"/> and continue with the priority list
</Card>

<Card title="CC skills">
| | |
| -- | -- |
| <Skill id="29519"/> | 1000 damage |
| <Skill id="30359"/> | 550 damage |
| <Skill id="10341"/> | 225 damage (with <Condition name="taunt"/>) |
| <Skill id="10287"/> | 100-400 damage |
| <Skill id="10363"/> | 150 damage |
| <Skill id="10358"/> | 100 damage |
</Card>
</GridItem>
</Grid>
