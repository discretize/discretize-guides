---
title: 'Boon Chronomancer'
date: '2018-05-16'
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

Yes, you've read right - the <Specialization prefix="boon" name="chronomancer"/> or <Specialization prefix="chaos" name="chronomancer"/> is capable of providing **every single boon** in the game to the party. You can permanently keep up ten boons plus <Boon name="aegis"/> and some <Boon name="resistance"/> which has great synergy with your own trait <Trait id="1865"/>, the <Specialization name="warrior"/>'s <Trait id="1471" profession="warrior"/> and the <Specialization name="weaver" prefix="arcane"/>'s <Trait id="1511" profession="elementalist"/>.

This is the recommended build variant if you plan to play **without a <Specialization name="druid"/> and a third <Specialization name="weaver" prefix="arcane"/> instead**, as one additional <Trait id="264" profession="elementalist"/> is enough to keep up 25x <Boon name="might"/> in combination with your own might output - making <Skill id="31582" profession="ranger"/>, <Skill id="12497" profession="ranger"/> and <Trait id="1016" profession="ranger"/> (redundant with <Trait id="2177" profession="elementalist"/> in fractals) the only loss while you gain much more DPS. The slow ramp-up time for <Boon name="might"/> is compensated by pre-stacking.

On top of all that the build has access to the usual mesmer utilities being <Skill id="10197"/> and <Effect name="stealth"/> skips, strong reflects, boon stripping and amazing crowd control skills such as <Skill id="29519"/>.

While the sheer amount of possibilities are nice to look at, the Chronomancer is one of the harder builds to play as the skills require timing and good dynamic decision-making.

<Divider text="Equipment (150 AR + 10 boons avg)"/>

As you overcap 100% boon duration with <Trait id="1865"/>, <Item id="72339"/>, <Item id="79722"/> and <Item id="70600"/> in fractals, <Item id="69370"/> is the recommended alternative to increase <Boon name="resistance"/> uptime (remember, it's another 2% DPS boost for your Weavers). Another option is to aim for 100% without <Item id="72339"/> and keep your (raid) boon duration runes. You can also keep your [Hybrid Chronomancer](https://discretize.eu/builds/mesmer/hybrid-chronomancer) gear and just swap runes to Revenant which trades exactly 30% boon duration.

Especially for a Chrono it is highly recommended to aim higher than the minimum required Agony Resistance (e.g. <Item id="70596"/>, 18x <Item id="86180"/> and Agony Impedance as well as Mist Attunement) as you gain additional Boon Duration from the <Item id="79722"/>.

Note that the optimal gear uses <Item id="86180"/> infusions, please use our [gear optimizer](http://old.discretize.eu/) to determine the optimal gear for your needs.

<Grid>
<GridItem sm="4">
<Armor helmAffix="Commander" helmId="75727" helmRune="Revenant" helmRuneId="69370" helmRuneCount="6" shouldersAffix="Berserker" shouldersId="48083" shouldersRune="Revenant" shouldersRuneId="69370" shouldersRuneCount="6" coatAffix="Berserker" coatId="48079" coatRune="Revenant" coatRuneId="69370" coatRuneCount="6" glovesAffix="Berserker" glovesId="48080" glovesRune="Revenant" glovesRuneId="69370" glovesRuneCount="6" leggingsAffix="Commander" leggingsId="76139" leggingsRune="Revenant" leggingsRuneId="69370" leggingsRuneCount="6" bootsAffix="Berserker" bootsId="48078" bootsRune="Revenant" bootsRuneId="69370" bootsRuneCount="6"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainType="Sword" weapon1MainAffix="Commander" weapon1MainId="73724" weapon1MainSigil1="Concentration" weapon1MainSigil1Id="72339" weapon1OffType="Shield" weapon1OffAffix="Commander" weapon1OffId="76075" weapon1OffSigil="Paralyzation" weapon1OffSigilId="24639" weapon2MainType="Staff" weapon2MainAffix="Commander" weapon2MainId="76089" weapon2MainSigil1="Concentration" weapon2MainSigil1Id="72339" weapon2MainSigil2="Force" weapon2MainSigil2Id="24615"/>

<Card title="Swap Weapons">
* Focus when reflects or pulls are needed
* Torch for <Boon name="might"/> stacking
</Card>
</GridItem>

<GridItem sm="4">
<Trinkets backItemAffix="Commander" backItemId="79830" backItemStatId="1125" accessory1Affix="Berserker" accessory1Id="39232" accessory2Affix="Berserker" accessory2Id="39233" amuletAffix="Commander" amuletId="80241" amuletStatId="1125" ring1Affix="Berserker" ring1Id="75669" ring2Affix="Berserker" ring2Id="76024"/>

<Consumables foodId="43550" utilityId="67530" infusionId="37131"/>
</GridItem>
</Grid>

Note that you can also run an Offhand Sword instead of Staff for better DPS. It's still possible to achieve 100% <Boon name="retaliation"/> uptime on stationary fights with Sword but Staff is overall the safer option with more <Boon name="aegis"/> uptime, as your only other source is <Trait id="670"/> without it.

<Divider text="Healing Variant"/>

The **Healing Variant** can be used if your party has trouble surviving without a dedicated healer. Note that using full Minstrel equipment, 6x <Item id="24842"/>, <Trait id="1865"/> and <Item id="79722"/> puts you above 100% Boon Duration already - no <Item id="72339"/> needed. You can replace Minstrel with Cleric items for even more Healing Power if you have additional Concentration (like from having more Agony Resistance).

Your main heal sources are <Trait id="1915"/>, <Trait id="740"/>, <Trait id="1987"/>, <Boon name="regeneration"/> and your healing skill. Keep in mind that <Trait id="757"/> is a strong condition cleanse combined with <Skill id="10213"/> charges. If you have <Trait id="738"/> traited, you can use up mantra charges as the preparation itself heals already as well.

<Grid>
<GridItem sm="4">
<Armor helmAffix="Minstrel" helmId="73970" helmRune="Monk" helmRuneId="24842" helmRuneCount="6" shouldersAffix="Minstrel" shouldersId="73670" shouldersRune="Monk" shouldersRuneId="24842" shouldersRuneCount="6" coatAffix="Minstrel" coatId="74448" coatRune="Monk" coatRuneId="24842" coatRuneCount="6" glovesAffix="Minstrel" glovesId="75866" glovesRune="Monk" glovesRuneId="24842" glovesRuneCount="6" leggingsAffix="Minstrel" leggingsId="70414" leggingsRune="Monk" leggingsRuneId="24842" leggingsRuneCount="6" bootsAffix="Minstrel" bootsId="75349" bootsRune="Monk" bootsRuneId="24842" bootsRuneCount="6"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainType="Sword" weapon1MainAffix="Minstrel" weapon1MainId="76730" weapon1MainSigil1="Transference" weapon1MainSigil1Id="74326" weapon1OffType="Shield" weapon1OffAffix="Minstrel" weapon1OffId="74748" weapon1OffSigil="Paralyzation" weapon1OffSigilId="24639" weapon2MainType="Staff" weapon2MainAffix="Minstrel" weapon2MainId="75200" weapon2MainSigil1="Transference" weapon2MainSigil1Id="74326" weapon2MainSigil2="Water" weapon2MainSigil2Id="24551"/>
</GridItem>

<GridItem sm="4">
<Trinkets backItemAffix="Minstrel" backItemId="79830" backItemStatId="1123" accessory1Affix="Minstrel" accessory1Id="79444" accessory1StatId="1123" accessory2Affix="Minstrel" accessory2Id="79745" accessory2StatId="1123" amuletAffix="Minstrel" amuletId="80241" amuletStatId="1123" ring1Affix="Minstrel" ring1Id="79460" ring1StatId="1123" ring2Affix="Minstrel" ring2Id="79710" ring2StatId="1123"/>

<Consumables foodId="68634" utilityId="67528" infusionId="37125"/>
</GridItem>
</Grid>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1Id="23" traits1="Inspiration" traits1Selected="738,740,1866" traits2Id="45" traits2="Chaos" traits2Selected="670,669,1687" traits3Id="40" traits3="Chronomancer" traits3Selected="1987,1978,2022"/>

<Card title="Situational Traits">
| | |
| -- | -- |
| <Trait id="756" size="big" disableText/> | Can be taken for faster revive speed and emergency reflects if you don't run <Skill id="10213"/>. |
| <Trait id="1995" size="big" disableText/> | A very slight DPS increase in case you don't need the healing from <Trait id="1987"/>. |
| <Trait id="751" size="big" disableText/> | Use it together with a focus for frequent <Control name="pull"/>s and reflects. |
| <Trait id="674" size="big" disableText/> | Increases the duration of all your <Effect name="stealth"/> skills by 50%. |
| <Trait id="752" size="big" disableText/> | Two seconds longer duration for Glamour skills like <Skill id="10197"/>. |
</Card>
</GridItem>

<GridItem sm="5">
<Skills heal="10213" utility1="30814" utility2="29856" utility3="10236" elite="29519"/>

<Card title="Situational Skills">
| | |
| -- | -- |
| <Skill id="10311" size="big" disableText/> | If you don't need CC, this a is a higher DPS option combined with <Trait id="1890"/>. |
| <Skill id="30305" size="big" disableText/> | A stronger single group heal with lower <Boon name="resistance"/> uptime. |
| <Skill id="21750" size="big" disableText/> | A personal DPS increase at the cost of less <Boon name="resistance"/>. |
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
2. Use <Skill id="10190"/> (<Boon name="quickness" disableText/><Boon name="alacrity" disableText/><Boon name="vigor" disableText/><Boon name="stability" disableText/>) and <Skill id="10214"/> (<Boon name="resistance" disableText/>)
3. Cast <Skill id="10216"/> (<Trait id="1866" disableText/>), <Skill id="10310"/> (1st illusion) and swap to Sword/Shield
4. <Skill id="10173"/> (2nd illusion)
5. <Skill id="30643"/> and <Skill id="29830"/> at the end of the cast
    1. Use the remaining three shatters while continueing with the skills below - if a defiance bar is up, use <Skill id="10287"/> first, otherwise <Skill id="49068"/>(<Boon name="might" disableText/><Boon name="fury" disableText/><Boon name="regeneration" disableText/>)
    2. <Skill id="29519"/> if a defiance bar is up
    3. <Skill id="10236"/>
    4. <Skill id="29856"/> and <Skill id="30814"/>
5. <Skill id="30747"/> ends
6. Shatter everything again while continueing
7. <Skill id="29856"/> and <Skill id="30814"/>
8. <Skill id="10334"/>
9. Swap back to Staff
10. <Skill id="10236"/>
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

<Video youtube="SKD6K-zCUx4" title="No Staff Rotation by Yui [SC]"/>
</GridItem>

<GridItem>
<Card title="Skill priority">
As really every skill you have is worth using, you should simply cast everything whenever it is off recharge after following the opener sequence to the left.

If you're running a setup with <Item id="72339"/>, remember to weapon swap as often as possible and use <Skill id="10236"/> and phantasms triggering <Trait id="1866"/> in the 7 seconds afterwards.

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
- <Boon name="resistance"/> with <Skill id="29830"/> (<Trait id="1687" disableText/>) and <Skill id="10214"/> (<Item id="69370" disableText/>)

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
