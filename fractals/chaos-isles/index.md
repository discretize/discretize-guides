---
title: 'Chaos Isles'
date: '2020-09-29'
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

<Grid>
<GridItem sm="8">
## Start: You think this is Cliffside  
  
Kill the four *Veteran Chanters* at the beginning to open the gate on the right-hand side. The fastest person can rush ahead and move to the next checkpoint at the *Chaos Anomaly*, everyone else can `/gg` and resurrect at the checkpoint there.
</GridItem>
<GridItem sm="4">
<Image src="./images/start.jpg" caption="The starting area"/>
</GridItem>
  
<GridItem sm="12">
<Video title="Skip to Chaos Anomaly (Any class)" timestamp="19" youtube="Alpgs_GaZV0"/>  
</GridItem>
</Grid>

---

## Chaos Anomaly

<Grid>
<GridItem>
Stack <Boon name="Might"/> before the four *K1T-A golems* and kill them to spawn the Chaos Anomaly. Every 25% health, she will become immune to damage and you have to kill K1T-A golems again to continue. With every phase there will be one less K1T-A golem but the remaining grow in strength, the final single golem at 25% health has about 1.5m health.

Pay attention to the <Control name="Knockback"/> zones from the small JT-12 golems and look out for _Flux Bombs_, the debuff can be hard to notice on the mosaic ground.
</GridItem>

<GridItem>
<Tabs>
<Tab specialization="Revenant">
It is favorable to run <Skill name="Legendary Centaur Stance"/> for projectile absorption with <Skill name="Protective Solace"/> and condition cleanse with <Skill name=" Purifying Essence"/>. Recommended to use the Salvation / Invocation / Renegade variant for more energy for the whole fight.
</Tab>

<Tab specialization="Guardian">
You can use <Skill name="Binding Blade"/> to group the little cats at the start and then every phase of Chaos Anomaly, the position you need to place yourself for perfect pull can vary based on what cat you killed last, there are variations you cant pull all of them, only 2.
</Tab>

<Tab specialization="ranger">
Run an offhand axe and use <Skill id="12638"/> to pull golems closer.
</Tab>
</Tabs>
</GridItem>
</Grid>

<Image src="./images/kitty_golems.jpg" caption="The four K1T-A golems before the Chaos Anomaly"/>

---

<Grid>
<GridItem sm="5">
<Image src="./images/forest.jpg" caption="The blizzard forest"/>
</GridItem>
  
<GridItem sm="7">
## Blizzard path (Forest)

You will need to enlighten four *bonfires* on the path to progress to the end boss, **the *Enlighten* charges have unlimited use so this can be soloed** but if you want to be safe simply wait for everyone.

You can stack <Effect name="Stealth"/> to skip the mobs though it usually is not necessary. 
Learn to dodge the tentacle <Control name="Knockback"/>s. Mobility skills and <Item id="49940"/> are very good here.

</GridItem>
</Grid>

---


<Grid>
<GridItem sm="8">
## Legendary Brazen Gladiator  
  
The end boss is only vulnerable when his protective bubble is removed by pulling him into the moving purple areas.    
He will also apply a group-wide <Control name="Daze"/> if he hits anyone with the third hit of his auto-attack chain. Avoiding this is the highest priority during the fight. Either use blocks, dodges and invulnerables or simply do not stand in front of him when it hits. Learn to recognize the animation.

Note that you can take aggro from him by walking inside his hitbox and cancel the third auto-attack by moving out before.  
Another trick is to bypass the damage from purple zones by repeated jumping.

Starting at 50% health, he will randomly start a _pulling attack_ which can be prevented by breaking his defiance bar. Save your crowd control skills for this.

Also pay attention to the small _JT-12_ golems and their AoEs as they apply <Control name="Knockback"/> and can shove you off the platform.

<Image src="./images/legendary_brazen_gladiator.jpg" caption="The Legendary Brazen Gladiator"/>
</GridItem>

<GridItem sm="4">
<Tabs>
<Tab specialization="Revenant">
Use <Skill name="Inspiring Reinforcement"/> in <Skill name="Legendary Dwarf Stance" disableText/> for <Boon name="Stability"/> against <Control name="Daze"/>.
</Tab>
</Tabs> 
  
<Tabs>
<Tab specialization="soulbeast">
Use <Skill name="Path of Scars"/> to pull the small JT-12 golems closer. <Skill name="Dolyak stance"/> with the trait <Trait name=" Leader of the Pack"/> gives the whole party <Boon name="Stability"/>.
</Tab>
</Tabs>

<Tabs>
<Tab specialization="Firebrand">
Tome 3 skill 1 and 5 grants <Boon name="Stability"/>, if that's not enough take <Skill name="Stand your ground"/>.
</Tab>
</Tabs>

<Tabs>
<Tab specialization="Berserker">
Take <Skill name="Headbutt"/> for the 50% Defiance bar and <Skill name="Outrage"/> against the <Control name="Daze"/>!
</Tab>  
</Tabs>
</GridItem>
</Grid>


