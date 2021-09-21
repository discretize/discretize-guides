---
title: 'Snowblind'
date: '2021-02-24'
image: './images/header.jpg'
group: 'T4'
api: 2952
bosses: 2
difficulties: [{ level: 86, ar: 125 }, { level: 93, ar: 137 }]
record:
  {
    time: '3:32',
    by: [{ name: 'Snow Crows', tag: 'SC' }],
    youtube:
      [
        { id: 'vvW8-vlCAjI', name: 'Yui', specialization: 'Chronomancer' },
        { id: '5rJTZVRhEqQ', name: 'Derpy', specialization: 'Tempest' },
        { id: 'WKvibVHOjsY', name: 'Roul', specialization: 'Daredevil' },
        { id: '5OW6VHot8WQ', name: 'Cheezy', specialization: 'Druid' },
      ],
  }
cycle: 'Night'
potions: [{ id: 8883, description: 'for the Svanir & end boss' }]
sigils: [{ id: 36053 }, { id: 24667, description: 'for the Svanir & end boss' }]
consumables: [78978, 49940]
---

## Ice Wall <Item id="8883" disableText/><Item id="24667" disableText/>

<Grid>
<GridItem sm="8">
Light up the *Bonfire* with your special action key skill. Kill the spawning *Icebrood Elementals* or use control effects like <Control name="Pull"/> to prevent them from extinguishing it and throw *Firewood* into the fire to keep it burning. The stronger the bonfire, the faster the ice wall will melt - usually after around 75 seconds.

If you gain too many stacks of _Hypothermia_ (one every 5 seconds), reset them by standing at the bonfire.

When there are only a few percent remaining, go near the fire to leave combat and pre-equip <Item id="49940"/> to be faster on the bridge.
</GridItem>

<GridItem sm="4">

<MDImage src="fractals/snowblind/images/the_start_area.jpg" caption="The start area"/>

</GridItem>
</Grid>

<Tabs>
<Tab specialization="Weaver">
Cast a <Skill name="Conjure Fiery Greatsword"/> for <Specialization name="Renegade"/> at the wall right before it melts.
</Tab>

<Tab specialization="Renegade">
First swap your legend to <Skill name="Legendary Centaur Stance"/> / <Skill name="Legendary Renegade Stance"/>, but stay on <Skill name="Legendary Renegade Stance" disableText/>. Place <Item id="78978"/> then  skip to the first bonfire on the left with anything like: <Skill name="Conjure Fiery Greatsword"/> or <Item id="49940"/> or <Item id="85244"/>, place portal exit when you lit the fire, then go to the *Elemental source*, deplete your energy below 10 for extra 25 energy on legend swap, swap to <Skill name="Legendary Centaur Stance"/>, what you need to do is in the next paragraph with video.
</Tab>
</Tabs>

---

<Grid>
<GridItem sm="6">
## Elemental Source

At the start of the fight, light up the five bonfires to remove the 10 stacks of _Rime Shield_ from the boss. Each stack reduces its damage taken by 10%.

Every 25%, the Elemental Source casts _Wind Gust_ (icy projectiles) which makes the bonfires loose health. If a bonfire goes down, you will need to throw firewood into it and light it up again using your special action key.

With reflects and high DPS you can simply burst the boss before any bonfire expires. Note that the Elemental Source is a structure so no potion or sigil will work on it.
</GridItem>

<GridItem sm="6">

<MDImage src="fractals/snowblind/images/the_elemental_source.jpg" caption="The Elemental Source"/>

</GridItem>

<GridItem sm="12">
<Tabs>
<Tab specialization="Renegade">
Place a bubble on top of the *Elemental Source*, absorbing **EVERY** projectile so you do not have to dodge anymore.

<Video title="Renegade bubble" youtube="ORcJL1p1pN8"/>
</Tab>

<Tab specialization="Weaver">
With the right angle, you can <Skill id="5697"/> against the Elemental Source.
</Tab>
</Tabs>
</GridItem>
</Grid>

---

<Grid>
<GridItem sm="5">

<MDImage src="fractals/snowblind/images/the_icy_forest.jpg" caption="The icy forest"/>

</GridItem>

<GridItem sm="7">
## Forest <Item id="8883" disableText/><Item id="24667" disableText/>

After the Elemental Source is destroyed, everyone except the fastest player can `/gg` and wait for the next checkpoint at the cave to trigger. Mobility skills and <Item id="85244"/> / <Item id="49940"/> are very good here, **skip videos below**.
</GridItem>

<GridItem sm="12">
<Tabs>
<Tab specialization="Soulbeast">
<Video title="Ranger skip" timestamp="100" youtube="3Zc_ZJqPD0s"/>
</Tab>

<Tab specialization="Berserker">
<Video title="Warrior skip" timestamp="21" youtube="29qQ2xU1YHk"/>
</Tab>

<Tab specialization="Guardian">
<Video title="Guardian skip" timestamp="258" youtube="MmJTsOhdQeo"/>
</Tab>

<Tab specialization="Daredevil">
<Video title="Thief skip" timestamp="125" youtube="Alpgs_GaZV0"/>
</Tab>
</Tabs>
</GridItem>
</Grid>

<Grid>
<GridItem sm="8">
## Shaman Lornarr Dragonseeker <Item id="8883" disableText/><Item id="24667" disableText/>

Stack <Boon name="Might"/> before the final boss. Make sure to dodge into the boss room to avoid getting <Condition name="Chilled"/> from the icy bolts.

He gains 3 stacks of _Rime Shield_ reducing his incoming damage from the three respawning _Corrupted Ice Crystals_, destroy them before focusing the Shaman.

At 75%, 50% and 25% you will need to kill a summoned _Icebrood Effigy_. Basically dodge every red circle during the fight and break the defiance bars immediately to prevent mechanics.

<MDImage src="fractals/snowblind/images/shaman_lornarr_dragonseeker.jpg" caption="Shaman Lornarr Dragonseekers cave"/>
</GridItem>

<GridItem sm="4">
<Tabs>
<Tab specialization="Renegade">
Take either <Skill name="Legendary Dwarf Stance"/> or <Skill name="Legendary Centaur Stance"/> as secondary legend, both have their advantages. <Skill name="Legendary Dwarf Stance" disableText/> can give <Boon name="Stability"/> while <Skill name="Legendary Centaur Stance" disableText/> can give more condition cleanse and projectile absorption with <Skill name="Protective solace"/>.
</Tab>
</Tabs>

<Tabs>
<Tab specialization="Tempest">
Use <Specialization name="Tempest"/> <Skill id="22572"/> for better cleave. The range of <Skill id="22572"/> is sufficient to hit the boss, the mobs in the middle and at least one *Corrupted Ice Crystals* at the side, so make sure you aim accordingly.
</Tab>

<Tab specialization="Berserker">
Equip a greatsword and <Skill name="blood reckoning"/> for double <Skill name="arc divider"/>. Use your greatsword to cleave down the adds quickly!
</Tab>
</Tabs>
</GridItem>
</Grid>
