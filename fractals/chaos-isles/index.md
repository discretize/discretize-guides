---
title: 'Chaos Isles'
date: '2018-04-17'
image: './images/legendary_brazen_gladiator.jpg'
group: 'T4'
api: 3038
bosses: 2
difficulties: [{ level: 88, ar: 129 }]
record:
  {
    time: '3:48',
    by: { name: 'Discretize', tag: 'dT' },
    youtube:
      [
        { id: 'WN_ohtdzUEY', name: 'Hyperiel', specialization: 'Chronomancer' },
        { id: 'W0heJU1YHRs', name: 'Metagame', specialization: 'Warrior' },
        { id: 'p4Swksv1-To', name: 'Nimajeb', specialization: 'Holosmith' },
        { id: 'uCu_f50blpc', name: 'Xarlor', specialization: 'Weaver' },
      ],
  }
cycle: 'Day'
sigils:
  [
    { id: 24615 },
    { id: 24554, description: 'for the Chaos Anomaly' },
    { id: 24868 },
  ]
consumables: [49940]
---

## Start

<Grid>
<GridItem>
Kill the four *Veteran Chanters* at the beginning to open the gate on the right-hand side. The fastest person can rush ahead and move to the next checkpoint at the *Chaos Anomaly*, everyone else can `/gg` and resurrect at the checkpoint there.
</GridItem>
<GridItem sm="4">
<Image src="./images/start.jpg" caption="The starting area" compact/>
</GridItem>
</Grid>

---

## Chaos Anomaly

<Grid>
<GridItem>
Stack <Boon name="might"/> before the four *K1T-A golems* and kill them to spawn the Chaos Anomaly. Every 25% health, she will become immune to damage and you have to kill K1T-A golems again to continue. With every phase there will be one less K1T-A golem but the remaining grow in strength, the final single golem at 25% health has about 1.5m health.

Pay attention to the <Control name="knockback"/> zones from the small JT-12 golems and look out for _Flux Bombs_, the debuff can be hard to notice on the mosaic ground.
</GridItem>

<GridItem>
<Tabs>
<Tab specialization="mesmer">
Trait <Trait id="751"/> and use <Skill id="10363"/> at 75%/50%/25% to grab the golems together.
</Tab>

<Tab specialization="spellbreaker">
You can <Skill id="14502"/> golems towards the center area.
</Tab>

<Tab specialization="ranger">
Run an offhand axe and use <Skill id="12638"/> to pull golems closer.
</Tab>
</Tabs>
</GridItem>
</Grid>

<Image src="./images/kitty_golems.jpg" caption="The four K1T-A golems before the Chaos Anomaly"/>

---

## Blizzard path (Forest)

<Grid>
<GridItem>
You will need to enlighten four *bonfires* on the path to progress to the end boss while every player only has **one** *Enlighten* charge.

You can stack <Effect name="stealth"/> to skip the mobs though it usually is not necessary. Do not assign a bonfire to each player, simply lighten them up as soon as you reach them.  
Learn to dodge the tentacle <Control name="knockback"/>s. Mobility skills and <Item id="49940"/> are very good here.
</GridItem>
<GridItem sm="4">
<Image src="./images/forest.jpg" caption="The blizzard forest" compact/>
</GridItem>
</Grid>

---

## Legendary Brazen Gladiator

<Grid>
<GridItem>
The end boss is only vulnerable when his protective bubble is removed by pulling him into the moving purple areas.    
He will also apply a group-wide <Control name="daze"/> if he hits anyone with the third hit of his auto-attack chain. Avoiding this is the highest priority during the fight. Either use blocks, dodges and invulnerables or simply do not stand in front of him when it hits. Learn to recognize the animation.

Note that you can take aggro from him by walking inside his hitbox and cancel the third auto-attack by moving out before.  
Another trick is to bypass the damage from purple zones by repeated jumping.

Starting at 50% health, he will randomly start a _pulling attack_ which can be prevented by breaking his defiance bar. Save your crowd control skills for this.

Also pay attention to the small _JT-12_ golems and their AoEs as they apply <Control name="knockback"/> and can shove you off the platform.
</GridItem>

<GridItem sm="4">
<Tabs>
<Tab specialization="chronomancer">
Use a combination of <Skill id="29578"/>, <Skill id="29526"/>, <Skill id="10377"/>, <Skill id="10236"/> and <Skill id="29830"/> to keep up <Boon name="quickness"/> and block every single dazing auto-attack with <Boon name="aegis"/>.
</Tab>

<Tab specialization="ranger">
Use <Skill id="12638"/> to pull the small JT-12 golems closer.    
        <Skill id="12569"/> with <Trait id="1038"/> grants the whole party <Boon name="stability"/>.
</Tab>
</Tabs>
</GridItem>
</Grid>

<Image src="./images/legendary_brazen_gladiator.jpg" caption="The Legendary Brazen Gladiator"/>
