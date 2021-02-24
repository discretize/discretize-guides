---
title: 'Meta explained'
date: '2021-02-24'
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
2. Breaking [CC bars](guides/cc-distribution) immediately to gain the 50% damage modifier from <Effect name="Exposed"/>.
3. High and fast single target burst potential.
4. Stacking unique damage buffs such as <Skill name="banesignet"/> or <Skill name="onewolfpack"/>

<Message>
It is vital to understand that these three concepts in conjunction create massive amounts of burst causing phases to only last a few seconds. This is also due to the fact that the 50% <Effect name="Exposed"/> modifier stacks multiplicative with many other damage modifiers. This is the reason why Power builds are generally more powerful in fractals. 

The gameplay is therefore much more fast paced compared to raids and requires different thinking and rotations that are tailored around the <Effect name="Exposed"/> window.
</Message>

For T4s there are several other important concepts:
4. Projectile reflects and <Boon name="Stability"/>.
5. High cleave damage. 
6. Fast movement using leaps, blinks and teleports to perform skips for the team. 
7. <Effect name="Stealth"/> to skip trash mobs. 

## What is the current fractal meta?

It is important to note, that each challenge mote encounter has a different most effective tactic available (meta), which is never equals to the proposed composition below. Discretize focuses on clearing daily fractals efficiently, and the proposed composition brings enough utility to deal with all situations that are occurring in fractals without needing to relog to another character. 

Most fights in fractals are so short that condi classes or power damage classes with a longer ramp-up time (e.g. <Specialization name="Chronomancer"/>) do not get to the point where they unfold their potential; also slaying potions such as <Item name="powerfulpotionofslayingscarletsarmies"/> favor power burst classes over condi. 

This composition is often called the "daily comp" or also "rainbow comp" <Specialization name="Weaver" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Firebrand" disableText/><Specialization name="Renegade" disableText/><Specialization name="Berserker" disableText/>.

<Tabs>
<Tab specialization="Renegade">
* Provides permanent <Boon name="Alacrity"/> and around 10 stacks of <Boon name="Might"/>.
* Knocks out large chunks of the CC bar, however, is not solely responsible for CC! 
* Provides a unique damage buff <Trait name="assassinspresence"/>, which increases the entire group's ferocity by 150. 
* Provides <Skill name="soulcleavessummit"/>, which also boosts the entire group's damage. 
* Deals about half the damage of a DPS class. 
* Has blinks available from skills such as <Skill name="phasetraversal"/> and <Skill name="deathstrike"/>.
* Provides <Boon name="Stability"/> and projectile destruction on demand (from <Skill name="Legendary Dwarf stance"/> and <Skill name="Legendary Centaur Stance"/> respectively).
* If <Instability name="No Pain, No Gain"/> or <Instability name="Vengeance"/> instability is present it can strip boons with <Skill name="Banish Enchantment"/> (<Skill name="Legendary Demon stance"/>).

[Build](builds/revenant/renegade)
</Tab>

<Tab specialization="Firebrand">
* Provides permanent <Boon name="Quickness"/>, on demand <Boon name="Aegis"/> and <Boon name="Resistance"/>.
* Generates a fair share of <Boon name="Fury"/> by <Skill name="Feel my wrath"/> and the sword symbol <Skill name="Symbol of Blades"/>.
* Contributes to CC with <Skill name="banesignet"/>, which is also a **unique damage buff** that increases the entire group's power by 216. 
* The damage depends on the encounter. In Nightmare <Specialization name="Guardian"/> or <Specialization name="Dragonhunter"/> can be played resulting in very high DPS; in Shattered Observatory as <Specialization name="Firebrand"/> 1/2 up to 3/4 of a DPS player. 
* Provides instant <Condition name="Vulnerability"/> application with <Skill name="swordofjustice"/>, which helps immensely to kill adds quickly at Mama, Siax and Skorvald.
* Has blinks available from skills such as <Skill name="symbol of blades"/>, <Skill name="judges intervention"/> and <Skill name="mercifulintervention"/>.
* Can provide situational <Boon name="Stability"/> for T4s or Artsariiv using <Skill name="Stand your ground"/>.

[Build](builds/guardian/firebrand)
</Tab>

<Tab specialization="Berserker">
* Contributes high amount of CC with <Skill name="Headbutt"/> and <Skill name="Tremor"/>.
* Provides unique buffs with <Skill name="bannerofdiscipline"/> and <Skill name="bannerofstrength"/>, which increases the entire group's power, precision, and ferocity by 100. 
* Blasts fire fields to keep up <Boon name="Might"/> during a fight. 
* Provides <Boon name="Fury"/> on some encounters via <Skill name="Battle Standard"/>.
* In slower groups that drop <Boon name="Might"/> or <Boon name="Fury"/> the <Specialization name="Berserker"/> can take <Skill name="For Great Justice"/>.
* Is a third DPS class on most bosses, which makes it in conjunction with banners a non-brainer to bring. 
* Provides very high cleave DPS in T4s. 

[Build](builds/warrior/berserker)
</Tab>

<Tab specialization="Soulbeast">
* Contributes to CC with <Skill id="45743"/>, <Skill name="pointblankshot"/> and <Skill name="pathofscars"/>.
* Provides the strongest unique temporary DPS boost, <Skill name="onewolfpack"/>, which helps to meet DPS checks. 
* Provides a unique 5% damage modifier with <Skill name="frost spirit"/>
* Deals very high damage. 
* Allows the team to <Effect name="Stealth"/> in T4s due to the smoke field from the <Skill id="31568" disableText/> [Smokescale](https://wiki.guildwars2.com/wiki/Juvenile_Smokescale) pet.

[Build](builds/ranger/soulbeast)
</Tab>

<Tab specialization="Weaver">
* Contributes to CC with <Skill name="updraft"/>.
* Deals very high burst damage, is top DPS on most bosses. 
* Provides and blasts fire fields to keep up <Boon name="Might"/> during the battle. 
* Provides conjures (<Skill name="conjurelightninghammer"/>, <Skill name="conjurefrostbow"/> and <Skill name="conjurefierygreatsword"/>) for the team.
* Provides AoE <Condition name="Blinded"/> for T4s via <Skill name="Glyph of storms"/>.
* Can execute various T4s skips with <Skill name="lightningflash"/>.

[Build](builds/elementalist/weaver)
</Tab>
</Tabs>

Removing one of these 5 classes will introduce new issues or be strictly worse. 

Removing <Specialization name="Firebrand"/> + <Specialization name="Renegade"/>: the only other class, which can provide <Boon name="Alacrity"/> is the <Specialization name="Chronomancer"/>. However, <Specialization name="Chronomancer"/> needs to play perfectly to keep up 5-man <Boon name="Quickness"/> and <Boon name="Alacrity"/> and is therefore considered an unreliable boon provider. CC is comparable to what <Specialization name="Renegade"/> provides but lacking <Skill name="bane signet"/> and <Trait name="assassinspresence"/>! Also <Boon name="Might"/> becomes a bigger issue without a <Specialization name="Renegade"/>.

Removing <Specialization name="Berserker"/>: without the extra precision from the banners the party would be required to run either more assassins gear or another <Specialization name="Soulbeast"/> with <Trait name="spotter"/>. <Specialization name="Berserker"/> provides high CC and DPS in CMs and very high cleave damage making it hard to replace in a daily clear. 

Removing <Specialization name="Soulbeast"/>: indisputable the worst idea as it provides the strongest damage buff in the game (<Skill name="onewolfpack"/>), a unique buff (<Skill name="frost spirit"/>) and the highest burst in the current revision of the game. Also your party loses <Effect name="Stealth"/> for T4s. 

Removing <Specialization name="Weaver"/>: not a terrible idea. The <Specialization name="Weaver"/> could be replaced with a second <Specialization name="Soulbeast"/>. Double <Specialization name="Soulbeast"/> works well on most encounters in CMs, requires some fiddling here and there, but is not terrible overall. However, with that composition you will run into cleave problems in T4s. Also missing some blasts from the <Specialization name="Weaver"/> and the AoE <Condition name="Blinded"/> from <Skill name="sandstorm"/>.

This shows how well the current meta builds synergize with each other and how important it is that every single player maxes out their role.

## What and how do I play in PuGs?

Generally you can safely play meta builds in PuGs, but also most condi builds work well. For the sake of not having to regear - if you start for example with a <Specialization name="Scourge" text="Condi Scourge"/> - when you want to get better in fractals, we recommend to pick a meta or offmeta build from our [builds overview](/builds). In contrary to what people might say, condi builds work just fine. At Ensolyss a good group's phase takes about 12 - 15 seconds. <Effect name="Exposed"/> lasts for 5 seconds. That means, there is more than 33% uptime of <Effect name="Exposed"/> during which the group deals 50% more damage. In a unorganized group Ensolyss' phase duration ranges around 40 - 60 seconds which is around 8 - 12% uptime of <Effect name="Exposed"/>. The longer the fight the lower the <Effect name="Exposed"/>-uptime, the more the fight becomes like a golem where power and condi bench equally high numbers.

<Specialization name="Firebrand" text="Condi Firebrand"/> performs extremely well in T4s and is for slower groups (PuGs) in CMs the superior choice over <Specialization name="Firebrand" text="Power Firebrand"/>. It is also worth mentioning that the <Item id="79722"/> (or the <Item id="79608"/> which is a component for the omni potion) provides 15% increased condition damage attribute **and** 15% increased outgoing condition damage. Also <Specialization name="Chronomancer" text="Power Chronomancer"/> can flourish in slower groups or PuGs.

PuGs rarely play the meta builds causing people who play meta to deal lower damage and perform worse overall due to the synergy of the meta classes. If you are one of those that seek to improve we highly encourage you to find a static via our `#looking-for-static` channel on [discord](https://discord.com/invite/G3QDSv) or [apply to Discretize](apply). We encourage the fractal community to strive for self-improvement and help in any possible way on our discord server or in-game. However, there are many reasons for why the meta composition does not work well in PuGs.

Some people are for what ever reasons not able to find a static or not committed enough to put time into a game **(which is totally understandable)** and just want a fast and wipe-less clear. For those we recommend a different team composition: 
| | |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <Specialization name="Renegade"/> | <br/>The <Specialization name="Renegade"/>'s role is to provide 100% <Boon name="Alacrity"/> uptime, and some <Boon name="Might"/> uptime, strong utilities in terms of heavy crowd control, <Skill name="Soulcleaves Summit"/> for extra team DPS and low to medium power DPS. <Specialization name="Renegade"/> has party heals with <Skill name="Soulcleaves Summit"/> and <Skill name="Breakrazors Bastion"/>. It can also give <Boon name="Stability"/> where needed with <Skill name="Legendary Dwarf Stance"/>. If <Instability name="No Pain, No Gain"/> or <Instability name="Vengeance"/> instability is present use <Skill name="Banish Enchantment"/> (<Skill name="Legendary Demon stance"/>) to strip boons.<br/><br/>**For Tier 4 fractals or if you play in an intermediate group in CMs without <Specialization name="Firebrand" text="Heal Firebrand"/> we recommend <Specialization text="Heal Renegade" name="Renegade"/>.**<br/><br/> |
| <Specialization name="Firebrand" text="Firebrand"/> | <br/>The <Specialization text="Firebrand" name="Firebrand"/> is perfectly viable in PuGs and it's role consists of providing 100% <Boon name="Quickness"/> uptime, utilities in terms of crowd control, reflects, shared <Boon name="Aegis"/> and medium DPS. It can even provide <Boon name="Resistance"/> for a short time with tomes. <br/><br/><Card>**0-9000 <Item id="94020"/>**: <Specialization text="Heal Firebrand" name="Firebrand"/> is usually used in PuGs, making fractals effortless even with very bad instability combos. Remember to use <Skill name="Bane Signet"/> share variant found in [our builds section!](/builds/guardian/heal-firebrand) <br/>**18000 and more <Item id="94020"/>**: <Specialization name="Firebrand" text="Power Firebrand"/> and meta strategies are used. In depth knowledge of all encounters and builds is required.<br/> __**NOTE:**__ <Specialization name="Firebrand" text="Condi Firebrand"/> can be played when there is a <Specialization name="Renegade" text="Heal Renegade"/> present in lower KP PuGs (below 18000 <Item id="94020"/>) or you are confident that your group does not need a <Specialization text="Heal Firebrand" name="Firebrand"/>.</Card><br/>      |
| <Specialization name="Berserker" text="Banner Berserker"/> | <br/>The <Specialization text="Banner Berserker" name="Berserker"/> is the strongest build for <Specialization name="Warrior"/> in fractals, essential to any team, providing party buffs in the form of <Skill id="14405" profession="warrior"/>, <Skill id="14407" profession="warrior"/>. Furthermore, it has excellent single defiance bar damage in <Skill name="Tremor"/> and <Skill name="Headbutt"/>. The build also has medium burst and excellent sustained damage. In case you are playing without a <Specialization name="Weaver"/> and your <Specialization name="Firebrand" text="Heal Firebrand"/> is not able to **maintain 25x <Boon name="Might"/> you can cover the mistake by taking <Skill name="For great justice"/>!** <br/><br/>**<Specialization name="Spellbreaker"/> is not used, only in some T4 encounters like Molten Boss Effigy and Twilight Oasis last boss Amala if you don't have a <Specialization name="Reaper" text="Power Reaper"/> in your group or your <Specialization name="Renegade"/> can't fulfill it's boonstripping role properly with <Skill name="Legendary Demon stance" disableText/> or you are specifically asked to run it.**<br/><br/>  |
| <Specialization name="Weaver" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Holosmith" disableText/><br/><Specialization name="Firebrand" disableText/><Specialization name="Reaper" disableText/><Specialization name="Dragonhunter" disableText/>  | <br/>Pick any of the meta or offmeta classes as damage dealers offered in the [What Should I Play section](/guides/what-should-i-play)<br/><br/> |
| <br/><Specialization name="Weaver" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Holosmith" disableText/><br/><Specialization name="Firebrand" disableText/><Specialization name="Reaper" disableText/><Specialization name="Dragonhunter" disableText/>  | <br/>Pick any of the meta or offmeta classes as damage dealers offered in the [What Should I Play section](/guides/what-should-i-play) |

<Message>
Despite  <Specialization name="Renegade" text="Heal Renegade"/> being the superior choice for PuG groups, <Specialization name="Firebrand" text="Heal Firebrand"/> is almost exclusively played even in high KP PuGs. Our recommendation is based on what we spotted to work best with an average team that can carry their weight to some degree (not running away from healer, expecting to be carried), but does not reflect whats being played in game.
</Message>

## What are the differences between the meta and how PuGs play?
One of the biggest difference is, that they don't always understand how their actions translate into the game. Learning to do the mechanics correctly, flawlessly, and reliably is - in the beginning - the most important task. PuGs assume the worst usually, so one player in the party is a healer instead. 

Another difference is that PuGs often claim, that CC is solely the job of the <Specialization name="Renegade"/>. That is not true since <Specialization name="Renegade"/> can only knock out **about half** of the bars. CC is a group effort involving **all** party members!

Many PuGs like to play <Specialization name="Dragonhunter"/>. That is just fine as you don't know what to expect of your fellow PuG mates and you prefer to be self-sufficient. But please use <Skill name="bane signet"/> with <Trait name="perfectinscriptions"/> to CC and provide a party-wide unique damage buff! It is more worth it than the +500 DPS you gain from pressing an auto-attack instead. 

<Divider text="What now?"/>
### If you do not know what to play yet we can help you with very basic description of the classes [here](/guides/what-should-i-play) or if you already read that we recommend reading how you can utilize the Defiance bar by breaking it [here!](/guides/cc-distribution)
