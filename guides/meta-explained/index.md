---
title: Meta explained
date: 2021-09-13T20:56:24.756Z
sections: []
image: ./images/preview.png
description: Everything around Meta and the current Meta composition
hidden: "false"
---

## What does meta mean?  
There are many different interpretations for meta, but we consider **[Urban Dictionary's](https://www.urbandictionary.com/define.php?term=meta) definition** to be the most accurate one. According to Urban Dictionary meta is "*a term used in MMO meaning the Most Effective Tactic Available. It's basically what works in a game regardless of what you wish would work.*"  
Many players are using certain compositions - non meta ones - on a daily basis, which does not elevate them to meta. It might work adequately for their goal - a wipe-less and safe clear - however, it is not the fastest or the most efficient way to play. 

The meta for fractals therefore not only encompasses what classes and builds are most effective but also how to play - in other words - what rotation should be used. Example skill rotations for every meta build can be found in the CM-Guides of the respective builds. 

## What is necessary to clear fractals efficiently?
It boils down to five important concepts that need to be fulfilled permanently while in combat. Failing one of these will decelerate the speed and smoothness of the run:
1. Boons: 25x<Boon name="Might"/>, <Boon name="Fury"/>, <Boon name="Quickness"/> and <Boon name="Alacrity"/>.
2. Conditions: 25x<Condition name="vulnerability"/>, along with any unique condis that your class needs to gain damage modifiers.
3. Breaking [CC bars](guides/cc-distribution) to gain the damage modifier from <Effect name="Exposed"/>.
4. High and fast group single target burst potential.
5. Stacking unique damage buffs such as <Skill name="banesignet"/> or <Skill name="onewolfpack"/>

<Message>
It is vital to understand that these concepts in conjunction create massive amounts of burst causing phases to only last a few seconds (even with condi classes). This is also due to the fact that the <Effect name="Exposed"/> modifier stacks multiplicative with many other damage modifiers. 

The gameplay is therefore much more fast paced compared to raids and requires different thinking and rotations that are tailored around the <Effect name="Exposed"/> window.
</Message>

For T4s there are several other important concepts:
1. Projectile reflects and <Boon name="Stability"/>.
2. High cleave damage. 
3. Fast movement using leaps, blinks and teleports to perform skips for the team. 
4. <Effect name="Stealth"/> to skip trash mobs. 

## What is the current fractal meta?

<Message>
It is important to note, that each challenge mote encounter has a different most effective tactic available (meta), which is often different to the proposed compositions below. Discretize focuses on clearing daily fractals efficiently, and the proposed compositions brings enough utility to deal with all situations that are occurring in fractals without needing to relog to another character. 
</Message>

With the May 11th 2021 balance patch came a huge shake up to the fractal META due to the <Effect name="Exposed"/> change. Instead of being a 50% damage modifier, it was nerfed to 30% power and buffed to 100% condi damage. This has led to condition builds becoming competetive with power builds on many fractals. This has led to a massive shake up of the fractal META and a big split between daily run comps and boss kill comps. For individual bosses power still shines and in most cases can get much faster kills than condi comps can (apart from Ensolyss and 100CM), but for full runs due to the minimal time needed to precast, ease of the comp and the fact it gets similar if not faster times to power runs, for most groups condi comps tend to be a safer pick. 

With this in mind we have two comps we use for our runs. A <Composition name="Daily Condi" composition="Renegade,Firebrand,Firebrand,Soulbeast,Daredevil" roles="Alacrity/CC/DPS,Quickness/CC/DPS,Quickness/CC/DPS,Sun Spirit/CC/DPS,Venoms/CC/DPS" size="small"/> comp for runs where people want to get in and out asap with minimal effort. And a <Composition name="Daily Power" composition="Renegade,Firebrand,Dragonhunter,Soulbeast,Soulbeast" roles="Alacrity/CC/DPS,Quickness/CC/DPS,CC/DPS,Frost Spirit/CC/DPS,Spotter/CC/DPS" size="small"/> comp for days when groups want to get some faster boss kills requiring more co-ordination.

<Message>
For groups such as PuGs or statics less focused on optimal strats and comps the meta changes entirely. To find out more information about what changes click [here](#pug), or scroll down to the bottom of the page.
</Message>

### <Composition name="Daily Condi" composition="Renegade,Firebrand,Firebrand,Soulbeast,Daredevil" roles="Alacrity/CC/DPS,Quickness/CC/DPS,Quickness/CC/DPS,Sun Spirit/CC/DPS,Venoms/CC/DPS" size="small"/>

As mentioned above this comp is ran for an easy daily clear without class swapping. It has high burst for a condi comp with lots of sustain, while being easy to play regardless of instabilities, perfroming well on every encounter. Read below to see why each class is taken;

<Tabs>
<Tab specialization="Renegade">
* Provides permanent <Boon name="Alacrity"/> and around 10 stacks of <Boon name="Might"/>.
* Deals a large amount of CC through <Skill name="Darkrazors Daring"/> and <Skill name="Scorchrazor"/>
* Deals a good amount of damage, coming close or beating other classes on some encounters
* Has blinks available from skills such as <Skill name="phasetraversal"/>

<BuildLink build="Condi Alac Renegade" specialization="Renegade"/>
</Tab>

<Tab specialization="Firebrand">
* Provides permanent <Boon name="Quickness"/>, on demand <Boon name="Aegis"/>, <Boon name="Resistance"/> and some <Boon name="Might"/>.
* Generates a fair share of <Boon name="Fury"/> by <Skill name="Feel my wrath"/> and the sword symbol <Skill name="Symbol of Vengeance"/>.
* Deals a decent amount of DPS with reasonable burst. Also by playing two <Specialization name="Firebrand"/> you can run <Trait name="Legendary Lore"/> for even more damage while still maintaining <Boon name="Quickness"/>.
* Contributes a huge amount of CC with <Skill name="sanctuary"/>.
* Provides a party damage increase through Ashes of the Just (Tome 1-5).
* Can provide situational <Boon name="Stability"/> using <Skill name="Stand your ground"/>, <Skill name="Tome of Courage"/> and <Skill name="Mantra of Liberation"/>.

<BuildLink build="Condi Firebrand" specialization="Firebrand"/>
</Tab>

<Tab specialization="Soulbeast">
* Deals high damage, especially on encounters with longer phases such as Ensloyss and 100CM. 
* Provides strong party DPS boosts through <Skill name="vulture stance"/> while also helping with <Boon name="Might"/> generation. 
* Provides a unique damage modifier with <Skill name="sun spirit"/>
* Can bring <Skill name="Moa Stance"/> allowing your <BuildLink build="Condi Alac Renegade" specialization="Renegade"/> to play a very offensive build with minimal boon duration.
* Brings a good amount of CC with <Skill name="Concussion Shot"/> and <Skill id="46432"/>.


<BuildLink build="Condi Soulbeast" specialization="Soulbeast"/>
</Tab>
<Tab specialization="Daredevil">
* Currently both <Specialization name="Daredevil" text="Condi Daredevil"/> and <Specialization name="Deadeye" text="Condi Deadeye"/> are viable options.
* Both builds have the highest burst of any condi class in the game
* Provides strong party dps buffs through <Skill name="Spider Venom"/> and <Skill name="Skale Venom"/>.
* Provides a massive amount of CC by sharing <Skill name="Basilisk Venom"/>.
* Has high mobility with many blinks, portals and <Effect name="Stealth"/>, great for skips and completing T4s fast.

<BuildLink build="Condi Daredevil" specialization="Daredevil"/> / <BuildLink build="Condi Deadeye" specialization="Deadeye"/>
</Tab>
</Tabs>

### <Composition name="Daily Power" composition="Renegade,Firebrand,Dragonhunter,Soulbeast,Soulbeast" roles="Alacrity/CC/DPS,Quickness/CC/DPS,CC/DPS,Frost Spirit/CC/DPS,Spotter/CC/DPS" size="small"/>
This comp is used when parties want to go for some faster boss kills and would like a run requiring more co-ordination. It brings insanely high burst with lots of CC, whilst still being a safe pick for consistant daily clears. In addition although we often chose to play <BuildLink build="Power Dragonhunter" specialization="Dragonhunter"/>, it is very easy to replace with a different class. Classes such as  <BuildLink build="Power Weaver" specialization="Weaver"/>,  <BuildLink build="Power Berserker" specialization="Berserker"/> and  <BuildLink build="Power Holosmith" specialization="Holosmith"/> are all great picks! Read below to see why each class is taken; 
<Tabs>
<Tab specialization="Renegade">
* Provides permanent <Boon name="Alacrity"/> and around 10 stacks of <Boon name="Might"/>.
* Knocks out large chunks of the CC bar, however, is not solely responsible for CC! 
* Provides a unique damage buff <Trait name="assassinspresence"/>, which increases the entire group's ferocity by 150. 
* Deals solid damage, can also burst very high making some of your DPS classes sweat. 
* Has blinks available from skills such as <Skill name="phasetraversal"/> and <Skill name="deathstrike"/>.
* Provides <Boon name="Stability"/> and projectile destruction on demand (from <Skill name="Legendary Dwarf stance"/> and <Skill name="Legendary Centaur Stance"/> respectively).
* If <Instability name="No Pain, No Gain"/> or <Instability name="Vengeance"/> instability is present it can strip boons with <Skill name="Banish Enchantment"/> (<Skill name="Legendary Demon stance"/>).

<BuildLink build="Power Renegade" specialization="Renegade"/>
</Tab>

<Tab specialization="Firebrand">
* Provides permanent <Boon name="Quickness"/>, on demand <Boon name="Aegis"/> and <Boon name="Resistance"/>.
* Generates a fair share of <Boon name="Fury"/> by <Skill name="Feel my wrath"/> and the sword symbol <Skill name="Symbol of Blades"/>.
* Contributes to CC with <Skill name="banesignet"/>, which is also a **unique damage buff** that increases the entire group's power by 216. 
* Depending on the fight or if the group is confident. <Specialization name="Guardian"/> or <Specialization name="Dragonhunter"/> can be played resulting in very fast kills.
* Provides instant <Condition name="Vulnerability"/> application with <Skill name="swordofjustice"/>, which helps immensely to kill adds quickly at Mama, Siax and Skorvald.
* Has blinks available from skills such as <Skill name="symbol of blades"/>, <Skill name="judges intervention"/> and <Skill name="mercifulintervention"/>.
* Can provide situational <Boon name="Stability"/> for T4s or Artsariiv using <Skill name="Stand your ground"/>.

<BuildLink build="Power Firebrand" specialization="Firebrand"/>
</Tab>

<Tab specialization="Dragonhunter">
* Generates a fair share of <Boon name="Fury"/> by <Skill name="Feel my wrath"/> and the sword symbol <Skill name="Symbol of Blades"/>.
* Contributes to CC with <Skill name="banesignet"/>, which is also a **unique damage buff** that increases the entire group's power by 216. 
* Has a high burst with a reasonably short cooldown. Also by prestacking symbols and traps before the fight you can increase your burst a massive amount and destroy any other DPS class out there.
* Provides instant <Condition name="Vulnerability"/> application with <Skill name="swordofjustice"/>, which helps immensely to kill adds quickly at Mama, Siax and Skorvald.
* Has blinks available from skills such as <Skill name="symbol of blades"/>, <Skill name="judges intervention"/> and <Skill name="mercifulintervention"/>.
* Can provide situational <Boon name="Stability"/> for T4s or Artsariiv using <Skill name="Stand your ground"/>.
* If you want to play a different DPS class, this can be swapped out relatively easily.

<BuildLink build="Power Dragonhunter" specialization="Dragonhunter"/>
</Tab>

<Tab specialization="Soulbeast">
* Contributes to CC with <Skill id="45743"/>, <Skill name="pointblankshot"/> and <Skill name="pathofscars"/>.
* Provides the strongest unique temporary DPS boost, <Skill name="onewolfpack"/>, which helps to meet DPS checks. 
* Provides a unique 5% damage modifier with <Skill name="frost spirit"/>
* Deals very high damage. 
* Allows the team to <Effect name="Stealth"/> in T4s due to the smoke field from the <Skill id="31568" disableText/> [Smokescale](https://wiki.guildwars2.com/wiki/Juvenile_Smokescale) pet.

<BuildLink build="Power Soulbeast" specialization="Soulbeast"/>
</Tab>
</Tabs>

## Advanced Comps

The previous section shows how well the current meta builds synergize with each other and how important it is that every single player maxes out their role. However, if your group is filled with good players and you're starting to feel capped by the firebrand damage in your daily kills times there are other more advanced comps that can offer some higher celings on certain bosses while still being stable picks for daily usage.

### <Composition name="_RGB"/>

Thanks to the addition of <Skill name = "Moa Stance"/> and the additional <Specialization name="Dragonhunter"/> <Boon name="Quickness"/> is able to be maintained soley from the precast and some coordinated uses of <Skill name = "Feel my Wrath"/>. This means the two <Specialization name="Dragonhunter"/> are able to fully unload their high damage low cooldown bursts to cover for the two <Specialization name="Soulbeast"/> during their downtime. The loss of the <Specialization name="Berserker"/> banners is made of for a bit by the extra <Skill name = "Bane Signet"/> with  <Trait name = "Perfect Inscriptions"/> providing a high ammount of power when its needed to phase bosses. The missing precision can be made up for by either gear swaps or a <Specialization name="Soulbeast"/> running <Trait name="spotter"/>.

Pros of the <Specialization name="Soulbeast" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Renegade" disableText/><Specialization name="Dragonhunter" disableText/><Specialization name="Dragonhunter" disableText/> composition:

* Very high burst potential on specific phases
* Good boon duration on demand allowing more aggressive variants of support builds
* Precasting powerful traps such as <Skill name = "Frost Trap"/> and <Skill name = "Procession of Blades"/> allows for strong openers

Cons of the <Specialization name="Soulbeast" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Renegade" disableText/><Specialization name="Dragonhunter" disableText/><Specialization name="Dragonhunter" disableText/> composition:

* Requires fast phasing and transitions or starts to suffer from lack of sustained damage
* Can be gated on certain bosses by <Skill name = "SicEm!"/>
* If fights take to long to complete boons start dropping causing a domino effect making the end of fights potentially ugly

<Card title="META Comps Comparison">
| | <Composition name="Daily Condi" composition="Renegade,Firebrand,Firebrand,Soulbeast,Daredevil" roles="Alacrity/CC/DPS,Quickness/CC/DPS,Quickness/CC/DPS,Sun Spirit/CC/DPS,Venoms/CC/DPS" size="small"/> | <Composition name="Daily Power" composition="Renegade,Firebrand,Dragonhunter,Soulbeast,Soulbeast" roles="Alacrity/CC/DPS,Quickness/CC/DPS,CC/DPS,Frost Spirit/CC/DPS,Spotter/CC/DPS" size="small"/> | <Composition name="_RGB"/> |
| -- | -- | -- | -- |
| **General Info** | A very easy to play comp that can faceroll all fractals regardless of instabilities. This is a great option if your group wants to clear fractals safely with little effort. Unless you are an organised consistant static, overall the run time is often the same or faster than playing power. |  A solid, consistant power comp providing plenty of CC and group support. This comp is a great start for people looking to run no healer and start to decrease their individual boss kill times. Additionally the <Specialization name="Dragonhunter"/> can be replaced with a different [DPS class](/guides/what-should-i-play) relatively easily. | A more offensive comp that pushes past the DPS barriers that Rainbow comp suffers from. Requires co-ordinated play and high DPS to phase bosses before boons run out, especially since most of your <Boon name="Quickness"/> comes from the precast. |
| **Difficulty** | Easy | Medium | Advanced |
| **Pros** | Lots of sustain and can deal with [ bad Instabilities](/guides/fractal-basics) very easily.<br/><br/>Comp can run pretty much any [Condition DPS class](/guides/what-should-i-play) and will still work on all fractals. |Access to an abundant amount of [CC](/guides/cc-distrobution)<br/><br/>Keeping up boons is easy with plenty of sources for <Boon name="Might"/> and plenty of sources to keep <Condition name="Vulnerability"/> at 25 stacks.<br/> | Very high burst potential on specific phases<br/><br/>Good boon duration on demand allowing more aggressive variants of support builds<br/><br/>Precasting powerful traps such as <Skill name = "Frost Trap"/> and <Skill name = "Procession of Blades"/> allows for strong openers |
| **Cons** | Some bosses can really start to drag on due to short phases and the time condis take to ramp up.<br/><br/>Condi comps can be quite boring to play if you enjoy optimizing your gameplay and pushing boss times.<br/> | The comp is fairly restrictive due to the fact you want two <Specialization name="Soulbeast"/> for <Skill name="One Wolf Pack"/>, meaning only the <Specialization name="Dragonhunter"/> can be replaced easily.<br/><br/>In terms of clear time this comp requires a lot more effort and co-ordination to be faster than running a condi comp. Also requiring you to swap to a condi comp for a quick Ensolyss and 100CM kill. <br/> | Requires fast phasing and transitions or starts to suffer from lack of sustained damage<br/><br/>Can be gated on certain bosses by <Skill name = "SicEm!"/><br/><br/>If fights take to long to complete boons start dropping causing a domino effect making the end of fights potentially ugly |
| **Strong Bosses** | Ensolyss<br/>Ai, Keeper of the peak<br/>Artsariiv | Skorvald<br/>Artsariiv<br/>Arkk | Skorvald<br/>Artsariiv<br/>Arkk |
| **Weaker Bosses** | MAMA<br/>Arkk | Ensolyss<br/>Siax | MAMA<br/>Ensolyss |

</Card>

<a name="pug">
## What and how do I play in PuGs?
</a>
PuGs rarely play optimally as a group, causing people to generaly deal lower damage and perform worse overall due to lack of synergy. If you are one of those that seek to improve we highly encourage you to find a static via our `#looking-for-static` channel on [discord](https://discord.gg/NpS2gN5) or [apply to Discretize](apply). We encourage the fractal community to strive for self-improvement and help in any possible way on our discord server or in-game.

Some people are for what ever reasons not able to find a static or not committed enough to put time into a game **(which is totally understandable)** and just want a fast and wipe-less clear. For those we recommend a different, much more open team composition:
<Message>
Although both condition and power builds preform great in PuGs, it is reccomended to choose between a condition or power comp before starting. This is because you will want to CC bosses at different times depending on the comp and will affect the damage output of some classes. It should also be noted that condition comps are significantly easier to play and currently in most cases faster overall than power based comps, with a **significantly higher success rate!**
</Message>

<Tabs>
<Tab title="Condi Comp">
| | |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <BuildLink build="Condi Alac Renegade" specialization="Renegade"/> | <br/>The <Specialization name="Renegade"/>'s role is to provide 100% <Boon name="Alacrity"/> uptime, and some <Boon name="Might"/> uptime, strong utilities in terms of heavy crowd control and decent DPS on its own. Although <BuildLink build="Condi Alac Renegade" specialization="Renegade"/> deals more damage, playing <BuildLink build="Power Renegade" specialization="Renegade"/> is also acceptable.|
| <BuildLink build="Heal Firebrand" specialization="Firebrand"/> | <br/>The <Specialization text="Firebrand" name="Firebrand"/> role consists of providing 100% <Boon name="Quickness"/> uptime, utilities in terms of crowd control, reflects, shared <Boon name="Aegis"/>. It can even provide <Boon name="Resistance"/> for a short time with tomes. <br/><br/><Card><Specialization text="Heal Firebrand" name="Firebrand"/> is usually used in PuGs, making fractals effortless even with very bad instability combos. However due to the high sustain condi comps have <BuildLink build="Seraph Firebrand" specialization="Firebrand"/> can be safely used for more interactive gameplay, or even <BuildLink build="Condi Firebrand" specialization="Firebrand"/> if the group is confident. In depth knowledge of all encounters and builds is required.</Card><br/>      |
| <br/><Specialization name="Weaver" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Scourge" disableText/><br/><Specialization name="Firebrand" disableText/><Specialization name="Deadeye" disableText/><Specialization name="Mirage" disableText/>  | <br/>Pick any of the condition meta or offmeta classes as damage dealers offered in the [What Should I Play section](/guides/what-should-i-play) |
| <Specialization name="Weaver" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Scourge" disableText/><br/><Specialization name="Firebrand" disableText/><Specialization name="Deadeye" disableText/><Specialization name="Mirage" disableText/>  | <br/>Pick any of the condition meta or offmeta classes as damage dealers offered in the [What Should I Play section](/guides/what-should-i-play)<br/><br/> |
| <br/><Specialization name="Weaver" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Scourge" disableText/><br/><Specialization name="Firebrand" disableText/><Specialization name="Deadeye" disableText/><Specialization name="Mirage" disableText/>  | <br/>Pick any of the condition meta or offmeta classes as damage dealers offered in the [What Should I Play section](/guides/what-should-i-play) |
</Tab>
<Tab title="Power Comp">
| | |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <BuildLink build="Power Renegade" specialization="Renegade"/> | <br/>The <Specialization name="Renegade"/>'s role is to provide 100% <Boon name="Alacrity"/> uptime, and some <Boon name="Might"/> uptime, strong utilities in terms of heavy crowd control and decent DPS on its own. It can also give <Boon name="Stability"/> where needed with <Skill name="Legendary Dwarf Stance"/>. If <Instability name="No Pain, No Gain"/> or <Instability name="Vengeance"/> instability is present use <Skill name="Banish Enchantment"/> (<Skill name="Legendary Demon stance"/>) to strip boons.<br/> |
| <BuildLink build="Heal Firebrand" specialization="Firebrand"/> | <br/>The <Specialization text="Firebrand" name="Firebrand"/> role consists of providing 100% <Boon name="Quickness"/> uptime, utilities in terms of crowd control, reflects, shared <Boon name="Aegis"/> and medium DPS. It can even provide <Boon name="Resistance"/> for a short time with tomes. <br/><br/><Card><Specialization text="Heal Firebrand" name="Firebrand"/> is usually used in PuGs, making fractals effortless even with very bad instability combos. Remember to use <Skill name="Bane Signet"/> share variant found in [our builds section!](/builds/guardian/heal-firebrand). However <BuildLink build="Seraph Firebrand" specialization="Firebrand"/> can be safely used for more interactive gameplay,</Card><br/> |
| <BuildLink build="Power Berserker" specialization="Berserker"/> | <br/>The <Specialization text="Banner Berserker" name="Berserker"/> is the strongest build for <Specialization name="Warrior"/> in fractals, essential to any team, providing party buffs in the form of <Skill id="14405" profession="warrior"/>, <Skill id="14407" profession="warrior"/>. Furthermore, it has excellent single defiance bar damage in <Skill name="Tremor"/> and <Skill name="Headbutt"/>. The build also has medium burst and excellent sustained damage. In case you are playing without a <Specialization name="Weaver"/> and your <Specialization name="Firebrand" text="Heal Firebrand"/> is not able to **maintain 25x <Boon name="Might"/> you can cover the mistake by taking <Skill name="For great justice"/>!** <br/><br/>**<Specialization name="Spellbreaker"/> is not used, only in some T4 encounters like Molten Boss Effigy and Twilight Oasis last boss Amala if you don't have a <Specialization name="Reaper" text="Power Reaper"/> in your group or your <Specialization name="Renegade"/> can't fulfill it's boonstripping role properly with <Skill name="Legendary Demon stance" disableText/> or you are specifically asked to run it.**<br/><br/>If your group are playing condi DPS classes you should also swap since your banners aren't needed or the extra CC.<br/>  |
| <Specialization name="Weaver" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Holosmith" disableText/><br/><Specialization name="Chronomancer" disableText/><Specialization name="Reaper" disableText/><Specialization name="Dragonhunter" disableText/>  | <br/>Pick any of the power meta or offmeta classes as damage dealers offered in the [What Should I Play section](/guides/what-should-i-play)<br/><br/> |
| <br/><Specialization name="Weaver" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Holosmith" disableText/><br/><Specialization name="Chronomancer" disableText/><Specialization name="Reaper" disableText/><Specialization name="Dragonhunter" disableText/>  | <br/>Pick any of the power meta or offmeta classes as damage dealers offered in the [What Should I Play section](/guides/what-should-i-play) |
</Tab>
</Tabs>

## What are the differences between the meta and how PuGs play?
One of the biggest difference is, that they don't always understand how their actions translate into the game. Learning to do the mechanics correctly, flawlessly, and reliably is - in the beginning - the most important task. PuGs assume the worst usually, so one player in the party is a healer instead. 

Another difference is that PuGs often claim, that CC is solely the job of the <Specialization name="Renegade"/>. That is not true since <Specialization name="Renegade"/> can only knock out **about half** of the bars. CC is a group effort involving **all** party members, **EVEN IN CONDI COMPS!**

Many PuGs like to play <Specialization name="Firebrand"/> or <Specialization name="Scourge"/>. That is just fine as you don't know what to expect of your fellow PuG mates and you prefer to be self-sufficient. But please dont be afraid to run more supportive skills such as <Skill name="Sanctuary"/> or <Skill name="Spectral Grasp"/>! It is more worth it than the +500 DPS you gain from having a minor dps utility instead. 

<Divider text="What now?"/>
### If you do not know what to play yet we can help you with very basic description of the classes [here](/guides/what-should-i-play) or if you already read that we recommend reading how you can utilize the Defiance bar by breaking it [here!](/guides/cc-distribution)
