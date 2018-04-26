---
title: "Power Weaver"
date: "2018-04-17"
group: "Meta Builds"
role: "Damage"
profession: "Elementalist"
specialization: "Weaver"
benchmark: { small: { dps: 37301, by: "Derpy [SC]", youtube: "kwTiXVsQ4BQ" }, large: { dps: 47338, by: "Simbah [Sy]", youtube: "6O5lZ_8XxVQ" }}
skills: [5536]
traits: [264, 1502]
boons: ["Might", "Fury", "Swiftness",  "Protection"]
conditions: ["Weakness", "Vulnerability", "Blind"]
---

The current optimal build for Elementalists in fractals is the <Specialization prefix="power" name="weaver"/>. It offers both the highest burst and consistent DPS in the game on large, stationary hitboxes and very good DPS on small hitboxes. The trait <Trait id="1502"/> in combination with <Item id="24868"/> and slaying potions like <Item id="50082"/> put it ahead of other DPS professions. Keep in mind that all six bosses in the current CM fractals are stationary, have a large hitbox and favor burst damage.

Additionally with the <Specialization name="chronomancer" prefix="boon"/> and an average uptime of at least ten boons, <Specialization name="weaver" prefix="arcane"/> with <Trait id="1511"/> has become extremly strong.

Weaver has some utilities in the form of burst <Condition name="vulnerability"/>, AoE <Condition name="blind"/>, <Skill id="5536"/> and easy <Boon name="might"/> pre-stacking. The bad news is that Weaver is really squishy compared to the old Tempest, it has no reflects, no crowd control skills apart from <Skill id="5733"/> and looses access to <Boon name="stability"/> and <Boon name="protection"/> from Overloads.

Arcane Weaver somewhat mitigates the squishiness by taking <Trait id="257"/> and providing good <Boon name="protection"/> uptimes with <Trait id="264"/>. It also provides around 7 stacks <Boon name="might"/> uptime the party, even more with around 30% boon duration from <Item id="79722"/> and <Trait id="2004"/>. This allows a replacement of the <Specialization name="druid"/> with another <Specialization name="weaver"/> as there is enough <Boon name="might"/> on the party and you "only" loose <Skill id="31582" profession="ranger"/>, <Skill id="12497" profession="ranger"/> and <Trait id="1016" profession="ranger"/> (redundant with <Trait id="2177"/>) but gain much more DPS.

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
* Staff with <Item id="36053"/>/<Item id="36054"/>
* Staff with <Item id="24658"/>/<Item id="24868"/>
* At least a Scepter and Dagger for <Boon name="might"/> stacking, Sword if you want to go the extra mile
</CardContent>
</Card>
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
<Traits title="Standard Arcane Variant" traits1Id="31" traits1="Fire" traits1Selected="296,325,1510" traits2Id="37" traits2="Arcane" traits2Selected="253,257,1511" traits3Id="56" traits3="Weaver" traits3Selected="2177,2061,2131"/>

Use the **Arcane variant** if you have a **<Specialization name="chronomancer" prefix="boon"/>** and spend less than 50% of the fight with a broken defiance bar (e.g. Artsariiv, Arkk).

<Traits title="Air Variant" traits1Id="41" traits1="Air" traits1Selected="232,1502,226"/>

Use the **Air variant** if you don't need <Boon name="might"/> and have less than ten boons on average or spend **more than 50% of the fight with a broken defiance bar** (e.g. MAMA, Ensolyss).
</Column>

<Column>
<Skills weapon1Skill1="" weapon1Skill2="" weapon1Skill3="" weapon1Skill4="" weapon1Skill5="" utilitySkill1="5569" utilitySkill2="5624" utilitySkill3="5734" utilitySkill4="5539" utilitySkill5="5516"/>

<Card>
<CardHeader>
Situational
</CardHeader>
<CardContent>
| | |
| -- | -- |
| <Skill id="5638" size="big" text="false"/> | Deals the same damage as <Skill id="5539"/> with a higher cooldown and less charges but affects up to five targets. Useful to cleave adds faster. |
| <Trait id="1673" size="big" text="false"/> | If you have no problems with survivability, you can take this trait for a higher <Boon name="retaliation"/> uptime. |
| <Skill id="5536" size="big" text="false"/> | A 900 range teleport, sufficient for most blink spots. |
| <Skill id="5507" size="big" text="false"/> | An alternative healing skill providing a stronger condition cleanse. |
| <Skill id="43638" size="big" text="false"/> | Used for a stronger burst opener when you can't make use of <Skill id="5516"/> (e.g. Skorvald). |
| <Skill id="5567" size="big" text="false"/> | Can be better on big hitboxes compared to <Skill id="5624"/> at the disadvantage of not being able to move. Mostly used as a third weapon. |
| <Skill id="5639" size="big" text="false"/> | Used for personal <Boon name="stability"/> (e.g. Aetherblade console room, Underground Facility). |
| <Trait id="2115" size="big" text="false"/> | Can be considered for some extra health if you are at 100% critical chance without <Trait id="2177"/>. |
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
Skill priority
</CardHeader>
<CardContent>
The rotation is very complex and highly depends on a good <Boon name="alacrity"/> uptime. Below is a descending list of priorities:

1. Use <Skill id="5548"/> whenever possible (basically every 6s) and fill the gaps inbetween with the skills listed below. Any delay on using it will delay your important DPS skills, thus always use <Skill id="5548"/> first.
2. Use <Skill id="5501"/> whenever possible and immediately switch to <Skill id="5495" text="false"/> while casting. Cast <Skill id="5528"/> before switching back to <Skill id="5492" text="false"/>, cast <Skill id="43762"/> and finally a new <Skill id="5548"/>.
3. While attuned to <Skill id="5492" text="false"/>/<Skill id="5495" text="false"/> or <Skill id="5492" text="false"/>/<Skill id="5494" text="false"/> and <Skill id="5548"/>, <Skill id="41125"/> and <Skill id="43762"/> are on cooldown use a conjured weapon and switch back to <Skill id="5492" text="false"/>/<Skill id="5492" text="false"/> during the first attack:
   * In <Skill id="5624"/>: <Skill id="5725"/> (inside the bosses hitbox) => 2x auto-attack chain
   * Or in <Skill id="5516"/>: Only when you can whirl against a wall <Skill id="5697"/> => <Skill id="5517"/> => <Skill id="5531"/>
   * Or in <Skill id="5567"/>: <Skill id="5568"/> => <Skill id="5723"/> => <Skill id="5720"/>
4. Switch to <Skill id="5494" text="false"/> when <Skill id="5737"/> is ready or will be in <4 seconds. Cast <Skill id="41125"/> and <Skill id="5552"/> first and switch back to <Skill id="5492" text="false"/>/<Skill id="5494" text="false"/> while casting <Skill id="5737"/> to profit from the better modifiers in <Skill id="5492"/>
   * If <Skill id="5501"/> is ready skip <Skill id="41125"/> and <Skill id="5552"/> and cast <Skill id="5737"/> immediately followed by <Skill id="5501"/> while switching back to <Skill id="5492" text="false"/>
5. Use <Skill id="5539"/> (or <Skill id="5638"/>) three times while double-attuned with <Trait id="2131"/> and holding <Skill id="5624"/> (Ferocity boost), preferably while the defiance bar is broken
6. Use <Skill id="5679"/> if you can't finish another <Skill id="5491"/> before leaving <Skill id="5492" text="false"/>
7. Don't start casting <Skill id="5491"/> if you can't finish it
8. If the boss fight will end before you can use another <Skill id="5737"/>, use <Skill id="5736"/> instead (ideally during <Skill id="5492" text="false"/>/<Skill id="5494" text="false"/> cycle)
   * Ideally during the <Skill id="5492" text="false"/>/<Skill id="5495" text="false"/> cycle (<Skill id="5736"/> => <Skill id="5495" text="false"/>/<Skill id="5492" text="false"/> => <Skill id="5528"/> => <Skill id="5501"/> => <Skill id="5492" text="false"/>/<Skill id="5495" text="false"/>)
9. If the boss fight will end in the next seconds and you have no good skills left attune to <Skill id="5494" text="false"/>/<Skill id="5492" text="false"/> to get a last burst with <Skill id="41125"/> in
   </CardContent>
   </Card>

<Video videoId="6O5lZ_8XxVQ" videoTitle="Large Hitbox: 47.3k DPS by Simbah [Sy]"/>
</Column>

<Column>
<Card>
<CardHeader>
Opener
</CardHeader>
<CardContent>
### Pre-casting
Start in <Skill id="5495" text="false"/>/<Skill id="5492" text="false"/> and pre-cast <Skill id="5528"/> three seconds before the fight starts. Switch to <Skill id="5492" text="false"/>/<Skill id="5495" text="false"/> and use <Skill id="5548"/> and <Skill id="43762"/> a moment before <Skill id="5528"/> triggers. Attune to <Skill id="5494" text="false"/>/<Skill id="5492" text="false"/> and continue with the normal opener below.

### Normal opener

1. Start in <Skill id="5494" text="false"/>/<Skill id="5492" text="false"/> with <Skill id="5737"/> and <Skill id="5501"/>
2. Switch to <Skill id="5492" text="false"/>/<Skill id="5494" text="false"/>
3. <Skill id="5548"/> and <Skill id="41125"/>
4. <Skill id="5624"/>

* <Skill id="5725"/>
* <Skill id="5492" text="false"/>/<Skill id="5492" text="false"/>
* <Skill id="5539"/> x3
* 2x <Skill id="5726"/> chain

5. <Skill id="5548"/> and <Skill id="5679"/>
6. Switch to <Skill id="5495" text="false"/>/<Skill id="5492" text="false"/>
7. <Skill id="5528"/>
8. <Skill id="5516"/>

* <Skill id="5517"/>
* <Skill id="5531"/>
* <Skill id="5492" text="false"/>/<Skill id="5495" text="false"/>

9. <Skill id="5548"/>
10. <Skill id="43762"/>
11. <Skill id="5492" text="false"/>/<Skill id="5492" text="false"/>
12. Continue with the usual priority list

### Situational

Start in <Skill id="5492" text="false"/>/<Skill id="5495" text="false"/> with <Skill id="5548"/> and <Skill id="43762"/>. Attune to <Skill id="5494" text="false"/>/<Skill id="5492" text="false"/> and continue with the rotation above. This is useful for fights like Arkk where you can't precast and have to avoid mechanics.
</CardContent>
</Card>

<Card>
<CardHeader>
CC skills
</CardHeader>
<CardContent>
| | |
| -- | -- |
| <Skill id="5733"/> | 232 damage |
| <Skill id="5721"/> | 300 damage |
</CardContent>
</Card>
</Column>
</Grid>
