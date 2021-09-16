---
skills:
  - 30815
  - 43739
effects:
  - Stealth
title: Power Holosmith
sections:
  - type: mdx
    title: General
    content: >-
      The <Specialization text="Power Holosmith" name="Holosmith"/> is a
      flexible build that can do well in a variety of different group
      compositions.

      It offers:

      - High burst and good sustained damage

      - Good crowd control

      - Good utility through <Condition name="Vulnerability"/> and access to some <Condition name="Blinded"/>, <Condition name="Crippled"/> and <Condition name="Immobile"/>

      - The ability to boonstrip with <Skill name="Detonate Mine Field"/> when running <Skill name="Throw Mine"/>

      - An increbile skill set for various skips in Tier 4 fractals due to access to <Effect name="Stealth"/>, as well as <Effect name="Superspeed"/> and a targeted leap with <Skill name="Jump Shot"/>

      - Some self-generation of <Boon name="Might"/>, <Boon name="Quickness"/> and <Boon name="Fury"/>


      The main thing the build lacks compared to other Power DPS classes is a unique party buff for Power compositions like <Specialization text="Power Dragonhunter" name="Dragonhunter"/>'s <Skill name="Bane Signet"/> share.


      There are 3 different versions of <Specialization text="Power Holosmith" name="Holosmith"/>, namely Sword ECSU, Sword PBM and Rifle PBM. They are named after:

      - The weapon they are holding, Sword+Shield vs Rifle.

      - The Grandmaster Holosmith Trait they use, Enhanced Capacity Storage Unit (ECSU) vs Photonic Blasting Module (PBM).
       
      This guide will focus mainly on the Sword ECSU variant since it is the most flexible of the 3.
  - type: equipment
    title: Equipment
    content: ""
  - type: mdx
    title: Default Build
    content: >-
      <Grid>

      <GridItem sm="7">

      <Traits traits1Id="38" traits1="Firearms" traits1SelectedIds="1914,1923,526" traits2Id="6" traits2="Explosives" traits2SelectedIds="1882,1892,1947" traits3Id="57" traits3="Holosmith" traits3SelectedIds="2106,2152,2137"/>


      </GridItem>


      <GridItem sm="5">

      <Skills healId="21659" utility1Id="6020" utility2Id="5818" utility3Id="42842" eliteId="42009"/>


      <Card title="Additional Skills">


      |                                           |                                                                                                                                                                                                               |

      | ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

      | Toolbelt                                  | <Skill id="21661" size="big" disableText/><Skill id="6172" size="big" disableText/><Skill id="6178" size="big" disableText/><Skill id="42163" size="big" disableText/>                                        |

      | <Skill id="6020" size="big" disableText/> | <Skill id="5806" size="big" disableText/><Skill id="5807" size="big" disableText/><Skill id="5808" size="big" disableText/><Skill id="5809" size="big" disableText/><Skill id="5810" size="big" disableText/> |


      </Card>


      </GridItem>

      </Grid>
  - type: mdx
    title: Variations
    content: >-
      <Grid>


      <GridItem sm="7">

      <Card title="Situational Traits">


      |                                                       |                                                                                                                    |

      | ----------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |

      | <Trait name="Photonic Blasting Module" size="big" disableText/> | When running the Rifle or Sword PBM build. |

      | <Trait name="Sanguine Array" size="big" disableText/> | If you are already crit capped without <Trait name="High Caliber"/> and struggle with <Boon name="Might"/> uptime. |


      <Traits traits1Id="21" traits1="Tools" traits1SelectedIds="532,512,1856" unembossed/>

      If your <Boon name="Quickness"/> uptime is low, you can swap out the Firearms trait line with Tools and replace <Skill id="5805"/> with <Skill id="43739"/>.


      <Traits traits1="Scrapper" traits1Selected="Gyroscopic Acceleration" unembossed />

      For many skips in Tier 4 fractals, you can swap to Scrapper for more <Effect name="Stealth"/> and <Effect name="Superspeed"/>. <Effect name="Stealth"/> can be provided through <Skill name="Sneak Gyro"/>. <Effect name="Superspeed"/> is provided through Gyros with a delay due to <Trait name="Gyroscopic Acceleration"/>. <Skill name="Medic Gyro"/> also provides some instant <Effect name="Superspeed"/> on top. <Skill name="Bulwark Gyro"/> and <Skill name="Purge Gyro"/> can be used without drawing aggro from enemies. <Skill name="Bypass Coating"/> can provide some instant <Effect name="Superspeed"/> as well.

      </Card>

      </GridItem>


      <GridItem sm="5">

      <Card title="Situational Skills">


      |                                            |                                                                                                                                                                                                       |

      | ------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

      | <Skill id="5977" size="big" disableText/>  | You can equip <Skill id="5927"/> shortly before the fight and precast its toolbelt skill if you want to go the extra mile.                                                                            |

      | <Skill id="5857" size="big" disableText/>  | An alternative heal skill if condition cleanse is needed, you can cast it AFTER (cause of water field) firefield to blast might.                                                                      |

      | <Skill id="43739" size="big" disableText/> | Another (group) block that even reflects projectiles if heat is above 50. (replace it with <Skill id="6020"/>)                                                                                        |

      | <Skill id="30337" size="big" disableText/> | Good alternative for burst, replace it with <Skill id="5818"/>. Very effective **countermeasure for <Instability name="No Pain, No Gain"/>**! Can stack multiple <Skill id="6164"/> before the start. |


      </Card>

      </GridItem>

      </Grid>
  - type: mdx
    title: Rotation/Skill Usage
    content: >
      <Grid>

      <GridItem sm="7">

      <Card title="Rotation">


      1.  **Preheat to 90%**


      2.  <Skill name="Laser Disk" profession="Engineer"/>


      3.  <Skill name="engage Photon Forge" profession="Engineer"/>


      4.  <Skill name="Prime light beam" profession="Engineer"/> (To help with CCing)


      5.  <Skill name="Grenade Barrage" profession="Engineer"/>


      6.  <Skill name="Corona Burst" profession="Engineer"/>


      7.  <Skill name="Photon Blitz" profession="Engineer"/>


      8.  <Skill name="Light Strike" profession="Engineer"/>

          1.  <Skill name="Bright Slash" profession="Engineer"/>

          2.  <Skill name="Flash Cutter" profession="Engineer"/>

          3.  x2

      9.  <Skill name="Corona Burst" profession="Engineer"/>


      10. <Skill name="Deactivate Photon Forge" profession="Engineer"/>


      11. <Skill name="Refraction Cutter" profession="Engineer"/>


      12. <Skill name="Shrapnel Grenade" profession="Engineer"/>

          1.  <Skill name="Poison Grenade" profession="Engineer"/>

      13. <Skill name="Sun Edge" profession="Engineer"/>

          1.  <Skill name="Sun Ripper" profession="Engineer"/>

          2.  <Skill name="Gleam Saber" profession="Engineer"/>

          3.  x2

      14. <Skill name="Refraction Cutter" profession="Engineer"/>


      15. <Skill name="Shrapnel Grenade" profession="Engineer"/>


      16. <Skill name="Sun Edge" profession="Engineer"/>

          1.  <Skill name="Sun Ripper" profession="Engineer"/>

          2.  <Skill name="Gleam Saber" profession="Engineer"/>

          3.  x2

      17. <Skill name="Refraction Cutter" profession="Engineer"/>

          1.  <Skill name="Blowtorch" profession="Engineer"/>

      18. <Skill name="Shrapnel Grenade" profession="Engineer"/>


      19. <Skill name="engage Photon Forge" profession="Engineer"/> (your heat should be around 90%)


      20. Repeat from step 4


      </Card>

      </GridItem>


      <GridItem sm="5">

      <Card title="Notes and Tips">


      - Don't interrupt your auto attack chain in Photon Forge


      - Keep in mind that <Trait id="2106"/> consumes its charges while <Trait id="2122"/> is a duration buff.


      - Use <Skill id="42842"/> and <Skill id="42009"/> off cooldown.


      - Use <Skill id="6178"/> and <Skill id="42163"/> off cooldown.


      - Make use of <Skill id="5808"/> to mitigate damage in add heavy fights.


      - <Skill id="5830"/> can help in controlling movement of enemies without breakbar.


      - Never <Skill id="44386"/>, always try to <Skill id="41123"/> at 149 heat.


      You can switch to <Specialization name="Scrapper"/> and equip <Skill id="30815"/> if you need <Effect name="Stealth"/> for longer passages (e.g. [Twilight Oasis Fractal](https://discretize.eu/fractals/twilight-oasis)). It provides >40 seconds for the whole group. A smoke field can also be provided by <Skill id="5824"/> to blast <Effect name="Stealth"/>.

      </Card>


      <Card title="CC skills">


      |                     |            |

      | ------------------- | ---------- |

      | <Skill id="21661"/> | 100 damage |

      | <Skill id="6057"/>  | 100 damage |

      | <Skill id="42009"/> | 232 damage |

      | <Skill id="42521"/> | 232 damage |

      | <Skill id="42521"/> | 232 damage |


      </Card>

      </GridItem>

      </Grid>
rating: Good
role: Power Damage
profession: Engineer
specialization: Holosmith
conditions:
  - Vulnerability
  - Blinded
  - Crippled
  - Immobile
code: "[&DQMGOyYfOSsqDyoPowCGAIYAowBXFlcW8BWJAQAAAAAAAAAAAAAAAAAAAAA=]"
hasCMGuide: false
classification:
  - 2
  - 4
  - 4
  - 3
  - 4
character:
  - title: 150 Agony Resistance
    gear: |-
      {
        "gear": [
          "Berserker",
          "Berserker",
          "Berserker",
          "Berserker",
          "Berserker",
          "Berserker",
          "Berserker",
          "Berserker",
          "Berserker",
          "Berserker",
          "Berserker",
          "Berserker",
          "Berserker",
          "Berserker"
        ],
        "attributes": {
          "Health": 15922,
          "Armor": 2343,
          "Power": 3946,
          "Precision": 2286,
          "Toughness": 1225,
          "Vitality": 1000,
          "Ferocity": 1856,
          "Condition Damage": 850,
          "Expertise": 0,
          "Concentration": 225,
          "Healing Power": 0,
          "Agony Resistance": 150,
          "Condition Duration": 0,
          "Boon Duration": 15,
          "Critical Chance": 111.23809523809524,
          "Critical Damage": 273.73333333333335,
          "Bleeding Duration": 33,
          "Effective Power": 32200.5492289586,
          "Power DPS": 44884.86261410479,
          "Burning Damage": 377.703125,
          "Burning Stacks": 4,
          "Burning DPS": 1510.8125,
          "Bleeding Damage": 104.9375,
          "Bleeding Stacks": 15.561,
          "Bleeding DPS": 1632.9324375,
          "Poison Damage": 121.46875,
          "Poison Stacks": 2,
          "Poison DPS": 242.9375,
          "Torment Damage": 155.68125,
          "Torment Stacks": 0,
          "Torment DPS": 0,
          "Confusion Damage": 104.9375,
          "Confusion Stacks": 0,
          "Confusion DPS": 0,
          "Damage": 48271.54505160479,
          "Effective Health": 46631557.5,
          "Survivability": 23706.943314692424,
          "Effective Healing": 390,
          "Healing": 390
        },
        "infusions": [
          37131,
          37131,
          37131,
          37131,
          37131,
          37131,
          37131,
          37131,
          37131,
          37131,
          37131,
          37131,
          37131,
          37131,
          37131,
          37131,
          37131,
          37131
        ],
        "weight": "medium",
        "runeId": 24836,
        "runeName": "Scholar",
        "weapons": {
          "weapon1MainType": "Sword",
          "weapon1MainSigil1": "force",
          "weapon1OffType": "Shield",
          "weapon1OffSigil": "impact",
          "weapon2MainSigil2": "impact"
        },
        "consumables": {
          "food": "bowl-of-sweet-and-spicy-butternut-squash-soup",
          "utility": "superior-sharpening-stone",
          "infusion": "Mighty +9 Agony Infusion"
        }
      }
    note: Due to the naturally high crit-chance from the Firearms Trait Line, this
      build does not rely on high Agony Resistance to reach crit-cap. You will
      only need higher AR or Assassin pieces if you want to swap to <Trait
      name="Sanguine Array"/> for better self-generated <Boon name="Might"/>.
date: 2021-09-16T12:03:40.050Z
benchmark:
  small:
    dps: 38143
    by: TJ [SC]
    youtube: p6mZtHhu7GM
---
.