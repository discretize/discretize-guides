---
title: 'Underground Facility'
date: '2018-04-17'
image: './images/start.jpg'
group: 'T4'
api: 2947
bosses: 2
difficulties: [{ level: 81, ar: 116 }]
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

## Locked Gates <Item id="8892" text="false"/><Item id="24684" text="false"/>

|                               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| ----------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Preparation**               | The best way - as usual - is to stack <Effect name="stealth"/> on the platform before jumping down and not killing a single mob. Clarify this before running ahead and assign people for the roles below.<br/>Standing on the first pressure plate grants access to the second pressure plate, the second pressure plate grants access to the console room and the two pressure plates in the console room grant access to the console locker. A player needs about 20 seconds to activate the final console without interruption.                                                                                                                                                                                                                                                                                                                                                                                                     |
| **The First Pressure Plate**  | The best option for this is a <Specialization name="mesmer"/> who teleports up from the ground floor [as seen here](https://youtu.be/jQCKegeS3DI) and gives party <Effect name="stealth"/> from above.<br/>Otherwise let the most 'useless' class walk up with a little head start (usually the <Specialization name="warrior"/>).<br/>The rest of the party should keep <Effect name="stealth"/> up and run through the open gate below immediately.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **The Second Pressure Plate** | This is usually done by an <Specialization name="elementalist"/> who teleports up from below while the others keep up <Effect name="stealth"/>.<br/>Other options are <Specialization name="thief"/> or <Specialization name="mesmer"/> who can even come back easily for the Console room using <Skill id="13106"/> or <Skill id="10197"/> respectively.<br/>**Activating the second pressure plate permanently opens the first door.**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **The Console Room**          | Two people without special abilities should step on the two pressure plates to open the console locker. They are also responsible for keeping aggro from the opener, especially the spawning _Veteran Dredge_ next to the locker.<br/>Now for the actual console, <Item id="8686"/> and other <Effect name="stealth"/> sources are very strong. It should be activated by someone who's able to block the <Control name="knockback"/> from the locker closing, so the other two people can step off the pressure plates and protect the opener from the spawning mobs. The opener should indicate the step off in chat to time it with block skills.<br/>**The whole party can do `/gg` after the console is done, but it is not necessary** only if the <Specialization name="mesmer"/> want's to give <Effect name="stealth"/>, since the checkpoint was changed in the June 26th patch and everyone resurrects in the Console Room. |

<Grid>
<GridItem>
<Tabs>
<Tab specialization="chronomancer">
Use <Skill id="10200"/> to teleport and <Skill id="10245"/> with <Skill id="29830"/> and <Trait id="674"/> for long party <Effect name="stealth"/>.    
        You can block the console locker <Control name="knockback"/> with <Skill id="29526"/>, <Skill id="10192"/> or a lucky <Trait id="713"/> signet cast.
</Tab>

<Tab specialization="elementalist">
Take <Skill id="5536"/> or <Skill id="5641"/> when activating the console.
</Tab>

<Tab specialization="guardian">
<Skill id="30029"/>, <Skill id="9084"/> and <Skill id="9253"/> block the console <Control name="knockback"/>.
</Tab>

<Tab specialization="thief">
Use the smoke field from <Skill id="13113"/> or <Skill id="14184"/> to stack <Effect name="stealth"/>. <Skill id="13027"/> and <Skill id="13117"/> combined with <Trait id="1136"/> provide enough <Effect name="stealth"/> to completely activate the console.
</Tab>

<Tab specialization="ranger">
Use <Skill id="31568"/> from your Smokescale pet to stack <Effect name="stealth"/>.
</Tab>
</Tabs>
</GridItem>

<GridItem sm="4">
<Image src="./images/start.jpg" caption="The starting area"/>
<Image src="./images/console_locker.jpg" caption="The console locker" compact/>
</GridItem>
</Grid>

---

## Guns _or_ Bombs path <Item id="8892" text="false"/><Item id="24684" text="false"/><Label>Random</Label>

<Grid>
<GridItem>
After resurrecting, skip the mobs with <Effect name="stealth"/> and the guns or nine bombs to destroy the gate.

On the **guns** path, any equipped gun near the door will break when the door reaches 75%/50%/25% health. **After the June 26th update, you no longer need to use three guns simultaneously, can go one by one as fast as you can**.

On the **bombs** path, be sure to take the _Concealing Dust_ at the begin **and** at the end to permanently keep <Effect name="stealth"/> up on yourself. Same applies if you gain aggro of any mob, just walk into a <Effect name="stealth"/> zone. **After the June 26th update, you can use portals and blinks/teleports with bombs**
</GridItem>

<GridItem sm="4">
<Image src="./images/gun_path.jpg" caption="The gun path" compact/>
</GridItem>
</Grid>

<Tabs>
<Tab specialization="chronomancer">
Immediately cast <Skill id="10245"/> twice with <Skill id="29830"/> after resurrecting to skip past the mobs.
        Use <Skill id="29578"/> with <Skill id="10197"/> to quickly port back to the Bombs/Guns.    
        **Note that teleporting while carrying a Gun or Bomb does not work.**
</Tab>

<Tab specialization="thief">
Cast <Skill id="13117"/> for immediate <Effect name="stealth"/>.
</Tab>
</Tabs>

---

## <Boss/> Champion Rabsovich <Item id="8892" text="false"/><Item id="24684" text="false"/>

When you destroy the door, you will reach the most annoying boss ingame, have fun casting half of your skills into his shield. There's really no trick with him apart from breaking his defiance bar as often as possible. If needed, do `/gg` afterwards to reset your wasted cooldowns.

---

## <Boss red/> Dredge Powersuit <Item id="8892" text="false"/><Item id="24684" text="false"/> _or_ Rampaging Ice Elemental <Item id="8885" text="false"/><Item id="24661" text="false"/><Label>Random</Label>

<Grid>
<GridItem>
You can either stack <Effect name="stealth"/> and skip towards the Endboss together or let the <Specialization name="mesmer"/> teleport ahead and do a <Skill id="10197"/>. In the latter case, <Specialization name="mesmer"/> does `/gg` after placing the portal to reset cooldowns so do not resurrect until <Specialization name="mesmer"/> is done, then take the portal together. Keep in mind the maximum range.

After loosing potential aggro of the mobs from the corridor, pull the boss to the next lava bucket, trigger it to inflict _Superheated_ for 10x damage and nuke. Stay on the boss as long as possible before moving to the next bucket but pay attention to his _Mending_ heal skill, which can be interrupted by simply attacking him as long as the Superheated debuff is up.

The most deadly skills here are the _Bombs_ from the Dredge Powersuit (they spawn slightly away from him) and _Shatterstone_ (dropping ice shards on every player) and _Freeze Row_ from the Ice Elemental (small delayed Ice-AoEs in a V-Shape which explode after 2.75s - unblockable).
</GridItem>

<GridItem sm="4">
<Tabs>
<Tab specialization="chronomancer">
You can take <Skill id="29526"/> against the Dredge Powersuit boss.
</Tab>

<Tab specialization="thief">
Teleport to the lava buckets from below with <Skill id="13025"/>.
</Tab>
</Tabs>
</GridItem>
</Grid>

<Image src="./images/ice_elemental.jpg" caption="The Rampaging Ice Elemental"/>
