---
title: 'Meta explained'
date: '2021-06-04'
image: './images/preview.png'
description: 'Everything around Meta and the current Meta composition'
hidden: 'false'
---

## What does meta mean?

There are many different interpretations for meta, but we consider **[urbandictionary's](https://www.urbandictionary.com/define.php?term=meta) definition** to be the most accurate one: meta is "a term used in MMO meaning the Most Effective Tactic Available. It's basically what works in a game regardless of what you wish would work."  
Many players are using certain compositions - non meta ones - on a daily basis, which does not elevate them to meta. It might work adequately for their goal - a wipe-less and safe clear - however, it is not the fastest or the most efficient way to play.

The meta for fractals therefore not only encompasses what classes and builds are most effective but also how to play - in other words - what rotation should be used. Example skill rotations for every meta build can be found in the CM-Guides of the respective builds.

## What is necessary to clear fractals efficiently?

It boils down to three important concepts that need to be fulfilled permanently while in combat. Failing one of these will decelerate the speed and smoothness of the run:

1. Boons: 25x<Boon name="Might"/>, <Boon name="Fury"/>, <Boon name="Quickness"/> and <Boon name="Alacrity"/>.
2. Breaking [CC bars](guides/cc-distribution) immediately to gain the damage modifier from <Effect name="Exposed"/>.
3. High and fast single target burst potential.
4. Stacking unique damage buffs such as <Skill name="banesignet"/> or <Skill name="onewolfpack"/>

<Message>
It is vital to understand that these three concepts in conjunction create massive amounts of burst causing phases to only last a few seconds. This is also due to the fact that the <Effect name="Exposed"/> modifier stacks multiplicative with many other damage modifiers. This is the reason why Power builds are generally more powerful in fractals.

The gameplay is therefore much more fast paced compared to raids and requires different thinking and rotations that are tailored around the <Effect name="Exposed"/> window.
</Message>

For T4s there are several other important concepts: 4. Projectile reflects and <Boon name="Stability"/>. 5. High cleave damage. 6. Fast movement using leaps, blinks and teleports to perform skips for the team. 7. <Effect name="Stealth"/> to skip trash mobs.

## What is the current fractal meta?

It is important to note, that each challenge mote encounter has a different most effective tactic available (meta), which means the proposed compositions below are not always the optimal choice per boss. Discretize focuses on clearing daily fractals efficiently, and the proposed compositions brings enough utility to deal with all situations that are occurring in fractals without needing to relog to another character. This allows for a smooth experience in getting a clear done while still being quite effective regardless of the situation.

Most fights in fractals are so short that condi classes or power damage classes with a longer ramp-up time (e.g. <Specialization name="Chronomancer"/>) do not get to the point where they unfold their potential; also slaying potions such as <Item name="powerfulpotionofslayingscarletsarmies"/> favor power burst classes over condi.

There are some fights however that condi benefits more from because of long phases, bosses moving often and the 100% condition damage modifier from <Effect name="Exposed"/> (e.g. Sunqua Peak and Ensolyss). Condition comps are also fantastic for groups who just want to safely clear and don't mind killing bosses slower than power comps do. Also on some T4 fights condition comps outperform power due to incoming damage pressure or the fact you can skip phases when bosses go invulnerable due to condis still ticking (e.g. Sirens Reef and Volcanic).

The recommended composition is often called the <Composition name="_RGB"/> comp, with its condition counterpart being the <Composition name="_CRGB"/> comp.

### <Composition name="_RGB"/>

Currently the RGB comp (or variants of it) is the most optimal comps to be running in a static scenario on 98cm, 99cm (minus Ensolyss) and many of the T4 fractals. It has high overall damage with insane burst, enough CC to delete any breakbar and great boon generation and extension for longer fights. Read below to see why each class is taken;
<Tabs>
<Tab specialization="Renegade">

- Provides permanent <Boon name="Alacrity"/> and around 10 stacks of <Boon name="Might"/>.
- Knocks out large chunks of the CC bar, however, is not solely responsible for CC!
- Provides a unique damage buff <Trait name="assassinspresence"/>, which increases the entire group's ferocity by 150.
- Deals solid damage, can also burst very high making some of your DPS classes sweat.
- Has blinks available from skills such as <Skill name="phasetraversal"/> and <Skill name="deathstrike"/>.
- Provides <Boon name="Stability"/> and projectile destruction on demand (from <Skill name="Legendary Dwarf stance"/> and <Skill name="Legendary Centaur Stance"/> respectively).
- If <Instability name="No Pain, No Gain"/> or <Instability name="Vengeance"/> instability is present it can strip boons with <Skill name="Banish Enchantment"/> (<Skill name="Legendary Demon stance"/>).

[Build](builds/revenant/power-renegade)
</Tab>

<Tab specialization="Firebrand">
* Provides permanent <Boon name="Quickness"/>, on demand <Boon name="Aegis"/> and <Boon name="Resistance"/>.
* Generates a fair share of <Boon name="Fury"/> by <Skill name="Feel my wrath"/> and the sword symbol <Skill name="Symbol of Blades"/>.
* Contributes to CC with <Skill name="banesignet"/>, which is also a **unique damage buff** that increases the entire group's power by 216. 
* Depending on the fight or if the group is confident. <Specialization name="Guardian"/> or <Specialization name="Dragonhunter"/> can be played resulting in very fast kills.
* Provides instant <Condition name="Vulnerability"/> application with <Skill name="swordofjustice"/>, which helps immensely to kill adds quickly at Mama, Siax and Skorvald.
* Has blinks available from skills such as <Skill name="symbol of blades"/>, <Skill name="judges intervention"/> and <Skill name="mercifulintervention"/>.
* Can provide situational <Boon name="Stability"/> for T4s or Artsariiv using <Skill name="Stand your ground"/>.

[Build](builds/guardian/power-firebrand)
</Tab>

<Tab specialization="Dragonhunter">
* Generates a fair share of <Boon name="Fury"/> by <Skill name="Feel my wrath"/> and the sword symbol <Skill name="Symbol of Blades"/>.
* Contributes to CC with <Skill name="banesignet"/>, which is also a **unique damage buff** that increases the entire group's power by 216. 
* Has a high burst with a reasonably short cooldown. Also by prestacking symbols and traps before the fight you can increase your burst a massive amount and destroy any other DPS class out there.
* Provides instant <Condition name="Vulnerability"/> application with <Skill name="swordofjustice"/>, which helps immensely to kill adds quickly at Mama, Siax and Skorvald.
* Has blinks available from skills such as <Skill name="symbol of blades"/>, <Skill name="judges intervention"/> and <Skill name="mercifulintervention"/>.
* Can provide situational <Boon name="Stability"/> for T4s or Artsariiv using <Skill name="Stand your ground"/>.
* If you want to play a different DPS class, this can be swapped out relatively easily.

[Build](builds/guardian/power-Dragonhunter)
</Tab>

<Tab specialization="Soulbeast">
* Contributes to CC with <Skill id="45743"/>, <Skill name="pointblankshot"/> and <Skill name="pathofscars"/>.
* Provides the strongest unique temporary DPS boost, <Skill name="onewolfpack"/>, which helps to meet DPS checks. 
* Provides a unique 5% damage modifier with <Skill name="frost spirit"/>
* Deals very high damage. 
* Allows the team to <Effect name="Stealth"/> in T4s due to the smoke field from the <Skill id="31568" disableText/> [Smokescale](https://wiki.guildwars2.com/wiki/Juvenile_Smokescale) pet.

[Build](builds/ranger/power-soulbeast)
</Tab>
</Tabs>

### <Composition name="_CRGB"/>

As mentioned above on 100cm, Ensolyss and some T4 fights condition comps will outperform power. Currently the CRGB comp (or variants of it) are a solid option for these cases especially if you want an easy run without swapping. Read below to see why each class is taken;

<Tabs>
<Tab specialization="Renegade">
<BuildLink build="Condi Alac Renegade" specialization="Renegade"/> most importantly provides the group with <Boon name="Alacrity"/> and a good amount of <Boon name="Might"/> while also making the DPS classes sweat as you come very close to their damage. It also has great group support with <Skill name="Soulcleaves Summit"/>, <Skill name="Breakrazors Bastion"/> and plenty of CC with <Skill name="Darkrazors Daring"/> and <Skill name="Scorchrazor"/>

[Build](builds/revenant/condi-alac-renegade)
</Tab>

<Tab specialization="Firebrand">
Most importantly <BuildLink build="Condi Firebrand" specialization="Firebrand"/> brings <Boon name="Quickness"/> through <Skill name="Mantra of Potence"/> and if needed <Trait name="Liberators Vow"/>. It also brings massive amounts of hard CC through <Skill name="Sanctuary"/> and a large amount of soft CC through <Skill name="Chains of Light"/>. As well as all of this it brings massive DPS through pre-stacking ashes (Skill 5) in <Skill name="Tome of Justice"/> before the fight begins.

[Build](builds/guardian/condi-firebrand)
</Tab>

<Tab specialization="Soulbeast">
Currently two <BuildLink build="Condi Soulbeast" specialization="Soulbeast"/> are taken as DPS as they each bring an important unique buff. One <BuildLink build="Condi Soulbeast" specialization="Soulbeast"/> brings <Skill name="Sun Spirit"/> and the other brings <Skill name="Moa Stance"/>. <Skill name="Moa Stance"/> is especially important as it allows your <BuildLink build="Condi Alac Renegade" specialization="Renegade"/> to play a very offensive build with minimal boon duration. As well as these buffs <BuildLink build="Condi Soulbeast" specialization="Soulbeast"/> also brings high damage and reasonable CC.

[Build](builds/soulbeast/condi-soulbeast)
</Tab>
</Tabs>

Although this is a decent setup the only essential classes are the <BuildLink build="Condi Alac Renegade" specialization="Renegade"/> and one <BuildLink build="Condi Firebrand" specialization="Firebrand"/>. If you want to replace a class, replacing a <BuildLink build="Condi Firebrand" specialization="Firebrand"/> or <BuildLink build="Condi Soulbeast" specialization="Soulbeast"/> is the place to start with a more offensive DPS class such as <BuildLink build="Condi Deadeye" specialization="Deadeye"/>. It is also not the most optimal comp you can be using, however what is optimal depends on the fight. We suggested the comp above so if you want to run one comp you don't need to swap between fights. If you are in a group that doesn't mind swapping classes you can run the following comps to decrease your killtimes;

Ensolyss - <Specialization name="Renegade" disableText/><Specialization name="Firebrand" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Deadeye" disableText/>

100CM - <Specialization name="Renegade" disableText/><Specialization name="Firebrand" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Deadeye" disableText/>

## Advanced Comps

The previous section shows how well the current meta builds synergize with each other and how important it is that every single player maxes out their role. However, if your group is filled with good players and you're starting to feel capped by the firebrand damage in your daily kills times there are other more advanced comps that can offer some higher celings on certain bosses while still being stable picks for daily usage.

### <Composition name="_RGB"/>

Thanks to the addition of <Skill name = "Moa Stance"/> and the additional <Specialization name="Dragonhunter"/> <Boon name="Quickness"/> is able to be maintained soley from the precast and some coordinated uses of <Skill name = "Feel my Wrath"/>. This means the two <Specialization name="Dragonhunter"/> are able to fully unload their high damage low cooldown bursts to cover for the two <Specialization name="Soulbeast"/> during their downtime. The loss of the <Specialization name="Berserker"/> banners is made of for a bit by the extra <Skill name = "Bane Signet"/> with <Trait name = "Perfect Inscriptions"/> providing a high amount of power when it's needed to phase bosses. The missing precision can be made up for by either gear swaps or a <Specialization name="Soulbeast"/> running <Trait name="spotter"/>.

Pros of the <Specialization name="Soulbeast" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Renegade" disableText/><Specialization name="Dragonhunter" disableText/><Specialization name="Dragonhunter" disableText/> composition:

- Very high burst potential on specific phases
- Good boon duration on demand allowing more aggressive variants of support builds
- Precasting powerful traps such as <Skill name = "Frost Trap"/> and <Skill name = "Procession of Blades"/> allows for strong openers

Cons of the <Specialization name="Soulbeast" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Renegade" disableText/><Specialization name="Dragonhunter" disableText/><Specialization name="Dragonhunter" disableText/> composition:

- Requires fast phasing and transitions or starts to suffer from lack of sustained damage
- Can be gated on certain bosses by <Skill name = "SicEm!"/>
- If fights take to long to complete boons start dropping causing a domino effect making the end of fights potentially ugly

Specific bosses where this comp excels:

- Skorvald
- Artsariiv
- Arkk

<Card title="META Comps Comparison">
| | <Specialization name="Dragonhunter" disableText/><Specialization name="Firebrand" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Renegade" disableText/> **Daily RGB**| <Specialization name="Firebrand" disableText/><Specialization name="Firebrand" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Renegade" disableText/> **Condi RGB** | <Specialization name="Dragonhunter" disableText/><Specialization name="Dragonhunter" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Renegade" disableText/> **Advanced RGB** |
| -- | -- | -- | -- |
| **General Info** | A solid easy to play comp providing plenty of CC and group support. This comp is a great start for people looking to run no healer. Additionally the <Specialization name="Dragonhunter"/> can be replaced with a different [DPS class](/guides/what-should-i-play) relatively easily. | A very easy to play comp that can faceroll all fractals regardless of instabilities. This in most cases will be slower than a power comp though but is a great option if your group wants to clear fractals safely with little effort.  | A more offensive comp that pushes past the DPS barriers that Rainbow comp suffers from. Requires coordinated play and high DPS to phase bosses before boons run out, especially since most of your <Boon name="Quickness"/> comes from the precast. |
| **Difficulty** | Easy | Easy | Advanced |
| **Pros** | Access to an abundant amount of [CC](/guides/cc-distribution)<br/><br/>Keeping up boons is easy with plenty of sources for <Boon name="Might"/> and plenty of sources to keep <Condition name="Vulnerability"/> at 25 stacks.<br/> | Lots of sustain and can deal with [ bad Instabilities](/guides/fractal-basics) very easily.<br/><br/>Comp can run pretty much any [Condition DPS class](/guides/what-should-i-play) and will still work on all fractals. | Very high burst potential on specific phases<br/><br/>Good boon duration on demand allowing more aggressive variants of support builds<br/><br/>Precasting powerful traps such as <Skill name = "Frost Trap"/> and <Skill name = "Procession of Blades"/> allows for strong openers |
| **Cons** | The comp is fairly restrictive due to the fact you want two <Specialization name="Soulbeast"/> for <Skill name="One Wolf Pack"/>, meaning only the <Specialization name="Dragonhunter"/> can be replaced easily. | Some bosses can really start to drag on due to short phases and the time condis take to ramp up.<br/><br/>Outside of 100CM <BuildLink build="Condi Soulbeast" specialization="Soulbeast"/> starts to struggle with it's DPS and while one is valuable with stances and <Skill name="Sun Spirit"/>, the second is often better replaced with something else. | Requires fast phasing and transitions or starts to suffer from lack of sustained damage<br/><br/>Can be gated on certain bosses by <Skill name = "SicEm!"/><br/><br/>If fights take too long to complete boons start dropping causing a domino effect making the end of fights potentially ugly |
| **Strong Bosses** | Skorvald<br/>Artsariiv<br/>Arkk | Ensolyss<br/>Ai, Keeper of the peak | Skorvald<br/>Artsariiv<br/>Arkk |
| **Weaker Bosses** | Ensolyss<br/>Siax | MAMA<br/>Skorvald | Ensolyss |

</Card>

## What and how do I play in PuGs?

PuGs rarely play the meta builds causing people who play meta to deal lower damage and perform worse overall due to the required synergy of the meta classes. If you are one of those that seek to improve we highly encourage you to find a static via our `#looking-for-static` channel on [discord](https://discord.gg/NpS2gN5) or [apply to Discretize](apply). We encourage the fractal community to strive for self-improvement and help in any possible way on our discord server or in-game. However, there are many reasons for why the meta composition does not work well in PuGs.

Some people are for whatever reasons not able to find a static or not committed enough to put time into a game **(which is totally understandable)** and just want a fast and wipe-less clear. For those we recommend a different team composition:
<Tabs>
<Tab title="Condi Comp">
| | |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <Specialization name="Renegade"/> | <br/>The <Specialization name="Renegade"/>'s role is to provide 100% <Boon name="Alacrity"/> uptime, and some <Boon name="Might"/> uptime, strong utilities in terms of heavy crowd control, <Skill name="Soulcleaves Summit"/> for extra team DPS and low to medium power DPS. <Specialization name="Renegade"/> has party heals with <Skill name="Soulcleaves Summit"/> and <Skill name="Breakrazors Bastion"/>. It can also give <Boon name="Stability"/> where needed with <Skill name="Legendary Dwarf Stance"/>. If <Instability name="No Pain, No Gain"/> or <Instability name="Vengeance"/> instability is present use <Skill name="Banish Enchantment"/> (<Skill name="Legendary Demon stance"/>) to strip boons.<br/> |
| <Specialization name="Firebrand" text="Firebrand"/> | <br/>The <Specialization text="Firebrand" name="Firebrand"/> role consists of providing 100% <Boon name="Quickness"/> uptime, utilities in terms of crowd control, reflects, shared <Boon name="Aegis"/>. It can even provide <Boon name="Resistance"/> for a short time with tomes. <br/><br/><Card><Specialization text="Heal Firebrand" name="Firebrand"/> is usually used in PuGs, making fractals effortless even with very bad instability combos. Remember to use the signet share variant found in [our builds section!](/builds/guardian/heal-firebrand) <br/>However due to the high sustain condi comps have <Specialization name="Firebrand" text="Condi Firebrand"/> can be safely used if the group is confident. In depth knowledge of all encounters and builds is required.</Card><br/> |
| <br/><Specialization name="Weaver" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Scourge" disableText/><br/><Specialization name="Firebrand" disableText/><Specialization name="Deadeye" disableText/><Specialization name="Mirage" disableText/> | <br/>Pick any of the condition meta or offmeta classes as damage dealers offered in the [What Should I Play section](/guides/what-should-i-play) |
| <Specialization name="Weaver" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Scourge" disableText/><br/><Specialization name="Firebrand" disableText/><Specialization name="Deadeye" disableText/><Specialization name="Mirage" disableText/> | <br/>Pick any of the condition meta or offmeta classes as damage dealers offered in the [What Should I Play section](/guides/what-should-i-play)<br/><br/> |
| <br/><Specialization name="Weaver" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Scourge" disableText/><br/><Specialization name="Firebrand" disableText/><Specialization name="Deadeye" disableText/><Specialization name="Mirage" disableText/> | <br/>Pick any of the condition meta or offmeta classes as damage dealers offered in the [What Should I Play section](/guides/what-should-i-play) |
</Tab>
<Tab title="Power Comp">
| | |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <Specialization name="Renegade"/> | <br/>The <Specialization name="Renegade"/>'s role is to provide 100% <Boon name="Alacrity"/> uptime, and some <Boon name="Might"/> uptime, strong utilities in terms of heavy crowd control, <Skill name="Soulcleaves Summit"/> for extra team DPS and low to medium power DPS. <Specialization name="Renegade"/> has party heals with <Skill name="Soulcleaves Summit"/> and <Skill name="Breakrazors Bastion"/>. It can also give <Boon name="Stability"/> where needed with <Skill name="Legendary Dwarf Stance"/>. If <Instability name="No Pain, No Gain"/> or <Instability name="Vengeance"/> instability is present use <Skill name="Banish Enchantment"/> (<Skill name="Legendary Demon stance"/>) to strip boons.<br/> |
| <Specialization name="Firebrand" text="Firebrand"/> | <br/>The <Specialization text="Firebrand" name="Firebrand"/> role consists of providing 100% <Boon name="Quickness"/> uptime, utilities in terms of crowd control, reflects, shared <Boon name="Aegis"/> and medium DPS. It can even provide <Boon name="Resistance"/> for a short time with tomes. <br/><br/><Card><Specialization text="Heal Firebrand" name="Firebrand"/> is usually used in PuGs, making fractals effortless even with very bad instability combos. Remember to use <Skill name="Bane Signet"/> share variant found in [our builds section!](/builds/guardian/heal-firebrand)</Card><br/> |
| <Specialization name="Berserker" text="Banner Berserker"/> | <br/>The <Specialization text="Banner Berserker" name="Berserker"/> is the strongest build for <Specialization name="Warrior"/> in fractals, essential to any team, providing party buffs in the form of <Skill id="14405" profession="warrior"/>, <Skill id="14407" profession="warrior"/>. Furthermore, it has excellent single defiance bar damage in <Skill name="Tremor"/> and <Skill name="Headbutt"/>. The build also has medium burst and excellent sustained damage. In case you are playing without a <Specialization name="Weaver"/> and your <Specialization name="Firebrand" text="Heal Firebrand"/> is not able to **maintain 25x <Boon name="Might"/> you can cover the mistake by taking <Skill name="For great justice"/>!** <br/><br/>**<Specialization name="Spellbreaker"/> is not used, only in some T4 encounters like Molten Boss Effigy and Twilight Oasis last boss Amala if you don't have a <Specialization name="Reaper" text="Power Reaper"/> in your group or your <Specialization name="Renegade"/> can't fulfill it's boonstripping role properly with <Skill name="Legendary Demon stance" disableText/> or you are specifically asked to run it.**<br/><br/>If your group are playing condi DPS classes you should also swap since your banners aren't needed or the extra CC.<br/> |
| <Specialization name="Weaver" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Holosmith" disableText/><br/><Specialization name="Chronomancer" disableText/><Specialization name="Reaper" disableText/><Specialization name="Dragonhunter" disableText/> | <br/>Pick any of the power meta or offmeta classes as damage dealers offered in the [What Should I Play section](/guides/what-should-i-play)<br/><br/> |
| <br/><Specialization name="Weaver" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Holosmith" disableText/><br/><Specialization name="Chronomancer" disableText/><Specialization name="Reaper" disableText/><Specialization name="Dragonhunter" disableText/> | <br/>Pick any of the power meta or offmeta classes as damage dealers offered in the [What Should I Play section](/guides/what-should-i-play) |
</Tab>
</Tabs>

<Message>
Although both condition and power builds perform great in PuGs, it is recommended to choose between a condition or power comp before starting. This is because you will want to CC bosses at different times depending on the comp and will affect the damage output of some classes.
</Message>

## What are the differences between the meta and how PuGs play?

One of the biggest differences is that they don't always understand how their actions translate into the game. Learning to do the mechanics correctly, flawlessly, and reliably is - in the beginning - the most important task. PuGs assume the worst usually, so one player in the party is a healer instead.

Another difference is that PuGs often claim that CC is solely the job of the <Specialization name="Renegade"/>. That is not true since <Specialization name="Renegade"/> can only knock out **about half** of the bars. CC is a group effort involving **all** party members!

Many PuGs like to play <Specialization name="Dragonhunter"/>. That is just fine as you don't know what to expect of your fellow PuG mates and you prefer to be self-sufficient. But please use <Skill name="bane signet"/> with <Trait name="perfectinscriptions"/> to CC and provide a party-wide unique damage buff! It is more worth it than the +500 DPS you gain from pressing an auto-attack instead.

<Divider text="What now?"/>

### If you do not know what to play yet we can help you with very basic description of the classes [here](/guides/what-should-i-play) or if you already read that we recommend reading how you can utilize the Defiance bar by breaking it [here!](/guides/cc-distribution)
