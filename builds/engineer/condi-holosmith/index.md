---
title: Condi Holosmith
hidden: True
archive: false
rating: Good
role: Condition Damage
profession: Engineer
specialization: Holosmith
conditions:
  - name: Vulnerability
    uptime: 20 Stacks
code: "[&DQMmLwY7OSsqDwAAhgAAAKMAAABXFgAA8BUAAAAAAAAAAAAAAAAAAAAAAAA=]"
cmGuide: ""
classification:
  - 2
  - 4
  - 4
  - 3
  - 4
date: 2023-04-04T17:40:50.083Z
---

The <Specialization text="Power Holosmith" name="Holosmith"/> is a flexible build that can do well in a variety of different group compositions.
It offers:

- High burst and good sustained damage
- Good crowd control
- Good utility through <Condition name="Vulnerability"/> and access to some <Condition name="Blinded"/>, <Condition name="Crippled"/> and <Condition name="Immobile"/>
- The ability to boonstrip with <Skill name="Detonate Mine Field"/> when running <Skill name="Throw Mine"/>
- An incredible skill set for various skips in Tier 4 fractals due to access to <Effect name="Stealth"/>, as well as <Effect name="Superspeed"/> and a targeted leap with <Skill name="Jump Shot"/>
- Some **self**-generation of <Boon name="Might"/>, <Boon name="Quickness"/> and <Boon name="Fury"/>

The build benefits from slaying potions such as <Item name="Powerful Potion of slaying scarlets armies"/> and <Item name="Impact" type="Sigil"/>.

The main thing the build lacks compared to other Power DPS classes is a unique party buff for Power compositions like <Specialization text="Power Dragonhunter" name="Dragonhunter"/>'s <Skill name="Bane Signet"/> share.

There are 3 different versions of <Specialization text="Power Holosmith" name="Holosmith"/>, namely Sword ECSU, Sword PBM, and Rifle PBM. They are named after:

- The weapon they are holding, Sword+Shield vs Rifle.
- The Grandmaster Holosmith Trait they use, Enhanced Capacity Storage Unit (ECSU) vs Photonic Blasting Module (PBM).

This guide will focus mainly on the Sword ECSU variant since it is the most flexible of the 3.

<Divider text="Equipment"/>

<CharacterWithAr>  
<Character title="Power Holosmith" gear='{"attributes":{"profession":"Engineer","specialization":"Holosmith","data":{"Health":20522,"Armor":2343,"Power":3630,"Precision":1961,"Toughness":1225,"Vitality":1460,"Ferocity":1606,"Condition Damage":750,"Expertise":0,"Concentration":225,"Healing Power":0,"Agony Resistance":150,"Condition Duration":0,"Boon Duration":0.15,"Critical Chance":1.0576190476190477,"Critical Damage":2.570666666666667,"Power Coefficient":3260,"Power2 Coefficient":0,"Burning Coefficient":2.51,"Bleeding Coefficient":13.24,"Poison Coefficient":2.62,"Torment Coefficient":0,"Confusion Coefficient":0,"Flat DPS":0,"Bleeding Duration":0.33,"Siphon Base Coefficient":139.75,"Effective Power":32151.980456336667,"NonCrit Effective Power":12507.25380822225,"Power DPS":40360.206502756075,"Power2 DPS":0,"Siphon DPS":139.75,"Bleeding Damage":96.3125,"Bleeding Stacks":17.6092,"Bleeding DPS":1695.986075,"Burning Damage":355.421875,"Burning Stacks":2.51,"Burning DPS":892.1089062499999,"Confusion Damage":118.665625,"Confusion Stacks":0,"Confusion DPS":0,"Poison Damage":112.84375,"Poison Stacks":2.62,"Poison DPS":295.650625,"Torment Damage":142.74375,"Torment Stacks":0,"Torment DPS":0,"Damage":43383.70210900607,"Effective Health":95687653.7313433,"Survivability":48646.49401695135,"Effective Healing":390,"Healing":390}},"armor":{"weight":"Medium","helmAffix":"Berserker","helmRuneId":24836,"helmRune":"Scholar","helmRuneCount":6,"helmInfusionId":37131,"shouldersAffix":"Berserker","shouldersRuneId":24836,"shouldersRune":"Scholar","shouldersRuneCount":6,"shouldersInfusionId":37131,"coatAffix":"Berserker","coatRuneId":24836,"coatRune":"Scholar","coatRuneCount":6,"coatInfusionId":37131,"glovesAffix":"Berserker","glovesRuneId":24836,"glovesRune":"Scholar","glovesRuneCount":6,"glovesInfusionId":37131,"leggingsAffix":"Berserker","leggingsRuneId":24836,"leggingsRune":"Scholar","leggingsRuneCount":6,"leggingsInfusionId":37131,"bootsAffix":"Berserker","bootsRuneId":24836,"bootsRune":"Scholar","bootsRuneCount":6,"bootsInfusionId":37131},"weapon":{"weapon1MainId":30699,"weapon1MainType":"Sword","weapon1MainSigil1Id":24615,"weapon1MainAffix":"Berserker","weapon1MainInfusion1Id":37131,"weapon1OffId":30696,"weapon1OffType":"Shield","weapon1OffSigilId":24868,"weapon1OffAffix":"Berserker","weapon1OffInfusionId":37131,"weapon2MainInfusion2Id":37131,"weapon2MainSigil2Id":24868},"backAndTrinket":{"backItemAffix":"Berserker","backItemInfusion1Id":37131,"backItemInfusion2Id":37131,"amuletAffix":"Berserker","ring1Affix":"Berserker","ring1Infusion1Id":37131,"ring1Infusion2Id":37131,"ring1Infusion3Id":37131,"ring2Affix":"Berserker","ring2Infusion1Id":37131,"ring2Infusion2Id":37131,"ring2Infusion3Id":37131,"accessory1Affix":"Berserker","accessory1InfusionId":37131,"accessory2Affix":"Berserker","accessory2InfusionId":37131},"consumables":{"foodId":91805,"utilityId":77569},"skills":{"healId":21659,"utility1Id":5805,"utility2Id":6161,"utility3Id":42842,"eliteId":42009},"assumedBuffs":{"value":[{"id":"might","type":"Boon"},{"id":"fury","type":"Boon"},{"id":"protection","type":"Boon"},{"id":"vulnerability","type":"Condition"},{"id":"jade-bot","gw2id":96613,"type":"Item"},{"id":"omnipotion","gw2id":79722,"type":"Item"}]},"traits":{"selection":[[1914,1923,526],[1882,1892,1947],[2106,2152,2137]],"lines":[38,6,57]}}'>

You will only need some Assassin pieces if you want to swap to <Trait name="Sanguine Array"/> for better self-generated <Boon name="Might"/>.

You can use Off-Hand Pistol if there is absolutely no need for the CC from Shield.

</Character>
</CharacterWithAr>  



<Divider text="Build"/>



<Grid>
<GridItem sm="7">
<Traits traits1Id="38" traits1="Firearms" traits1SelectedIds="1914,1923,526" traits2Id="6" traits2="Explosives" traits2SelectedIds="1882,1892,1947" traits3Id="57" traits3="Holosmith" traits3SelectedIds="2106,2152,2137"/>

</GridItem>

<GridItem sm="5">
<Card title="Additional Skills">

|                                           |                                                                                                                                                                                                               |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Toolbelt                                  | <Skill id="21661" size="big" disableText/><Skill id="6172" size="big" disableText/><Skill id="6164" size="big" disableText/><Skill id="42163" size="big" disableText/>                                        |
| <Skill id="6020" size="big" disableText/> | <Skill id="5806" size="big" disableText/><Skill id="5807" size="big" disableText/><Skill id="5808" size="big" disableText/><Skill id="5809" size="big" disableText/><Skill id="5810" size="big" disableText/> |

</Card>

<Card title="CC skills">

|                                    |            |
| ---------------------------------- | ---------- |
| <Skill id="21661"/>                | 200 damage |
| <Skill name="Magnetic Inversion"/> | 150 damage |
| <Skill id="6057"/>                 | 100 damage |
| <Skill id="42009"/>                | 232 damage |
| <Skill id="42521"/>                | 232 damage |

</Card>

</GridItem>
</Grid>

<Grid>

<GridItem sm="7">
<Card title="Situational Traits">

|                                                                 |                                                                                                                    |
| --------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| <Trait name="Photonic Blasting Module" size="big" disableText/> | When running the Rifle or Sword PBM build.                                                                         |
| <Trait name="Sanguine Array" size="big" disableText/>           | If you are already crit capped without <Trait name="High Caliber"/> and struggle with <Boon name="Might"/> uptime. |

<Traits traits1Id="21" traits1="Tools" traits1SelectedIds="532,512,1856" unembossed/>

If your <Boon name="Quickness"/> uptime is low, you can swap out the Firearms trait line with Tools and replace <Skill id="5805"/> with <Skill id="43739"/>.

<Traits traits1="Scrapper" traits1Selected="Gyroscopic Acceleration" unembossed />

For many skips in Tier 4 fractals, you can swap to Scrapper for more <Effect name="Stealth"/> and <Effect name="Superspeed"/>. <Effect name="Stealth"/> can be provided through <Skill name="Sneak Gyro"/>. <Effect name="Superspeed"/> is provided through Gyros with a delay due to <Trait name="Gyroscopic Acceleration"/>. <Skill name="Medic Gyro"/> also provides some instant <Effect name="Superspeed"/> on top. <Skill name="Bulwark Gyro"/> and <Skill name="Purge Gyro"/> can be used without drawing aggro from enemies. <Skill name="Bypass Coating"/> can provide some instant <Effect name="Superspeed"/> as well.
</Card>
</GridItem>

<GridItem sm="5">
<Card title="Situational Skills">

|                                                     |                                                                                                                                                                                                         |
| --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <Skill id="5857" size="big" disableText/>           | An alternative heal skill if condition cleanse is needed. You can cast it AFTER (cause of water field) a fire field to blast <Boon name="might"/>.                                                      |
| <Skill id="43739" size="big" disableText/>          | A (group) block that also reflects projectiles if heat is above 50.                                                                                                                                     |
| <Skill name="Bomb Kit" size="big" disableText/>     | Default pick for the Rifle variant instead of <Skill name="Rifle Turret"/>. Can be helpful to provide a smoke field through <Skill name="Smoke Bomb"/> or fire field through <Skill name="Fire Bomb"/>. |
| <Skill name="Flamethrower" size="big" disableText/> | Can provide a fire field and a blast finisher. You can pre-cast the toolbelt skill <Skill name="Incendiary Ammo"/> for some extra damage.                                                               |

</Card>

</GridItem>
</Grid>

<Divider text="Rotation/Skill Usage"/>

<Grid>
<GridItem sm="6">
<Card title="Rotation">

1.  **Preheat to 90**
2.  <Skill name="Laser Disk" profession="Engineer"/>
3.  <Skill name="engage Photon Forge" profession="Engineer"/>
4.  <Skill name="Prime light beam" profession="Engineer"/> (To help with CCing)
5.  <Skill name="Grenade Barrage" profession="Engineer"/>
6.  <Skill name="Corona Burst" profession="Engineer"/>
7.  <Skill name="Photon Blitz" profession="Engineer"/>
8.  2x <Skill name="Light Strike" profession="Engineer"/> -> <Skill name="Bright Slash" profession="Engineer"/> -> <Skill name="Flash Cutter" profession="Engineer"/>
9.  <Skill name="Corona Burst" profession="Engineer"/>
10. <Skill name="Deactivate Photon Forge" profession="Engineer"/>
11. <Skill name="Refraction Cutter" profession="Engineer"/>
12. <Skill name="Shrapnel Grenade" profession="Engineer"/>
13. <Skill name="Poison Grenade" profession="Engineer"/>
14. 2x <Skill name="Sun Edge" profession="Engineer"/> -> <Skill name="Sun Ripper" profession="Engineer"/> -> <Skill name="Gleam Saber" profession="Engineer"/>
15. <Skill name="Refraction Cutter" profession="Engineer"/>
16. <Skill name="Shrapnel Grenade" profession="Engineer"/>
17. 2x <Skill name="Sun Edge" profession="Engineer"/> -> <Skill name="Sun Ripper" profession="Engineer"/> -> <Skill name="Gleam Saber" profession="Engineer"/>
18. <Skill name="Refraction Cutter" profession="Engineer"/>
19. <Skill name="Shrapnel Grenade" profession="Engineer"/>
20. <Skill name="Freeze Grenade" profession="Engineer"/>
21. <Skill name="engage Photon Forge" profession="Engineer"/> (your heat should be around 90)
22. Repeat from step 6

</Card>
<Card title="Notes">

- Use <Skill id="6178"/> off cooldown.
- Use <Skill id="42163"/> off-cooldown. This skill can be used inside the hitbox when multiple enemies are around to hit the boss multiple times. If this can be done, for example on Ensolyss, you can delay this skill for that.
- <Skill id="5808"/> can be used to mitigate damage in add heavy fights.
- When running off-hand Pistol, <Skill name="Blowtorch"/> is used instead of <Skill name="Freeze Grenade"/> in step 20.
- When running off-hand Pistol, <Skill id="5830"/> can help in controlling the movement of enemies without break bar.
- Try to manage your Heat in split phases. Ideally, you always want to be back at 90 Heat when starting to burst into a new phase.
- <Skill name="Poison Grenade" profession="Engineer"/> will not always be up at the same step as its cooldown is higher than the duration of your loop. The general idea of using 2 extra damaging skills while cooling down still applies.

</Card>

</GridItem>
<GridItem sm="6">

<Card title="Rotation Explanation">

- The idea of the opening is to stack as many damage modifiers as possible with your biggest skills. By entering Forge at the start, you will trigger <Trait name="Solar Focusing Lens"/>. Due to being in Forge, you will also gain the extra damage from <Trait name="Lasers Edge"/>. <Skill name="Grenade Barrage"/> will help with stacking <Trait name="Explosive Temper"/>.
- You want to always use your big damaging skills like <Skill name="Laser Disk"/> and <Skill name="Prime Light Beam"/> in Forge when possible. Only use them outside of Forge if the boss will die/phase before you can go back into Forge to use them there.
- In Forge, your high damage weapon skills are <Skill name="Corona Burst"/> and <Skill name="Photon Blitz"/>, as well as auto-attack chains. Try to not interrupt your Forge auto-attack chain. Your goal is to <Skill name="Deactivate Photon forge"/> at exactly 149 Heat. This can be achieved by using auto-attack chains until around 140 Heat (as seen in step 8), then using <Skill name="Corona Burst"/> and <Skill name="Deactivate Photon forge"/>. <Skill name="Corona Burst"/> will keep building up some Heat, however you cannot <Skill id="44386"/> if you already left Forge directly after its cast.
- Out of Forge, your basic rotation can be seen in steps 15-17. The main goal is to use <Skill name="Refraction Cutter"/> above 100 Heat 3 times. If you are slow, you might want to skip some extra skills like <Skill name="Poison Grenade"/> and <Skill name="Freeze Grenade"/> and prioritize <Skill name="Engage Photon Forge"/> at 90 Heat.

</Card>

<Card title="Pre-Casting">

- Make sure that you will start the fight on your desired Heat (usually 90).
- You want to make sure to always at least pre-cast <Skill name="Laser Disk"/> before taking the singularity.
- You can either swap utility skills manually or via a template. Make sure to have the same traits in both templates selected if you choose the template route.
- If this is taken care of, you can do the following extra pre-casts:
  1. Equip <Skill name="Thumper Turret"/>, <Skill name="Bomb Kit"/> and <Skill name="Flamethrower"/>.
  2. Place <Skill name="Big Ol Bomb"/>.
  3. Use <Skill name="Fire Bomb"/> or <Skill name="Napalm"/> to provide a fire field.
  4. Use <Skill name="Rumble"/>, <Skill name="Flame Blast"/> and <Skill name="Magnetic Inversion"/> to blast.
  5. Use <Skill name="Incendiary Ammo"/>.
  6. Swap to your regular utilities and use <Skill name="Laser Disk"/>.
  7. Take the singularity.
- If you want to go the extra mile, you can keep the Flamethrower equipped and use <Skill name="Incendiary Ammo"/> again and place <Skill name="Napalm"/> on the boss spawn location before swapping it out.
- <Skill name="Holographic Shockwave"/> provides yet another blast finisher if it works with your Heat management.

</Card>

</GridItem>
</Grid>
