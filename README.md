# Rat Infrastructures 

Open data and visualization companion to the chapter "Mapping Unwanted Relatedness: Rat-zones, Expertise, and the Ambivalence of Care in Western Medellín" by Santiago Orrego, in C. Ritter and T. Pikner (eds.), *Expertise and Environmental Care in Multispecies Worlds* (Routledge, 2027). The chapter follows rat-human encounters in western Medellín, Colombia, as brief collisions that reorganize everyday space into "rat-zones". This repository shares the encounter records behind the chapter's diagrams. The records trace where noticing happened, not a census of rats. 

## Data 

`Data/rat_observations.csv` contains 166 encounter records from two observation sites, collected on 15 days between 4 and 18 October 2021. The neighborhood is anonymized, and the file contains no street or institution names. 

| Column           | Description                                                  |
| ---------------- | ------------------------------------------------------------ |
| `location`       | Observation site code (`G1`, `G2`)                           |
| `date`           | Day of observation, day/month/year                           |
| `time`           | Time of the encounter, 24-hour clock                         |
| `rats`           | Number of rats present (1 to 5)                              |
| `rats_actions`   | What the rats were doing: Running, Exploring, Eating, Walking a fence |
| `people`         | Number of people present (1 to 5)                            |
| `people_actions` | What the people were doing: Walking, Standing, Hunting       |
| `results`        | Outcome: People ran away, Rat ran away, Both ran away, No relation, Rat killed |
| `rats_killed`    | Number of rats killed in the encounter (0 to 2)              |

Each row is one encounter, coded with the chapter's outcome categories (see section 2.1 of the chapter). Records come from my observation at a "disciplined distance" and are shaped by fear, speed, and partial visibility. Some entries are reported by residents rather than seen by me.