---
title: 'Power Staff Weaver'
date: '2018-07-01'
rating: 'Meta'
role: 'Damage'
profession: 'Elementalist'
specialization: 'Weaver'
benchmark:
  {
    small: { dps: 30746, by: 'Roul [SC]', youtube: 'TPF1Ur8OVZI' },
    large: { dps: 34677, by: 'Roul [SC]', youtube: '4OgPFRiDaMI' },
  }
skills: [5536]
traits: [264, 1502]
boons: ['Might', 'Fury', 'Swiftness', 'Protection']
conditions: ['Weakness', 'Vulnerability', 'Blind']
---

The current optimal build for Elementalists in fractals is the <Specialization prefix="power" name="weaver"/>. It offers both the highest burst and consistent DPS in the game on large, stationary hitboxes and very good DPS on small hitboxes. The trait <Trait id="1502"/> in combination with <Item id="24868"/> and slaying potions like <Item id="50082"/> put it ahead of other DPS professions. Keep in mind that all six bosses in the current CM fractals are stationary, have a large hitbox and favor burst damage.

Additionally with the <Specialization name="chronomancer" prefix="boon"/> and an average uptime of at least ten boons, <Specialization name="weaver" prefix="arcane"/> with <Trait id="1511"/> has become extremly strong.

Weaver has some utilities in the form of burst <Condition name="vulnerability"/>, AoE <Condition name="blind"/>, <Skill id="5536"/> and easy <Boon name="might"/> pre-stacking. The bad news is that Weaver is really squishy compared to the old Tempest, it has no reflects, no fast reachable crowd control skills apart from <Skill id="5733"/> and looses access to <Boon name="stability"/> and <Boon name="protection"/> from Overloads.

Arcane Weaver somewhat mitigates the squishiness by taking <Trait id="257"/> and providing good <Boon name="protection"/> uptimes with <Trait id="264"/>. It also provides around 7 stacks <Boon name="might"/> uptime for the party, even more with around 30% boon duration from <Item id="79722"/> and <Trait id="2004"/>. This allows a replacement of the <Specialization name="druid"/> with another <Specialization name="weaver"/> as there is enough <Boon name="might"/> on the party and you "only" loose <Skill id="31582" profession="ranger"/>, <Skill id="12497" profession="ranger"/> and <Trait id="1016" profession="ranger"/> (redundant with <Trait id="2177"/>) but gain much more DPS.

<Divider text="Equipment"/>

<Grid>
<GridItem sm="4">
<Armor weight="Light" helmAffix="Berserker" helmRune="Scholar" shouldersAffix="Berserker" shouldersRune="Scholar" coatAffix="Berserker" coatRune="Scholar" glovesAffix="Berserker" glovesRune="Scholar" leggingsAffix="Berserker" leggingsRune="Scholar" bootsAffix="Berserker" bootsRune="Scholar"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainType="Staff" weapon1MainAffix="Berserker" weapon1MainSigil1="Force" weapon1MainSigil2="Impact"/>

<Card title="Swap Weapons">
* Staff with <Item id="36053" disableText/> / <Item id="24615" disableText/> (<Item id="36054"/> doesn't stack anymore)
* Staff with <Item id="24658" disableText/> / <Item id="24868" disableText/> for the [Nightmare Fractal](https://discretize.eu/fractals/nightmare)
* At least a Scepter and Dagger for <Boon name="might"/> stacking, Sword if you want to go the extra mile.
* Note that the Gear with and without <Trait id="1016" profession="ranger"/> is identical.
</Card>
</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemAffix="Berserker" accessory1Affix="Berserker" accessory2Affix="Berserker" amuletAffix="Berserker" ring1Affix="Berserker" ring2Affix="Berserker"/>

<Consumables food="Bowl of Sweet and Spicy Butternut Squash Soup" utility="Tin of Fruitcake" infusion="Mighty +9 Agony Infusion"/>
</GridItem>
</Grid>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits title="Standard Arcane Variant" traits1="Fire" traits1Selected="Burning Precision,Pyromancer\u0027s Training,Persisting Flames" traits2Id="37" traits2="Arcane" traits2SelectedIds="253,257,1511" traits3Id="56" traits3="Weaver" traits3SelectedIds="2177,2061,2131"/>

Use the **Arcane variant** if you have a <Specialization name="chronomancer" prefix="boon"/> (If you do not have a <Specialization name="chronomancer" prefix="boon"/> look for another group.). The only places where you want to play **Air** <Specialization name="weaver"/> are speedkills of Skorvald, Siax and Ensolyss. The damage in these fights is similar over the whole fight, but slightly worse in the beginning and better at the end. Another point of **Air** is to allow the <Specialization name="mesmer"/> to play the [Hybrid variant](https://discretize.eu/builds/mesmer/hybrid-chronomancer] for higher DPS and <Boon name="alacrity"/> uptime.

<Traits title="Air Variant" traits1Id="41" traits1="Air" traits1SelectedIds="232,1502,226"/>

</GridItem>

<GridItem sm="5">
<Skills heal="Glyph of Elemental Harmony" utility1="Glyph of Storms" utility2="Conjure Lightning Hammer" utility3="Arcane Blast" elite="Conjure Fiery Greatsword"/>

<Card title="Situational">
| | |
| -- | -- |
| <Skill id="5638" size="big" disableText/> | Deals the same damage as <Skill id="5539"/> with a higher cooldown and less charges but affects up to five targets. Useful to cleave adds faster or if you need adittional blast finisher. |
| <Skill id="5567" size="big" disableText/> | Can be used on big hitboxes. Has more burst than  <Skill id="5624"/>. Can be used from range with the disadvantage of not being able to move. Mostly used as a third weapon or to swap with another weaver. |
| <Skill id="40183" size="big" disableText/> | An alternative damage skill for long burst phases. | 
| <Skill id="5536" size="big" disableText/> | A 900 range teleport, sufficient for most blink spots. |
| <Skill id="44239" size="big" disableText/> | An alternative healing skill providing additional group heal. | 
| <Skill id="5507" size="big" disableText/> | An alternative healing skill providing a strong condition cleanse. | 
| <Skill id="44926" size="big" disableText/> | Strong defence against pulsing damage (e.g. Heat Room Thaumanova Reactor).  |
| <Skill id="5641" size="big" disableText/> | Provides three blocks (e.g. Aether blade console room, Underground Facility).|
| <Trait id="1673" size="big" disableText/> | If you have no problems with survivability, you can take this trait for a higher <Boon name="retaliation"/> uptime. |
| <Skill id="5639" size="big" disableText/> | Used for personal <Boon name="stability"/> (e.g. Aether blade console room, Underground Facility). |
| <Trait id="2115" size="big" disableText/> | Can be considered for some extra health if you are at 100% critical chance without <Trait id="2177"/>. |
</Card>
</GridItem>
</Grid>

<Divider text="Details"/>

<Grid>
<GridItem sm="6">
<Card title="Skill priority">
The rotation is very complex and highly depends on a good <Boon name="alacrity"/> uptime. Below is a descending list of priorities:

1.  Use <Skill id="5548"/> whenever possible (basically every 6s) and fill the gaps in between with the skills listed below. Any delay on using it will delay your important DPS skills, thus always use <Skill id="5548"/> first.
2.  Use <Skill id="5501"/> whenever possible and immediately switch to <Skill id="5495" disableText/> while casting. Cast <Skill id="5528"/> before switching back to <Skill id="5492" disableText/>, cast <Skill id="43762"/> and finally a new <Skill id="5548"/>.
    1. You can also start in <Skill id="5492" disableText/>/<Skill id="5492" disableText/>, use <Skill id="5548"/>, <Skill id="5679"/>, attune to <Skill id="5495" disableText/>/<Skill id="5492" disableText/> use <Skill id="5528"/> and cast <Skill id="5501"/> while attuning back to <Skill id="5492" disableText/>/<Skill id="5495" disableText/>.
3.  While attuned to <Skill id="5492" disableText/>/<Skill id="5495" disableText/> or <Skill id="5492" disableText/>/<Skill id="5494" disableText/> and <Skill id="5548"/>, <Skill id="41125"/> and <Skill id="43762"/> are on cooldown use a conjured weapon and switch back to <Skill id="5492" disableText/>/<Skill id="5492" disableText/> during the first attack:
    1. In <Skill id="5624"/>: <Skill id="5725"/> (inside the bosses hitbox) => 2x auto-attack chain.
    2. Or in <Skill id="5516"/>: Only when you can whirl against a wall <Skill id="5697"/> => <Skill id="5517"/> => <Skill id="5531"/>. In the standard rotation this weapon is used in <Skill id="5495" disableText/>/<Skill id="5492" disableText/> to skip <Skill id="5519" disableText/>.
    3. Or in <Skill id="5567"/>: <Skill id="5568"/> => <Skill id="5723"/> => <Skill id="5720"/>.
4.  Switch to <Skill id="5494" disableText/> when <Skill id="5737"/> is ready or will be in <4 seconds. Cast <Skill id="41125"/> and <Skill id="5552"/> first and switch back to <Skill id="5492" disableText/>/<Skill id="5494" disableText/> while casting <Skill id="5737"/> to profit from the better modifiers in <Skill id="5492"/>
    1. If <Skill id="5501"/> is ready skip <Skill id="41125"/> and <Skill id="5552"/> and cast <Skill id="5737"/> immediately followed by <Skill id="5501"/> while switching back to <Skill id="5492" disableText/>/<Skill id="5492" disableText/>
    2. You can also use this rotation to cast <Skill id="5737"/>: Start in <Skill id="5492" disableText/>/<Skill id="5492" disableText/>, <Skill id="5548" disableText/>, <Skill id="5679" disableText/>, <Skill id="5495" disableText/>/<Skill id="5492" disableText/>, <Skill id="5528" disableText/>,<Skill id="43762" disableText/> , <Skill id="5501" disableText/>, <Skill id="5494" disableText/>/<Skill id="5495" disableText/>, <Skill id="42321" disableText/>, <Skill id="5737" disableText/>, <Skill id="5492" disableText/>/<Skill id="5494" disableText/>, <Skill id="5548" disableText/>, <Skill id="41125" disableText/> and continue with a weapon.
5.  Use <Skill id="5539"/> (or <Skill id="5638"/>) three times while double-attuned with <Trait id="2131"/> and holding <Skill id="5624"/> (Ferocity boost), preferably while the defiance bar is broken.
6.  Use <Skill id="5679"/> if you can't finish another <Skill id="5491"/> before leaving <Skill id="5492" disableText/>
7.  Don't start casting <Skill id="5491"/> if you can't finish it
8.  If the boss fight will end in the next seconds and you have no good skills left attune to <Skill id="5494" disableText/>/<Skill id="5492" disableText/> to get a last burst with <Skill id="41125"/> in.

</Card>

<Video youtube="4OgPFRiDaMI" title="Huge Hitbox: 34.5k DPS by Roul [SC]"/>
</GridItem>

<GridItem sm="6">
<Card title="Opener">
### Pre-casting
Start in <Skill id="5495" disableText/>/<Skill id="5492" disableText/> and pre-cast <Skill id="5528"/> three seconds before the fight starts. Switch to <Skill id="5492" disableText/>/<Skill id="5495" disableText/> and use <Skill id="5548"/> and <Skill id="43762"/> a moment before <Skill id="5528"/> triggers. Attune to <Skill id="5494" disableText/>/<Skill id="5492" disableText/> and continue with the normal opener below.

### Normal opener

1. Start in <Skill id="5494" disableText/>/<Skill id="5492" disableText/> with <Skill id="5737"/> and <Skill id="5501"/>
2. Switch to <Skill id="5492" disableText/>/<Skill id="5494" disableText/>
3. <Skill id="5548"/> and <Skill id="41125"/>
4. <Skill id="5624"/>
   1. <Skill id="5725"/>
   2. <Skill id="5492" disableText/>/<Skill id="5492" disableText/>
   3. <Skill id="5539"/> x3
   4. 2x <Skill id="5726"/> chain
5. <Skill id="5548"/> and <Skill id="5679"/>
6. Switch to <Skill id="5495" disableText/>/<Skill id="5492" disableText/>
7. <Skill id="5528"/>
8. <Skill id="5516"/>
   1. <Skill id="5517"/>
   2. <Skill id="5531"/>
   3. <Skill id="5492" disableText/>/<Skill id="5495" disableText/>
9. <Skill id="5548"/>
10. <Skill id="43762"/>
11. <Skill id="5492" disableText/>/<Skill id="5492" disableText/>
12. Continue with the usual priority list

### Situational

Start in <Skill id="5492" disableText/>/<Skill id="5495" disableText/> with <Skill id="5548"/> and <Skill id="43762"/>. Attune to <Skill id="5494" disableText/>/<Skill id="5492" disableText/> and continue with the rotation above. This is useful for fights where the breakbar is delayed or you are moving to the boss initially.
</Card>

<Card title="Hard CC skills">
| | |
| -- | -- |
| <Skill id="5553"/> | 150 damage |
| <Skill id="5683"/> **if** crossed | 150 damage |
| <Skill id="42321"/> | 200 damage |
| <Skill id="5671"/> **if** crossed | 200 damage |
| <Skill id="5733"/> | 232 damage |
| <Skill id="5721"/> | 300 damage |
</Card>

<Card title="Soft CC skills">
| | |
| -- | -- |
| <Skill id="5528"/> | 45 damage <Condition name="crippled"/> 3 sec|
| <Skill id="5519"/>, <Skill id="41125"/>, <Skill id="43762"/>, <Skill id="42321"/> | 60 damage <Condition name="weakness"/> 3 sec|
| <Skill id="5552"/> | 100 damage <Condition name="blind"/> 5 sec|
| <Skill id="5686"/> | 100 damage <Condition name="Immobile"/> 2 sec|
| <Skill id="40332"/> | 140 damage <Condition name="blind"/> 4 sec, <Condition name="weakness"/> 3 sec|
| <Skill id="44550"/> | 150 damage <Condition name="crippled"/> 6 sec, <Condition name="weakness"/> 3 sec|
| <Skill id="41184"/> | 166-192 damage <Condition name="chilled"/> 2-4 sec, <Condition name="weakness"/> 3 sec|
| <Skill id="5515"/> | 198 damage <Condition name="chilled"/> 6 sec|
</Card>
</GridItem>
</Grid>
