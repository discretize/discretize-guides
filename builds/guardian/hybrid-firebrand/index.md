---
title: 'Firebrand'
date: '2020-07-25'
rating: 'Meta'
role: 'Support'
profession: 'Guardian'
specialization: 'Firebrand'
benchmark: { small: { dps: 23300, by: 'MajesticNoodle [BATS]', youtube: 'G1Y1u4ZwJh8' } }
skills: [9093, 9153, 9251]
boons: ['Quickness', 'Fury', 'Might', 'Stability', 'Retaliation', 'Aegis']
conditions: ['Vulnerability', 'Blinded', 'Crippled']
code: '[&DQEqOhAvPjpLF0sX/gA2AXoWehZIAf4AiRKJEgAAAAAAAAAAAAAAAAAAAAA=]'
author: 'ganymed.3541'
nightmareguide: '/cm-guides/guardian/power-firebrand/nightmare'
shatteredguide: '/cm-guides/guardian/power-firebrand/shatteredobservatory'
---

The **<Specialization text="Power Quickness Firebrand" name="Firebrand"/>** (also **_Quickness Firebrand_** or **_Quickbrand_**) provides permanent <Boon name="Quickness"/> to the party while dealing high DPS.

It plays very similar to <Specialization text="Power Dragonhunter" name="Dragonhunter"/> with the addition of <Specialization name="Firebrand"/> mantras and tomes. Thanks to those, the build is able to adapt to various situations with <Boon name="Stability"/>, <Boon name="Resistance"/>, reflects and pulls.


Using <Skill name="Bane Signet"/> to break defiance bars also increases your allies' power by 216 for 10 seconds thanks to <Trait name="Perfect Inscriptions"/>.

<Message>
Its worth to mention that *<Specialization text="Power Quickness Firebrand" name="Firebrand"/>* is very strong with short phases. For various T4 fractals, long fight or if you simply happen to be in a slower group (most PuG groups), you want to run *<Specialization text="Condition Quickness Firebrand" name="Firebrand"/>* ([Build](/builds/guardian/condi-firebrand) ) as it provides much better DPS for longer fights. 
</Message>

<Message>
After July 2020 Balance patch, <Skill name="Feel my Wrath"/> got nerfed! In order to provide permanent quickness for fights longer then 1,5 minutes, <Specialization name="Firebrand"/> needs to increase their **boon duration to 24.6%**.
</Message>
<Divider text="Equipment"/>

Note that this build variant only gains boon duration from the <Item id="79722"/>.

If you are unable to provide enough <Boon name="Quickness"/> with that, **please swap Berserker items for Diviner's until you reach 100% <Boon name="Quickness"/> uptime**.

<Tabs>
<Tab title="162 Agony Resistance (24.6% BD)">
Check the [gear optimizer](http://old.discretize.eu) for more gear variants!
<Grid>
<GridItem sm="4">
<Armor weight="Heavy" helmAffix="Assassin" helmRune="Scholar" shouldersAffix="Assassin" shouldersRune="Scholar" coatAffix="Assassin" coatRune="Scholar" glovesAffix="Assassin" glovesRune="Scholar" leggingsAffix="Diviner" leggingsRune="Scholar" bootsAffix="Assassin" bootsRune="Scholar"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainType="Greatsword" weapon1MainAffix="Berserker" weapon1MainSigil1="Force" weapon1MainSigil2="Impact" weapon2MainType="Sword" weapon2MainAffix="Berserker" weapon2MainSigil1="Force" weapon2OffType="Focus" weapon2OffAffix="Berserker" weapon2OffSigil="Impact"/>

<Card title="Alternative weapons">
- Greatswords, Scepters, Swords with <Item name="Night" type="Sigil" disableText/>/<Item name="impact" type="Sigil" disableText/> and <Item name="Serpent Slaying" type="Sigil" disableText/>/<Item name="Impact" type="Sigil" disableText/>
- Greatswords and foci with (see [Consumables Guide](/guides/consumables))
- Maces for symbol precast
- Hammer and/or Staff for <Boon name="Might"/> stacking
</Card>
</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemAffix="Diviner" accessory1Affix="Berserker" accessory2Affix="Berserker" amuletAffix="Berserker" ring1Affix="Berserker"  ring2Affix="Berserker"/>

<Consumables foodId="41569" utilityId="77569" infusionId="37131"/>

<Card title="Notes">
Use <Trait name="Righthandstrength"/> when there are multiple <Specialization name="Guardian"/>s in your party. Only then you have permanent <Boon name="Retaliation"/>. **Taking <Trait name="Righthandstrength"/> requires no assassin's pieces!**

</Card>
</GridItem>
</Grid>
</Tab>

<Tab title="222 Agony Resistance (24.6% BD)">
Check the [gear optimizer](http://old.discretize.eu) for more gear variants!
<Grid>
<GridItem sm="4">
<Armor weight="Heavy" helmAffix="Berserker" helmRune="Scholar" shouldersAffix="Berserker" shouldersRune="Scholar" coatAffix="Berserker" coatRune="Scholar" glovesAffix="Berserker" glovesRune="Scholar" leggingsAffix="Berserker" leggingsRune="Scholar" bootsAffix="Diviner" bootsRune="Scholar"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainType="Greatsword" weapon1MainAffix="Berserker" weapon1MainSigil1="Force" weapon1MainSigil2="Impact" weapon2MainType="Sword" weapon2MainAffix="Berserker" weapon2MainSigil1="Force"  weapon2OffType="Focus" weapon2OffAffix="Berserker" weapon2OffSigil="Impact"/>

<Card title="Alternative weapons">
- Greatswords, Scepters, Swords with <Item name="Night" type="Sigil" disableText/>/<Item name="impact" type="Sigil" disableText/> and <Item name="Serpent Slaying" type="Sigil" disableText/>/<Item name="Impact" type="Sigil" disableText/>
- Greatswords and foci with (see [Consumables Guide](/guides/consumables))
- Maces for symbol precast
- Hammer and/or Staff for <Boon name="Might"/> stacking
</Card>
</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemAffix="Berserker"  accessory1Affix="Berserker" accessory2Affix="Berserker" amuletAffix="Berserker" ring1Affix="Berserker"  ring2Affix="Berserker"/>

<Consumables foodId="41569" utilityId="77569" infusionId="37131"/>

<Card title="Notes">
You can play full berserker when you can ensure that <Boon name="Quickness"/> doesn't drop in combat. 
</Card>
</GridItem>
</Grid>
</Tab>

</Tabs>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1="Radiance" traits1Selected="Healers Retribution, Retribution, Perfect Inscriptions" traits2="Zeal" traits2Selected="Fiery Wrath, Zealous Blade, Symbolic Avenger" traits3="Firebrand" traits3Selected="Liberators Vow, Stalwart Speed, Loremaster"/>
 
</GridItem>

<GridItem sm="5">
<Skills heal="Mantra of Solace" utility1="Mantra of Potence" utility2="Sword of Justice" utility3="Bane Signet" elite="Feel My Wrath"/>

<Card title="Situational Skills">
| | |
| -- | -- |
| <Skill id="9246" size="big" disableText/> | A 1,200 range teleport to an ally. |
| <Skill name="Hallowed Ground" size="big" disableText/> | Can be used where <Boon name="Stability"/> or stunbreak is needed. |
| <Skill id="9153" size="big" disableText/> | Can be used where <Boon name="Stability"/> or stunbreak is needed. |
| <Skill id="9125" size="big" disableText/> | Deals additional 200 defiance bar damage. |
| <Skill id="9251" size="big" disableText/> | A stationary reflect lasting for 10 seconds. |

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
- Keep in mind that equipping/stowing a tome grants you 3 seconds of <Boon name="Quickness"/> every 8 seconds thanks to <Trait name="swift scholar"/>!

The DPS rotation is the same as [Power Dragonhunter](/builds/guardian/power-dragonhunter):

- If the encounter allows you to, you can prestack the following symbols:
  - Equip Mace and precast <Skill name="Symbol of Faith"/>
  - Equip Scepter and precast <Skill name="Symbol of Punishment"/>
  - And finally, equip Sword and cast <Skill name="Symbol of Blades"/>
  - This way, when the encounter starts, 3 symbols will hit the target and get up your stacks of <Trait name="symbolicavenger"/>
- On greatsword:
  - Use <Skill name="Symbol of Wrath"/>, you should cancel the aftercast with weapon stowing or simply moving
  - Use <Skill name="Whirling Wrath"/> while standing in a symbol inside the target's hitbox (if done correctly it results in 14 hits)
  
- On Sword:
  - Use <Skill name="Ray of Judgment"/>
  - Use <Skill name="Symbol of Blades"/> 
  - Use <Skill name="Zealots Defense"/> 
  - <Skill name="Shield of Wrath"/> when you're not receiving hits - use it shortly before breaking defiance bars. Can also be used to help with stacking might
 
- Apart from that:
  - <Skill name="Bane Signet"/> to break defiance bars and provide the group with a temporary 216 power buff
  - <Skill id="9226"/> (after <Skill id="9147"/>) is nice CC skill as well
  - <Skill name="Sword of Justice"/> for additional DPS and vulnerability. Also provides 3 seconds of cripple
  - Scepter plays the same as the sword, just without <Skill name="Zealots Defense"/>

Tomes are very useful when no other skills are ready. <Skill name="Tome of Justice"/> also gets refreshed every time an enemy dies (works with anomalies at Artsariiv/Arkk, knights at MAMA and hallucinations at Siax).

<Skill name="Tome of Courage"/> and <Skill name="Tome of Resolve"/> are great for high incoming damage scenarios.

- <Skill name="Tome of Justice"/> (F1):
  - Skill 4 is a ticking AoE, good for single target and great for AoE DPS, provides fire field so make sure to use it before the fight to stack some might
  - Skill 5 makes your surrounding allies inflict <Condition name="Burning"/> - worth using as precast
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
  - Skill 4 grants <Boon name="Resistance"/> and breaks stun
  - Skill 5 grants <Boon name="Aegis"/>, <Boon name="Protection"/>, <Boon name="Stability"/> and 300 toughness for 5 seconds

</Card>
</GridItem>

<GridItem sm="6">
<Card title="Rotation">
**Scepter/Sword Rotation:**
1. <Skill name="banesignet" profession="guardian"/>
1. <Skill name="Sword of Justice" profession="guardian"/> 
1. <Skill name="Symbol of Punishment" profession="guardian"/> (Scepter/Sword 2)
2. <Skill name="Sword of Justice" profession="guardian"/> 
1. <Skill name="Ray of Judgment" profession="guardian"/> (Focus 4)
1. <Skill name="Shield of Wrath" profession="guardian"/> (Focus 5)
1. **Weapon Swap**
1. <Skill name="Sword of Justice" profession="guardian"/>
1. <Skill name="Symbol of Wrath " profession="guardian"/> (GS 4)
1. <Skill name="Whirling Wrath" profession="guardian"/> (GS 2)
1. <Skill name="Leap of Faith" profession="guardian"/> (GS 3)
1. <Skill name="Binding Blade" profession="guardian"/> (GS 5)
1. If the phase lasts longer than this, continue with the SC rotation. 
</Card>
</GridItem>
<GridItem sm="6">
<Card title="Defiance Bar Damage">
| | |
| -- | -- |
| <Skill id="9093"/> | 300 damage |
| <Skill id="9226"/> (after <Skill id="9147"/>) | 150 damage |
| <Skill name="Hammer of Wisdom"/> | 200 damage |
| Skill 3 in <Skill name="Tome of Justice"/> (F1) | 150 damage |
| <Skill name="Chains of light"/> | 250 damage |
</Card>
</GridItem>

</Grid>
