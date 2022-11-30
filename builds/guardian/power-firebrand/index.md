---
title: Power (Quick) Firebrand
hidden: false
archive: true
rating: Meta
role: Power Damage
profession: Guardian
specialization: Firebrand
conditions:
  - name: Vulnerability
    uptime: 25 stacks
boons:
  - name: Quickness
    uptime: 100%
    variant: group
  - name: Might
    uptime: 5 stacks
    variant: group
  - name: Fury
    uptime: 100%
    variant: group
code: '[&DQEQLyo6PjZLFyYPehZIAUgBLQH+ALkBiRI3AQAAAAAAAAAAAAAAAAAAAAA=]'
cmGuide: static
classification:
  - 5
  - 3
  - 4
  - 2
  - 4
date: 2022-08-05T09:45:27.587Z
---

The **<Specialization text="Power Quickness Firebrand" name="Firebrand"/>** (also **_Quickness Firebrand_** or **_Quickbrand_**) provides permanent <Boon name="Quickness"/> to the party while dealing good DPS.

It plays very similar to <BuildLink build="Power Dragonhunter" specialization="Dragonhunter"/> and <BuildLink build="Power Willbender" specialization="Willbender"/> with the addition of <Specialization name="Firebrand"/> mantras and tomes. Thanks to those, the build is able to adapt to various situations with <Boon name="Stability"/>, <Boon name="Resistance"/>, reflects and pulls.

Using <Skill name="Bane Signet"/> to break defiance bars also increases your allies' <Attribute name="Power"/> by 216 for 10 seconds thanks to <Trait name="Perfect Inscriptions"/>.

<Warning>

Its worth mentioning that <Specialization text="Power Quickness Firebrand" name="Firebrand"/> is exceedingly strong when bosses phase quickly. For various T4 fractals, long fights, or if you happen to be in a slower group (most PuG groups), you want to run <BuildLink build="Condi Firebrand" specialization="Firebrand"/> as it provides much higher sustained DPS. If you can't evaluate yourself if this build is a good pick for your party, you should not be playing it!

</Warning>

<Divider text="Equipment"/>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1="Radiance" traits1Selected="Right Hand Strength,Retribution,Perfect Inscriptions" traits2="Zeal" traits2Selected="Fiery Wrath,Zealous Blade,Symbolic Avenger" traits3="Firebrand" traits3Selected="Liberators Vow,Weighty Terms,Loremaster"/>

<Card title="Defiance Bar Damage">

|                                               |            |
| --------------------------------------------- | ---------- |
| <Skill id="9093"/>                            | 300 damage |
| <Skill id="9226"/> (after <Skill id="9147"/>) | 150 damage |
| <Skill name="Hammer of Wisdom"/>              | 200 damage |
| <Skill name="Chapter 3: Heated Rebuke"/> (F1) | 150 damage |
| <Skill name="Chains of light"/>               | 250 damage |
| <Skill name="Sanctuary"/>                     | 750 damage |

</Card>
<Card title="Alternative Weapons">

- Greatswords, Scepters, Swords with <Item name="Night" type="Sigil" disableText/>/<Item name="impact" type="Sigil" disableText/> and <Item name="Serpent Slaying" type="Sigil" disableText/>/<Item name="Impact" type="Sigil" disableText/>
- Greatswords and foci with (see [Cheat Sheet](/guides/cheat-sheet))
- Maces for symbol precast
- Hammer and/or Staff for <Boon name="Might"/> stacking

</Card>
</GridItem>

<GridItem sm="5">
<Card title="Situational Skills">

|                                                        |                                                                                     |
| ------------------------------------------------------ | ----------------------------------------------------------------------------------- |
| <Skill id="9246" size="big" disableText/>              | A 1,200 range teleport to an ally.                                                  |
| <Skill name="Hallowed Ground" size="big" disableText/> | When <Boon name="Stability"/> is needed.                                            |
| <Skill id="9153" size="big" disableText/>              | When <Boon name="Stability"/> or a stunbreak is needed.                             |
| <Skill name="advance" size="big" disableText/>         | When <Boon name="Aegis"/> is needed.                                                |
| <Skill id="9125" size="big" disableText/>              | Deals an additional 200 defiance bar damage.                                        |
| <Skill id="9251" size="big" disableText/>              | A stationary reflect lasting for 10 seconds.                                        |
| <Skill id="43357" size="big" disableText/>             | When <Boon name="Stability"/> or a stunbreak is needed.                             |
| <Skill id="9247" size="big" disableText/>              | A 1200 range teleport to an enemy.                                                  |
| <Skill name="Purging flames" size="big" disableText/>  | Cleanses conditions.                                                                |
| <Skill name="Sanctuary" size="big" disableText/>       | Huge CC and projectile destruction.                                                 |
| <Skill name="Mantra of lore" size="big" disableText/>  | Cleanses multiple conditions thanks to charges.                                     |
| <Skill name="renewed focus" size="big" disableText/>   | Recharges all virtue skills, grants <Effect name="Invulnerability"/> for 3 seconds. |

</Card>
</GridItem>
</Grid>

<Divider text="Details"/>

To keep up <Boon name="Quickness"/>:

- Use <Skill name="Feel My Wrath"/> whenever ready
- Use <Skill name="mantraofpotence"/> and <Skill name="mantraofsolace"/> (keep in mind that <Skill name="mantraofsolace"/> only shares <Boon name="Quickness"/> once every 7 seconds thanks to <Trait name=" liberators vow"/>)
- Only use these skills close to your allies - try to "puke" on them with the mantras
- Keep in mind that equipping/stowing a tome grants you 3 seconds of <Boon name="Quickness"/> every 8 seconds thanks to <Trait name="swift scholar"/>!

The DPS rotation is the same as [Power Dragonhunter](/builds/guardian/power-dragonhunter):

- If the encounter allows you to, you can prestack the following symbols:
  - Equip Mace and precast <Skill name="Symbol of Faith"/>
  - Equip Scepter and precast <Skill name="Symbol of Punishment"/>
  - And finally, equip sword and cast <Skill name="Symbol of Blades"/>
  - This way, when the encounter starts, 3 symbols will hit the target and get up your stacks of <Trait name="symbolicavenger"/>
- On greatsword:
  - Use <Skill name="Symbol of Resolution"/>, you should cancel the aftercast with weapon stowing or simply moving
  - Use <Skill name="Whirling Wrath"/> while standing in a symbol inside the target's hitbox (if done correctly it results in 14 hits)
- On Sword:
  - Use <Skill name="Ray of Judgment"/>, try if possible to cancel the aftercast with weapon swap, stow, or <Skill name="Symbol of Blades"/>
  - Use <Skill name="Symbol of Blades"/>
  - Use <Skill name="Zealots Defense"/>
  - <Skill name="Shield of Wrath"/> when you're not receiving hits - use it shortly before breaking defiance bars. Can also be used to help with stacking <Boon name="Might"/>
- Apart from that:
  - <Skill name="Bane Signet"/> to break defiance bars and provide the group with a temporary 216 <Attribute name="Power"/> buff
  - <Skill id="9226"/> (after <Skill id="9147"/>) is nice CC skill as well
  - <Skill name="Sword of Justice"/> for additional DPS and vulnerability. Also provides 3 seconds of <Condition name="Crippled"/>
  - Scepter plays the same as the sword, just without <Skill name="Zealots Defense"/>

Tomes are very useful when no other skills are ready. <Skill name="Tome of Justice"/> also gets refreshed every time an enemy dies (works with anomalies at Skorvald/Artsariiv/Arkk, knights at MAMA, and hallucinations at Siax).

<Skill name="Tome of Courage"/> and <Skill name="Tome of Resolve"/> are great for high incoming damage scenarios.

- <Skill name="Tome of Justice"/> (F1):
  - <Skill name="chapterscorchedaftermath"/> is a ticking AoE, good for single target and great for AoE DPS, provides fire field so make sure to use it before the fight to stack some might
  - <Skill name="epilogue ashes of the just"/> makes your surrounding allies inflict <Condition name="Burning"/> - worth using as precast
  - <Skill name="Chapter 3: Heated Rebuke"/> is an AoE pull (150 defiance bar damage)
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

<Divider text="Rotation / Skill Usage"/>

<Grid>
<GridItem xs="12" sm="6">
<Card title="Information">

Golem rotations out of the raid builds are generally suboptimal in fractals due to <Effect name="Exposed"/> and phases being much shorter compared to raids. The raid rotations are optimized for sustained DPS while in fractals a player needs the ability to adapt a rotation to the amount of time a group needs to finish a phase.\
For that reason, you can find a video with openers, that are efficient to use here.
</Card>

<Card title="Firebrand openers">

<Video caption="by MagicBot [dT], edited by Vince [dT]" youtube="pFUHvaqPOO0"/>
</Card>
</GridItem>

<GridItem xs="12" sm="6">
<Card title="Precasting">

If you have a _Mistlock Singularity_ present you can use these skills for precasts:

1.  Cast <Skill name="tome of justice"/>: <Skill name="chapterscorchedaftermath"/> and <Skill name="Epilogue: Ashes of the just"/>
2.  Blast the fire field by casting <Skill name="Holy Strike"/> or <Skill name="mightyblow"/>
3.  Use 3 charges of <Skill name="mantraofpotence"/> and share <Skill name="mantraofsolace"/> (keep in mind that <Skill name="mantraofsolace"/> only shares <Boon name="Quickness"/> once every 7 seconds thanks to <Trait name=" liberators vow"/>)
4.  Use <Skill name="Stand your ground"/> or <Skill name="saveyourselves"/>
5.  Use <Skill name="Feelmywrath"/>
6.  Use <Skill name="banesignet"/>
7.  Take _Mistlock Singularity_
8.  Use <Skill name="Feelmywrath"/>

</Card>
</GridItem>

<GridItem xs="12" sm="6">
<Card title="Golem Rotation">

**Scepter/Sword Rotation:**

1.  <Skill name="banesignet" profession="guardian"/>
2.  <Skill name="Sword of Justice" profession="guardian"/>
3.  <Skill name="Symbol of Punishment" profession="guardian"/> (Scepter/Sword 2)
4.  <Skill name="Sword of Justice" profession="guardian"/>
5.  <Skill name="Ray of Judgment" profession="guardian"/> (Focus 4)
6.  <Skill name="Shield of Wrath" profession="guardian"/> (Focus 5)
7.  **Weapon Swap**
8.  <Skill name="Sword of Justice" profession="guardian"/>
9.  <Skill name="Symbol of Resolution " profession="guardian"/> (GS 4)
10. <Skill name="Whirling Wrath" profession="guardian"/> (GS 2)
11. <Skill name="Leap of Faith" profession="guardian"/> (GS 3)
12. <Skill name="Binding Blade" profession="guardian"/> (GS 5)
13. If the phase lasts longer than this, continue with the SC rotation.

</Card>
</GridItem>

<GridItem xs="12" sm="6">
<Card title="Golem Rotation">

<Video youtube="G1Y1u4ZwJh8" caption="MajesticNoodle [BATS]"/>
</Card>
</GridItem>
</Grid>

<Divider text="Underwater combat"/>

It is very much recommended to play <BuildLink build="Condi Firebrand" specialization="Firebrand"/> since it provides much better DPS compared to the power variant. If you still want to play <Specialization text="Power Quickness Firebrand" name="Firebrand"/> for whatever reason follow these rough guidelines.

- Open with <Skill name="refraction"/> for <Boon name="resolution"/>
- Cast <Skill name="purify"/> and swap to spear. Camp spear now.
- Priority list:
  1.  <Skill name="Zealots flurry"/> (Spear 2)
  2.  <Skill name="Symbol of spears"/> (Spear 4)
  3.  <Skill name="brilliance"/> (Spear 3)
