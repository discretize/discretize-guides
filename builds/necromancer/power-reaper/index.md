---
title: 'Power Reaper'
date: '2019-01-20'
rating: 'Good'
role: 'Damage'
profession: 'Necromancer'
specialization: 'Reaper'
benchmark: { small: { dps: 29213 by: 'Target [SC]', youtube: '0KMNHsKSfoI' } }
skills: [30792]
traits: [2020, 2018, 2031]
boons: ['Might', 'Fury', 'Quickness']
conditions:
  ['Vulnerability', 'Weakness', 'Crippled', 'Chilled', 'Poison', 'Blind']
author: Amerikajinn
---

The <Specialization name="Reaper" text="Power Reaper"/> build, while not one of the strongest in terms of DPS, is a versatile build that can modify itself to suit a variety of scenarios without many issues.

With two main trait variants (Blood Magic for higher group sustain/CC and revival power; and Soul Reaping for a more powerful rotation and higher <Condition name="vulnerability"/> application) and multiple offensive skill options (<Control name="Pull"/>, boon corruptions, <Condition name="blind"/>, <Control name="Immobile"/>, etc.) <Specialization name="Reaper" text="Power Reaper"/> can modify itself to fit many given situations in fractals.

This build's weakness is its inability to be healed whilst in shroud, which can also affect your ability to maintain shroud for the rotation of the Soul Reaping variant, this can be offset by anticipating large attacks from bosses and sneaking in usage of <Skill name="Summon Shadow Fiend" disableText/>'s <Skill name="Haunt"/> skill or Greatsword's <Skill name="Death Spiral"/>.

However, large amounts of self-produced <Condition name="vulnerability"/>, <Boon name="Quickness"/> and <Boon name="Might"/> will allow this build to perform well as a "solo carry" build that suffers less from underperforming teammates and heavily rewards a skilled user.

<Divider text="Equipment"/>

<Grid>
<GridItem sm="4">
<Armor weight="Light" helmAffix="Berserker" helmRune="Scholar" shouldersAffix="Berserker" shouldersRune="Scholar" coatAffix="Berserker" coatRune="Scholar" glovesAffix="Berserker" glovesRune="Scholar" leggingsAffix="Berserker" leggingsRune="Scholar" bootsAffix="Berserker" bootsRune="Scholar"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainType="Greatsword" weapon1MainAffix="Berserker" weapon1MainSigil1="Impact" weapon1MainSigil2="Force" weapon2MainType="Axe" weapon2MainAffix="Berserker" weapon2MainSigil1="Force"  weapon2OffType="Warhorn" weapon2OffAffix="Berserker" weapon2OffSigil="Impact"/>

<Card title="Swap Weapons">
* Swap out weapon sigils for your Greatsword and Axe as neccesary (<Item id="36053" disableText/> for night fractals, <Item id="24615" disableText/> for Nightmare, etc.)
* A budget option is to just have individual greatswords with the required slaying sigils until you can get your specialized axes (see [Consumables Guide](/guides/consumables))
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
<Traits traits1="Spite" traits1Selected="Spiteful Talisman, Awaken the Pain, Close to Death" traits2="Soul Reaping" traits2Selected="Unyielding Blast, Vital Persistence, Death Perception" traits3="Reaper" traits3Selected="Chilling Nova , Decimate Defenses, Reapers Onslaught"/>

<Card title="Situational Traits">
- Should you need to (though usually only for underperforming groups, you can swap out Soul Reaping for Blood Magic (if you need more team revival power via <Trait name="Ritual of Life"/> and <Trait name="Transfusion"/>, and if needed more warhorn CC via <Trait name="Banshees Wail"/>

</Card>
</GridItem>

<GridItem sm="5">
<Skills heal="Summon Blood Fiend" utility1="Well of Suffering" utility2="Well of Corruption" utility3="Signet of Spite" elite="Summon Flesh Golem"/>

<Card title="Situational Skills">
| | |
| -- | -- |
||If you are going to replace a skill, <Skill name="Well of Corruption"/> is your least damaging skill.|
| <Skill name="Summon Shadow Fiend" size="big" disableText/> | Will deal more damage than Well of Corruption for longer drawn out fights, and is also a nice source of Life Force via <Skill name="Haunt"/>|
| <Skill name="Summon flesh Wurm" size="big" disableText/> | A 1200 range teleport skill that can double as a projectile blocker for fights like Old Tom in the [Uncategorized Fractal](/fractals/uncategorized). |
| <Skill name="Spectral Walk " size="big" disableText/> | A secondary teleport skill that allows one to solo the turret room in the [Thaumanova Fractal](/fractals/thaumanova). |
| <Skill name="Spectral Grasp" size="big" disableText/> | A useful 1200 range 5 target pull to help stack up golems at the Chaos Anomaly fight or the adds in the Arkk fight. Also provides an extra 150 defiance bar damage. Hits up to five times if you cast it inside a mob with other enemies outside. |
| <Skill name="Suffer" size="big" disableText/> | A defensive utility to help mitigate conditions on you, as well as apply extra Chill for usage with <Trait name="Cold Shoulder"/> |
| <Skill name="You are all Weaklings" size="big" disableText/> | A defensive stun break utility. |
| <Skill name="Corrupt Boon" size="big" disableText/> | Provides additional boon mitigation for fractals with the No Pain no Gain instability. |
| <Skill name="Corrosive Poison Cloud" size="big" disableText/> | A useful skill for mitigating projectiles at fights like Artsariiv or Arkk in the [Shattered Observatory Fractal](/fractals/shattered-observatory). |
| <Skill name="Nothing Can Save You" size="big" disableText/> | Makes your attacks unblockable, great to break the Ooze in [Thaumanova Reactor Fractal](/fractals/thaumanova-reactor). |
</Card>
</GridItem>
</Grid>

<Divider text="Details"/>

<Grid>
<GridItem sm="7">
<Card title="Rotation">
<Grid>
 Your rotation falls into three main parts:
</Grid>
<GridItem sm="2">
**Greatsword**
-

</GridItem>
This is to be used essentially whenever you're not in <Skill name= "Reapers Shroud"/>

Pre 50% HP
<GridItem sm="10">

1. <Skill name="Grave Digger"/>
2. <Skill name="Death Spiral"/>
3. <Skill name="Dusk Strike"/> => <Skill name="Fading Twilight"/> => <Skill name="Chilling Scythe"/> x 3
4. <Skill name="Grave Digger"/>
5. <Skill name="Death Spiral"/>
6. <Skill name="Nightfall"/>
7. <Skill name="Grasping Darkness"/>
8. Weapon Swap
   </GridItem>

Post 50% HP
<GridItem sm="10">

1. <Skill name="Grave Digger"/> x 9
2. <Skill name="Nightfall"/>
3. <Skill name="Grasping Darkness"/>
4. Weapon Swap
   </GridItem>

## **Axe/Warhorn**

Use this as part of your rotation, but the best time is to be using this as you are about to break a defiance bar (in tandem with the <Skill name= "Reapers Shroud"/> portion of your rotation)
<GridItem sm="10">

1. <Skill name="Ghastly Claws"/>
2. <Skill name="Locust Swarm"/>
3. <Skill name="Well of Suffering"/>
4. <Skill name= "Reapers Shroud"/> (seen below)
5. <Skill name="Ghastly Claws"/>
6. Weapon Swap
   </GridItem>

## **<Skill name= "Reapers Shroud"/>**

Your aim is to use this when you have all of your persistent AoE abilities active (<Skill name="Well of Suffering"/>, <Skill name="Locust Swarm"/>, and <Skill name="Nightfall"/> )
<GridItem sm="10">

1. <Skill name="Soul Spiral"/>
2. <Skill name="Life Rend"/> => <Skill name="Life Slash"/> => <Skill name="Life Reap"/> x 5 (or if you're going to drop below 50% life force)
3. <Skill name= "Reapers Shroud"/> (to leave shroud)
   </GridItem>

</Card>
<Card title="Advanced Notes">
- By utilizing weapon stowing you can get extra damage out of your consecutive <Skill name="Gravedigger"/> uses.
- Always finish your auto-attack chains in both <Skill name="Reapers Shroud"/> and Greatsword.
- Utilize smart positioning for skills like <Skill name="Grasping Darkness"/> and <Skill name="Life Reap"/>, as you gain bonus effects by hitting multiple targets (bonus life force, cooldown reduction for shroud from <Skill name="Life Reap" disableText/>, etc.)
- While you can use shroud as a way to mitigate large amounts of damage, it will result in a 5% dps loss until you can get your life force back up again, as well as locking you out of using shroud.
- <Skill name="Deaths Charge"/> is a fantastic way to get around faster outside of using blink skills.

</Card>
</GridItem>

<GridItem sm="5">

<Card title="Opener">
- If able to immediately break the defiance bar
   - Begin in Axe/Warhorn to use precast <Skill name="Locust Swarm"/> for initial damage then <Skill name="Wail of Doom"/> to break bar.
   - As the bar is broken immediately use <Skill name="Well of Suffering"/>, then weapon swap
   - Use <Skill name="Nightfall"/> then <Skill name="Grasping Darkness"/>, then enter <Skill name="Reapers Shroud"/>
   - Use <Skill name="Soul Spiral"/> then continue auto-attack chains until you cannot continue wihtout dropping below 50% Life Force.
   - Continue with the usual rotation.
- If the defiance bar won't be broken immediately (e.g. Ensolyss)
   - Start in Greatsword
   - Use Greatsword Auto-attack chains, <Skill name="Gravedigger"/>, and <Skill name="Death Spiral"/> until the bar is about to be broken
   - As the Defiance bar is about to occur, use <Skill name="Nightfall"/> into <Skill name="Grasping Darkness"/> and then weapon swap to use <Skill name="Wail of Doom"/>
   - As the defiance bar is broken use the following:
   - <Skill name="Locust Swarm"/>
   - <Skill name="Ghastly Claws"/>
   - <Skill name="Reapers Shroud"/>
   - <Skill name="Soul Spiral"/>
   - Then continue the rotation as normal

Note: You can pre-cast <Skill name="Haunt"/> (even if the boss is invulnerable at first) to apply instant <Condition name="Chilled"/> for 10% damage boost.
</Card>

<Card title="Defiance Bar Damage">
| | |
| -- | -- |
| <Skill name="Grasping Darkness" size="big" disableText/> | 150 with <Control name="pull"/> |
| <Skill name="Wail of Doom" size="big" disableText/> | 200 with <Control name="daze"/> (300 if traited) |
| <Skill name="Charge" size="big" disableText/> | 200 with <Control name="knockdown"/> and 232 with <Control name="launch"/>| 
| <Skill name="Terrify" size="big" disableText/> | 100 with <Control name="daze"/> |
| <Skill name="Executioners Scythe" size="big" disableText/> | 150 with <Control name="daze"/> |
</Card>

<Video youtube="0KMNHsKSfoI" title="Small Hitbox: 29.2k DPS by Target [SC]"/>
</GridItem>
</Grid>
