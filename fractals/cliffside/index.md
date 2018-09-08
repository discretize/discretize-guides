---
title: 'Cliffside'
date: '2018-04-17'
image: './images/header.jpg'
group: 'T4'
api: 2930
bosses: 1
difficulties: [{ level: 82, ar: 118 }, { level: 94, ar: 139 }]
record:
  {
    time: '4:29',
    by: { name: 'Happens', tag: 'hP' },
    youtube:
      [
        { id: '05wgY9N_pdc', name: 'Guts', specialization: 'Chronomancer' },
        { id: '3iqOCAT23S8', name: 'Never Moa', specialization: 'Tempest' },
        { id: 'fqK7UO-6R7M', name: 'Goni', specialization: 'Tempest' },
      ],
  }
cycle: 'Day'
potions: [{ id: 8881 }]
sigils: [{ id: 24678 }, { id: 24615 }]
consumables: [78978]
---

<Message>
You will need an experienced <Specialization name="mesmer"/> for this fractal or take double the time. The Mesmer should run <Skill id="10200"/>, <Skill id="29578"/>, <Skill id="10197"/>, <Skill id="10377"/> and <Trait id="752"/> until the end fight.
</Message>

---

<Grid>
<GridItem sm="8">
## Start & Ankle Seals <Item id="8881" disableText/><Item id="24678" disableText/>

Kill the Cultists but take the _Cultist Hammer_ before finishing the last one to get a hammer charge.  
Take the portal to above (...or walk) and destroy the two _Ankle Seals_ using hammer `Skill 4`. Both sigils have to get hit two times, do not finish mobs unless you need a charge.  
Use `/gg` afterwards and stay dead until the <Specialization name="mesmer"/> reaches the Chest Seal.
</GridItem>

<GridItem sm="4">
<Image src="./images/ankle_seals.jpg" caption="The ankle seals"/>
</GridItem>
</Grid>

<Tabs>
<Tab specialization="mesmer">
At the start, immediately blink forward and use <Effect name="stealth"/> to prevent aggro from the mobs. Place a <Skill id="10197"/>, walk upstairs while the others kill the mobs and open the portal in front of the *Ankle Seals*.    
        Afterwards, wait at the gate for the others to finish the two seals, then rush ahead and use <Skill id="29578"/> with <Skill id="10200"/> and teleport twice to reach the next level.    
        Keep walking until you reach the last wooden board, then `/gg` as well.
</Tab>

<Tab specialization="elementalist">
Place a <Skill id="5516"/> near the next corridor to speed things up for the Mesmer.
</Tab>
</Tabs>

---

## Chest Seal <Item id="8881" disableText/><Item id="24678" disableText/>

<Grid>
<GridItem>
As soon as the Mesmer did `/gg` too, everyone can resurrect and will respawn in front of the *Chest Seal* with a new *Cultist Hammer* ahead of you.    
It will take five hits to break the chest seal. If you see your Mesmer running ahead and placing a portal to the *Arm Seals*, try to get a hammer charge before taking it to above.
</GridItem>

<GridItem>
<Tabs>
<Tab specialization="chronomancer">
After 2-3 hits against the Seal, place a <Skill id="10197"/>, use <Skill id="29578"/> with <Skill id="29830"/> and blink to forward. Run up to the *Right Arm Seal*, wait for the destruction of the *Chest Seal* and cast <Skill id="29578"/> again before opening the portal for the remaining party.
</Tab>

<Tab specialization="ranger">
<Skill id="12638"/> from an offhand Axe helps pulling the Cultists to you.
</Tab>
</Tabs>
</GridItem>
</Grid>

<Image src="./images/chest_seal.jpg" caption="The chest seal"/>

---

## Arm Seals <Item id="8881" disableText/><Item id="24678" disableText/>

<Grid>
<GridItem sm="8">
This is a matter of timing, so look out for the <Specialization name="mesmer"/> and the hammer carrier. In a perfect world you have a charge left from below, then hit the *Right Arm Seal* once before killing the Veteran Cultist to gain another charge. Run to the *Left Arm Seal*.

During the portal jumping, keep Cultist's health as low as possible but **only finish them when a hammer charge is needed**. If the Mesmer runs out of portals and more are needed, use a <Item id="78978"/>. Ideally, both seals take three hits to be destroyed—two portals are more than enough.

Type `/gg` after finishing both seals and stay dead. If you wipe before both seals are destroyed, they will reset to full health.
</GridItem>

<GridItem sm="4">
<Image src="./images/arm_seal.jpg" caption="One of the arm seals"/>
</GridItem>
</Grid>

<Tabs>
<Tab specialization="chronomancer">
Place a <Skill id="10197"/> at the *Right Arm Seal*. After walking to the *Left Arm Seal* together and hitting it, take the hammer and collect a charge before opening the portal.    
        It is possible to hit the seals four times during one portal and destroy them both. Position the portal in front of the Seals and try to take it back during the <Control name="stun"/> after hitting a seal. You can use <Skill id="10200"/> as a stunbreak.
</Tab>

<Tab specialization="warrior">
You can take the *Cultist Hammer* and use <Skill id="21815"/> during the Portal jumping to nullify the high incoming damage.
</Tab>

<Tab specialization="ranger">
Again, <Skill id="12638"/> from an offhand Axe helps pulling the Cultists to you.
</Tab>
</Tabs>

---

<Grid>
<GridItem sm="4">
## The way up
Do not resurrect yourself yet, wait for the <Specialization name="mesmer"/> to finish his portal and do `/gg` himself again or you will be stuck with an useless Mesmer for the entire end fight.
</GridItem>

<GridItem sm="8">
<Tabs>
<Tab specialization="mesmer">
After the whole party `/gg`'ed, resurrect yourself and place a <Skill id="10197"/> at the revival position.    
    Blink up to the Arch Diviner, open the portal and **walk away from it** before doing `/gg` again to reset your cooldowns. If you kill yourself on the portal it bugs and you'll have to keep <Skill id="10200"/> in your bar to follow your comrades.    
    Now the whole party can resurrect and use the portal, type `go` in chat to indicate that. Before taking the portal on your own, switch your skills and traits back. This takes some timing to get right.
</Tab>
</Tabs>
</GridItem>

<GridItem sm="8">
## Arch Diviner <Item id="8881" disableText/><Item id="24678" disableText/>
After the Mesmer indicates you to resurrect, take the portal to above and combat the Arch Diviner. His defiance bar appears very shortly but frequently, try to break it as often as possible to benefit from <Trait id="1502"/>.

Every 25% of his health, you will need to collect a _Cultist Hammer_ charge similar to before by killing one of the four spawned Cultists and hit the final Seal to make the Arch Diviner vulnerable again. Cultists apply a lot of conditions so kill them fast and try to stay out of their aggro range.

Do not get caught in any of the Arch Diviner's voidzones, otherwise you will be teleported and trapped inside a distant cage which messes up positioning. Also, try to stack on him as he teleports to the furthermost person.
</GridItem>

<GridItem sm="4">
<Tabs>
<Tab specialization="mesmer">
You can <Skill id="10363"/> all four Cultists during the Seal phase to the center.
</Tab>
</Tabs>
</GridItem>
</Grid>

<Image src="./images/arch_diviner.jpg" caption="The arch diviner and the final seal"/>
