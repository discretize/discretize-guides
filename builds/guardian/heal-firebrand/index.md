---
title: 'Heal Firebrand'
date: '2021-06-01'
rating: 'Good'
role: 'Support'
profession: 'Guardian'
specialization: 'Firebrand'
skills: [9093, 9153, 9251]
boons: ['Quickness', 'Fury', 'Might', 'Swiftness', 'Stability', 'Aegis']
conditions: ['Vulnerability', 'Blinded', 'Crippled']
code: '[&DQEQLjElPjZLF0sXehZ6FksBNgH+AP4AiRKJEgAAAAAAAAAAAAAAAAAAAAA=]'
cmguides: '/cm-guides/guardian/heal-firebrand'
classification: [4, 1, 3, 1, 2]
---

<Divider text="Overview"/>

<Message>
This build is very common in PuGs. It is part of a composition called PuG Meta. More info about this composition can be found [here](/guides/meta-explained). This build provides a high amount of boons and a lot of safety to the group via its healing. It therefore shines most in less experienced groups as well as when you have bad instabilities. Once the safety of a dedicated healer is no longer needed, you can move on to running [Power Firebrand](/builds/guardian/power-firebrand) or [Condi Firebrand](/builds/guardian/condi-firebrand). We also added a new heal variant that is inbetween the full heal and damage versiont called [Zealot Firebrand](/builds/guardian/zealot-firebrand) for parties wanting to transition to no heal runs.

</Message>

<Specialization name="Firebrand" text="Heal Firebrand"/> provides a good amount of <Boon name="Might"/>, permanent <Boon name="Quickness"/>, <Boon name="Fury"/>, <Boon name="Regeneration"/> and <Boon name="Swiftness"/> as well as some <Boon name="Protection"/> and <Boon name="Resolution"/>. It also has on-demand access to <Boon name="Aegis"/>, <Boon name="Stability"/> and <Boon name="Resistance"/>.

It offers a decent amount of healing through symbols, dodges, <Skill name="Mantra of Solace"/>, <Boon name="Regeneration"/>, <Skill name="Bow of Truth"/>, etc.

Similar to the <Specialization name="Firebrand" text="Power Firebrand"/> it provides good offensive support by sharing the 216 <Attribute name="Power"/> from <Skill name="Bane Signet"/> through <Trait name="Perfect Inscriptions"/>.

The build is very flexible and can be adapted to the encounter, instabilities and the group you are playing with.

<Divider text="Equipment"/>

Note that this build variant is optimized for 150 agony resistance.  
If you have more AR, feel free to swap out more Harrier pieces for Cleric but make sure you are maintaining 100% boon duration on both weapon sets.

You can play full Harrier, however you will lose some <Attribute name="Healing Power"/>.

Check the [gear optimizer](http://old.discretize.eu) for more gear variants!

<Grid>
<GridItem sm="4">
<Armor weight="Heavy" helmAffix="Harrier" helmRune="Monk" shouldersAffix="Harrier" shouldersRune="Monk" coatAffix="Harrier" coatRune="Monk" glovesAffix="Harrier" glovesRune="Monk" leggingsAffix="Harrier" leggingsRune="Monk" bootsAffix="Harrier" bootsRune="Monk" helmInfusionId="49432" shouldersInfusionId="49432" coatInfusionId="49432" glovesInfusionId="49432" leggingsInfusionId="49432" bootsInfusionId="49432" />
</GridItem>
 
<GridItem sm="4">
<Weapons weapon1MainType="Staff" weapon1MainAffix="Harrier" weapon1MainSigil1="Transference" weapon1MainSigil2="Concentration" weapon2MainType="Axe" weapon2MainAffix="Harrier" weapon2MainSigil1="Transference" weapon2OffType="Shield" weapon2OffAffix="Harrier" weapon2OffSigil="Concentration" weapon1MainInfusion1Id="49432" weapon2MainInfusion1Id="49432" weapon1MainInfusion2Id="49432" weapon2OffInfusionId="49432"/>
<Card title="Swap Weapons">
* Greatsword for pulling adds in Nightmare CM after MAMA.
* Mace when  <Boon name="Fury"/> is fully covered by others.
</Card>
</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemAffix="Cleric" accessory1Affix="Cleric" accessory2Affix="Cleric" amuletAffix="Harrier" ring1Affix="Cleric" ring2Affix="Harrier" backItemInfusion1Id="49432" backItemInfusion2Id="49432" accessory1InfusionId="49432" accessory2InfusionId="49432" ring1Infusion1Id="49432" ring1Infusion2Id="49432" ring1Infusion3Id="49432" ring2Infusion1Id="49432" ring2Infusion2Id="49432" ring2Infusion3Id="49432"/>
<Consumables food="Delicious Rice Ball" utilityId="67528" infusion="Healing +9 Agony Infusion"/>
</GridItem>

</Grid>

<Divider text="Default Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1="Radiance" traits1Selected="Healers Resolution, Wrath of justice, Perfect Inscriptions" traits2="Honor" traits2Selected="Invigorated Bulwark, Honorable Staff, Writ of Persistence" traits3="Firebrand" traits3Selected="Liberators Vow, Weighty Terms, Loremaster"/>
 
</GridItem>

<GridItem sm="5">
<Skills heal="Mantra of Solace" utility1="Mantra of Potence" utility2="Bane Signet" elite="Mantra of Liberation"/>

</GridItem>
</Grid>

<Divider text="Situational"/>

<Grid>
<GridItem sm="6">
<Card title="Common Utility Skills">
| | |
| -- | -- |
| <Skill name="Bow of Truth" size="big" disableText/> | A strong AoE heal for 5 seconds. |
| <Skill name="Mantra of Lore" size="big" disableText/> | A strong condition cleanse to counterplay <Instability name="Afflicted"/>. Also offers extra passive healing through <Boon name="Regeneration"/>. |
| <Skill name="Advance" size="big" disableText/> | Extra <Boon name="Aegis"/> without a cast time. Use this when when the extra damage mitigation from <Boon name="Aegis"/> is more beneficial than the cleanse or healing from another utility.|
| <Skill name="Hammer of Wisdom" size="big" disableText/> | Provides 200 extra Defiance bar damage when no other utility is needed. |
| <Skill name="Stand Your Ground" size="big" disableText/> | Can be used for extra <Boon name="Stability"/>. Advantages over <Skill name="Hallowed Ground"/> are the instant cast and the lower cooldown. |
| <Skill name="Hallowed Ground" size="big" disableText/> | Can be used for extra <Boon name="Stability"/>. This skill provides more <Boon name="Stability"/> on a stationary target than <Skill name="Stand Your Ground"/>.
| <Skill name="Sanctuary" size="big" disableText/> | Strong CC over time for mostly stationary enemies with a defiance bar.
| <Skill name="Wall of Reflection" size="big" disableText/> | Stationary reflect for 8 seconds. |
| <Skill name="Purging Flames" size="big" disableText/> | Burns enemies and cleanses conditions from allies within. Useful when conditions are inflicted multiple times in a short period of time but often inferior to <Skill name="Mantra of Lore"/>. |

</Card>
</GridItem>

<GridItem sm="6">
<Card title="Less Common Utility Skills">
| | |
| -- | -- |
| <Skill name="Signet of Wrath" size="big" disableText/> | Can be run with Radiance in Condition-based groups to share 216 <Attribute name="Condition Damage"/> through <Trait name="Perfect Inscriptions"/>. Keep in mind that this does not provide the immediate defiance bar damage of <Skill name="Bane Signet"/>. |
| <Skill name="Hold the Line" size="big" disableText/> | Provides extra <Boon name="Protection"/>. |
| <Skill name="Judges Intervention" size="big" disableText/> | 1200 range blink to an enemy. Mainly useful for skips. |
| <Skill name="Merciful Intervention" size="big" disableText/> | 1200 range blink to an ally. Can be used for skips to blink to a <Skill name="Sword of Justice"/>. Can also be taken to help allies who frequently down. |
</Card>

<Card title="Elite Skills">
| | |
| -- | -- |
| <Skill name="Mantra of Liberation" size="big" disableText>| Should always be used unless there is absolutely no need for <Boon name="Stability"/> and <Boon name="Resolution"/>. |
| <Skill name="Feel My Wrath" size="big" disableText/> | Can be used if you struggle upkeeping <Boon name="Quickness"/> or <Boon name="Fury"/>. |
| <Skill name="Signet of Courage" size="big" disableText/> | Good passive healing if neither of the other 2 skills are useful in a given situation. |
</Card>
</GridItem>

</Grid>

<Grid>
<GridItem sm="7">
<Card title="Virtues">
<Traits unembossed traits1="Virtues" traits1Selected="Resolute Subconscious, Absolute Resolve, Battle Presence"/>
If you need more healing or an extra free utility slot, you can swap out Radiance for Virtues. You can then remove <Skill name="Bane Signet"/> for a 2nd utility of choice. Keep in mind that you will lose out on a lot of CC, the shared 216 <Attribute name="Power"/> from <Skill name="Bane Signet"/> and the shared 216 <Attribute name="Condition Damage"/> from triggering <Trait name="Wrath of Justice"/>, so only take this when the extra healing is needed, most likely when dealing with bad instabilities or for less experienced groups.
</Card>
</GridItem>
<GridItem sm="5">
<Card title="Situational Traits">
| | |
| -- | -- |
| <Trait name="Right-Hand Strength" size="big" disableText/> | If there is no need for the personal <Boon name="Resolution"/> from <Trait name="Healers Resolution"/>. |
| <Trait name="Pure of Heart" size="big" disableText/> | Trades in some <Boon name="Might"/> for extra healing, can be useful for some T4 fractals with many attacking adds. |
| <Trait name="Master of Consecrations" size="big" disableText/> | Use this when you are using a Consecration skill while running the Virtues trait line. |
</Card>
</GridItem>

</Grid>

<Divider text="Skill Explanations"/>

<Grid>
<GridItem sm="6">
<Card title="Axe/Shield">
* <Skill name="Core Cleave"/> does decent damage even as a healer.
* <Skill name="Symbol of Vengeance"/> places a symbol that will pulse <Boon name="Fury"/>. Due to <Trait name="Writ of Persistence"/> this will also passively heal allies within. This skill should be used off-cooldown when on the Axe weapon set.
* <Skill name=Blazing Edge/> can be used for CC or to pull adds together.
* <Skill name="Shield of Judgment"/> grants <Boon name="Protection"/> and <Boon name="Aegis"/>. This is your main source of <Boon name="Protection"/> so make sure to prioritize this skill when <Boon name="Aegis"/> is needed.
* <Skill name="Shield of Absorption"/> is very versatile. This skill can be double-tapped for quick CC or healing or can be channeled longer for negating projectiles. This skill will cancel other skills you are currently casting.

</Card>
</GridItem>
<GridItem sm="6">
<Card title="Staff">
* <Skill name="Bolt of Wrath"/> is rather weak but can be used to aggro enemies from range.
* <Skill name="Holy Strike"/> can be used to heal, aggro adds from range or to blast <Boon name="Might"/> or condi cleanse.
* <Skill name="Symbol of Swiftness"/> places a symbol that will pulse <Boon name="Swiftness"/>. Due to <Trait name="Writ of Persistence"/> this will also passively heal allies within. This skill should be used off-cooldown when on the Staff weapon set.
* <Skill name="Empower"/> is one of your main sources of <Boon name="Might"/> and should be used off-cooldown while on Staff. You can give yourself <Boon name="Aegis"/> while channeling via instant cast skills if attacks are incoming.
* <Skill name="Line of Warding"/> is a very niche skill. This skill will cancel other skills you are currently casting.

</Card>
</GridItem>
<GridItem sm="6">
<Card title="Mace">
* <Skill name="True Strike"/> does decent damage and heals when finishing the auto-attack chain.
* <Skill name="Symbol of Faith"/> places a symbol that will pulse <Boon name="Regeneration"/>. Due to <Trait name="Writ of Persistence"/> this will also passively heal allies within. This skill should be used off-cooldown when on the Mace weapon set.
* <Skill name="Protectors Strike"/> grants <Boon name="Aegis"/> if you block an attack while channeling it. It can sometimes be useful to run itno an attack on purpose while channeling this attack to trigger the <Boon name="Aegis"/> application.

</Card>
</GridItem>
<GridItem sm="6">
<Card title="CC Skills">
| | |
| -- | -- |
| <Skill name="Blazing Edge"/> | 150 damage |
| <Skill name="Shield of Absorption"/> | 150 damage |
| <Skill name="Bane Signet"/> | 300 damage |
| <Skill name="Hammer of Wisdom"/> | 200 damage |
| <Skill name="Tome of Justice"/> Skill 3 | 150 damage |
| <Skill name="Sanctuary"/> | 150/s damage |
</Card>
</GridItem>

</Grid>

<Card title="Tomes">
Activating a Tome will replace your weapon skills and grant you 5 skill usages in the Tome. You can also leave the Tome early though.

Entering a Tome has a cast time and your Skill 5 on both weapon sets can cancel skill casts so make sure to not spam the 5 button when entering the Tome or you might end up cancelling the Tome.

Tomes also have the passive effect from the Virtues. Through <Trait name="Loremaster"/> those passive effects will be kept even if the Tomes are on cooldown.

All Tomes are built in a similar way:

- Skill 1 creates an effect in a cone in front of you.
- Skill 2 creates an effect around you.
- Skill 3 is a ground target skill.
- Skill 4 creates a field.
- Skill 5 grants a unique buff to your allies.

<Skill name="Tome of Justice"/>:

- Use this Tome mainly for providing a Fire Field.
- Skill 1 and 2 are mostly useless on <Specialization name="Firebrand" text="Heal Firebrand"/>.
- Skill 3 is a CC. It pulls enemies together and can be used from range.
- Skill 4 creates a Fire Field that can be used to blast <Boon name="Might"/>.
- Skill 5 grants an effect to allies that makes them inflict burning on their next attacks. This scales with <Attribute name="Condition Damage"/> so be careful when using this skill or skip it entirely when running with <Specialization name="Firebrand" text="Condi Firebrands"/>.
- When running Radiance, dealing damage with any skill in this Tome will trigger <Trait name="Wrath of Justice"/> and share the <Attribute name="Condition Damage"/> to allies.
- When running Radiance killing certain enemies will reset this Tome. Keep in mind this will not reset the skills in the Tome.
- A common rotation in this Tome is 4-(5)-exit.

<Skill name="Tome of Resolve"/>:

- Use this Tome for emergency healing and cleansing.
- Skill 1 heals in a cone in front of you.
- Skill 2 heals and cleanses conditions.
- skill 3 gives some boons but will rarely be used.
- Skill 4 places a healing field that can also be blasted for extra healing.
- Skill 5 converts conditions into boons and grants allies an cimoning healing modifier.
- When running Virtues entering this Tome also cleanses conditions.
- Common rotations in this Tome are 2-5-4-1-2 for maximum sustained healing or 5-4-2-1-1 for maximum burst healing.

<Skill name="Tome of Courage"/>:

- Use this Tome for massive <Boon name="Stability"/>, <Boon name="Resistance"/> or a reflect.
- Skill 1 grants <Boon name="Stability"/>.
- Skill 2 inflicts 1 second of <Condition name="Taunt"/> on the enemy.
- Skill 3 places a bubble that reflects incoming projectiles.
- Skill 4 places a field that pulses <Boon name="Resistance"/> to allies. This will help dealing with non-damaging conditions such as <Condition name="Blinded"/> and <Condition name="Slow"/>.
- Skill 5 provides <Boon name="Protection"/>, <Boon name="Aegis"/>, <Boon name="Stability"/> as well as extra Toughness.
- There is no set rotation in this Tome, use whatever skills you need for their utility and make sure to press Skill 5 as it is an incredibly strong skill.
- You can camp in this Tome for a few extra seconds to get an extra cast on an important skill, for example a 2nd reflect. However only do this when absolutely needed as you will not have access to the boons and healing your weapon skills provide.

</Card>

<Divider text="Providing Boons"/>

<Card title="Standard Boons">
+ <Boon name="Quickness"/> will be provided by using <Skill name="Mantra of Solace"/> (which triggers <Trait name="Liberators Vow"/> every 7 seconds) and <Skill name="Mantra of Potence"/>. Keep 2 charges of <Skill name="Mantra of Solace"/> to provide <Boon name="Aegis"/> and use it evrey time you go back to 3 charges. You can use <Skill name="Mantra of Potence"/> down to 0 charges whenever you are stacked with your group.
+ <Boon name="Might"/> comes from different sources. <Skill name="Empower"/> is a big source of <Boon name="Might"/> and should be used off-cooldown whenever you are on Staff and on the group. Using <Skill name="Tome of Justice"/> Skill 4 and blasting it with <Skill name="Holy Strike"/> will also grant <Boon name="Might"/> and give others the option to also blast additional <Boon name="Might"/>. Using <Skill name="Mantra of Potence"/> as mentioned above will also contribute to <Boon name="Might"/> generation.
+ <Boon name="Fury"/> will be provided through <Skill name="Symbol of Vengeance"/>. Make sure to use this off-cooldown when on the Axe weapon set while peopel are stacked together. Try to use this skill 2 times before swapping to Staff.
+ <Boon name="Swiftness"/> mainly comes from <Skill name="Symbol of Swiftness"/>. Make sure to use this whenever you are on Staff.
+ <Boon name="Regeneration"/> will be provided through <Skill name="Mantra of Lore"/> when equipped. You can use it similarly to <Skill name="Mantra of Solace"/> and keep 2 charges for condi cleanse while providing some <Boon name="Regeneration"/> whenever it goes back to 3 charges.
+ Some <Boon name="Protection"/> can be provided through <Skill name="Shield of Judgment"/>. This is your only reliable source of <Boon name="Protection"/> as you do not want to use <Skill name="Tome of Courage"/> just for the <Boon name="Protection"/> from Skill 5.
+ <Boon name="Resolution"/> is provided through <Skill name="Mantra of Liberation"/>. If you think you will not need a lot of <Boon name="Stability"/> you can use this down to 2 charges similar to <Skill name="Mantra of Solace"/> in order to provide some <Boon name="Resolution"/> to the group.

</Card>

<Card title="Pre-Stacking Boons">
* Provide a Fire Field if needed. <Skill name="Tome of Justice"/> Skill 4 provides a short Fire Field. <Skill name="Hallowed Ground"/> provides a longer Fire Field as well as extra <Boon name="Resolution"/> but has to be specifically slotted for pre-stacking.
* <Skill name="Holy Strike"/> to blast <Boon name="Might"/>.
* <Skill name="Empower"/> and cast <Skill name="Mantra of Solace"/> once and every other equipped Mantra as often as you can during the cast.
* <Skill name="Feel My Wrath"/> if you have it equipped.
* <Skill name="Bane Signet"/> if you can start the fight within 10 seconds of usage.
* Take the singularity.
* <Skill name="Empower"/> and use <Skill name="Mantra of Potence"/> once during this cast.
* <Skill name="Symbol of Swiftness"/> on the way to the boss and swap to Axe before the fight starts to place <Skill name="Symbol of Vengeance"/>.

</Card>

<Grid>

<GridItem sm="6">
<Card title="Aegis">
* Correct application of <Boon name="Aegis"/> requires knowledge of the encounters and which attacks are impactful to block.
* As mentioned above keep <Skill name="Mantra of Solace"/> and 2 charges and use them when <Boon name="Aegis"/> is needed.
* <Skill name="Shield of Judgment"/> will also give <Boon name="Aegis"/>. Prioritize this over the charges of <Skill name="Mantra of Solace"/> since this is also your main source of <Boon name="Protection"/>.
* <Skill name="Tome of Courage"/> Skill 5 will also provide <Boon name="Aegis"/>, however you will not enter this Tome for a single application of <Boon name="Aegis"/>.
* <Skill name="Advance"/> is an instant-cast skill providing <Boon name="Aegis"/> when chosen.
* If Mace is equipped, <Skill name="Protectors Strike"/> also grants <Boon name="Aegis"/> when blocking an attack while channeling.
* You can use instant-cast skills, namely <Skill name="Mantra of Solace"/> and <Skill name="Advance"/> while channeling other skills so if you need to use <Skill name="Empower"/> but an attack is incoming you can still cast it and get <Boon name="Aegis"/> from one of those skills.

</Card>
</GridItem>

<GridItem sm="6">
<Card title="Stability">
* Correct application of <Boon name="Stability"/> requires knowledge of the encounters and which attacks and be negated with <Boon name="Stability"/> without taking too much damage.
* Make sure to not apply too much <Boon name="Stability"/> at once. For example if you use <Skill name="Stand Your Ground"/>, you will most likely not need to apply any more <Boon name="Stability"/> until the boon ends since it provides 5 stacks.
* <Skill name="Mantra of Liberation"/> is the easiest access to <Boon name="Stability"/>. However keep in mind this only provides one stack.
* The most common utility skill choice for extra <Boon name="Stability"/> is <Skill name="Stand Your Ground"/> but when the longer cooldown of <Skill name="Hallowed Ground"/> is not an issue that one can be used very well on stationary targets.
* You can use <Skill name="Mantra of Liberation"/> and <Skill name="Stand Your Ground"/> while casting <Skill name="Empower"/> if an interrupt is incoming.
* <Skill name="Tome of Courage"/> will also grant access to a very high amount of <Boon name="Stability"/> but is on a fairly long cooldown. Make sure to open the Tome ahead of time due to both the Tome and the skills within having a cast time.
* Make sure to provide enough healing while in <Skill name="Tome of Courage"/> since it replaces your weapons skills. This can be achieved though dodges, utility skills or pre-placed symbols.

</Card>
</GridItem>

</Grid>

<Divider text="Healing"/>

<Card title="Sustained Healing">
* Try to keep your group alive as well as you can through sustained healing and use your burst healing only when it is needed. Keep in mind that active damage mitigation through avoiding attacks or blocking them is very valuable and will help a lot more than a slight increase in healing numbers.
* A lot of consistent healing comes from your symbols through <Trait name="Writ of Persistence"/>. Since you want to use <Skill name="Symbol of Vengeance"/> and <Skill name="Symbol of Swiftness"/> off-cooldown anyways to provide boons, This will give you a nice amount of healing through the entire fight. Same goes for <Skill name="Empower"/>.
* Thanks to <Trait name="Selfless Daring"/> you will also heal at the end of a dodge roll. Make sure to keep enough endurance to avoid mechanics but otherwise feel free to use up dodges for healing.
* If <Skill name="Mantra of Lore"/> is equipped, it will provide <Boon name="Regeneration"/> to your group so make sure to use it down to 2 charges whenever it goes back up to 3.
* If Mace is equipped the auto-attacks will provide a good amount of healing and <Skill name="Symbol of Faith"/> will provide extra <Boon name="Regeneration"/>.

</Card>

<Card title="Burst Healing">
* For emergency situations you have some smaller burst healing options as well as your <Skill name="Tome of Resolve"/>.
* If you are swapping to Staff when healing is needed keep in mind that <Skill name="Symbol of Swiftness"/> provides healing over time while <Skill name="Holy Strike"/> and <Skill name="Empower"/> provide burst healing.
* <Skill name="Bow of Truth"/> is a great option for high burst healing when slotted.
* <Skill name="Tome of Resolve"/> is the biggest source of burst healing and should be used as a last resort due to its long cooldown. However due to the cast of both opening the Tome and the skils within, make sure to not hesitate too long. If hte healing does not need to be immediate you can use 2-5-4-1-2, if you need the instant burst healing you can use 5-4-2-1-1.
 
</Card>

<Card title="Condition Cleanse">
* If a lot of condition cleanse is needed you will most likely slot <Skill name="Mantra of Lore"/> which will then be your main reliable source of condition cleanse while also providing some extra <Boon name="Regeneration"/>.
* Blasting Light Fields also causes area condition cleanse. On Staff you can place <Skill name="Symbol of Swiftness"/> and blast it with <Skill name="Holy Strike"/>.
* <Skill name="Tome of Resolve"/> Skill 2 and 5 will cleanse conditions as well, however same as with burst healing this is often a last resort. When running Virtues, opening this Tome will also cleanse conditions.

</Card>

<Divider text="Videos"/>
<Message>
Here's two In-Depth video guides on <Specialization name="Firebrand" text="Heal Firebrand"/>. Keep in mind that we still highly recommend playing the default Radiance/Honor build from the build section.
</Message>

<Grid>
<GridItem sm="6">
<Video youtube="sxiTwW7oDA8" title="Build Guide by Ascers"/>
</GridItem>

<GridItem sm="6">
<Video youtube="oigZbGyQvbQ" title="Build Guide by Rheyo"/>
</GridItem>
</Grid>
