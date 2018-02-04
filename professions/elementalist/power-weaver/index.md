# Power Weaver (DPS)

The current optimal build for Elementalists in fractals is the <Icon name="weaver"/>. It offers both the highest burst and consistent DPS in the game on large, stationary hitboxes and very good DPS on small hitboxes. The trait <Trait id="1502"/> in combination with <Item id="24868"/> and Slaying Potions like <Item id="50082"/> put it ahead of other DPS professions. Keep in mind that all six bosses in the current CM fractals are stationary, have a large hitbox and favor burst damage.

Weaver has some utilities in the form of good <Condition name="vulnerability"/> output, AoE <Condition name="blind"/>, <Skill id="5536"/> and easy <Boon name="might"/> pre-stacking. The bad news is that Weaver is really squishy compared to the old Tempest, it has no reflects, no crowd control skills apart from <Skill id="5721"/> and looses access to <Boon name="stability"/> and <Boon name="protection"/> from Overloads.

Nonetheless, Weaver is currently the strongest DPS for an offensive team setup but relies heavily on fast CC and survivability help from other classes.

<Divider>
Equipment
</Divider>

<Grid>
<Column>
<Armor helmId="48081" helmRuneId="24836" helmRuneCount="6" helmAffix="Berserker" helmRune="Scholar" shouldersId="48083" shouldersRuneId="24836" shouldersRuneCount="6" shouldersAffix="Berserker" shouldersRune="Scholar" coatId="48079" coatRuneId="24836" coatRuneCount="6" coatAffix="Berserker" coatRune="Scholar" glovesId="48080" glovesRuneId="24836" glovesRuneCount="6" glovesAffix="Berserker" glovesRune="Scholar" leggingsId="48082" leggingsRuneId="24836" leggingsRuneCount="6" leggingsAffix="Berserker" leggingsRune="Scholar" bootsId="48078" bootsRuneId="24836" bootsRuneCount="6" bootsAffix="Berserker" bootsRune="Scholar"/>
</Column>

<Column>
<Weapons weapon1MainId="46773" weapon1MainSigil1Id="24615" weapon1MainSigil2Id="24868" weapon1MainType="Staff" weapon1MainAffix="Berserker" weapon1MainSigil1="Force" weapon1MainSigil2="Impact"/>

<Card>
<CardHeader>
Swap Weapons
</CardHeader>
<CardContent>
* Staffs with Night and Slaying Sigils
* At least a Scepter for <Boon name="might"/> stacking
</CardContent>
</Card>
</Column>

<Column>
<Trinkets backItemId="49384" backItemStatId="584" backItemAffix="Berserker" accessory1Id="39233" accessory1Affix="Berserker" accessory2Id="39232" accessory2Affix="Berserker" amuletId="39273" amuletAffix="Berserker" ring1Id="75669" ring1Affix="Berserker" ring2Id="76024" ring2Affix="Berserker"/>

<Consumables foodId="41569" utilityId="67530" infusionId="37131"/>
</Column>
</Grid>

<Divider>
Build
</Divider>

<Grid>
<Column width="9">
<Traits traits1Id="31" traits1="Fire" traits1Selected="296,325,1510" traits2Id="41" traits2="Air" traits2Selected="232,1502,226" traits3Id="56" traits3="Weaver" traits3Selected="2177,2061,2131"/>
</Column>

<Column>
<Skills weapon1Skill1="" weapon1Skill2="" weapon1Skill3="" weapon1Skill4="" weapon1Skill5="" utilitySkill1="5569" utilitySkill2="5567" utilitySkill3="5734" utilitySkill4="40183" utilitySkill5="5516"/>

<Card>
<CardHeader>
Situational
</CardHeader>
<CardContent>
| | |
| -- | -- |
| <Trait id="2115" size="big" text="false"/> | Can be considered for some extra health if you are at 100% critical chance without <Trait id="2177"/>. |
| <Skill id="5536" size="big" text="false"/> | A 900 range teleport, sufficient for most blink spots. |
| <Skill id="5507" size="big" text="false"/> | An alternative healing skill providing a stronger condition cleanse. |
| <Skill id="5624" size="big" text="false"/> | Is better on small hitboxes compared to <Skill id="5567"/>. |
| <Skill id="5539" size="big" text="false"/> | Another strong DPS option on small hitboxes, especially if the fight is too short to make use of additional conjured weapons. |
| <Skill id="5638" size="big" text="false"/> | Deals the same damage as <Skill id="5539"/> with a higher cooldown and less charges, but affects up to five targets. Useful in short fights with adds. |
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
The rotation is very complex and highly depends on a good <Effect name="alacrity"/> uptime. Below is a descending list of priorities:

* Don't cancel any auto-attacks like <Skill id="5491"/>
* Use <Skill id="40183"/> (and <Skill id="5539"/> or <Skill id="5638"/>) off recharge, if possible while double-attuned to <Skill id="5492"/>
* Use <Skill id="5548"/> whenever possible (basically every 6s) and fill the gaps inbetween with the skills listed below
    * Use <Skill id="5679"/> whenever you are in <Skill id="5492"/>
    * Switch to <Skill id="5494"/> is off cooldown. <Skill id="41125"/> (and <Skill id="5552"/>) is a DPS increase over auto-attacking while waiting to go back in <Skill id="5492"/>
    * Use <Skill id="5501"/> whenever possible and immediately switch to <Skill id="5495"/> while casting. Cast <Skill id="5528"/> before switching back to <Skill id="5492"/>, cast <Skill id="43762"/> and finally another <Skill id="5548"/>
    * While attuned to <Skill id="5492"/>/<Skill id="5492"/> -> <Skill id="5516"/> -> 2nd <Skill id="5516"/>: 
        * <Skill id="5568"/>
        * <Skill id="5723"/>, if possible after attuning to <Skill id="5492"/> to benefit from <Trait id="2131"/>
        * <Skill id="5720"/>
    * In <Skill id="5516"/>:
        * Only when you can whirl against a wall <Skill id="5697"/> (2x)
        * <Skill id="5517"/>
        * <Skill id="5531"/> (if possible with <Trait id="2131"/>)
    * Or in <Skill id="5624"/> (on small hitboxes):
        * <Skill id="5725"/>
        * 3x auto-attack chain
</CardContent>
</Card>
</Column>

<Column>
<Video videoId="-RtVPPtJobk" videoTitle="Large Hitbox: 41.7k DPS by Eldar [qT]"/>

<Card>
<CardHeader>
CC skills
</CardHeader>
<CardContent>
| | |
| -- | -- |
| <Skill id="5721"/> | 300 damage |
| <Skill id="5733"/> | 232 damage |
</CardContent>
</Card>
</Column>
</Grid>
