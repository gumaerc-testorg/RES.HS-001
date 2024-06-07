---
content_type: page
description: Students learn about filtering, and get color estimates for low and high
  states, which for 4U1822, do not have significant differences.
draft: false
title: 'Investigation 5: Variable X-ray Sources - Activity 4'
uid: 2a5ae59d-331a-47f9-9c32-a30aa3a8a48d
---
## **Interpreting the Light Curve of 4U1822: Colors for High and Low States**

Note: During Summer 2008, this activity was dropped in favor of spending more time to understand the basic analysis of 4U1822, as it is more related to the independent investigation project on 4U2129. It was thought that filtering could be taught to just the groups who needed it, whereas defending an argument (activity 5) was required of all students.

**Physical resources:** None

**Electronic resources:** Restaurant analogy histogram data, energy histogram graph paper {{% resource_link "d766aac0-24d7-4ce7-bfac-66cb87806438" "restaurant energy histogram" %}}

**Overview:** Students learn about filtering, and get color estimates for low and high states, which for 4U1822, do **not** have significant differences.

**Extend restaurant analogy to filtering:**

- Give students handout with observations of both calories consumed **and** time each person left the restaurant, paired. {{% resource_link "3d0e2d80-6317-4c3a-bd2b-b1628374e5b8" "Observation file (PDF)" %}}
- Have students produce a "breakfast" energy histogram (i.e. only including calories consumed by people leaving between 8:00 and 11:00) and a "dinner" energy histogram (i.e. only including calories consumed by people leaving between 17:00 and 24:00)
- Draw an analogy with using the time filter on an image, and then extracting a spectrum, to see differences

**Students learn to filter the image, based on "interesting" light curve regions:**

- Extract a light curve, and then choose the lowest 1/3 of one period of the light curve to call the "low flux state" of the object, and the highest 1/3 of one period of the light curve to call the "high flux state" of the object.
- Use the "rebin image" Chandra Ed tool to filter in time and retain only those photons received during the "low flux state" in a resulting image. Process: filtering an image in time 
    - **Note**: only **one** time filtered region can be worked with at a time, as Chandra Ed will name the resulting time-filtered file the **same** thing.
    - Use the "energy cut" Chandra Ed tool to cut filtered images into low (0.3–2 keV), medium (2–4 keV) and high (4–8 keV) energy images.
    - For an annulus region, use the "Counts in regions" tool to record the number of counts in that region for the low, medium and high energy images.
    - Record these observations in a table showing counts in each energy range as well as percentage of total counts.
- Repeat above steps for the "high flux state" and add to the comparison chart. {{% resource_link "1d524dda-87e7-47eb-9fc5-1f816c608bb7" "Simple color analysis file (PDF)" %}}.
- Discuss what the lack of color change might mean. (There must not be significant absorption by clouds, which we saw can change the shape of the spectrum. Thus, the X-ray emitting object must be large enough to be seen, even when behind the companion star, as we also saw from the dip of the light curve that didn't go to zero.)

**Teacher tips/tricks:**

- Color differences are the first level of comparing how the spectrum of the object might vary over time. Indeed, students **will** examine how the spectrum changes in the project topic object 4U2129. However, Chandra observations with the diffraction grating are more complex and will not give an accurate spectrum when the Chandra Ed tools are used, which is why we limit ourselves to examining only colors (i.e. counts in different filtered images.)
- Although 4U1822 does not show significant color differences, other potential objects **do** show color or spectrum differences.
- Students can also generate a ratio between the flux received during the low and high flux states by comparing the **total** counts in each state, divided by the length of time for each time cut.

**Assessment ideas:**

- Describe what it would be like to be on a planet or spacecraft nearby to this object. How would it be different than being nearby our own sun?

## **Alternative/Additional Activity: Analysis of Two Additional Variable Sources**

Although during Summer 2008, there was not enough time, it is possible for students to repeat the complete analysis (light curves, linear sizes from light curves, and color information from high and low states) for two additional variable targets, given below. In this case, during activity 5, students could then present arguments about what they think **each** of the 3 analyzed objects might be. Alternatively, these two objects could serve as an additional independent investigation project.

Cyg X-1: Probable stellar mass black hole with orbiting dense clouds as part of accretion from massive companion. {{% resource_link "003cc52f-3453-47b0-b333-e2f67ddeca92" "Color analysis (PDF)" %}}

Burster GS 1826: An X-ray binary system where accretion onto surface of neutron star from companion star causes dramatic periodic increases in flux lasting ~100 seconds as a result of thermonuclear explosion of built up accreted matter. {{% resource_link "7890f4a3-8892-4bb2-bcde-19419fb263d6" "Color analysis (PDF)" %}}

{{% resource_link "4c972ea7-1349-4117-9360-b2f18ccd7ca4" "Summary of all three variable objects and their properties (PDF)" %}}