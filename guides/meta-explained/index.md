---
title: 'Meta explained'
date: '2020-06-14'
image: './images/preview.png'
description: 'Everything around Meta and the current Meta composition'
---

## What does meta mean? 
According to [urbandictionary](https://www.urbandictionary.com/define.php?term=meta) meta is "a term used in MMO meaning the Most Effective Tactic Available. It's basically what works in a game regardless of what you wish would work."  
Seeing players using certain compositions on a daily base does not elevate a strategy to meta. It might work adequately for their goal - a wipe-less and safe clear - however, it is not the fastest or the most efficient way to play. 

The meta for fractals therefore not only subsumes what classes and builds are most effective but also how to play - in other words - what rotation should be used. Example skill rotations for every metaclass can be found in their respective build pages. 

## What is necessary to clear fractals efficiently?
It boils down to three important concepts that need to be fulfilled permanently while in combat. Failing one of these will hurt the smoothness and speed of the run:
1. Boons: 25x<Boon name="might"/>, <Boon name="fury"/>, <Boon name="quickness"/> and <Boon name="alacrity"/>.
2. Breaking [CC bars](guides/cc-distribution) immediately to gain the 50% damage modifier from <Effect name="exposed"/>.
3. High single target burst potential.

For T4s there are several other concepts important:
4. Reflections and <Boon name="stability"/>
5. High cleave damage. 
6. Movement speed with leaps, blinks, and teleports. 
7. <Effect name="Stealth"/> to skip trash mobs. 

## What is the current fractal meta?

It is important to note, that each challenge mote encounter has a different most effective tactic available (meta), which never equals to the proposed composition below. Discretize focuses on clearing daily fractals efficiently, and the proposed composition brings enough utility to deal with all situations, that are occurring in fractals. 

Most fights in fractals are so short, that Condi classes or power damage classes with a longer ramp-up time (e.g. <Specialization name="chronomancer"/>) do not get to the point, where they unfold their potential. Also slaying potions such as <Item name="powerfulpotionofslayingscarletsarmies"/> favor power burst classes over Condi. 

This composition is often called the "daily comp" or also "rainbow comp".

<Tabs>
<Tab specialization="Renegade">
* Provides permanent <Boon name="Alacrity"/> and around 10 stacks of <Boon name="might"/>.
* Knocks out large chunks of the CC bar, however, is not solely responsible for CC! 
* Provides a unique damage buff <Trait name="assassinspresence"/>, which increases the entire group's ferocity by 100. 
* Provides <Skill name="soulcleavessummit"/>, which also boosts the entire group's damage. 
* Deals about half the damage of a DPS class. 
* Has blinks on <Skill name="phasetraversal"/> and <Skill name="deathstrike"/>.
* Provides <Boon name="Stability"/> and projectile destruction on demand.
* If <Instability name="No Pain, No Gain"/> or <Instability name="Vengeance"/> instability is present it can strip boons with <Skill name="Banish Enchantment"/> (<Skill name="Legendary Demon stance"/>).

[Build](builds/revenant/hybrid-renegade)
</Tab>

<Tab specialization="firebrand">
* Provides permanent <Boon name="Quickness"/>, on demand <Boon name="Aegis"/> and <Boon name="Resistance"/>.
* Contributes to CC with <Skill name="banesignet"/>.
* Provides a unique damage buff <Skill name="banesignet"/>, which increases the entire group's power by 216. 
* Deals about 3/4 of the damage of a DPS class. 
* Provides instant <Condition name="vulnerability"/> application with <Skill name="swordsofjustice"/>, which helps immensely to kill adds quickly at Mama, Siax and Skorvald.
* Has blinks on <Skill name="symbol of blades"/> <Skill name="judges intervention"/> and <Skill name="mercifulintervention"/>.
* Can provide situational <Boon name="stability"/> for T4s or Artsariiv.

[Build](builds/guardian/hybrid-firebrand)
</Tab>

<Tab specialization="Berserker">
* Contributes high amount of CC with <Skill name="Headbutt"/> and <Skill name="Tremor"/>.
* Provides unique buffs with <Skill name="bannerofdiscipline"/> and <Skill name="bannerofstrength"/>, which increases the entire group's power, precision, and ferocity by 100. 
* Blasts fire fields to keep up <Boon name="might"/> during the battle. 
* Is a third DPS class on most bosses, which makes it in conjunction with banners a non-brainer to bring. 
* Provides very high cleave DPS in T4s. 

[Build](builds/warrior/banner-berserker)
</Tab>

<Tab specialization="Soulbeast">
* Contributes to CC with <Skill id="45743"/>, <Skill name="pointblankshot"/> and <Skill name="pathofscars"/>.
* Provides the strongest unique temporary DPS boost, <Skill name="onewolfpack"/>, which helps to meet DPS checks. 
* Provides a unique 5% damage modifier with <Skill name="frost spirit"/>
* Deals very high damage. 

[Build](builds/ranger/power-soulbeast)
</Tab>

<Tab specialization="weaver">
* Contributes to CC with <Skill name="updraft"/>.
* Deals very high burst damage, is top DPS on most bosses. 
* Provides and blasts fire fields to keep up <Boon name="might"/> during the battle. 
* Provides AoE <Condition name="blind"/> for T4s via <Skill name="Glyph of storms"/>.
* Can execute various T4s skips with <Skill name="lightningflash"/>.

[Build](builds/ranger/power-soulbeast)
</Tab>
</Tabs>

Removing one of these 5 classes will introduce new issues or be strictly worse. 

Removing <Specialization name="Firebrand"/> + <Specialization name="Renegade"/>: the only other class, which can provide <Boon name="Alacrity"/> is the <Specialization name="Chronomancer"/>. However, <Specialization name="Chronomancer"/> needs <Trait name="Seizethemoment"/> to keep up 5-man <Boon name="Quickness"/> and high amounts of boon duration. CC is comparable to what <Specialization name="Renegade"/> provides but you are lacking <Skill name="bane signet"/> and <Trait name="assassinspresence"/>!

Removing <Specialization name="berserker"/>: without the extra precision from the banners the party would be required to run either more assassins gear or another <Specialization name="soulbeast"/> with <Trait name="spotter"/>. <Specialization name="berserker"/> provides high CC and DPS in CMs and very high cleave damage making it irreplaceable in a daily clear. 

Removing <Specialization name="Soulbeast"/>: indisputable the worst idea as it provides the strongest damage buff in the game (<Skill name="onewolfpack"/>), a unique buff (<Skill name="frost spirit"/>) and the highest burst in the current revision of the game. Also your party loses <Effect name="stealth"/> for T4s. 

Removing <Specialization name="weaver"/>: Not a terrible idea. The <Specialization name="weaver"/> could be replaced with a second <Specialization name="soulbeast"/>. Double <Specialization name="soulbeast"/> works well on most encounters in CMs, requires some fiddling at Siax but is not terrible overall. However, with that composition you will run into cleave problems in T4s. Also missing some blasts from the <Specialization name="weaver"/> and the AoE <Condition name="blind"/>.

This shows how well the current meta builds synergize with each other and how important it is to 

## What and how do I play in PuGs?

PuGs rarely play the meta builds causing people who play meta to deal lower damage and eventually to get frustrated. If you are one of those that seek to improve we highly encourage you to seek a static via our `#looking-for-static` channel on [discord](https://discordapp.com/invite/kaDXhb) or [apply](apply) to Discretize. Please note, that we of course encourage the fractal community to strive for self-improvement and help in any possible way on our discord server or in-game, however, we are very well aware that the proposed composition does not work well in PuGs.

Some people are for what ever reasons not able to find a static or not committed enough to put time into a game (which is totally understandable) and just want a fast and wipe-less clear. For those we recommend following team composition: 
| | |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <Specialization name="renegade"/> | The <Specialization name="renegade"/>'s role is to provide 100% <Boon name="alacrity"/> uptime, and some <Boon name="might"/> uptime, strong utilities in terms of heavy crowd control, <Skill name="Soulcleaves Summit"/> for extra team DPS and low to medium power DPS. <Specialization name="renegade"/> has party heals with <Skill name="Soulcleaves Summit"/> and <Skill name="Breakrazors Bastion"/>. It can also give <Boon name="stability"/> where needed with <Skill name="Legendary Dwarf Stance"/>. If <Instability name="No Pain, No Gain"/> or <Instability name="Vengeance"/> instability is present use <Skill name="Banish Enchantment"/> (<Skill name="Legendary Demon stance"/>) to strip boons.<br/><br/>**For Tier 4 fractals or if you need stronger heals in Challenge Modes we recommend <Specialization text="Heal Renegade" name="renegade"/>.**<br/><br/> |
| <Specialization name="firebrand" text="Firebrand"/> | <br/>The <Specialization text="Firebrand" name="firebrand"/> is perfectly viable in pugs and it's role consists of providing 100% <Boon name="quickness"/> uptime, utilities in terms of crowd control, reflects, shared <Boon name="aegis"/> and medium power DPS. It can even provide <Boon name="resistance"/> for a short time with tomes.<br/><br/>**For Challenge Modes <Specialization text="Heal Firebrand" name="firebrand"/> is only worth taking over <Specialization text="Heal Renegade" name="renegade"/> if your group needs insane heals. For Tier 4 fractals it is perfectly fine, just remember to use <Skill name="Bane Signet"/> share variant found in [our builds section!](/builds/guardian/heal-firebrand)**<br/><br/>  |
| <Specialization name="berserker" text="Banner Berserker"/> | <br/>The <Specialization text="Banner Berserker" name="berserker"/> is the strongest build for <Specialization name="warrior"/> in fractals, essential to any team, providing party buffs in the form of <Skill id="14405" profession="warrior"/>, <Skill id="14407" profession="warrior"/>. Furthermore, it has excellent single defiance bar damage in <Skill name="Tremor"/> and <Skill name="Headbutt"/>, the build also has relatively high burst and excellent sustained damage.<br/><br/>**<Specialization name="spellbreaker"/> is not used, only in some T4 encounters like Molten Boss Effigy and Twilight Oasis last boss Amala if you don't have a <Specialization name="Reaper" text="Power Reaper"/> in your group or your <Specialization name="renegade"/> can't fulfill it's boonstripping role properly with <Skill name="Legendary Demon stance" disableText/> or you are specifically asked to run it.**<br/><br/>  |
| <Specialization name="weaver" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Holosmith" disableText/><br/><Specialization name="firebrand" disableText/><Specialization name="Reaper" disableText/><Specialization name="Dragonhunter" disableText/>  | <br/>Pick any of the meta or offmeta classes as damage dealers offered in the [What Should I Play section](/guides/what-should-i-play)<br/><br/> |
| <Specialization name="weaver" disableText/><Specialization name="Soulbeast" disableText/><Specialization name="Holosmith" disableText/><br/><Specialization name="firebrand" disableText/><Specialization name="Reaper" disableText/><Specialization name="Dragonhunter" disableText/>  | <br/>Pick any of the meta or offmeta classes as damage dealers offered in the [What Should I Play section](/guides/what-should-i-play) |




## What are the biggest problems with the meta in PuGs?
One of the biggest issues with PuGs is, that they fail to understand how their actions translate into the game. Instead of handling mechanics, they slap a <Specialization name="firebrand" text="Heal Firebrand"/> or any other healer on top of the party band-aiding the problem instead of fighting it on its roots. Learning to do the mechanics correctly, flawlessly, and reliably is - in the beginning - the most important task. PuGs assume, that at least one player in the party is not able to fulfill these requirements and use a healer instead. 

Now let's look at Skorvald. Many PuGs manage to bring him down to 40-45% percent with a healer after portaling back to the boss from the last island. The missing damage comes from not having a meta <Specialization name="Firebrand"/>. The same goes for the last phase. Skorvald does his high damaging spin attack because there is not enough damage available. Again, it is the healer's fault. The healer is only needed because it is not contributing as much DPS as the meta counterpart. 

Another huge problem is that PuGs often claim, that CC is solely the job of the <Specialization name="Renegade"/>. That is not true since <Specialization name="Renegade"/> can only knock out about half of the bars. CC is a group effort involving all party members!

Many PuGs like to play <Specialization name="Dragonhunter"/>. That is just fine as you don't know what to expect of your fellow PuG mates and you prefer to be self-sufficient. But please use <Skill name="bane signet"/> with <Trait name="perfectinscriptions"/> to CC and provide a huge party-wide unique buff! It is more worth it than the half a thousand DPS you gain from pressing an auto-attack instead. 


<br><br><br><br>









<Specialization name="weaver" size="large" disableText/><Specialization name="Soulbeast" size="large" disableText/><Specialization name="Firebrand" size="large" disableText/><Specialization name="Renegade" size="large" disableText/><Specialization name="Berserker"  size="large" disableText/>





