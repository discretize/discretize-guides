---
title: 'Boon Chronomancer'
date: '2018-11-18'
rating: 'Meta'
role: 'Support'
profession: 'Mesmer'
specialization: 'Chronomancer'
benchmark: { small: { dps: 7886, by: 'Yui [SC]', youtube: 'SKD6K-zCUx4' } }
skills: [10197, 10200, 29830, 10267, 10186, 10302, 10236, 29519]
traits: [1852]
boons:
  [
    'Quickness',
    'Alacrity',
    'Might',
    'Fury',
    'Retaliation',
    'Protection',
    'Swiftness',
    'Regeneration',
    'Vigor',
    'Aegis',
    'Stability',
    'Resistance',
  ]
conditions: ['Vulnerability']
effects: ['Stealth']
---

Yes, you've read correctly - the <Specialization text="Boon Chronomancer" name="chronomancer"/> or <Specialization text="Chaos Chronomancer" name="chronomancer"/> is capable of providing **every single boon** in the game to the party. You can permanently keep up ten boons plus <Boon name="aegis"/> and some <Boon name="resistance"/> which has great synergy with your own trait <Trait id="1865"/>, the <Specialization name="warrior"/>'s <Trait id="1471" profession="warrior"/> and the <Specialization name="weaver" text="Arcane Weaver"/>'s <Trait id="1511" profession="elementalist"/>.

This is the recommended build if you plan on playing **without a <Specialization name="druid"/> and a third DPS instead**, as one additional <Trait id="264" profession="elementalist"/> is enough to keep up 25x <Boon name="might"/> in combination with your own might output - making <Skill id="31582" profession="ranger"/>, <Skill id="12497" profession="ranger"/> and <Trait id="1016" profession="ranger"/> (redundant with <Trait id="2177" profession="elementalist"/> in fractals) the only loss while you gain much more DPS. The slow ramp-up time for <Boon name="might"/> is compensated by pre-stacking.

On top of the aforementioned, the build has access to the usual mesmer utilities being <Skill id="10197"/> and <Effect name="stealth"/> skips, strong reflects, boon stripping and amazing crowd control skills such as <Skill id="29519"/>.

While the sheer amount of possibilities are nice to look at, the Chronomancer is one of the harder builds to play as the skills require timing and good dynamic decision-making.

<Divider text="Equipment"/>

The gearsets below assume 10x <Trait name="Chaotic Persistence"/>, from easily accessible (150 AR, no stat infusions) to optimal (all augmentations, <Item id="70596"/> and 18x <Item id="86180"/>).  
A Raid optimized set (with 11x <Trait name="Chaotic Persistence" disableText/>) is included for the sake of convenience.

Note that you can use our [Gear Optimizer](http://old.discretize.eu) to calculate the optimal gear for your personal Agony Resistance level.

<Tabs outlined>
<Tab title="150 Agony Resistance (Regular Infusions)">
<Grid>
<GridItem sm="4">
<Armor helmAffix="Berserker" helmRune="Leadership" shouldersAffix="Berserker" shouldersRune="Leadership" coatAffix="Berserker" coatRune="Leadership" glovesAffix="Berserker" glovesRune="Leadership" leggingsAffix="Commander" leggingsRune="Leadership" bootsAffix="Berserker" bootsRune="Leadership"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainType="Sword" weapon1MainAffix="Commander" weapon1MainSigil1="Concentration" weapon1OffType="Shield" weapon1OffAffix="Commander" weapon1OffSigil="Paralyzation" weapon2MainType="Staff" weapon2MainAffix="Commander" weapon2MainSigil1="Concentration" weapon2MainSigil2="Force"/>

<Card title="Swap Weapons">
* Focus when reflects or pulls are needed
* Torch for <Boon name="might"/> stacking
</Card>
</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemAffix="Commander" accessory1Affix="Berserker" accessory2Affix="Commander" amuletAffix="Berserker" ring1Affix="Commander" ring2Affix="Commander"/>

<Consumables foodId="89002" utilityId="67530" infusionId="49432"/>
</GridItem>
</Grid>
</Tab>

<Tab title="222 Agony Resistance (Stat Infusions)">
<Grid>
<GridItem sm="4">
<Armor helmAffix="Commander" helmRune="Leadership" shouldersAffix="Berserker" shouldersRune="Leadership" coatAffix="Commander" coatRune="Leadership" glovesAffix="Berserker" glovesRune="Leadership" leggingsAffix="Berserker" leggingsRune="Leadership" bootsAffix="Berserker" bootsRune="Leadership"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainType="Sword" weapon1MainAffix="Berserker" weapon1MainSigil1="Concentration" weapon1OffType="Shield" weapon1OffAffix="Berserker" weapon1OffSigil="Paralyzation" weapon2MainType="Staff" weapon2MainAffix="Berserker" weapon2MainSigil1="Concentration" weapon2MainSigil2="Force"/>

<Card title="Swap Weapons">
* Focus when reflects or pulls are needed
* Torch for <Boon name="might"/> stacking
* Pistol for extra CC
* Offhand sword for extra DPS
</Card>
</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemAffix="Berserker" accessory1Affix="Berserker" accessory2Affix="Berserker" amuletAffix="Berserker" ring1Affix="Commander" ring2Affix="Berserker"/>

<Consumables foodId="89002" utilityId="67530" infusion="Mystical +9 Agony Infusion"/>
</GridItem>
</Grid>
</Tab>

<Tab title="Raid">
<Grid>
<GridItem sm="4">
<Armor helmAffix="Commander" helmRune="Leadership" shouldersAffix="Berserker" shouldersRune="Leadership" coatAffix="Commander" coatRune="Leadership" glovesAffix="Berserker" glovesRune="Leadership" leggingsAffix="Berserker" leggingsRune="Leadership" bootsAffix="Berserker" bootsRune="Leadership"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainType="Sword" weapon1MainAffix="Commander" weapon1MainSigil1="Concentration" weapon1OffType="Shield" weapon1OffAffix="Commander" weapon1OffSigil="Force" weapon2OffType="Sword" weapon2OffAffix="Commander" weapon2OffSigil="Force"/>
</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemAffix="Berserker" accessory1Affix="Commander" accessory2Affix="Berserker" amuletAffix="Berserker" ring1Affix="Commander" ring2Affix="Berserker"/>

<Consumables foodId="89002" utilityId="89203" infusion="Mystical +9 Agony Infusion"/>
</GridItem>
</Grid>
</Tab>
</Tabs>

Note that you can also run an Offhand Sword instead of Staff for better DPS. It's still possible to achieve 100% <Boon name="retaliation"/> uptime on stationary fights with Sword but Staff is overall the safer option with more <Boon name="aegis"/> uptime, as your only other source is <Trait id="670"/> without it.

<Divider text="Healing Variant"/>

The **Healing Variant** can be used if your party has trouble surviving without a dedicated healer. The set below is optimized for 150 AR.

Your main heal sources are <Trait id="1915"/>, <Trait id="740"/>, <Trait id="1987"/>, <Trait name="Illusionary Inspiration"/>, <Boon name="regeneration"/> and your heal skill. Keep in mind that <Trait id="757"/> is a strong condition cleanse combined with <Skill id="10213"/> charges. If you have <Trait id="738"/> traited, you can use up mantra charges as the preparation itself heals already as well.

<Grid>
<GridItem sm="4">
<Armor helmAffix="Giver" helmRune="Monk" shouldersAffix="Giver" shouldersRune="Monk" coatAffix="Minstrel" coatRune="Monk" glovesAffix="Minstrel" glovesRune="Monk" leggingsAffix="Minstrel" leggingsId="70414" leggingsRune="Monk" bootsAffix="Minstrel" bootsRune="Monk"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainType="Sword" weapon1MainAffix="Giver" weapon1MainSigil1="Transference" weapon1OffType="Shield" weapon1OffAffix="Giver" weapon1OffSigil="Paralyzation" weapon2MainType="Staff" weapon2MainAffix="Giver" weapon2MainSigil1="Transference" weapon2MainSigil2="Water"/>
</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemAffix="Minstrel" accessory1Affix="Minstrel" accessory2Affix="Minstrel" amuletAffix="Minstrel" ring1Affix="Minstrel" ring2Affix="Minstrel"/>

<Consumables foodId="68634" utilityId="67528" infusionId="37125"/>
</GridItem>
</Grid>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1="Illusions" traits1Selected="Shatterstorm, Phantasmal Haste, Phantasmal Force" traits2="Chaos" traits2Selected="Descent into Madness, Chaotic Dampening, Bountiful Disillusionment" traits3="Chronomancer" traits3Selected="Alls Well That Ends Well, Improved Alacrity, Seize the Moment"/>

<Traits title="Defensive: Inspiration over Illusions" traits1="Inspiration" traits1Selected="Sympathetic Visage, Restorative Illusions, Illusionary Inspiration"/>

<Card title="Situational Traits">
| | |
| -- | -- |
| <Trait id="1995" size="big" disableText/> | A very small DPS increase in case you don't need the heal from <Trait id="1987"/>. |
| <Trait id="751" size="big" disableText/> | Use it in combination with a focus for frequent <Control name="pull"/>s and reflects. |
| <Trait id="674" size="big" disableText/> | Increases the duration of all your <Effect name="stealth"/> skills by 50%. |
| <Trait name="Master of Manipulation" size="big" disableText/> | If you are running without the Illusions traitline, your CS cooldown will be longer and this trait is sometimes worth it for better Mimic alignment. |
</Card>
</GridItem>

<GridItem sm="5">
<Skills heal="Well of Eternity" utility1="Well of Action" utility2="Mimic" utility3="Signet of Inspiration" elite="Signet of Humility"/>

<Card title="Situational Skills">
| | |
| -- | -- |
| <Skill id="10311" size="big" disableText/> | If you don't need crowd control, this a is a higher <Boon name="Alacrity"/> option combined with <Skill name="Well of Recall"/> instead of <Skill name="Well of Action"/>. |
| <Skill id="21750" size="big" disableText/> | A personal DPS increase. |
| <Skill id="34326" size="big" disableText/> | One of the strongest reflect skills, protecting everyone inside from projectiles for 6 seconds. |
| <Skill id="10197" size="big" disableText/> | Party escort service. |
| <Skill id="10200" size="big" disableText/> | A 1200 range teleport. It breaks <Control name="stun"/> on use, which means it gets executed even if there is no valid path to your mouse target - keep this in mind. |
| <Skill id="29578" size="big" disableText/> | Enables you to use key utilities twice. If you use <Skill id="29830"/> at the end of the cast, you get a "free" mimic and can do stuff like triple <Skill id="10200"/> without the need for any illusions. |
| <Skill id="10267" size="big" disableText/> | Necessary if you need to remove boons and have no <Specialization name="spellbreaker"/>. |
| <Skill id="10245" size="big" disableText/> | Useful for party skipping. Provides 15 seconds of <Effect name="stealth"/> with <Trait id="674"/> and <Skill id="29830"/>. |

Keep in mind that you usually want to replace <Skill id="30814"/> first and use <Skill id="10311"/> instead if you need to swap an utility skill.
</Card>
</GridItem>
</Grid>

<Divider text="Details"/>

<Grid>
<GridItem>
<Card title="Written Opener">
1. Start on Staff with <Skill id="10169"/> (<Boon name="retaliation" disableText/><Boon name="aegis" disableText/><Boon name="swiftness" disableText/>) and <Skill id="10331"/> (<Boon name="protection" disableText/>)
2. <Skill id="10190"/> (<Boon name="quickness" disableText/><Boon name="alacrity" disableText/><Boon name="vigor" disableText/><Boon name="stability" disableText/>)
3. Cast <Skill id="10310"/> (1st illusion) and swap to Sword/Shield
4. <Skill id="10173"/> (2nd illusion)
5. <Skill id="30643"/> and <Skill id="29830"/> at the end of the cast
    1. Use the remaining three shatters while continueing with the skills below - if a defiance bar is up, use <Skill id="10287"/> first, otherwise <Skill id="49068"/>(<Boon name="might" disableText/><Boon name="fury" disableText/><Boon name="regeneration" disableText/>)
    2. <Skill id="29519"/> if a defiance bar is up
    3. <Skill id="10236"/>
    4. <Skill id="30814"/>
    5. <Skill name="Mimic"/>
5. <Skill id="30747"/> ends
6. Shatter everything again while continueing
7. <Skill name="Signet of Inspiration"/> (free)
8. <Skill name="Tides of Time"/>
9. <Skill name="Well of Action"/>
10. <Skill name="Mimic"/>
11. Weapon swap
12. <Skill name="Signet of Inspiration"/> (free)
13. <Skill name="Signet of Inspiration"/>
</Card>

<Card title="CC skills">
| | |
| -- | -- |
| <Skill id="29519"/> | 1000 damage |
| <Skill id="30643"/> | 200-1200 damage (+30% while <Item id="24639" disableText/> is active) |
| <Skill id="10287"/> | 100-400 damage |
| <Skill id="30814"/> | 150 damage with <Condition name="slow"/> |
| <Skill id="29856"/> | 99 damage with <Condition name="chilled"/> |
</Card>

<Video youtube="Q9WBVpiuChU" title="No Staff Rotation by Kite"/>
</GridItem>

<GridItem>
<Card title="Skill priority">
As really every skill you have is worth using, you should simply cast everything whenever it is off recharge after following the opener sequence to the left.

### Boons

- <Boon name="quickness"/> with <Skill id="30814"/> and <Trait id="2022"/>
- <Boon name="alacrity"/> with <Skill id="30643"/>, <Skill id="29856"/> and <Trait id="1927"/>
- 15-20x <Boon name="might"/> with <Skill id="49068"/> (<Trait id="1687" disableText/>), <Trait id="1866"/> and <Skill id="10273"/>
- <Boon name="fury"/> with <Skill id="10287"/> (<Trait id="1687" disableText/>) and <Skill id="10273"/>
- <Boon name="protection"/> with <Skill id="30769"/>, <Skill id="10331"/> (<Trait id="669" disableText/>) and <Trait id="667"/>
- <Boon name="vigor"/> with <Skill id="10190"/> (<Trait id="1687" disableText/>)
- <Boon name="retaliation"/> with <Skill id="10169"/> and <Trait id="670"/>
- <Boon name="swiftness"/> with <Skill id="10169"/>, <Trait id="670"/>, <Skill id="10331"/> and <Skill id="10236"/>
- <Boon name="aegis"/> with <Trait id="1852"/>, <Skill id="10169"/> and <Trait id="670"/>
- <Boon name="regeneration"/> with <Skill id="10192"/> (<Trait id="1687" disableText/>), <Skill id="10331"/> and <Trait id="666"/>
- <Boon name="stability"/> with every shatter (<Trait id="1687" disableText/>)
- <Boon name="resistance"/> with <Skill id="29830"/> (<Trait id="1687" disableText/>)

Are we done yet? No!

### Crowd Control

Break any defiance bar with <Skill id="29519"/>, <Skill id="30643"/> and <Skill id="10287"/>. <Item id="24639"/> on your shield helps as well.

### Conditions

You can put out around 15x <Condition name="vulnerability"/> with <Skill id="10216"/> and your sword auto-attack (the clones from <Skill id="10173"/> and <Skill id="30769"/> execute the sword chain as well!). You can run <Item id="24567"/> instead of <Item id="24615"/> on your staff for additional ~3 stacks.

### DPS

Use <Skill id="10334"/>, your phantasms and <Skill id="21750"/> (optional) whenever they are ready. Don't cancel your sword auto-attacks as the third hit deals the most damage. As soon as you get three illusions up cast <Skill id="49068"/> (plus all other shatters afterwards). You will end up doing around 4-6k DPS on fractal bosses with optimized gear.
</Card>
</GridItem>
</Grid>
