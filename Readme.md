# Proposal for Semester Project

**Patterns & Trends in Environmental Data / Computational Movement
Analysis Geo 880**

| Semester:      | FS22                              |
|----------------|---------------------------------- |
| **Data:**      | Wild Boar Movement Data           |
| **Title:**     | Territorial Analysis of Wild Boar Trajectory Data  |
| **Student 1:** | Ramon Sager                       |
| **Student 2:** | Silvia Juen                       |

## Abstract 
<!-- (50-60 words) -->
- Since Wild Boar show at least to some extent (habitat dependent) territoriality, we want to find out, if we can, based on the given data, identify (core) territories of the tracked Individuals and territorial behaviours among these individuals....

## Research Questions
- Can we identify (core) territories of individual Wild Boar in their resting/sleeping sites and feeding grounds?
- Can we assess territorial behaviour among Wild Boar at the edges of these territories based on trajectoy data?  
    - i.e. may there be a relaxation in one habitat compared to the other?
 - Can we detect a change in the trajectory of the "intruder" after a spatio-temporal meet up between two Individuals?
    - Or do individuals temporaly avoid conspesifics, but still use the same territories in the feeding grounds.


## Results / products
<!-- What do you expect, anticipate? -->
- We expect that we can at least to some extent identify core territories. Given that, we further expect that these territories differ in size between the resting sites (the forest patch) and the feeding grounds (agricultural sites). 
- Further, we expect to observe changes in the trajectory of an Individual that intrudes the territory of another Individual, after they have met in close proximity. However, we expect this behaviour to be relaxed in the ressource rich feeding grounds, compared to the smaller forest patch, where they rest & sleep. 
- Another observation may be, that Individuals avoid each other more in a temporal manner, instead of spatially, in the feeding grounds.

## Data
- We will use the provided Wild Boar data. 
- Additionally, we might include agricultural land use data, provided by the canton of Bern and Forest Data form "geo.admin".

## Analytical concepts
<!-- Which analytical concepts will you use? What conceptual movement spaces and respective modelling approaches of trajectories will you be using? What additional spatial analysis methods will you be using? -->

- Kernel Density Estimation / Convex Hull
- Deriving Movement Parameters
- Temporal Matching
- 
-
-
-

## R concepts
<!-- Which R concepts, functions, packages will you mainly use. What additional spatial analysis methods will you be using? -->


- Packages (from what we know so far):
- readr        # to import tabular data (e.g. csv)
- dplyr        # to manipulate (tabular) data
- ggplot2      # to visualize data
- sf           # to handle spatial vector data
- terra        # To handle raster data
- lubridate    # To handle dates and times

## Risk analysis
<!-- What could be the biggest challenges/problems you might face? What is your plan B? -->
- The temporal resolution of the sampling might be not enough to identify specific behaviours (as territorial behaviour)

### Plan B
- Can we identify feeding occasions based on these data (focusing on the agricultural sites), and therefore further localise feeding territories?


## Questions? 
<!-- Which questions would you like to discuss at the coaching session? -->
