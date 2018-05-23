---
title: "Power Spellbreaker"
date: "2018-05-16"
group: "Great Builds"
role: "Damage"
profession: "Warrior"
specialization: "Spellbreaker"
benchmark: { small: { dps: 36790, by: "Tempys [SC]", youtube: "6H4kDruLOeg" }}
skills: [45333]
conditions: ["Weakness", "Vulnerability"]
---

The <Specialization prefix="power" name="spellbreaker"/> is a strong DPS option with great crowd control options, high burst and excellent small hitbox damage. It offers some utilities in terms of <Condition name="vulnerability"/>, reflects and boon removal with <Skill id="45333"/>.

Keep in mind that if you are the only Warrior in your party, you should run the [<Specialization name="warrior" prefix="banner"/>](https://discretize.eu/builds/warrior/banner-warrior) variant instead.

<Divider>
Equipment (150 AR and <Trait id="1016" profession="ranger"/>)
</Divider>
<Grid>
<Row>
<Column>
**Note:** Without <Trait id="1016" profession="ranger"/> from a <Specialization name="druid"/> you have to run more Assassin's pieces to reach 100% critical chance. It is highly recommended to aim higher than the minimum required Agony Resistance (e.g. <Item id="70596"/>, 18x <Item id="37131"/> and Agony Impedance as well as Mist Attunement). To determine the optimal gear for your personal Agony Resistance please use our [gear optimizer](http://old.discretize.eu/#mechanics/gear-optimizer).
</Column>
</Row>

<Row>
<Column>
<Armor helmAffix="Assassin" helmId="48129" helmRune="Scholar" helmRuneId="24836" helmRuneCount="6" shouldersAffix="Assassin" shouldersId="48131" shouldersRune="Scholar" shouldersRuneId="24836" shouldersRuneCount="6" coatAffix="Berserker" coatId="48073" coatRune="Scholar" coatRuneId="24836" coatRuneCount="6" glovesAffix="Berserker" glovesId="48074" glovesRune="Scholar" glovesRuneId="24836" glovesRuneCount="6" leggingsAffix="Berserker" leggingsId="48076" leggingsRune="Scholar" leggingsRuneId="24836" leggingsRuneCount="6" bootsAffix="Berserker" bootsId="48072" bootsRune="Scholar" bootsRuneId="24836" bootsRuneCount="6"/>
</Column>

<Column>
<Weapons weapon1MainType="Mace" weapon1MainAffix="Berserker" weapon1MainId="46766" weapon1MainSigil1="Force" weapon1MainSigil1Id="24615" weapon1OffType="Axe" weapon1OffAffix="Berserker" weapon1OffId="46759" weapon1OffSigil="Impact" weapon1OffSigilId="24868" weapon2MainType="Axe" weapon2MainAffix="Berserker" weapon2MainId="46759" weapon2MainSigil1="Force" weapon2MainSigil1Id="24615" weapon2OffType="Dagger" weapon2OffAffix="Berserker" weapon2OffId="46760" weapon2OffSigil="Impact" weapon2OffSigilId="24868"/>
<Card>
<CardHeader>
Swap Weapons
</CardHeader>
<CardContent>
* All weapons with <Item id="36053"/>/<Item id="36054"/> and slaying sigils
* A warhorn for pre-stacking
</CardContent>
</Card>
</Column>

<Column>
<Trinkets backItemAffix="Berserker" backItemId="49384" backItemStatId="161" accessory1Affix="Berserker" accessory1Id="39232" accessory2Affix="Berserker" accessory2Id="39233" amuletAffix="Berserker" amuletId="39273" ring1Affix="Berserker" ring1Id="75669" ring2Affix="Berserker" ring2Id="76024"/>

<Consumables foodId="41569" utilityId="77569" infusionId="37131"/>
</Column>
</Row>
</Grid>

<Divider>
Build
</Divider>

<Grid>
<Column width="9">
<Traits traits1Id="4" traits1="Strength" traits1Selected="1444,2000,1437" traits2Id="51" traits2="Discipline" traits2Selected="1413,1484,1369" traits3Id="61" traits3="Spellbreaker" traits3Selected="2107,2095,2060"/>
</Column>

<Column>
<Skills utilitySkill1="14402" utilitySkill2="14516" utilitySkill3="14502" utilitySkill4="14404" utilitySkill5="14483"/>

<Card>
<CardHeader>
Situational
</CardHeader>
<CardContent>
| | |
| -- | -- |
| <Trait id="2126" size="big" text="false"/> | If enemy boons are present. |
| <Skill id="45333" size="big" text="false"/> | If enemy boons are present and you don't need the additional CC. Also useful as a strong projectile reflect. |
</CardContent>
</Card>
</Column>
</Grid>

<Divider>
Details
</Divider>

<Grid>
<Column width="10">
<Card>
<CardHeader>
Skill usage
</CardHeader>
<CardContent>
* Use <Skill id="14402"/> to charge up Adrenaline immediately before the fight starts
* Apply the following modifiers before using high damage skills:
  * Trigger <Trait id="1444"/> by using <Skill id="14502"/> or <Skill id="14516"/>. Adds 33% damage but keep in mind that it does not stack
  * Have 1-3 stacks of <Trait id="1437"/>. Remember that <Skill id="44165"/> counts as a burst skill. Each stack adds another 7% up to 21% total
  * Trigger <Trait id="2060"/> which goes hand in hand with <Trait id="1437"/> and adds another 10% damage
  * Have 1-5 stacks of <Trait id="2130"/> adding 60 Power and Ferocity per stack
* <Skill id="44165"/> block aspect acts similar to <Boon name="aegis"/>. Thus any attack you would be able to block with <Boon name="aegis"/> successfully activates <Skill id="44165"/>.
* You can apply missing <Condition name="vulnerability"/> with <Skill id="14507"/> and <Skill id="45160"/> at the cost of DPS (the latter one also reflects projectiles)

This comes down to the following rotation:

1. On Mace/Axe:
    1. <Skill id="14414"/>
    2. <Skill id="14503"/>
    3. <Skill id="14376"/> -> <Skill id="14377"/> (the third hit is too slow)
    4. <Skill id="14516"/> or <Skill id="14502"/>
    5. <Skill id="14418"/>
    6. <Skill id="14399"/>
    7. <Skill id="14414"/>
    8. Swap weapons
2. On Axe/Dagger:
    1. <Skill id="14421"/>
    2. <Skill id="44004"/>
    3. <Skill id="14398"/>
    4. <Skill id="14516"/> or <Skill id="14502"/> (only if you have another one left for the next <Skill id="14399"/> cycle)
    5. <Skill id="14353"/>
    6. <Skill id="14398"/>
    7. <Skill id="14369"/> -> <Skill id="14370"/> -> <Skill id="14371"/> (make sure to finish the chain)
    8. <Skill id="14421"/>
    9. Swap weapons

The opener uses a slightly different order to ensure having modifiers before the high damage skills:

1. Start on Mace/Axe
    1. <Skill id="14402"/>
    2. <Skill id="14516"/> (<Trait id="1444" text="false"/> and 1st <Trait id="2130" text="false"/>)
    3. <Skill id="14414"/> (1st <Trait id="1437" text="false"/> and 2nd <Trait id="2130" text="false"/>)
    4. <Skill id="14503"/> (3rd <Trait id="2130" text="false"/>)
    5. <Skill id="14418"/>
    6. <Skill id="14399"/>
2. Swap to Axe/Dagger
    1. <Skill id="14421"/>
    2. <Skill id="14353"/> (2nd <Trait id="1437" text="false"/>)
    3. <Skill id="14502"/> (<Trait id="1444" text="false"/> and 4th <Trait id="2130" text="false"/>)
    4. <Skill id="44004"/>
    5. <Skill id="14398"/>
    6. <Skill id="14369"/> -> <Skill id="14370"/> -> <Skill id="14371"/>
    7. <Skill id="14421"/>
    8. <Skill id="14398"/>
3. Swap to Mace/Axe and continue with the normal rotation
</CardContent>
</Card>
</Column>

<Column>
<Card>
<CardHeader>
CC skills
</CardHeader>
<CardContent>
| | |
| -- | -- |
| <Skill id="14516"/> | 300 damage |
| <Skill id="14502"/> | 150 damage |
| <Skill id="14503"/> | 100 damage |
| <Skill id="44165"/> | 100 damage |
| <Skill id="43532"/> | 150 damage if you move 600 yards away from the target |

If using <Skill id="14483"/>:

|                     |            |
| ------------------- | ---------- |
| <Skill id="14487"/> | 100 damage |
| <Skill id="14488"/> | 150 damage |
| <Skill id="14556"/> | 200 damage |
| <Skill id="14490"/> | 200 damage |

</CardContent>
</Card>

<Video videoId="6H4kDruLOeg" videoTitle="Small Hitbox: 36.7k DPS by Tempys [SC]"/>
</Column>
</Grid>
