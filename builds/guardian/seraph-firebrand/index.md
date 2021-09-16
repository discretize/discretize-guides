---
title: Seraph Firebrand
sections:
  - type: mdx
    title: Overview
    content: >-
      The **<Specialization text="Seraph Firebrand" name="Firebrand"/>** is a
      build for groups to use instead of a **<Specialization text="Heal
      Firebrand" name="Firebrand"/>**. It provides more than enough healing for
      most groups, permanent <Boon name="Quickness"/>, a large chunk (15-18
      stacks) of <Boon name="might"/> and on demand <Boon name="Stability"/> and
      <Boon name="Aegis"/>, whilst dealing a decent amount of damage. It is
      especially strong in PuGs where often a **<Specialization text="Heal
      Firebrand" name="Firebrand"/>** is overkill, especially in condi groups,
      but the convenience of having a more supportive player pumping out
      important boons such as <Boon name="might"/>, <Boon name="Stability"/>,
      <Boon name="Aegis"/> and heals is invaluable.


      The general idea of this build is to leverage the Seraph stat combo (<Attribute name="Precision"/>, <Attribute name="Healing Power"/>, <Attribute name="Condition Damage"/> and <Attribute name="Concentration"/>). This gives a high amount of <Attribute name="Healing Power"/> and <Attribute name="Condition Damage"/>. It then uses Runes, Sigils and Food to cap <Condition name="Burning"/> duration allowing you to deal a good amount of damage. There are three variants shown below; a Seraph variant, Celestial variant and a Celestial Heal variant. The Seraph Variant is a more offensive build and offers the most damage. The Celestial variant is slightly less damage but also a better option if playing outside of fractals. While the Celestial Heal variant is much more supportive and a last resort before swapping to <BuildLink build="Heal Firebrand" specialization="Firebrand"/> . All of these builds can be optimised further with a mix of gear to suit your needs using our [gear optimizer](https://discretize.github.io/discretize-gear-optimizer/).
  - type: equipment
    title: Equipment
    content: ""
  - type: mdx
    title: Build
    content: >-
      <Grid>

      <GridItem sm="7">

      <Card title="Build Guide by Ciello">


      <Video youtube="uV6eHEQKTms" caption="Although made in a previous patch, nothing has changed for this build."/>

      </Card>


      <Traits traits1="Radiance" traits1Selected="Right Hand Strength,Radiant Fire,Amplified Wrath" traits2="Honor" traits2Selected="protectorsrestoration,Empowering Might,Writ of Persistence" traits3="Firebrand" traits3Selected="Liberators Vow,Legendary Lore,Loremaster"/>


      <Card title="Defiance Bar Damage">


      |                                                 |                   |

      | ----------------------------------------------- | ----------------- |

      | <Skill name="Sanctuary"/>                       | 750 damage        |

      | <Skill id="45402"/>                             | 150 damage        |

      | Skill 3 in <Skill name="Tome of Justice"/> (F1) | 150 damage        |

      | <Skill id="9093"/>                              | 300 damage        |

      | <Skill name="Hammer of Wisdom"/>                | 200 damage        |

      | <Skill name="Chains of light"/>                 | 250 damage (50/s) |


      </Card>

      </GridItem>


      <GridItem sm="5">

      <Skills heal="Mantra of Solace" utility1="Mantra of Potence" utility2="" utility3="Sanctuary" elite="Feel My Wrath"/>


      <Card title="Situational Skills">


      |                                                       |                                                                                                                                                                                  |

      | ----------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

      | <Skill id="9153" size="big" disableText/>             | When <Boon name="Stability"/> or a stunbreak is needed.                                                                                                                          |

      | <Skill id="9251" size="big" disableText/>             | A stationary reflect lasting for 10 seconds.                                                                                                                                     |

      | <Skill name="Bow of Truth" size="big" disableText/>   | A strong AoE heal for 5 seconds.                                                                                                                                                 |

      | <Skill id="9084" size="big" disableText/>             | Provides <Boon name="Aegis"/> to 5 targets.                                                                                                                                      |

      | <Skill name="Bane Signet" size="big" disableText/>    | Provides CC and a 216 power buff to each party member when traited with <Trait name="Perfect Inscriptions"/>. This should be used when playing in power comps with high DPS.     |

      | <Skill id="9125" size="big" disableText/>             | Deals an additional 200 defiance bar damage. A very good replacement for <Skill name="Sanctuary"/> on Artsariiv and MAMA.                                                        |

      | <Skill id="9168" size="big" disableText/>             | Can be used as a source of <Condition name="Vulnerability"/>. If your group's <Condition name="Vulnerability"/> uptime is low, taking this is a DPS increase.                    |

      | <Skill id="43357" size="big" disableText/>            | When <Boon name="Stability"/> or a stunbreak is needed. Only take this if you can upkeep <Boon name="Quickness"/> and <Boon name="Fury"/> without <Skill name="Feel My Wrath"/>. |

      | <Skill name="Mantra of lore" size="big" disableText/> | Cleanses multiple conditions thanks to charges.                                                                                                                                  |

      | <Skill name="renewed focus" size="big" disableText/>  | Recharges all virtue skills, grants <Effect name="Invulnerability"/> for 3 seconds.                                                                                              |

      | <Skill id="9247" size="big" disableText/>             | A 1200 range teleport to an enemy.                                                                                                                                               |

      | <Skill id="9246" size="big" disableText/>             | A 1,200 range teleport to an ally.                                                                                                                                               |


      </Card>


      <Card title="Alternative traits">


      |                                                             |                                                                                                                              |

      | ----------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |

      | <Trait name="perfect inscriptions" size="big" disableText/> | Taken when playing in a power comp to share <Skill name="Bane Signet"/>.                                                     |

      | <Trait name="pureofheart" size="big" disableText/>          | Taken if the group is struggling with healing.                                                                               |

      | <Trait name="stalwartspeed" size="big" disableText/>        | Taken if you are struggling to upkeep <Boon name="Quickness"/> (particularly useful if you are playing <Skill id="43357"/>). |


      </Card>

      </GridItem>

      </Grid>
  - type: mdx
    title: Details
    content: >-
      Keeping up <Boon name="Quickness"/> is a lot easier than with a <BuildLink
      build="Condi Firebrand" specialization="Firebrand"/> thanks to the
      increased <Attribute name="Boon Duration"/>. Nevertheless, it has less
      room for errors compared to <BuildLink build="Heal Firebrand"
      specialization="Firebrand"/>! General guidelines for keeping up <Boon
      name="Quickness"/>:


      - Use <Skill name="Feel My Wrath"/> whenever ready.


      - Use <Skill name="Mantra of Potence"/> off cooldown and <Skill name="Mantra of Solace"/> every 7 seconds due to the cooldown of <Trait name="Liberators Vow"/>


      - Only use these skills close to your allies - try to "puke" on them with the mantras


      - Keep in mind that equipping/stowing a tome grants you (only you, not your party members!) 3 seconds of <Boon name="Quickness"/> every 8 seconds thanks to <Trait name="swift scholar"/>!


      <Message>

      To play <Trait name="Legendary Lore"/> you need to have at least 60% boon duration to upkeep <Boon name="Quickness"/>. Both the Seraph and the Celestial builds have 40% from gear. meaning you will need to get the rest from agony resistance and consumables. If you cannot get enough boon duration to be safe just play with <Trait name="Stalwart Speed"/>!

      </Message>


      The rotation is a **lot** simpler compared to any other <Specialization name="Guardian"/> build (except for HFB where your weapons do not have immediate effect on how efficient the build is). However, weapon swaps require careful consideration, because it is not efficient to be stuck on staff or to have less than 25 <Boon name="might"/> during a damage phase.\

      Getting the weapon swaps right is probably the hardest part (more info below). Generally, it is recommended to always camp Axe/Torch and only swap to staff to use <Skill name="Empower"/> to top up <Boon name="Might"/>.

      **General information:**


      - On Axe/Torch:

        - Use <Skill name="Symbol of Vengeance"/>

        - Use <Skill name="Zealots Flame"/> into <Skill name="Zealots Fire"/>

        - Use <Skill name="Cleansing Flame"/>

        - Try not to interrupt you auto attack chain

        - Make sure to have <Skill name="Blazing Edge"/> ready for when you need to CC or need to pull in any adds.

      - In <Skill name="Tome of Justice"/>:

        - Your standard DPS rotation is Chapter 2: Igniting Burst (F1-2), Chapter 4: Scorched Aftermath (F1-4), Epilogue: Ashes of the Just (F1-5), Chapter 1: Searing Spell (F1-1), Igniting Burst (F1-2).

        - Don't be afraid to replace a skill, preferably Chapter 1: Searing Spell (F1-1) or Chapter 2: Igniting Burst (F1-2), with Chapter 3: Heated Rebuke (F1-3) for more CC or to pull any adds.

      - On Staff:

        - Use <Skill name="Empower"/>

        - Blast fire fields with <Skill name="holystrike"/>. If there is no fire field you can put one down with tome1-4

        - Use <Skill name="Symbol of Swiftness"/>

      - Apart from that:

        - <Skill name="Sanctuary"/> or <Skill name="Bane Signet"/> to break defiance bars. Using <Skill name="Bane Signet"/> to provide the group with a temporary 216 <Attribute name="Power"/> buff (Should also be used when there is no defiance bar ready but it will be off cooldown for the next phase).

        - Remember to be smart about your free utility swap and adjust as necessary to the encounter and your party.

      Suggested key moments to swap to staff and <Skill name="Empower"/>:


      - **MAMA**: There is no exact key moment and you need to decide on your own when to swap to staff.


      - **Siax**: This build has quite good damage and is fairly self sustained enabling you to kill your add quickly. Swap to staff for the last few percent and be ready to <Skill name="Empower"/> in the middle. This works better the slower the group is due to weapon swap cooldown. If another person helps you kill your add (typically the <Specialization name="Renegade"/>) you can chill on staff for the add so you are ready to swap to Axe/Torch sooner.


      - **Enso**: Be on staff at the beginning of every phase and use <Skill name="Empower"/> while Ensolyss is invulnerable.


      - **Skorvald**: Anomalies 2 and 4. In case your group gets too fast you might have to skip <Skill name="Empower"/> at the 2nd island. When using the 66% portal make sure to drop a <Skill name="Symbol of Swiftness"/> on Skorvald before swapping to Axe/Torch.


      - **Artsariiv**: If your party deals the majority of its damage in the middle you want to empower at 66% and 33% shortly before she becomes vulnerable. If not you may empower while she is jumping away and the team kills the Anomaly.


      - **Arkk**: Finish your orb first by camping in the light field and auto attacking with the superior weapon (staff) so you can precast <Skill name="Empower"/> and <Skill name="Symbol of Swiftness"/>.


      - **Ai**: On light Ai you will want to <Skill name="Empower"/> mid at the beginning of the fight and after each split phase. You should also swap to Staff during the split mechanic so you can cast <Skill name="Empower"/> as everyone returns to the middle. On Dark Ai this is mostly the same aside from the lack of split phases so keep an eye on <Boon name="might"/> and be ready to swap to Staff when needed. Remember with the amount of movement on this fight to be casting <Skill name="Symbol of Swiftness"/> where possible to help keep everyone moving.


      Tomes are very useful when no other skills are ready. <Skill name="Tome of Justice"/> also gets refreshed every time an enemy dies (works with anomalies at Artsariiv/Arkk, knights at MAMA and hallucinations at Siax).


      <Skill name="Tome of Courage"/> and <Skill name="Tome of Resolve"/> are great for high incoming damage scenarios.


      - <Skill name="Tome of Resolve"/> (F2):

        - Skill 2 is a party condition cleanse

        - Skill 3 grants <Boon name="Vigor"/>, <Boon name="Regeneration"/> and <Boon name="Swiftness"/>

        - Skill 4 is a good party heal

        - Skill 5 increases healing on allies for 8s by 33% and converts up to 5 conditions to boons

      - <Skill name="Tome of Courage"/> (F3):

        - Skill 1 grants <Boon name="Stability"/> and <Boon name="Swiftness"/>

        - Skill 3 is a 5s reflect

        - Skill 4 grants <Boon name="Resistance"/> and breaks stun

        - Skill 5 grants <Boon name="Aegis"/>, <Boon name="Protection"/>, <Boon name="Stability"/> and 300 toughness for 5 seconds
rating: Good
role: Hybrid
profession: Guardian
specialization: Firebrand
skills:
  - 9153
  - 9251
  - 9084
  - 9128
  - 9093
conditions:
  - Burning
boons:
  - Quickness
  - Fury
  - Might
  - Stability
  - Swiftness
  - Aegis
code: "[&DQEQGjEvPj5LFwAAehYAAAAAAAAWAQAAiRIAAAAAAAAAAAAAAAAAAAAAAAA=]"
hasCMGuide: false
classification:
  - 4
  - 3
  - 4
  - 3
  - 4
character:
  - gear: |-
      {
        "gear": [
          "Seraph",
          "Seraph",
          "Seraph",
          "Seraph",
          "Seraph",
          "Seraph",
          "Seraph",
          "Seraph",
          "Seraph",
          "Seraph",
          "Seraph",
          "Seraph",
          "Seraph",
          "Seraph"
        ],
        "attributes": {
          "Health": 17145,
          "Armor": 2514,
          "Power": 1790,
          "Precision": 2566,
          "Toughness": 1243,
          "Vitality": 1550,
          "Ferocity": 300,
          "Condition Damage": 2788,
          "Expertise": 0,
          "Concentration": 876,
          "Healing Power": 883,
          "Agony Resistance": 162,
          "Condition Duration": 0,
          "Boon Duration": 58.4,
          "Critical Chance": 109.57142857142857,
          "Critical Damage": 170,
          "Burning Duration": 105,
          "Effective Power": 4374.3125,
          "Power DPS": 3776.3606565267614,
          "Burning Damage": 971.4164999999999,
          "Burning Stacks": 24.4,
          "Burning DPS": 23702.562599999997,
          "Bleeding Damage": 283.92,
          "Bleeding Stacks": 3.7,
          "Bleeding DPS": 1050.5040000000001,
          "Poison Damage": 301.17,
          "Poison Stacks": 0,
          "Poison DPS": 0,
          "Torment Damage": 424.0799999999999,
          "Torment Stacks": 0,
          "Torment DPS": 0,
          "Confusion Damage": 283.92,
          "Confusion Stacks": 0,
          "Confusion DPS": 0,
          "Damage": 28529.42725652676,
          "Effective Health": 59265978.75,
          "Survivability": 30130.13662938485,
          "Effective Healing": 720.39,
          "Healing": 720.39
        },
        "infusions": [
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130
        ],
        "weight": "Heavy",
        "runeId": 24765,
        "runeName": "Balthazar",
        "weapons": {
          "weapon1MainType": "Axe",
          "weapon1MainSigil1": "bursting",
          "weapon1OffType": "Torch",
          "weapon1OffSigil": "smoldering",
          "weapon2MainType": "Staff",
          "weapon2MainSigil1": "transferance",
          "weapon2MainSigil2": "smoldering"
        },
        "consumables": {
          "food": "bowl-of-fire-meat-chili",
          "utility": "toxic-focusing-crystal",
          "infusion": "Mighty +9 Agony Infusion"
        }
      }
    title: Seraph
    note: '**This is the standard build variant. It provides higher damage then the
      Celestial build in fractals whilst still providing more than enough
      support for most groups.** This setup currently overcaps <Condition
      name="Burning"/> duration. If you want to optimise for 100%, swap one
      Accessory to Vipers and use <Item id="92505"/>'
  - title: Celestial
    gear: |-
      {
        "gear": [
          "Celestial",
          "Celestial",
          "Celestial",
          "Celestial",
          "Celestial",
          "Celestial",
          "Celestial",
          "Celestial",
          "Celestial",
          "Celestial",
          "Celestial",
          "Celestial",
          "Celestial",
          "Celestial"
        ],
        "attributes": {
          "Health": 23535,
          "Armor": 3153,
          "Power": 2429,
          "Precision": 1962,
          "Toughness": 1882,
          "Vitality": 2189,
          "Ferocity": 939,
          "Condition Damage": 2290,
          "Expertise": 709,
          "Concentration": 882,
          "Healing Power": 889,
          "Agony Resistance": 162,
          "Condition Duration": 47.266666666666666,
          "Boon Duration": 58.8,
          "Critical Chance": 80.80952380952381,
          "Critical Damage": 212.6,
          "Burning Duration": 70,
          "Effective Power": 6668.827162916666,
          "Power DPS": 5757.223911921125,
          "Burning Damage": 838.2637499999998,
          "Burning Stacks": 24.4,
          "Burning DPS": 20453.635499999997,
          "Bleeding Damage": 239.10000000000002,
          "Bleeding Stacks": 5.4488666666666665,
          "Bleeding DPS": 1302.82402,
          "Poison Damage": 256.35,
          "Poison Stacks": 0,
          "Poison DPS": 0,
          "Torment Damage": 356.85,
          "Torment Stacks": 0,
          "Torment DPS": 0,
          "Confusion Damage": 239.10000000000002,
          "Confusion Stacks": 0,
          "Confusion DPS": 0,
          "Damage": 27513.683431921123,
          "Effective Health": 102033050.625,
          "Survivability": 51872.42024656838,
          "Effective Healing": 722.3700000000001,
          "Healing": 722.3700000000001
        },
        "infusions": [
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130
        ],
        "weight": "Heavy",
        "runeId": 24765,
        "runeName": "Balthazar",
        "weapons": {
          "weapon1MainType": "Axe",
          "weapon1MainSigil1": "bursting",
          "weapon1OffType": "Torch",
          "weapon1OffSigil": "earth",
          "weapon2MainType": "Staff",
          "weapon2MainSigil1": "bursting",
          "weapon2MainSigil2": "transference"
        },
        "consumables": {
          "foodId": "86997",
          "utility": "toxic-focusing-crystal",
          "infusion": "Mighty +9 Agony Infusion"
        }
      }
    note: '**This build bursts less than the Seraph variant but the difference is
      minimal. It also has the advantage of having more survivability due to
      gaining <Attribute name="Vitality"/> and <Attribute name="Toughness"/>
      from the Celestial stat type.** Playing full Celestial does over cap
      <Condition name="burning"/> duration, so if you want to optimize you can
      swap all but one of your trinkets (including your back item) to Seraphs,
      leaving one Celestial Accessory.'
  - title: Celestial Heal
    note: '**This build has much higher <Attribute name="Concentration"/> and
      <Attribute name="Healing Power"/> , with the trade off being it deals less
      damage. This variant is more suited to use in groups who are less
      confident and require more support or if you want to have more of a safety
      net to carry your party.**'
    gear: |-
      {
        "gear": [
          "Celestial",
          "Celestial",
          "Celestial",
          "Celestial",
          "Celestial",
          "Celestial",
          "Celestial",
          "Celestial",
          "Celestial",
          "Celestial",
          "Celestial",
          "Celestial",
          "Celestial",
          "Celestial"
        ],
        "attributes": {
          "Health": 23535,
          "Armor": 3153,
          "Power": 2429,
          "Precision": 1962,
          "Toughness": 1882,
          "Vitality": 2189,
          "Ferocity": 939,
          "Condition Damage": 2049,
          "Expertise": 744,
          "Concentration": 882,
          "Healing Power": 1064,
          "Agony Resistance": 162,
          "Condition Duration": 49.6,
          "Boon Duration": 73.8,
          "Critical Chance": 80.80952380952381,
          "Critical Damage": 212.6,
          "Burning Duration": 40,
          "Effective Power": 6668.827162916666,
          "Power DPS": 5757.223911921125,
          "Burning Damage": 773.8263749999999,
          "Burning Stacks": 23.131199999999996,
          "Burning DPS": 17899.532645399995,
          "Bleeding Damage": 217.41,
          "Bleeding Stacks": 5.535200000000001,
          "Bleeding DPS": 1203.407832,
          "Poison Damage": 234.66,
          "Poison Stacks": 0,
          "Poison DPS": 0,
          "Torment Damage": 324.315,
          "Torment Stacks": 0,
          "Torment DPS": 0,
          "Confusion Damage": 217.41,
          "Confusion Stacks": 0,
          "Confusion DPS": 0,
          "Damage": 24860.164389321122,
          "Effective Health": 92757318.75,
          "Survivability": 47156.74567869853,
          "Effective Healing": 936.1440000000001,
          "Healing": 936.1440000000001
        },
        "infusions": [
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          37130,
          86113
        ],
        "weight": "Heavy",
        "runeId": 24842,
        "runeName": "Monk",
        "weapons": {
          "weapon1MainType": "Axe",
          "weapon1MainSigil1": "bursting",
          "weapon1OffType": "Torch",
          "weapon1OffSigil": "smoldering",
          "weapon2MainType": "Staff",
          "weapon2MainSigil1": "transference",
          "weapon2MainSigil2": "smoldering"
        },
        "consumables": {
          "food": "bowl-of-fire-meat-chili",
          "utility": "toxic-focusing-crystal",
          "infusion": "Mighty +9 Agony Infusion"
        }
      }
date: 2021-09-16T19:32:15.738Z
---
<Divider text="Rotation"/>

<Grid>
<GridItem xs="12" sm="6">
<Card title="Example opener">

**Staff/Axe - Torch "Rotation":**

1.  <Skill name="Symbol of Swiftness" profession="guardian"/> (Staff 3)

2.  <Skill name="Holystrike"/> (Staff 2)

3.  **Weapon Swap**

4.  <Skill name="Zealots Flame" profession="guardian"/> (Torch 4)

5.  <Skill name="Symbol of Vengeance " profession="guardian"/> (Axe 2)

6.  <Skill name="Zealots Fire" profession="guardian"/> (Torch 4) (Use twice if available)

7.  <Skill name="Tome of Justice" profession="guardian"/> (F1)

    1.  Chapter 2: Igniting Burst (F1-2)

    2.  Chapter 4: Scorched Aftermath (F1-4)

    3.  Epilogue: Ashes of the Just (F1-5)

    4.  Chapter 1: Searing Spell (F1-1)

    5.  Chapter 2: Igniting Burst (F1-2)

8.  <Skill name="Cleansing Flame" profession="guardian"/> (Torch 5)

9.  <Skill name="Zealots Flame" profession="guardian"/> (Torch 4)

10. <Skill name="Zealots Fire" profession="guardian"/> (Torch 4)

11. <Skill name="Symbol of Vengeance " profession="guardian"/> (Axe 2)

12. Auto Attack

</Card>
</GridItem>

<GridItem xs="12" sm="6">
<Card title="Precasting">

If you have a _Mistlock Singularity_ present you can use these skills for precasts:

1.  Cast <Skill name="tome of justice"/> skill 4 and 5

2.  Blast the fire field by casting <Skill name="Holy Strike"/>

3.  Use <Skill name="Mantra of Potence"/> 3 times and <Skill name="Mantra of Solace"/> once due to the cooldown of <Trait name="Stalwart Speed"/>

4.  Use <Skill name="Empower"/> as you are sharing <Boon name="Quickness"/>.

5.  Use <Skill name="Feelmywrath"/>

6.  Use <Skill name="banesignet"/> (If you have it)

7.  Take _Mistlock Singularity_

8.  Use <Skill name="Feelmywrath"/>

</Card>
<Video title="Example Rotationby Ares" youtube="H3qHPXbFGyA" caption="The build used here is a different variation than the ones listed above, but the idea and survavability is essentially the same."/>
</GridItem>
</Grid>