---
title: 'Underground Facility'
date: '2020-03-27'
image: './images/start.jpg'
group: 'T4'
api: 2947
bosses: 2
difficulties: [{ level: 81, ar: 117 }]
record:
  {
    time: '3:52',
    by: { name: 'Quantify', tag: 'qT' },
    youtube:
      [
        { id: 'jQCKegeS3DI', name: 'Subi', specialization: 'Chronomancer' },
        { id: 'GsPXlgXHAZI', name: 'Fennec', specialization: 'Berserker' },
        { id: 'OMUxEYbtnWE', name: 'Deathly', specialization: 'Daredevil' },
      ],
  }
cycle: 'Night'
potions:
  [
    { id: 8892, description: 'for all the Dredge enemies' },
    { id: 8885, description: 'for the Ice Elemental endboss' },
  ]
sigils:
  [
    { id: 36053 },
    { id: 24684, description: 'for all Dredge enemies' },
    { id: 24661, description: 'for the Ice Elemental endboss' },
  ]
consumables: [78978, 49940, 8764, 8801, 8686]
---

## Start: Locked Gates <Item id="8892" disableText/><Item id="24684" disableText/>

<Message>
There are two ways to do this. For the faster way you require <Item id="78978"/>. The normal way takes much longer but needs nothing.
</Message>

<Divider text="Fast way"/> 

<Grid>
<GridItem sm="12">
<Tabs>
<Tab specialization="Guardian">
<Video title="Guardian skip" timestamp="37" youtube="MmJTsOhdQeo"/>
</Tab>

<Tab specialization="Guardian">
<Video title="Guardian skip 2" youtube="Nzi7wRSNY7Q"/>
</Tab>

<Tab specialization="Warrior">
<Video title="Warrior skip" timestamp="105"  youtube="29qQ2xU1YHk"/>
</Tab>

<Tab specialization="Revenant">
<Video title="Revenant skip" timestamp="144"  youtube="REnmbN7sZFQ"/>
</Tab>

<Tab specialization="Thief">
<Video title="Thief skip" timestamp="484" youtube="Alpgs_GaZV0"/>
</Tab>
</Tabs>
</GridItem>
</Grid>

<Divider text="Normal way (slower)"/>

|                               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| ----------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Preparation**               | The best way - as usual - is to stack <Effect name="stealth"/> on the platform before jumping down and not killing a single mob. Clarify this before running ahead and assign people for the roles below.<br/>Standing on the first pressure plate grants access to the second pressure plate, the second pressure plate grants access to the console room and the two pressure plates in the console room grant access to the console locker. A player needs about 20 seconds to activate the final console without interruption.                                                                                                                                                                                                                                                                                                                                                                                                     |
| **The First Pressure Plate**  | The best option is to let the most 'useless' class walk up with a little head start (usually the <Specialization name="warrior"/>).<br/>The rest of the party should keep <Effect name="stealth"/> up and run through the open gate below immediately.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **The Second Pressure Plate** | This is usually done by an <Specialization name="elementalist"/> who teleports up from below while the others keep up <Effect name="stealth"/>.<br/>Other option is <Specialization name="thief"/> who can even come back easily for the Console room using <Skill id="13106"/> or <Skill id="10197"/> respectively.<br/>**Activating the second pressure plate permanently opens the first door.**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **The Console Room**          | Two people without special abilities should step on the two pressure plates to open the console locker. They are also responsible for keeping aggro from the opener, especially the spawning _Veteran Dredge_ next to the locker.<br/>Now for the actual console, <Item id="8686"/> and other <Effect name="stealth"/> sources are very strong. It should be activated by someone who's able to block the <Control name="knockback"/> from the locker closing, so the other two people can step off the pressure plates and protect the opener from the spawning mobs. The opener should indicate the step off in chat to time it with block skills.<br/>**The whole party can do `/gg` after the console is done, but it is not necessary**. |

<Grid>
<GridItem sm="8">
<Tabs>
<Tab specialization="elementalist">
Take <Skill id="5536"/> or <Skill id="5641"/> when activating the console.
</Tab>

<Tab specialization="guardian">
<Skill id="30029"/>, <Skill id="9084"/> and <Skill id="9253"/> block the console <Control name="knockback"/>.
</Tab>

<Tab specialization="thief">
Use the smoke field from <Skill id="13113"/> or <Skill id="13065"/> to stack <Effect name="stealth"/>. <Skill id="13027"/> and <Skill id="13117"/> combined with <Trait id="1136"/> provide enough <Effect name="stealth"/> to completely activate the console.
</Tab>

<Tab specialization="ranger">
Use <Skill id="31568"/> from your Smokescale pet to stack <Effect name="stealth"/>.
</Tab>
</Tabs>
</GridItem>

<GridItem sm="6">
<Image src="./images/start.jpg" caption="The starting area"/>
</GridItem>
<GridItem sm="6">
<Image src="./images/console_locker.jpg" caption="The console locker"/>
</GridItem>
</Grid>

---

## Guns _or_ Bombs path <Item id="8892" disableText/><Item id="24684" disableText/><Label>Random</Label>

<Grid>
<GridItem sm="8">
After resurrecting, skip the mobs with <Effect name="stealth"/> and the guns or nine bombs to destroy the gate.

On the **guns** path, any equipped gun near the door will break when the door reaches 75%/50%/25% health.

On the **bombs** path, be sure to take the _Concealing Dust_ at the begin **and** at the end to permanently keep <Effect name="stealth"/> up on yourself. Same applies if you gain aggro of any mob, just walk into a <Effect name="stealth"/> zone.
<Message>
**You can use portals and blinks/teleports with bombs**
</Message>
</GridItem>

<GridItem sm="4">
<Image src="./images/gun_path.jpg" caption="The gun path"/>
  
<Tabs>
<Tab specialization="thief">
Cast <Skill id="13117"/> for immediate <Effect name="stealth"/>.
</Tab>
</Tabs>
</GridItem>
</Grid>

---

## Champion Rabsovich <Item id="8892" disableText/><Item id="24684" disableText/>

When you destroy the door, you will reach the most annoying boss ingame, have fun casting half of your skills into his shield. There's really no trick with him apart from breaking his defiance bar as often as possible. If needed, do `/gg` afterwards to reset your wasted cooldowns.

Skip here by one of the classes below:

<Tabs>
<Tab specialization="Guardian">
<Video title="Guarian skip to last boss, same for Ranger" timestamp="103" youtube="MmJTsOhdQeo"/>
</Tab>
  
<Tab specialization="Thief">
<Video title="Thief skip to last boss" timestamp="531" youtube="Alpgs_GaZV0"/>
</Tab>  
</Tabs>


---

## Dredge Powersuit <Item id="8892" disableText/><Item id="24684" disableText/> _or_ Rampaging Ice Elemental <Item id="8885" disableText/><Item id="24661" disableText/><Label>Random</Label>

<Grid>
<GridItem sm="8">
If you did not skip, stack <Effect name="stealth"/> and skip towards the Endboss together.

After loosing potential aggro of the mobs from the corridor, pull the boss to the next lava bucket, trigger it to inflict _Superheated_ for 10x damage and nuke. Stay on the boss as long as possible before moving to the next bucket but pay attention to his _Mending_ heal skill, which can be interrupted by simply attacking him as long as the Superheated debuff is up.

The most deadly skills here are the _Bombs_ from the Dredge Powersuit (they spawn slightly away from him) and _Shatterstone_ (dropping ice shards on every player) and _Freeze Row_ from the Ice Elemental (small delayed Ice-AoEs in a V-Shape which explode after 2.75s - unblockable).
</GridItem>

<GridItem sm="4">
<Tabs>
<Tab specialization="thief">
Teleport to the lava buckets from below with <Skill id="13025"/>.
</Tab>
</Tabs>
  
<Image src="./images/ice_elemental.jpg" caption="The Rampaging Ice Elemental"/>
</GridItem>
</Grid>


