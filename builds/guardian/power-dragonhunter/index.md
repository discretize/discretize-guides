---
title: 'Power Dragonhunter'
date: '2018-09-18'
rating: 'Meta'
role: 'Damage'
profession: 'Guardian'
specialization: 'Dragonhunter'
benchmark:
  { large: { dps: 34188, by: 'Roul [SC]', youtube: 'mnQ-RPBHa5k' } }
skills: [30783, 30039, 9153, 9251]
boons: ['Retaliation', 'Aegis']
conditions: ['Vulnerability', 'Blind', 'Crippled']
effects: ['Stealth']
---

The <Specialization name="dragonhunter" text="Power Dragonhunter"/> is currently a good and easy to play build for fractals. It has great burst options and deals high consistent damage while providing good defiance bar damage and <Condition name="vulnerability"/>.

The build also offers strong on-demand party support with <Skill id="30039"/> and reflects like <Skill id="9251"/>.

It benefits from slaying potions such as <Item id="50082"/> and <Item name="Impact" type="Sigil"/>.

<Divider text="Equipment"/>

<Grid>
<GridItem sm="4">
<Armor weight="Heavy" helmId="48075" helmRuneId="24836" helmRuneCount="6" helmAffix="Berserker" helmRune="Scholar" shouldersId="48077" shouldersRuneId="24836" shouldersRuneCount="6" shouldersAffix="Berserker" shouldersRune="Scholar" coatId="48073" coatRuneId="24836" coatRuneCount="6" coatAffix="Berserker" coatRune="Scholar" glovesId="48074" glovesRuneId="24836" glovesRuneCount="6" glovesAffix="Berserker" glovesRune="Scholar" leggingsId="48076" leggingsRuneId="24836" leggingsRuneCount="6" leggingsAffix="Berserker" leggingsRune="Scholar" bootsId="48072" bootsRuneId="24836" bootsRuneCount="6" bootsAffix="Berserker" bootsRune="Scholar"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainId="46762" weapon1MainSigil1Id="24615" weapon1MainSigil2Id="24868" weapon1MainType="Greatsword" weapon1MainAffix="Berserker" weapon1MainSigil1="Force" weapon1MainSigil2="Impact" weapon2MainId="46769" weapon2MainSigil1Id="24615" weapon2MainType="Scepter" weapon2MainAffix="Berserker" weapon2MainSigil1="Force" weapon2OffId="46761" weapon2OffSigilId="24868" weapon2OffType="Focus" weapon2OffAffix="Berserker" weapon2OffSigil="Impact"/>

<Card title="Alternative weapons">
- <Item id="36053" disableText/> / <Item id="24615" disableText/> and slaying sigils  
  (<Item id="36054"/> doesn't stack anymore)
- Hammer for <Boon name="might"/> stacking
</Card>
</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemId="49390" backItemAffix="Berserker" accessory1Id="39233" accessory1Affix="Berserker" accessory2Id="39232" accessory2Affix="Berserker" amuletId="39273" amuletAffix="Berserker" ring1Id="75669" ring1Affix="Berserker" ring2Id="76024" ring2Affix="Berserker"/>

<Consumables foodId="41569" utilityId="77569" infusionId="37131"/>
</GridItem>
</Grid>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1Id="16" traits1="Radiance" traits1SelectedIds="574,565,579" traits2Id="42" traits2="Zeal" traits2SelectedIds="634,653,2017" traits3Id="27" traits3="Dragonhunter" traits3SelectedIds="1898,1835,1955"/>
</GridItem>

<GridItem sm="5">
<Skills healId="21664" utility1Id="30364" utility2Id="9168" utility3Id="9093" eliteId="30273"/>

<Card title="Situational">
| | |
| -- | -- |
| <Skill id="9246" size="big" disableText/> | A 1,200 range teleport to an ally. |
| <Skill id="9153" size="big" disableText/> | Can be used where <Boon name="stability"/> or stunbreak is needed. |
| <Skill id="9125" size="big" disableText/> | Deals additional 200 defiance bar damage. |
| <Skill id="9251" size="big" disableText/> | A stationary reflect lasting for 10 seconds. |
</Card>
</GridItem>
</Grid>

<Divider text="Details"/>

<Grid>
<GridItem sm="7">
<Card title="Rotation">
1. <Skill name="Shield of Wrath" profession="guardian"/> (Focus 5)
2. **Weapon Swap**
3. <Skill name="Procession of Blades " profession="guardian"/> (Utility)
4. <Skill name="Spear of Justice" profession="guardian"/> (F1)
5. <Skill name="Symbol of Wrath " profession="guardian"/> (GS 4)
6. <Skill name="Whirling Wrath" profession="guardian"/> (GS 2)
7. **Weapon Swap**
8. <Skill name="Symbol of Punishment" profession="guardian"/> (Scepter 2)
9. <Skill name="Sword of Justice" profession="guardian"/> (Utility)
10. <Skill name="Ray of Judgment" profession="guardian"/> (Focus 4)
11. <Skill name="Dragons Maw" profession="guardian"/> (Elite)
12. <Skill name="Sword of Justice" profession="guardian"/> (Utility)
13. <Skill name="Symbol of Punishment" profession="guardian"/> (Scepter 2)
14. <Skill name="Sword of Justice" profession="guardian"/> (Utility)
15. <Skill name="Symbol of Punishment" profession="guardian"/> (Scepter 2)
</Card>
</GridItem>

<GridItem sm="5">
<Card title="CC skills">
| | |
| -- | -- |
| <Skill id="9093"/> | 300 damage |
| <Skill id="9226"/> (after <Skill id="9147"/>) | 150 damage |
| <Skill id="33134"/> (after <Skill id="29887"/>) | 150 damage |
| <Skill id="30273"/> | 150 damage |
</Card>
<Video youtube="mnQ-RPBHa5k" title="Large Hitbox: 34.2k DPS by Roul [SC]"/>
</GridItem>

<GridItem sm="7">
<Card title="Notes">
* Start on Greatsword:
  * Don't interrupt your auto-attack chain as the last hit deals the most damage
  * Use <Skill id="9146"/> and <Skill id="9081"/> off cooldown (stand inside the enemy's hitbox)
  * Align <Skill id="9146"/> with <Skill id="30364"/> and <Skill id="29887"/> if possible
  * <Skill id="9080"/> and <Skill id="9147"/> are worth using instead of an auto-attack chain if you don't have a symbol up
* on Scepter:
  * Use <Skill id="9098"/> after <Skill id="9090"/> to cancel the aftercast
  * Align <Skill id="9090"/> with <Skill id="30364"/> and <Skill id="29887"/> if possible
</Card>
</GridItem>

</Grid>
