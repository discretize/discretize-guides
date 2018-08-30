---
title: 'Aquatic Ruins'
date: '2018-08-30'
image: './images/header.jpg'
group: 'T4'
api: 2956
bosses: 1
difficulties: [{ level: 76, ar: 110 }]
record:
  {
    time: '2:13',
    by: { name: 'Happens', tag: 'hP' },
    youtube:
      [{ id: 'cRKap-6_W48', name: 'Guts', specialization: 'Chronomancer' }],
  }
cycle: 'Day'
potions: [{ id: 50082, description: 'only for the Krait at the beginning' }]
sigils:
  [
    { id: 24658, description: 'only for the Krait at the beginning' },
    { id: 24615 },
    { id: 24868 },
  ]
consumables: [78978]
---

<Message icon="warning circle">
<MessageHeader>
Disclaimer
</MessageHeader>
This is an underwater fractal. Make sure you have approriate underwater equipment with enough Agony Resistance.
</Message>

---

## Save the villagers <Item id="50082" text="false"/><Item id="24658" text="false"/>

<Grid>
<GridItem>
You can stack <Boon name="might"/> on the rack before entering the water. Kill the three groups of Krait and open the cages. Use `/gg` after the last cage to resurrect at the tunnel part.

<Tabs>
<Tab specialization="mesmer">
Use <Skill id="10255"/> to group up Krait. You can place a <Skill id="10197"/> on the rack and open it with <Skill id="29578"/> underwater to not loose time while the others stack <Boon name="might"/>. You can place another one at the 2nd cage, swim ahead and open it at the 3rd cage. Place a <Skill id="10325"/> to give a speed bost the the whole party.
</Tab>

<Tab specialization="warrior">
Take <Skill id="14403"/> and trait <Trait id="1711"/> to grant <Boon name="fury"/> and <Boon name="might"/>, since the <Specialization name="druid"/> can't get into <Skill id="33557"/> as often as on land.
</Tab>

<Tab specialization="weaver">
You can stay Weaver for this fractal and trait Air with <Trait id="232" text="false"/>, <Trait id="214" text="false"/> and most importantly <Trait id="1503"/> or retrait to Tempest. For utility, use <Skill id="5638" text="false"/>, <Skill id="40183" text="false"/>, <Skill id="5539" text="false"/> and <Skill id="43638"/> as Elite skill.
</Tab>

<Tab specialization="tempest">
You can retrait to Tempest for this fractal as it is one of the best choices for underwater combat (because of cleave and vulnerability uptime).     
        Trait Air with <Trait id="232" text="false"/>, <Trait id="214" text="false"/> and most importantly <Trait id="1503"/>. For utility, use <Skill id="5638" text="false"/>, <Skill id="5539" text="false"/>, <Skill id="30662" text="false"/> and <Skill id="29968" text="false"/> as Elite skill.     
        As rotation, alternate between <Skill id="29719"/> (<Skill id="5494" text="false"/>) and <Skill id="5597"/> (<Skill id="5492" text="false"/>) and <Skill id="5655"/> and Air autoattack (<Skill id="5494" text="false"/>) to maximize dps. 
</Tab>

<Tab specialization="ranger">
Retrait Druid to Marksmanship for <Trait id="986"/> and swap to <Trait id="965"/> in Nature Magic. Run five spirits (<Skill id="21773" text="false"/><Skill id="12497" text="false"/><Skill id="12493" text="false"/><Skill id="12498" text="false"/><Skill id="12569" text="false"/>) for easy boon application with <Trait id="1038"/>.
</Tab>
</Tabs>

</GridItem>

<GridItem sm="4">
    <Image src="./images/wooden_rack.jpg" caption="The wooden rack"/>
    <Image src="./images/trapped_villagers.jpg" caption="Villagers are trapped in cages"/>
</GridItem>
</Grid>

---

<Grid divided>
<GridItem>
## Dark Path <Label>Random</Label>

If you get this path, swim together and take the _Luminous Plants_ on the way to protect you and nearby players from dying. If you are able to survive it, take the shortcut to the left after entering the larger cave. Use dodges or <Effect name="invulnerability"/> for the last group of Krait. If someone reaches the end boss, use `/gg` to immediately resurrect there.
</GridItem>

<GridItem>
## Dolphin Path <Label>Random</Label>

If you get this path, spam `Skill 1` during swimming to reveal nearby hidden Krait and keep to the right. You can use `Skill 2` to create a distraction and `Skill 3` to get a short speed boost. `Skill 5` can be used to instantly revive nearby dead allies. Always dodge **twice** when you anticipate a Krait attack. As soon as someone reaches the end boss, use `/gg` to immediately resurrect there.
</GridItem>
</Grid>

---

## <Boss red="true"/> Jellyfish Beast

<Grid>
<GridItem>
Break Jellyfish Beast's defiance bar as often as possible to benefit from <Item id="24868"/> and deal more damage. If he eats you, use any kind of stunbreak to break free or spam Skill 1.
</GridItem>

<GridItem>

<Tabs>
<Tab specialization="chronomancer">
Use a combination of <Skill id="29830"/>, <Skill id="10377"/>, <Skill id="29578"/>, <Skill id="10236"/> and <Trait id="1866"/> to easily keep up <Boon name="quickness"/> for the whole fight.    
        If possible, cast <Skill id="10318"/> against a cage for high damage.
</Tab>

<Tab specialization="warrior">
Cast <Skill id="14480"/> against a cage for high damage.
</Tab>
</Tabs>

</GridItem>
</Grid>

<Image src="./images/the_jellyfish_beast.jpg" caption="The Jellyfish Beast"/>
