---
title: Heal Firebrand
rating: Good
role: Support
author: Ascers.6082
profession: Guardian
specialization: Firebrand
skills:
  - 9093
  - 9153
  - 9251
conditions:
  - Vulnerability
  - Blinded
  - Crippled
boons:
  - name: Quickness
    uptime: 150%
    variant: group
  - name: Might
    uptime: 23 stacks
    variant: group
  - name: Stability
    uptime: 100%
    variant: group
  - name: Aegis
    uptime: on demand
    variant: group
  - name: Regeneration
    uptime: 100%
    variant: group
  - name: Protection
    uptime: 100%
    variant: group
  - name: Resolution
    uptime: 78%
    variant: group
code: '[&DQExJS4rPjZLFwAAehYAAAAAAAAWAQAAiRIAAAAAAAAAAAAAAAAAAAAAAAA=]'
cmGuide: 'pug'
classification:
  - 4
  - 1
  - 3
  - 1
  - 2
date: 2022-03-06T22:04:57.566Z
archive: false
hidden: false
---

<Warning>

This build is very common in PuGs. More info about building effective team compositions can be found [here](/guides/effective-comp). This build provides a high amount of boons and a lot of safety to the group via its healing. It therefore shines most in less experienced groups as well as when you have bad instabilities. Once the safety of a dedicated healer is no longer needed, you can move on to running [Power Firebrand](/builds/guardian/power-firebrand) or [Condi Firebrand](/builds/guardian/condi-firebrand). We also added a new heal variant that is in-between the full heal and damage version called [Celestial Firebrand](/builds/guardian/celestial-firebrand) for parties wanting to transition to no heal runs.

</Warning>

The <Specialization name="Firebrand" text="Heal Firebrand" /> provides a good amount of <Boon name="Might" />, permanent <Boon name="Quickness" />, <Boon name="Fury" />, <Boon name="Regeneration" /> and <Boon name="Swiftness" /> as well as some <Boon name="Protection" /> and <Boon name="Resolution" />. It also has on-demand access to <Boon name="Aegis" />, <Boon name="Stability" /> and <Boon name="Resistance" />.

It offers a decent amount of healing through symbols, dodges, <Skill name="Mantra of Solace"/>, <Boon name="Regeneration"/>, <Skill name="Bow of Truth"/>, etc.

This build can provide good offensive support by sharing the 216 <Attribute name="Power"/> from <Skill name="Bane Signet"/> or 216 <Attribute name="Condition Damage"/> from <Skill name="Signet of Wrath"/> through <Trait name="Perfect Inscriptions"/> when running the Radiance trait line.

The build is very flexible and can be adapted to the encounter, instabilities and the group you are playing with. Make sure to read through the situational tab for an explanation of the different utility skills. The [CM Guides](/cm-guides/guardian/heal-firebrand/) will also give an overview of what you can run on different encounters.

<Divider text="Equipment"/>

<CharacterWithAr> 
<Character title="Heal Firebrand" gear={{
    "profession": "Guardian",
    "weight": "Heavy",
    "gear": [
      "Harrier",
      "Harrier",
      "Harrier",
      "Harrier",
      "Harrier",
      "Harrier",
      "Harrier",
      "Cleric",
      "Harrier",
      "Cleric",
      "Cleric",
      "Cleric",
      "Harrier",
      "Harrier"
    ],
    "attributes": {
      "Health": 14145,
      "Armor": 2787,
      "Power": 2995,
      "Precision": 1243,
      "Toughness": 1516,
      "Vitality": 1250,
      "Ferocity": 150,
      "Condition Damage": 1162,
      "Expertise": 0,
      "Concentration": 1121,
      "Healing Power": 1712,
      "Agony Resistance": 162,
      "Condition Duration": 0,
      "Boon Duration": 0.9973333333333333,
      "Critical Chance": 0.3657142857142857,
      "Critical Damage": 1.6,
      "Outgoing Healing": 0.8133600000000001,
      "Resolution Duration": 0.25,
      "Effective Power": 5670.022757142858,
      "Power DPS": 0,
      "Bleeding Damage": 131.8475,
      "Bleeding Stacks": 0,
      "Bleeding DPS": 0,
      "Burning Damage": 447.22062500000004,
      "Burning Stacks": 0,
      "Burning DPS": 0,
      "Confusion Damage": 159.530875,
      "Confusion Stacks": 0,
      "Confusion DPS": 0,
      "Poison Damage": 148.37875,
      "Poison Stacks": 0,
      "Poison DPS": 0,
      "Torment Damage": 196.04625,
      "Torment Stacks": 0,
      "Torment DPS": 0,
      "Damage": 0,
      "Effective Health": 78451970.14925374,
      "Survivability": 39884.07226703291,
      "Effective Healing": 1638.5520960000001,
      "Healing": 1638.5520960000001
    },
    "runeId": 24842,
    "runeName": "Monk",
    "infusions": [
      37125, 37125, 37125, 37125, 37125, 37125, 37125,
      37125, 37125, 37125, 37125, 37125, 37125, 37125,
      37125, 37125, 37125, 37125
    ],
    "weapons": {
      "weapon1MainType": "Axe",
      "weapon1MainSigil1": "transference",
      "weapon1OffType": "Shield",
      "weapon1OffSigil": "concentration",
      "weapon2MainType": "Staff",
      "weapon2MainSigil1": "transference",
      "weapon2MainSigil2": "concentration"
    },
    "consumables": {
      "foodId": 91690,
      "utility": "bountiful-maintenance-oil",
      "infusion": "Healing +9 Agony Infusion"
    },
    "skills": {
      "heal": "Mantra of Solace",
      "utility1": "mantra of Potence",
      "utility3": "Sanctuary",
      "elite": "Feel My Wrath"
    },
    "assumedBuffs": [{"id": "Might", "type": "Boon"}, {"id": "Fury", "type": "Boon"}, {"gw2id": 1786, "type": "Trait"}]
}}>

Note that this build variant is optimized for 150 agony resistance. If you have more Agony Resistance, feel free to swap out more Harrier pieces for Cleric but make sure you are maintaining 100% boon duration on both weapon sets. You can play full Harrier, however you will lose some <Attribute name="Healing Power"/>. Check the [gear optimizer](https://optimizer.discretize.eu/) for more gear variants!
</Character>
</CharacterWithAr>

<Divider text="Default Build"/>

<Traits
  traits1="Virtues"
  traits1Selected="Master of Consecrations, Absolute Resolve, Battle Presence"
  traits2="Honor"
  traits2Selected="Invigorated Bulwark, Honorable Staff, Writ of Persistence"
  traits3="Firebrand"
  traits3Selected="Liberators Vow, Weighty Terms, Loremaster"
/>

<Divider text="Situational Traits and Skills"/>

<Card title="Radiance">
<Traits
unembossed
traits1="Radiance"
  traits1Selected="Healers Resolution, Wrath of justice, Perfect Inscriptions"
  />
If you can afford to give up some healing for extra group DPS, you can swap out Virtues
for Radiance. Your 3rd utility will then be either <Skill name="Bane Signet" /> or <Skill name="Signet of Wrath"/> to share the passive through <Trait name="Perfect Inscriptions"/> . In Condition-based groups you can also take advantage of the extra shared 216 <Attribute name="Condition Damage" /> from triggering <Trait name="Wrath of Justice" />.
The advantage of this trait line is the increased group DPS. It gives up some passive healing from Virtues, the lower cooldown on Tomes and the 3rd open utility slot to achieve this.

</Card>
  
<Grid>
<GridItem sm="6">
<Card title="Common Utility Skills">

|                                                           |                                                                                                                                                                                               |
| --------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <Skill name="Bane Signet" size="big" disableText/>        | Can be run with Radiance in Power-based groups to share 216 <Attribute name="Power"/> through <Trait name="Perfect Inscriptions"/>. Provides good instant CC.                                 |
| <Skill name="Signet of Wrath" size="big" disableText/>    | Can be run with Radiance in Condition-based groups to share 216 <Attribute name="Condition Damage"/> through <Trait name="Perfect Inscriptions"/>.                                            |
| <Skill name="Sanctuary" size="big" disableText/>          | Strong CC over time for mostly stationary enemies with a defiance bar.                                                                                                                        |
| <Skill name="Bow of Truth" size="big" disableText/>       | A strong AoE heal for 5 seconds.                                                                                                                                                              |
| <Skill name="Mantra of Lore" size="big" disableText/>     | A strong condition cleanse to counterplay <Instability name="Afflicted"/>. Also offers extra passive healing through <Boon name="Regeneration"/>.                                             |
| <Skill name="Advance" size="big" disableText/>            | Extra <Boon name="Aegis"/> without a cast time. Use this when when the extra damage mitigation from <Boon name="Aegis"/> is more beneficial than the cleanse or healing from another utility. |
| <Skill name="Hammer of Wisdom" size="big" disableText/>   | Provides 200 extra Defiance bar damage when no other utility is needed.                                                                                                                       |
| <Skill name="Stand Your Ground" size="big" disableText/>  | Can be used for extra <Boon name="Stability"/>. Advantages over <Skill name="Hallowed Ground"/> are the instant cast and the lower cooldown.                                                  |
| <Skill name="Hallowed Ground" size="big" disableText/>    | Can be used for extra <Boon name="Stability"/>. This skill provides more <Boon name="Stability"/> on a stationary target than <Skill name="Stand Your Ground"/>.                              |
| <Skill name="Wall of Reflection" size="big" disableText/> | Stationary reflect for 8 seconds.                                                                                                                                                             |

</Card>

</GridItem>

<GridItem sm="6">

<Card title="Elite Skills">

|                                                              |                                                                                                                                                                                                              |
| ------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <Skill name="Mantra of Liberation" size="big" disableText /> | Great for on-demand <Boon name="Stability"/> and <Boon name="Resolution"/>. Make sure you are able to upkeep <Boon name="Quickness"/> or <Boon name="Fury"/> when not running <Skill name="Feel My Wrath"/>. |
| <Skill name="Feel My Wrath" size="big" disableText/>         | Use this if you otherwise struggle upkeeping <Boon name="Quickness"/> or <Boon name="Fury"/>.                                                                                                                |
| <Skill name="Signet of Courage" size="big" disableText/>     | Good passive healing if neither of the other 2 skills are useful in a given situation.                                                                                                                       |

</Card>

<Card title="Less Common Utility Skills">

|                                                              |                                                                                                                                                                                               |
| ------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <Skill name="Hold the Line" size="big" disableText/>         | Provides extra <Boon name="Protection"/>.                                                                                                                                                     |
| <Skill name="Judges Intervention" size="big" disableText/>   | 1200 range blink to an enemy. Mainly useful for skips.                                                                                                                                        |
| <Skill name="Merciful Intervention" size="big" disableText/> | 1200 range blink to an ally. Can be used for skips to blink to a <Skill name="Sword of Justice"/>. Can also be taken to help allies who frequently down.                                      |
| <Skill name="Purging Flames" size="big" disableText/>        | Burns enemies and cleanses conditions from allies within. Useful when conditions are inflicted multiple times in a short period of time but often inferior to <Skill name="Mantra of Lore"/>. |

</Card>

<Card title="Situational Traits">

|                                                              |                                                                                                                                               |
| ------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------- |
| <Trait name="Right-Hand Strength" size="big" disableText/>   | If there is no need for the personal <Boon name="Resolution"/> from <Trait name="Healers Resolution"/> while running the Radiance trait line. |
| <Trait name="Pure of Heart" size="big" disableText/>         | Trades in some <Boon name="Might"/> for extra healing, can be useful for some T4 fractals with many attacking adds.                           |
| <Trait name="Resolute Subconscious" size="big" disableText/> | Use this when you are not using any Consecration skill while running the Virtues trait line.                                                  |

</Card>

</GridItem>

</Grid>

<Divider text="Skill Explanations"/>

<Grid>

<GridItem sm="6">

<Card title="Axe/Shield">

- <Skill name="Core Cleave" /> does decent damage even as a healer.
- <Skill name="Symbol of Vengeance" /> places a symbol that will pulse <Boon name="Fury" />
  . Due to <Trait name="Writ of Persistence" /> this will also passively heal allies
  within. This skill should be used off-cooldown when on the Axe weapon set.
- <Skill name="Blazing Edge" /> can be used for CC or to pull adds together.
- <Skill name="Shield of Judgment" /> grants <Boon name="Protection" /> and <Boon name="Aegis" />
  . This is a main source of on-demand <Boon name="Aegis" /> and adds some extra <Boon name="Protection"/> on top of what you get from <Skill name="Mantra of Solace"/>.
- <Skill name="Shield of Absorption" /> is very versatile. This skill can be double-tapped
  for quick CC or healing or can be channeled longer for negating projectiles. This
  skill will cancel other skills you are currently casting.

</Card>
</GridItem>

<GridItem sm="6">
<Card title="Staff">

- <Skill name="Bolt of Wrath" /> is rather weak but can be used to aggro enemies
  from range.
- <Skill name="Holy Strike" /> can be used to heal, aggro adds from range or to blast <Boon name="Might" /> or
  condi cleanse.
- <Skill name="Symbol of Swiftness" /> places a symbol that will pulse <Boon name="Swiftness" />
  . Due to <Trait name="Writ of Persistence" /> this will also passively heal allies
  within. This skill should be used off-cooldown when on the Staff weapon set.
- <Skill name="Empower" /> is one of your main sources of <Boon name="Might" /> and
  should be used off-cooldown while on Staff. You can give yourself <Boon name="Aegis" /> while
  channeling via <Skill name="Advance"/> for incoming attacks if you are using this skill.
- <Skill name="Line of Warding" /> is a very niche skill. This skill will cancel
  other skills you are currently casting.

</Card>

</GridItem>

<GridItem sm="6">

<Card title="Mace">

- <Skill name="True Strike" /> does decent damage and heals when finishing the auto-attack
  chain.
- <Skill name="Symbol of Faith" /> places a symbol that will pulse <Boon name="Regeneration" />
  . Due to <Trait name="Writ of Persistence" /> this will also passively heal allies
  within. This skill should be used off-cooldown when on the Mace weapon set.
- <Skill name="Protectors Strike" /> grants <Boon name="Aegis" /> if you block an
  attack while channeling it. It can sometimes be useful to run into an attack on
  purpose while channeling this attack to trigger the <Boon name="Aegis" /> application.

</Card>
</GridItem>
<GridItem sm="6">
<Card title="CC Skills">

|                                                                                    |                                                                                     |
| ---------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| <Skill name="Blazing Edge"/>                                                       | 150 damage                                                                          |
| <Skill name="Shield of Absorption"/>                                               | 150 damage                                                                          |
| <Skill name="Bane Signet"/>                                                        | 300 damage                                                                          |
| <Skill name="Hammer of Wisdom"/>                                                   | 200 damage                                                                          |
| <MissingSkill name="Chapter 3: Heated Rebuke"/> in <Skill name="Tome of Justice"/> | 150 damage                                                                          |
| <Skill name="Sanctuary"/>                                                          | 150/s damage for 5 (or 7 with Virtues) seconds,<br/> adding up to 750 (1050) damage |

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

<Skill name="Tome of Justice" />:

- Use this Tome mainly for providing a Fire Field.
- <MissingSkill name="Chapter 1: Searing Spell"/> and <MissingSkill name="Chapter 2: Ignite Burst"/> are mostly useless on <Specialization name="Firebrand" text="Heal Firebrand"/>.
- <MissingSkill name="Chapter 3: Heated Rebuke"/> is a CC. It pulls enemies together and can be used from range.
- <MissingSkill name="Chapter 4: Scorched Aftermath"/> creates a Fire Field that can be used to blast <Boon name="Might"/>.
- <MissingSkill name="Epilogue: Ashes of the Just"/> grants an effect to allies that makes them inflict burning on their next attacks. This scales with <Attribute name="Condition Damage"/> so be careful when using this skill or skip it entirely when running with <Specialization name="Firebrand" text="Condi Firebrands"/>.
- When running Radiance, dealing damage with any skill in this Tome will trigger <Trait name="Wrath of Justice"/> and share the <Attribute name="Condition Damage"/> to allies through <Trait name="Perfect Inscriptions"/>.
- When running Radiance killing certain enemies will lower the cooldown on this Tome. Keep in mind this will not reset the skills in the Tome.
- A common rotation in this Tome is 4-(5)-exit.

<Skill name="Tome of Resolve" />:

- Use this Tome for emergency healing and cleansing.
- <MissingSkill name="Chapter 1: Desert Bloom"/> heals in a cone in front of you.
- <MissingSkill name="Chapter 2: Radiant Recovery"/> heals and cleanses conditions.
- <MissingSkill name="Chapter 3: Azure Sun"/> gives some boons but will rarely be used.
- <MissingSkill name="Chapter 4: Shining River"/> places a healing field that can also be blasted for extra healing.
- <MissingSkill name="Epilogue: Eternal Oasis"/> converts conditions into boons and grants allies an incoming healing modifier.
- When running Virtues entering this Tome also cleanses conditions.
- Common rotations in this Tome are 2-5-4-1-2 for maximum sustained healing or 5-4-2-1-1 for maximum burst healing.

<Skill name="Tome of Courage" />:

- Use this Tome for massive <Boon name="Stability"/>, <Boon name="Resistance"/> or a reflect.
- <MissingSkill name="Chapter 1: Unflinching Charge"/> grants <Boon name="Stability"/>.
- <MissingSkill name="Chapter 2: Daring Challenge"/> inflicts 1 second of <Condition name="Taunt"/> on the enemy which is a 75/s soft CC.
- <MissingSkill name="Chapter 3: Valiant Bulwark"/> places a bubble that reflects incoming projectiles.
- <MissingSkill name="Chapter 4: Stalwart Stand"/> places a field that pulses <Boon name="Resistance"/> to allies. This will help dealing with non-damaging conditions such as <Condition name="Blinded"/> and <Condition name="Slow"/>.
- <MissingSkill name="Epilogue: Unbroken Lines"/> provides <Boon name="Protection"/>, <Boon name="Aegis"/>, <Boon name="Stability"/> as well as extra Toughness.
- There is no set rotation in this Tome, use whatever skills you need for their utility and make sure to press Skill 5 as it is an incredibly strong skill.
- You can camp in this Tome for a few extra seconds to get an extra cast on an important skill, for example a 2nd reflect. However only do this when absolutely needed as you will not have access to the boons and healing your weapon skills provide.

</Card>

<Divider text="Providing Boons"/>

<Card title="Standard Boons">

- <Boon name="Quickness" /> will be provided by using <Skill name="Mantra of Solace" /> (which
  triggers <Trait name="Liberators Vow" /> every 7 seconds algning nicely with the recharge time of the skill with Alacrity and <Trait name="Weighty Terms"/>) and <Skill name="Mantra of Potence" />. You can use <Skill name="Mantra of Potence" /> down to 0 charges whenever you are stacked with your group.
- <Boon name="Might" /> comes from different sources. <Skill name="Empower" /> is
  a big source of <Boon name="Might" /> and should be used off-cooldown whenever
  you are on Staff and on the group. Using <Skill name="Tome of Justice" /> Skill
  4 and blasting it with <Skill name="Holy Strike" /> will also grant <Boon name="Might" /> and
  give others the option to also blast additional <Boon name="Might" />. Using <Skill name="Mantra of Potence" /> as mentioned above will also contribute to <Boon name="Might" /> generation.
- <Boon name="Fury" /> will be provided through <Skill name="Symbol of Vengeance" />
  . Make sure to use this off-cooldown when on the Axe weapon set while people are
  stacked together. Try to use this skill 2 times before swapping to Staff.
- <Boon name="Swiftness" /> mainly comes from <Skill name="Symbol of Swiftness" />
  . Make sure to use this whenever you are on Staff.
- <Boon name="Regeneration" /> will be provided through <Skill name="Mantra of Lore" /> when
  equipped. You can keep 2 charges for condi cleanse while providing some <Boon name="Regeneration" /> whenever it goes back to 3 charges.
- Your main source of <Boon name="Protection"/> comes from <Skill name="Mantra of Solace"/>. You can use it whenever you need it for healing but make sure to use it often enough to trigger <Trait name="Liberator's Vow"/> for <Boon name="Quickness"/>. Some <Boon name="Protection"/> can be provided through <Skill name="Shield of Judgment"/>. <Skill name="Tome of Courage"/> offers some <Boon name="Protection"/> from Skill 5 as well but you do not want to use this Tome just for a small boost in <Boon name="Protection"/>.
- <Boon name="Resolution" /> is provided through <Skill name="Mantra of Solace" /> and <Skill name="Mantra of Liberation" />. If you think you will not need all 3 charges for <Boon name="Stability" />, you can use <Skill name="Mantra of Liberation" /> down to 2 charges in order to to keep up permanent <Boon name="Resolution" /> for the group alongside <Skill name="Mantra of Solace" />.

</Card>

<Card title="Pre-Stacking Boons">

- Provide a Fire Field if needed. <MissingSkill name="Chapter 4: Scorched Aftermath"/> in <Skill name="Tome of Justice"/> provides a short Fire Field. <Skill name="Hallowed Ground"/> provides a longer Fire Field as well as extra <Boon name="Resolution"/> but has to be specifically slotted for pre-stacking.
- <Skill name="Holy Strike" /> to blast <Boon name="Might" />.
- <Skill name="Empower" /> and cast every equipped Mantra as often as you can during the cast.
- <Skill name="Feel My Wrath" /> if you have it equipped.
- <Skill name="Bane Signet" /> if you can start the fight within 10 seconds of usage.
- Take the singularity.
- <Skill name="Empower" /> and use <Skill name="Mantra of Potence" /> once during
  this cast.
- <Skill name="Symbol of Swiftness" /> on the way to the boss and swap to Axe before
  the fight starts to place <Skill name="Symbol of Vengeance" />.

</Card>

<Grid>

<GridItem sm="6">
<Card title="Aegis">

- Correct application of <Boon name="Aegis"/> requires knowledge of the encounters and which attacks are impactful to block.
- <Skill name="Shield of Judgment" /> is your main accessible source of <Boon name="Aegis"/> unless you slot <Skill name="Advance"/>.
- <MissingSkill name="Epilogue: Unbroken Lines"/> in <Skill name="Tome of Courage" /> will also provide <Boon name="Aegis" />. You do not want to enter this Tome only for the single application of <Boon name="Aegis" />, but it si nice to keep in mind when deciding whether to do into the Tome.
- <Skill name="Advance" /> is the only instant-cast skill providing <Boon name="Aegis" /> when chosen and can be used while casting other skills to not get interrupted.
- If Mace is equipped, <Skill name="Protectors Strike"/> also grants <Boon name="Aegis"/> when blocking an attack while channeling.

</Card>
</GridItem>

<GridItem sm="6">
<Card title="Stability">

- Correct application of <Boon name="Stability"/> requires knowledge of the encounters and which attacks and be negated with <Boon name="Stability"/> without taking too much damage.
- Make sure to not apply too much <Boon name="Stability"/> at once. For example if you use <Skill name="Stand Your Ground"/>, you will most likely not need to apply any more <Boon name="Stability"/> until the boon ends since it provides 5 stacks.
- <Skill name="Mantra of Liberation" /> is the easiest access to <Boon name="Stability" />. However keep in mind this only provides one stack.
- The most common utility skill choice for extra <Boon name="Stability"/> is <Skill name="Stand Your Ground"/> but when the longer cooldown of <Skill name="Hallowed Ground"/> is not an issue that one can be used very well on stationary targets.
- You can use <Skill name="Mantra of Liberation"/> and <Skill name="Stand Your Ground"/> while casting <Skill name="Empower"/> if an interrupt is incoming.
- <Skill name="Tome of Courage" /> will also grant access to a very high amount of <Boon name="Stability" /> but is on a fairly long cooldown. Make sure to open the Tome ahead of time due to both the Tome and the skills within having a cast time.
- Make sure to provide enough healing while in <Skill name="Tome of Courage"/> since it replaces your weapons skills. This can be achieved though dodges, utility skills or pre-placed symbols.

</Card>
</GridItem>

</Grid>

<Divider text="Healing"/>

<Card title="Sustained Healing">

- Try to keep your group alive as well as you can through sustained healing and use your burst healing only when it is needed. Keep in mind that active damage mitigation through avoiding attacks or blocking them is very valuable and will help a lot more than a slight increase in healing numbers.
- A lot of consistent healing comes from your symbols through <Trait name="Writ of Persistence"/>. Since you want to use <Skill name="Symbol of Vengeance"/> and <Skill name="Symbol of Swiftness"/> off-cooldown anyways to provide boons, This will give you a nice amount of healing through the entire fight. Same goes for <Skill name="Empower"/>.
- Thanks to <Trait name="Selfless Daring"/> you will also heal at the end of a dodge roll. Make sure to keep enough endurance to avoid mechanics but otherwise feel free to use up dodges for healing.
- If <Skill name="Mantra of Lore"/> is equipped, it will provide <Boon name="Regeneration"/> to your group so make sure to use it down to 2 charges whenever it goes back up to 3.
- If Mace is equipped the auto-attacks will provide a good amount of healing and <Skill name="Symbol of Faith"/> will provide extra <Boon name="Regeneration"/>.

</Card>

<Card title="Burst Healing">

- For emergency situations you have some smaller burst healing options as well
  as your <Skill name="Tome of Resolve" />.
- If you are swapping to Staff when
  healing is needed keep in mind that <Skill name="Symbol of Swiftness" />
  provides healing over time while <Skill name="Holy Strike" /> and
  <Skill name="Empower" /> provide burst healing.
- <Skill name="Bow of Truth" /> is a great option for high burst healing when slotted.
- <Skill name="Tome of Resolve" /> is the biggest source of burst healing and should
  be used as a last resort due to its long cooldown. However due to the cast of both
  opening the Tome and the skills within, make sure to not hesitate too long. If
  the healing does not need to be immediate you can use 2-5-4-1-2, if you need the
  instant burst healing you can use 5-4-2-1-1.

</Card>

<Card title="Condition Cleanse">

- If a lot of condition cleanse is needed you will most likely slot <Skill name="Mantra of Lore"/> which will then be your main reliable source of condition cleanse while also providing some extra <Boon name="Regeneration"/>.
- Blasting Light Fields also causes area condition cleanse. On Staff you can place <Skill name="Symbol of Swiftness"/> and blast it with <Skill name="Holy Strike"/>.
- In <Skill name="Tome of Resolve" /> <MissingSkill name="Chapter 2: Radiant Recovery"/> and <MissingSkill name="Epilogue: Eternal Oasis"/> will cleanse conditions as well,
  however same as with burst healing this is often a last resort. When running Virtues,
  opening this Tome will also cleanse conditions.

</Card>

<Divider text="Videos"/>

<Warning>

Here's two In-Depth video guides on <Specialization name="Firebrand" text="Heal Firebrand" />. Keep in mind that these videos were made before <Skill name="Mantra of solace"/> got changed from giving <Boon name="Aegis"/> to giving <Boon name="Protection"/> and <Boon name="Resolution"/>.

</Warning>

<Grid>

<GridItem sm="6">
  <Video youtube="sxiTwW7oDA8" title="Build Guide by Ascers" />
</GridItem>

<GridItem sm="6">
  <Video youtube="oigZbGyQvbQ" title="Build Guide by Rheyo" />
</GridItem>

</Grid>
