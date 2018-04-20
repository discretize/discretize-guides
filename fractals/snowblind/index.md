---
title: "Snowblind"
date: "2018-04-17"
image: "./images/header.jpg"
api: 2952
bosses: 2
difficulties: [{ level: 86, ar: 125 }, { level: 93, ar: 138 }]
tiers: ["T4"]
record: { time: "3:32", by: { name: "Snow Crows", tag: "SC" }, youtube: [{ id: "vvW8-vlCAjI", name: "Yui", specialization: "Chronomancer" }, { id: "5rJTZVRhEqQ", name: "Derpy", specialization: "Tempest" }, { id: "WKvibVHOjsY", name: "Roul", specialization: "Daredevil" }, { id: "5OW6VHot8WQ", name: "Cheezy", specialization: "Druid" }]}
cycle: "Day"
potions: [{ id: 8883, description: "for the Svanir & end boss" }]
sigils: [{ id: 36053 }, { id: 24667, description: "for the Svanir & end boss" }]
consumables: [78978, 49940]
---

## Ice Wall <Item id="8883" text="false"/><Item id="24667" text="false"/>

<Grid>
<Column>
Light up the *Bonfire* with your special action key skill. Kill the spawning *Icebrood Elementals* or use control effects like <Control name="pull"/> to prevent them from extinguishing it and throw *Firewood* into the fire to keep it burning. The stronger the bonfire, the faster the ice wall will melt - usually after around 75 seconds.

If you gain too many stacks of _Hypothermia_ (one every 5 seconds), reset them at the bonfire.

When there are only a few percent remaining, go near the fire to leave combat and pre-equip <Item id="49940"/> to be faster on the bridge.
</Column>
<Column width="6" compact>
<Image src="./images/the_start_area.jpg" title="The start area" compact/>
</Column>
</Grid>

<Tips>
    <Tip specialization="chronomancer">As you don't need crowd control for the next boss, you can take <Skill id="10311"/> for <Boon name="quickness"/> and use <Skill id="10197"/> with <Skill id="10200"/> to teleport the team ahead through the cold.</Tip>
</Tips>

---

## <Boss/> Elemental Source <Item id="8885" text="false"/><Item id="24661" text="false"/>

<Grid>
<Column>
At the start of the fight, light up the five bonfires to remove the 10 stacks of *Rime Shield* from the boss. Each stack reduces its damage taken by 10%.

Every 25%, the Elemental Source casts _Wind Gust_ (icy projectiles) which makes the bonfires loose health. If a bonfire goes down, you will need to throw firewood into it and light it up again using your special action key.

With reflects and high DPS you can simply burst the boss before any bonfire expires.
</Column>

<Column>
<Tips>
    <Tip specialization="chronomancer">Cast double <Skill id="10302"/> with <Skill id="29830"/> into the hitbox of the Elemental Source.</Tip>
    <Tip specialization="spellbreaker">Use <Skill id="45333"/> at 76% to reflect the *Wind Gust* attack.</Tip>
    <Tip specialization="elementalist">With the right angle, you can <Skill id="5697"/> against the Elemental Source.</Tip>
</Tips>
</Column>
</Grid>

<Image src="./images/the_elemental_source.jpg" title="The Elemental Source"/>

---

## Forest <Item id="8883" text="false"/><Item id="24667" text="false"/>

<Grid>
<Column>
After the Elemental Source is destroyed, everyone except the fastest player can `/gg` and wait for the next checkpoint at the cave to trigger. Mobility skills and <Item id="49940"/> are very good here.
</Column>
<Column width="5" compact>
    <Image src="./images/the_icy_forest.jpg" title="The icy forest" compact/>
</Column>
</Grid>

## <Boss red/> Shaman Lornarr Dragonseeker <Item id="8883" text="false"/><Item id="24667" text="false"/>

<Grid>
<Column>
Stack <Boon name="might"/> before the final boss. He gains 3 stacks of *Rime Shield* reducing his incoming damage from the three respawning *Corrupted Ice Crystals*, destroy them before focusing the Shaman.

At 75%, 50% and 25% you will need to kill a summoned _Icebrood Effigy_. Basically dodge every red circle during the fight and break the defiance bars immediately to prevent mechanics.
</Column>

<Column>
<Tips>
    <Tip specialization="chronomancer">Use <Skill id="29526"/> if you have trouble with incoming damage. <Skill id="10302"/> is also a valid option.    
        Pull all mobs together <Skill id="10363"/> whenever possible, usually when the *Icebrood Effigy* spawns.</Tip>
    <Tip specialization="druid">Cast <Skill id="31496"/> against the projectiles.</Tip>
</Tips>
</Column>
</Grid>

<Image src="./images/shaman_lornarr_dragonseeker.jpg" title="Shaman Lornarr Dragonseekers cave"/>
