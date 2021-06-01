---
title: 'Uncategorized'
date: '2021-06-01'
image: './images/header.jpg'
group: 'T4'
api: 2939
bosses: 3
difficulties: [{ level: 79, ar: 113 }, { level: 91, ar: 134 }]
record:
  {
    time: '2:14',
    by: [{ name: 'Lucky Noobs', tag: 'LN' }],
    youtube:
      [
        { id: 'CipdjbelW-0', name: 'Nightmare', specialization: 'Chronomancer' },
        { id: 'iwpSxdqcdyY', name: 'CopyThisStatic', specialization: 'Firebrand' },
        { id: 'rgh5tnrg29o', name: 'Runitdown', specialization: 'Berserker' },
        { id: 'BHXFkdm3TFY', name: 'Inam', specialization: 'Renegade'},

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

**Option 1 (recommended):** The whole party stacks <Effect name="Stealth"/> and skips together until the holding area. If a single Harpy spawned immediately at the begin, you can kill it before stealthing.

**Option 2:** Anyone with a <Item id="78978"/> skips alone and teleports the team to the holding area.

**Option 3:** Proceed as a group and either kill the Harpies or skip them. <Boon name="Aegis"/> and <Boon name="Stability"/> helps a lot; you can also reflect all of the attacks.

## Holding Area

Stack <Boon name="Might"/> while destroying the _Power Generator_, then stack in the structure on the left side of the room and let the adds come to you (line of sight).

Then kill the Rabbit, the Bandit Saboteur, the Flame Legion Fire Shaman and finally the Ettin. Try to keep all mobs together on the Flame Legion Fire Shaman to maximize cleave damage, but do not get caught in the Ettin's _Massive Smash_ attack. 

Reflects are strong here as well, especially against the Fire Shaman's projectiles. Well timed <Boon name="Aegis"/> also helps out against the hard hitting Ettin attacks. Try to break the defiance bars to maximize your damage.

<Tabs>
<Tab specialization="Weaver">
If positioned correctly, you can use <Skill id="5697"/> against the wall and deal lots of damage to the adds.
</Tab>
<Tab specialization="Berserker">
Equip a greatsword and <Skill name="blood reckoning"/> for double <Skill name="arc divider"/>. Use your greatsword to cleave down the adds quickly!
</Tab>
<Tab specialization="Firebrand">
Try to share <Boon name="Aegis"/> with your group by using <Skill name="Mantra of Solace"/> when the Ettin is about to hit the group.
</Tab>
<Tab specialization="Holosmith">
You can use <Skill name="Holographic Shockwave"/> and <Skill name="Primelight Beam"/> to help break the defiance bars. Try to land those skills on all adds!
</Tab>
</Tabs>
</GridItem>

<GridItem sm="5">
<Tabs>

<Tab specialization="Thief">
Use the smoke field from <Skill id="13113"/> or <Skill id="13065" profession="Daredevil"/> or simply cast <Skill id="13117"/> to stack <Effect name="Stealth"/>.    
        <Skill id="13065"/> is also useful against the Holding Area bosses.
</Tab>

<Tab specialization="Ranger">
Use <Skill id="31568"/> from your Smokescale pet and blast the smoke field to stack <Effect name="Stealth"/>.
</Tab>

<Tab specialization="Engineer">
You can spec into <Specialization name="Scrapper"/> and use the <Skill name="Sneak Gyro"/> which grants lots of <Effect name="Stealth"/> for your party. Alternatively, use <Skill id="5824"/> in the <Skill name="Bomb Kit"/> for a smoke field which you can then blast to stack <Effect name="Stealth"/>.
</Tab>
</Tabs>

<Image src="./images/harpies_jp.jpg" caption="Harpies protect their jumping puzzle"/>
</GridItem>
</Grid>

---

<Grid>
<GridItem sm="8">
## Pulsing Orbs

After killing the adds, walk past the three Harpies and run up the ramp towards Old Tom. You can dodge through or reflect the pulsing orbs and even skip the last part by walking on the left wall.

Note: Activating all three consoles at the same time will turn off the turrets. This can be helpful, but it is not necessary for proceeding the fractal.
</GridItem>

<GridItem sm="4">
<Image src="./images/pulsing_orbs.jpg" caption="The ramp up"/>
</GridItem>

<GridItem sm="4"> 
<Image src="./images/old_tom.jpg" caption="Old Tom"/>
</GridItem>

<GridItem sm="8">
## Old Tom <Item id="8887" disableText/><Item id="24672" disableText/>  
  
Stack <Boon name="Might"/> before Old Tom, break his defiance bar as quickly as possible and burst him down. Be careful with <Effect name="Agony"/> and try to not stand in his hitbox or very close to him while he is firing his projectiles. <Specialization name="Soulbeast"/> can use <Skill id="12489"/> or take <Skill name="Bear stance"/> with the trait <Trait name="Leader of the Pack"/> to help out with the Poison from the green projectiles.
</GridItem>
</Grid>

---

<Grid>
<GridItem sm="5">
## Raving Asura <Item id="8887" disableText/><Item id="24672" disableText/>  
  
Stack <Effect name="Stealth"/> before the Harpies and jump to the top. As soon as someone reaches the top level, you can safely use `/gg` and resurrect at the checkpoint there. Watch your objectives list on the top right of the screen. As soon as you see a change in the objective you have triggered the checkpoint and may use `/gg`.

Use reflects against the *Lightning Bolts* from the Raving Asura (or let others soak them) and kill the four golems to finish the fractal. You can save some AoE spells for when all four golems reactivate at the same time.
</GridItem>
  
<GridItem sm="7">
<Tabs>
<Tab specialization="Renegade">
First swap your legend to <Skill name="Legendary Centaur Stance"/> / <Skill name="Legendary Renegade Stance"/>, but stay on <Skill name="Legendary Renegade Stance" disableText/>. Go to the golems and deplete your energy below 10 for extra 25 energy on legend swap, swap to <Skill name="Legendary Centaur Stance"/>, then just use <Skill name="Protective Solace"/> to block the Raving Asura's projectiles until the end of fight.
</Tab>
<Tab specialization="Firebrand">
Drop a <Skill name="Wall of Reflection"/> first on Raving Asura, slightly offset towards your party. Once all four golems become active at the same time, go into <Skill name="Tome of Courage"/> and use "Chapter 3: Valiant Bulwark" to help avoiding the projectiles and reduce incoming damage with "Epilogue: Unbroken Lines".
</Tab>
</Tabs>   
</GridItem>

<GridItem sm="12">
<Image src="./images/raving_asura.jpg" caption="The Raving Asura and his entourage"/>
</GridItem>
</Grid>
