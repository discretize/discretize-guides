---
title: 'Uncategorized'
date: '2020-07-22'
image: './images/header.jpg'
group: 'T4'
api: 2939
bosses: 3
difficulties: [{ level: 79, ar: 113 }, { level: 91, ar: 134 }]
record:
  {
    time: '3:16',
    by: { name: 'Happens', tag: 'hP' },
    youtube:
      [
        { id: 'fMB69jScHWg', name: 'Never Moa', specialization: 'Tempest' },
        { id: '1HptYqPzPZE', name: 'Midnightz', specialization: 'Tempest' },
      ],
  }
cycle: 'Day'
potions: [{ id: 8887, description: 'for Old Tom and the Raving Asura' }]
sigils:
  [
    { id: 24868 },
    { id: 24615 },
    { id: 24672, description: 'for Old Tom and the Raving Asura' },
  ]
consumables: [78978, 49940, 8764, 8801]
---

<Grid>
<GridItem sm="7">
## Start

**Option 1 (recommended):** The whole party stacks <Effect name="stealth"/> and skips together until the holding area. If a single Harpy spawned immediately at the begin, you can kill it before stealthing.

**Option 2:** Anyone with a <Item id="78978"/> skips alone and teleports the team to the holding area.

## Holding Area

Stack <Boon name="might"/> before destroying the _Power Generator_, stack in the structure on the left side of the room and let your <Specialization name="renegade"/> destroy the _Power Generator_.

Then kill the Rabbit, the Bandit Saboteur, the Flame Legion Fire Shaman and finally the Ettin. Try to keep all mobs together on the Flame Legion Fire Shaman to maximize cleave damage, but do not get caught in the Ettin's _Massive Smash_ attack. Reflects are strong here as well, especially against the Fire Shaman's projectiles.

<Tabs>
<Tab specialization="Weaver">
If positioned correctly, you can <Skill id="5697"/> against the wall.
</Tab>
<Tab specialization="Berserker">
Equip a greatsword and <Skill name="blood reckoning"/> for double <Skill name="arc divider"/>. Use your greatsword to cleave down the adds quickly! Use [consumables](/guides/consumables) to CC!
</Tab>
</Tabs>
</GridItem>

<GridItem sm="5">
<Tabs>

<Tab specialization="Daredevil">
Use the smoke field from <Skill id="13113"/> or <Skill name="Smoke Screen" profession="Daredevil"/> or simply cast <Skill id="13117"/> to stack <Effect name="stealth"/>.    
        <Skill id="13065"/> is also useful against the Holding Area bosses.
</Tab>

<Tab specialization="Soulbeast">
Use <Skill id="31568"/> from your Smokescale pet to stack <Effect name="stealth"/>.
</Tab>
</Tabs>

<Image src="./images/harpies_jp.jpg" caption="Harpies protect their jumping puzzle"/>
</GridItem>
</Grid>

---

<Grid>
<GridItem sm="8">
## Pulsing Orbs

You can skip this part with <Specialization name="Weaver"/> or <Specialization name="Daredevil"/> shown in the videos down below or you can just walk past the three Harpies (no <Effect name="stealth"/> needed) and run up the ramp towards Old Tom. You can dodge through or reflect the pulsing orbs and even skip the last part by walking on the left wall.
</GridItem>

<GridItem sm="4">
<Image src="./images/pulsing_orbs.jpg" caption="The ramp up"/>
</GridItem>

<GridItem sm="12">
<Tabs>
<Tab specialization="Weaver">
<Message>  
Use the same starting spot as in the <Specialization name="Daredevil"/>'s video, not where the video shows, the end point is the same!
</Message> 

<Video title="Ele skip" timestamp="79" youtube="OjUvCp2h_04"/>
</Tab>  
  
<Tab specialization="Daredevil">
<Video title="Daredevil skip" timestamp="125" youtube="Alpgs_GaZV0"/>
</Tab>
</Tabs> 
</GridItem>

<GridItem sm="12">
<Message> 
If you skipped don't forget to trigger the "Reach the top" checkpoint (red dot on the mini map) to prevent the fractal from bugging.    
</Message> 
</GridItem> 
 
<GridItem sm="4"> 
<Image src="./images/old_tom.jpg" caption="Old Tom"/>
</GridItem>

<GridItem sm="8">
## Old Tom <Item id="8887" disableText/><Item id="24672" disableText/>  
  
Stack <Boon name="might"/> before Old Tom and simply nuke him down. Be careful with <Effect name="agony"/> and try to let Pets and Illusions soak the green projectiles when his defiance bar is not broken. <Specialization name="Soulbeast"/> can use <Skill id="12489"/> and take <Skill name="Bear stance"/> with the trait <Trait name="Leader of the Pack"/> almost nullifies the Poison from the green projectiles.
</GridItem>
</Grid>

<GridItem sm="12"> 
<Tabs>
<Tab specialization="guardian">
<Video title="Guardian skip" youtube="MmJTsOhdQeo"/>
</Tab>
<Tab specialization="Soulbeast">
<Video title="Soulbeast skip" timestamp="225"  youtube="3Zc_ZJqPD0s"/> 
</Tab>
<Tab specialization="Berserker">
<Video title="Berserker skip" youtube="3DPh3uRNKIk"/>
</Tab>
</Tabs>
</GridItem>

---

<Grid>
<GridItem sm="5">
## Raving Asura <Item id="8887" disableText/><Item id="24672" disableText/>  
  
If no one did a portal to above, stack <Effect name="stealth"/> before the Harpies and jump to the top. As soon as someone reaches the top level, you can safely use `/gg` and resurrect at the checkpoint there. Use reflects against the *Lightning Bolts* from the Raving Asura (or let others soak them) and kill the four golems to finish the fractal.
</GridItem>
  
<GridItem sm="7">
<Tabs>
<Tab specialization="Renegade">
First swap your legend to <Skill name="Legendary Centaur Stance"/> / <Skill name="Legendary Renegade Stance"/>, but stay on <Skill name="Legendary Renegade Stance" disableText/>. Go to the golems and deplete your energy below 10 for extra 25 energy on legend swap, swap to <Skill name="Legendary Centaur Stance"/>, then just use <Skill name="Protective Solace"/> to block the Racing Asura's projectiles until the end of fight.
</Tab>
</Tabs>   
</GridItem>

<GridItem sm="12">
<Image src="./images/raving_asura.jpg" caption="The Raving Asura and his entourage"/>
</GridItem>
</Grid>

