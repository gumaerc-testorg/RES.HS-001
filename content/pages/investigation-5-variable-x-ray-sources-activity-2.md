---
content_type: page
description: Students observe this object, which is seen through a grating. Students
  discover how a grating changes and limits the information available from the observation.
  Students learn to extract an X-ray light curve, and learn about error bars to reinforce
  their understanding of histograms.
draft: false
title: 'Investigation 5: Variable X-ray Sources - Activity 2'
uid: ea8eced3-10f2-44c2-ae16-32c206ff5f68
---
## **Extracting X-ray Light Curves: Binary Star 4U1822**

**Overview:** Students observe this object, which is seen through a grating. Students discover how a grating changes and limits the information available from the observation. Students learn to extract an X-ray light curve, and learn about error bars to reinforce their understanding of histograms.

**Physical resources:** diffraction gratings, incandescent bulb, coins

**Electronic resources:** X-ray image of 4u1822

**Exploration and review of diffraction gratings:**

- Students open the object 4u1822 (obsid 671), and describe what they see. Students create a three color image, using the energy ranges 0.3–2.0 keV (red), 2.0–4.0 keV (green), 4.0–8.0 keV (blue) **Process: energy cutting. Process: creating a three-color image.** Example image: {{% resource_link "fbfabb21-f246-467b-b237-dff6496926ac" "4u1822 true color" %}} 
    - Have we seen anything like this before? What must be different? (Some students may think the streaks coming out from the central object are jets, but they are not … see below.)
- Explain that the observation was taken with a grating in front of the detector. Show diagrams of Chandra telescope showing placement of grating and detector. 
    - Diagram of grating placement
    - Image of grating
    - [Interactive Chandra diagram showing relation of different parts](http://chandra.harvard.edu/about/interactiveCraft.html#)
- Review action of a grating: Students observe an incandescent source through a hand-held grating and describe how the pattern they see is similar to the Chandra observation. Give students two gratings to hold at an angle to each other to reproduce exactly what is seen in the three color image. ({{% resource_link "5056b906-cbbb-43af-81c2-41561d4e1c46" "cross dispersion" %}})

**Create a light curve:**

- Select appropriate region: annulus avoiding dark area in center of observation (pixels that have been overexposed, but are read out by Chandra as low counts), but with an outer radius of about 50 pixels (25 arcseconds) 
    - To use an annulus: "Region…Shape….Annulus", then click and drag to create an annulus on the image. Double click, and set the inner and outer radius, with "Annuli" = 1. Alternatively, drag the edges of the annulus using the mouse.
- Students use "Quick light curve" tool to extract a light curve: Process: extracting a light curve. ([Learning to use the DS9 imaging system](https://cxc.harvard.edu/ciao/threads/ds9/)) 
    - Assign different bin sizes to different groups. Bin width = 10 seconds, 100 seconds, 500 seconds, 1000 seconds and 5000 seconds.
    - Compare results among groups. At what bin size is the clearest pattern shown?
- Why are these different? Why would error bars be different? as a motivation for noise activity…

**Noise and error bars activity:**

- Discuss probability of obtaining "heads" on a coin toss: 50%
- Each group toss coin 4 times: record table with number of heads, number of tosses and percentage of heads on whiteboard table. Measurements show a wide spread around what we **know** to be the proper value.
- Toss coin in groups of more each, recording number of heads obtained after 4, 8, 16 and 32 tosses, and resulting percentage. 
    - Images: Student data table, and resulting observations: coin toss data, coin toss results
    - Observation: Repeated measurements show a smaller range, presumably around the "actual" value.
    - Model: Error bars indicate the range in which we'd find the actual value of a quantity.
- Student challenge: What are the advantages and disadvantages of narrow vs. wide bins? (Narrow = see changes in time easily **but** changes must be large to be real, as error bars are larger, Wide = error bars are smaller, but not as easy to see changes over time.)

**Teacher tips/tricks:**

- Error on a bin is related to the number of counts in that bin, which is why wider bins have smaller error bars. For bins with at least 10 counts, the error bar is approximately the square root of the number of counts. In this way, we see that a bin with 10 counts has an error.

**Assessment ideas:**

- Why would someone want to rename error bars "uncertainty bars" instead?
- Predict what you'd see in the true color grating image if you observed an object producing a spectrum with very low intensity at high energy? (The "streak" would show red and green parts, but no blue parts, or the blue parts would have very low intensity.
- Why do X-ray astronomers avoid looking at dim sources through gratings? (There are just not enough counts to get high numbers of counts when they are spread out by the grating.)

{{< resource uuid="eae43fe6-5014-4942-a60a-ba9566760b1f" >}}