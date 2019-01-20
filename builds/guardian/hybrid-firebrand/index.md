---
title: 'Hybrid Firebrand'
date: '2019-01-20'
rating: 'Meta'
role: 'Support'
profession: 'Guardian'
specialization: 'Firebrand'
benchmark:
  { large: { dps: 32230, by: 'Derpy Moa [SC]', youtube: 'vTjd9gm6Z9Q' } }
skills: [30783, 30039, 9153, 9251]
boons: ['Quickness', 'Fury', 'Might', 'Stability', 'Retaliation', 'Aegis']
conditions: ['Vulnerability', 'Blind', 'Crippled']
---

<Divider text="Equipment"/>

<Grid>
<GridItem sm="4">
<Armor weight="Heavy" helmAffix="Berserker" helmRune="Scholar" shouldersAffix="Berserker" shouldersRune="Scholar" coatAffix="Berserker" coatRune="Scholar" glovesAffix="Berserker" glovesRune="Scholar" leggingsAffix="Berserker" leggingsRune="Scholar" bootsAffix="Berserker" bootsRune="Scholar"/>
</GridItem>
 
<GridItem sm="4">
<Weapons weapon1MainType="Greatsword" weapon1MainAffix="Berserker" weapon1MainSigil1="Impact" weapon1MainSigil2="Force" weapon2MainType="Axe" weapon2MainAffix="Berserker" weapon2MainSigil1="Impact" weapon2OffType="Focus" weapon2OffAffix="Berserker" weapon2OffSigil="Force"/>

<Card title="Swap Weapons">
* Greatswords and foci with <Item name="Night" type="Sigil"/> and <Item name="Serpent Slaying" type="Sigil"/>
* A scepter for higher DPS on encounters where the CC and <Boon name="fury"/> from axe are not needed
* A hammer for <Boon name="might"/> stacking
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
<Traits traits1="Radiance" traits1Selected="Healers Retribution, Retribution, Perfect Inscriptions" traits2="Zeal" traits2Selected="Fiery Wrath, Zealous Blade, Symbolic Avenger" traits3="Firebrand" traits3Selected="Liberators Vow, Stalwart Speed, Loremaster"/>
 
<Card title="Situational Traits">
| | |
| -- | -- |
| <Trait name="Unrelenting Criticism" size="big" disableText/> | If you are certain that you can provide enough <Boon name="Quickness"/> for the entire fight you can take this trait for an additional 100 defiance bar damage with <Skill name="Symbol of Vengeance"/>. |
</Card>
</GridItem>

<GridItem sm="5">
<Skills heal="Mantra of Solace" utility1="Mantra of Potence" utility2="Sword of Justice" utility3="Bane Signet" elite="Feel My Wrath"/>

<Card title="Situational Skills">
| | |
| -- | -- |
| <Skill id="9246" size="big" disableText/> | A 1,200 range teleport to an ally. |
| <Skill name="Hallowed Ground" size="big" disableText/> | Can be used where <Boon name="stability"/> or stunbreak is needed. |
| <Skill id="9153" size="big" disableText/> | Can be used where <Boon name="stability"/> or stunbreak is needed. |
| <Skill id="9125" size="big" disableText/> | Deals additional 200 defiance bar damage. |
| <Skill id="9251" size="big" disableText/> | A stationary reflect lasting for 10 seconds. |
| <Skill name="Sanctuary" size="big" disableText/> | A slow but strong CC skill. Also destroys projectiles inside. |
</Card>
</GridItem>
</Grid>

<Divider text="Details"/>

<Grid>
<GridItem sm="12">
<Card title="Skill Usage">
To keep up <Boon name="Quickness"/>:

- Use <Skill name="Feel My Wrath"/> whenever ready
- Use <Skill name="Restoring Reprieve"/> and <Skill name="Potent Haste"/> but leave one charge left (unless the fight is close to being over)
- Only use these skills close to your allies - try to "puke" on them with the mantras

The DPS rotation is exactly the same as [Power Dragonhunter](/builds/guardian/power-dragonhunter):

- On Greatsword:
  - Use <Skill name="Symbol of Wrath"/> whenever ready
  - Use <Skill name="Whirling Wrath"/> while standing in a symbol inside the target's hitbox (if done correctly it results in 14 hits)
  - <Skill name="Leap of Faith"/> and <Skill name="Binding Blade"/> (again - inside the target's hitbox) are worth using instead of auto-attacks as well
- On Axe/Focus:
  - Use <Skill name="Symbol of Vengeance"/> whenever ready - this also provides <Boon name="Fury"/> for the party
  - <Skill name="Shield of Wrath"/> when you're not receiving hits - use it shortly before breaking defiance bars
  - <Skill name="Ray of Judgment"/> when everything else is used
- Apart from that:
  - <Skill name="Bane Signet"/> to break defiance bars and provide the group with a temporary 216 power buff
  - <Skill name="Blazing Edge"/> and <Skill id="9226"/> (after <Skill id="9147"/>) are strong CC skills as well
  - <Skill name="Sword of Justice"/> for additional DPS
  - Always weapon swap when it's off cooldown, unless an important damage skill becomes ready in the next 1-2 seconds
  - Scepter plays exactly the same as axe but with higher DPS and ranged

Tomes are very useful when no other skills are ready. <Skill name="Tome of Justice"/> also gets refreshed every time an enemy dies (works with anomalies at Artsariiv/Arkk, knights at MAMA and hallucinations at Siax).

<Skill name="Tome of Courage"/> and <Skill name="Tome of Resolve"/> are great for high incoming damage scenarios.

- <Skill name="Tome of Justice"/> (F1):
  - Skill 4 is a ticking AoE, good for single target and great for AoE DPS
  - Skill 5 makes your surrounding allies inflict <Condition name="Burning"/> - also worth using especially when precasted
  - Skill 3 is an AoE pull (150 defiance bar damage)
  - Often these skills are used as an opener
- <Skill name="Tome of Resolve"/> (F2):
  - Skill 2 is a party condition cleanse
  - Skill 3 grants <Boon name="Vigor"/>, <Boon name="Regeneration"/> and <Boon name="Swiftness"/>
  - Skill 4 is a good party heal
  - Skill 5 increases healing on allies for 8s by 33% and converts up to 5 conditions to boons
- <Skill name="Tome of Courage"/> (F3):
  - Skill 1 grants <Boon name="Stability"/> and <Boon name="Swiftness"/>
  - Skill 3 is a 5s reflect
  - Skill 4 grants <Boon name="resistance"/> and breaks stun
  - Skill 5 grants <Boon name="Aegis"/>, <Boon name="Protection"/>, <Boon name="Stability"/> and 300 toughness for 5 seconds

</Card>
</GridItem>

<GridItem sm="7">
<Card title="Defiance Bar Damage">
| | |
| -- | -- |
| <Skill id="9093"/> | 300 damage |
| <Skill id="9226"/> (after <Skill id="9147"/>) | 150 damage |
| <Skill name="Blazing Edge"/> | 150 damage |
| Skill 3 in <Skill name="Tome of Justice"/> (F1) | 150 damage |
</Card>
</GridItem>

<GridItem sm="5">
<Video youtube="6oRoJ72CNqI" title="Huge Hitbox: 38.1k DPS by Fallen [SC]"/>
</GridItem>
</Grid>
