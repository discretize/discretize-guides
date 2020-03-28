---
title: 'Volcanic'
date: '2020-03-27'
image: './images/header.jpg'
group: 'T4'
api: 2989
bosses: 2
difficulties: [{ level: 92, ar: 137 }]
record:
  {
    time: '3:48',
    by: { name: 'Quantify', tag: 'qT' },
    youtube:
      [{ id: 'un7xbSP-7KI', name: 'Deathly', specialization: 'Chronomancer' }],
  }
cycle: 'Night'
potions:
  [
    { id: 8890, description: 'for all the Grawl enemies' },
    { id: 8885, description: 'for the Imbued Shaman endboss' },
  ]
sigils:
  [
    { id: 36053 },
    { id: 24648, description: 'for the Grawl enemies' },
    { id: 24661, description: 'for the Imbued Shaman endboss' },
  ]
consumables: [78978, 49940]
---

## Start: Grawl slaughter! <Item id="8890" disableText/><Item id="24648" disableText/>  

<Grid>
<GridItem sm="6">

While four people kill the respawning Grawls to fill the progress bar, one person (usually the <Specialization name="Renegade"/> but anyone can run) should run ahead to the next area and trigger the checkpoint at the *Grawl Shaman*. This way, everyone can portal after the section is completed and resurrect to skip the Boulder passage. <Specialization name="elementalist"/> can precast strong DPS skills like <Skill id="5737"/> and <Skill id="5501"/> on the spawn locations of the Grawls, since the mobs take damage seconds before they actually appear. You can use <Skill id="5738"/> to reduce incoming damage and <Skill id="22572"/> to cleave the adds faster. <Specialization name="berserker"/> can equip a greatsword and <Skill name="bloodreckoning"/> for 2x <Skill name="arcdivider"/>! 
</GridItem>

<GridItem sm="6">
<Image src="./images/the_start_area.jpg" caption="The start area"/>
</GridItem>

<GridItem sm="12">
<Tabs> 
<Tab specialization="guardian">
<Video title="Guardian skip" timestamp="403" youtube="MmJTsOhdQeo"/>  
</Tab>

<Tab specialization="ranger">
<Video title="Ranger skip" timestamp="202" youtube="3Zc_ZJqPD0s"/>
</Tab>

<Tab specialization="Warrior">
<Video title="Warrior skip" timestamp="45"  youtube="REnmbN7sZFQ"/>
</Tab>

</Tabs>
</GridItem>
</Grid>

---



<Grid>
<GridItem sm="5">
<Tabs>
<Tab specialization="weaver">
Use either <Skill id="5683"/> and <Skill id="5686"/> or <Skill id="5671"/> to keep the *Veteran Grawl Shamans* in your <Skill id="5548"/>, <Skill id="43762"/> and <Skill id="41125"/>.    
        If everyone LoS'ed the boss correctly, he will be close enough to <Skill id="5697"/> against the altar he stood on.
</Tab>
</Tabs>
</GridItem>

<GridItem sm="7">
## Grawl Shaman <Item id="8890" disableText/><Item id="24648" disableText/> 
 
Kill the _Veteran Grawl Shamans_ to prevent them from sacrificing the captives. Control effects like <Control name="stun"/> and <Condition name="immobile"/> hinder them from reaching the edge.

You will need to throw eight _Infused Stones_ at the bubble protecting the Grawl Shaman boss to break it and make him vulnerable. The stones spawn on rockfalls, wait until the falling animation finishes and dodge into it to collect it. You can ping the Grawl Shaman (`Ctrl + T`) for easy targeting.

After the bubble is broken, stand below the boss to LoS him and he will come down immediately. Throw another _Infused Stone_ at him if his bubble reappears during the fight.
</GridItem>
</Grid>

<Image src="./images/the_grawl_shaman.jpg" caption="The Grawl Shaman"/>  

---

## Imbued Shaman <Item id="8885" disableText/><Item id="8886" disableText/><Item id="24661" disableText/>

<Grid>
<GridItem sm="8">
**Take the shortcut on the right-hand side down, jump into the lava then run and jump to the final platform to trigger the next checkpoint**, then everyone uses `/gg` to reset cooldowns. Walk until the end of the boardwalk, stack <Boon name="might"/> and jump down to the Imbued Shaman (the bat follows you to the end of the walkway, but it takes here 10 or more seconds to reach it. Make sure you have the boons stacked and are on the correct weapon before she flies in you fire field).

Every 25% health, it gains a protective bubble and starts moving to a random villager. It will heal for about 20% health if it reaches their target, so break the bubble quickly by casting 40 offensive abilities while targeting the Imbued Shaman (you actually don't have to hit him). Try to keep him in the center as the villagers are located at the edge of the area.

He will also spawn 10-30 _Lava Elementals_ during this phase, kill them fast as they cast a lot of projectiles and inflict high <Condition name="burning"/> stacks on the team. Note that repeated jumping prevents the application of <Condition name="burning"/> from the floor.

Avoid the _Bash_ and _Wing Buffer_ attacks (they <Control name="knockback"/>) and utilize conditions clears & reflects to finish the fractal successfully.

<Image src="./images/the_imbued_shaman.jpg" caption="The Imbued Shaman"/>
</GridItem>


<GridItem sm="4">
<Tabs>
<Tab specialization="Renegade">
Use <Skill name="Legendary Demon Stance"/> / <Skill name="Legendary Renegade Stance"/> to spam <Boon name="Resistance"/> after the bosses bubble phase.
</Tab>
</Tabs>
 
<Tabs>  
<Tab specialization="Firebrand">
Use Tome 3 skill 4 for party wide <Boon name="Resistance"/>!
</Tab>  
</Tabs> 
 
<Tabs>
<Tab specialization="Elementalist">
Take <Skill id="5507"/> for an additional condition cleanse. Use <Skill id="22572"/> to cleave the Lava Elementals faster.
</Tab>
</Tabs>
 
<Tabs>
<Tab specialization="ranger">
Use <Skill id="12489"/> periodical condition clear. 
</Tab>
</Tabs>
</GridItem>
</Grid>


