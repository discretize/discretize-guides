# discretize-guides

Welcome to the discretize-guides source folders! All our content is located here and can easily be updated using GitHub's versioning system.

## Contribute

You can contribute either directly by forking, editing pages and submitting pull requests or indirectly by opening issues. Any help is appreciated!

### Discretize Markdown Language

All our guides are written using an extended version of the [Markdown Language](http://commonmark.org/). You can try it out yourself using the [Discretize Markdown Editor](http://d2aixolucmz3zk.cloudfront.net/editor)!

### Guide index files

You'll notice that each of our guide sections (Mechanics, Builds, Fractals) have an `index.json` file inside their root directory. This file stores an **array of guide groups** (like _Meta Builds_, _Great Builds_, _Challenge Mode Fractals_) where each group contains the **guide items** (like _Power Weaver_, _Cliffside Fractal_).

#### Below is a full list of possible fields for the guide group object:

| Field       | Example                                        | Description                                      |
| ----------- | ---------------------------------------------- | ------------------------------------------------ |
| id          | `"advanced mechanics"`                         | The group id                                     |
| header      | `"Advanced Mechanics"`                         | The group header, displayed on the overview page |
| description | `` | (Optional) Group description, in markdown |
| itemsPerRow | `2`                                            | How many card items should be displayed per row  |
| items       | `{ ... }`                                      | The actual guide items                           |

#### These are the fields of the guide item:

| Field       | Example                           | Description                                 |
| ----------- | --------------------------------- | ------------------------------------------- |
| id          | `"consumables`                    | The guide id, used for the url              |
| header      | `"Consumables"`                   | The guide header                            |
| meta        | `` | (Optional) Sub header        |
| description | `` | (Optional) Guide description |
| category    | `"mesmer"`                        | (Optional) Guide category, used for the url |

#### Professions guide specific fields:

| Field          | Example          | Description                                    |
| -------------- | ---------------- | ---------------------------------------------- |
| specialization | `"chronomancer"` | The build specialization                       |
| benchmark      | `{ ... }`        | Contains DPS numbers for small and large golem |
| perks          | `[ ... ]`        | Build perks like Quickness, Reflects, Stealth  |

#### Fractal guide specific fields:

| Field        | Example        | Description                                 |
| ------------ | -------------- | ------------------------------------------- |
| api          | `"3177`        | API daily T4 achievement id for the fractal |
| bosses       | `3`            | Amount of bosses present in the fractal     |
| difficulties | `[ ... ]`      |                                             |
| tiers        | `["CM", "T4"]` |                                             |
| record       |                |                                             |
| details      |                |                                             |
