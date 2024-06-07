---
content_type: page
description: Students learn how images are displayed in order to gather the maximum
  information from them using contrast and bias settings. Students apply color tables
  to create a false color image.
draft: false
title: 'Investigation 2: Light and Color - Activity 2'
uid: bb1d0c90-031d-4fd8-b970-edaabac98829
---
## **Introduction to Image Processing**

Information in images (counts in pixels) vs. how they are displayed (contrast/bias)

**Overview:** Students learn how images are displayed in order to gather the maximum information from them using contrast and bias settings. Students apply color tables to create a false color image.

**Electronic resources:** MOBS Prudential Center image ({{% resource_link "0dbb5f38-1779-4825-8b71-2539d76bde47" "PrudentialCenterMicoObs.fits" %}}), {{% resource_link "83369edf-8048-40a5-9740-e3230357465c" "prudential1" %}}, {{% resource_link "91b0b150-ec1d-480a-b06a-b64031ec7eae" "prudential2" %}}, {{% resource_link "dc280760-d9a4-4581-ade0-a6c27cb1fd21" "prudential3" %}}, {{% resource_link "972e6fe1-63a2-4453-92a8-63644b1330be" "orion1" %}}, {{% resource_link "b609aac3-8dec-4655-a9e5-f7d76579df0c" "orion2" %}}, {{% resource_link "d4bc165d-211f-4f0d-9c50-bbf240813779" "orion3" %}}, Orion image ({{% resource_link "2dce9455-f5ab-4921-a5bc-5d9c7a014713" "orionChallenge.fits" %}}), Challenge images (to be reproduced): {{% resource_link "8094a6da-c5cf-4203-81c1-d97859f99427" "Orion (PDF" %}}), {{% resource_link "07d07aa0-38fe-4a4e-86fa-e79d43734765" "prudential (PDF)" %}}

Flexible Image Transport System (FITS) is a digital file format used to store, transmit, and manipulate scientific and other images. FITS is the most commonly used digital file format in astronomy. [DS9](http://hea-www.harvard.edu/RD/ds9/) is an application that supports these files and is [available for free](http://hea-www.harvard.edu/RD/ds9/).

**Discuss: How do we measure the amount of light collected by a detector?**

- Relate "counts" which are the value of each pixel to the particle model of light. Each photon collected is turned into a certain number of electrons which are counted by electronics. More photons → more counts. Demonstrate with an image in DS9.
- Note: Whenever we measure light, we are really measuring what our instrument "packages," so we have to understand how it works to turn that measurement **back** into a real physical quantity. (Noise comes from packaging effects…)

**Demonstrate in small groups:**

- In DS9, show how to use the contrast (right click or control click (Mac) and move up and down), bias (right click or control click (Mac) and move left and right), color tables ("Color" from toolbar) and changes in scale ("Scale" from toolbar) to alter how an image is displayed.
- For each tool: Instructor demonstrates on a terrestrial image (Prudential tower image), then students repeat analysis.
- Instructor then gives a challenge to have students make the image look like a new example, without being shown how to do it. Each new example should highlight an important feature of the object that is not immediately obvious when first opened. In other words, changing how an image is displayed allows us to see or highlight different features of the image. 
    - Possible challenge images: {{% resource_link "83369edf-8048-40a5-9740-e3230357465c" "prudential1" %}}, {{% resource_link "91b0b150-ec1d-480a-b06a-b64031ec7eae" "prudential2" %}}, {{% resource_link "dc280760-d9a4-4581-ade0-a6c27cb1fd21" "prudential3" %}}
    - "Key" to image processing settings to create these images: {{% resource_link "07d07aa0-38fe-4a4e-86fa-e79d43734765" "prudential (PDF)" %}}
- Continue this process with an astronomical image (Orion nebula), giving the students three different challenges to point out three different features. 
    - Possible challenge images: {{% resource_link "972e6fe1-63a2-4453-92a8-63644b1330be" "orion1" %}}, {{% resource_link "b609aac3-8dec-4655-a9e5-f7d76579df0c" "orion2" %}}, {{% resource_link "d4bc165d-211f-4f0d-9c50-bbf240813779" "orion3" %}}
    - "Key" to image processing settings to create these images: {{% resource_link "8094a6da-c5cf-4203-81c1-d97859f99427" "Orion (PDF)" %}}. For each case of image processing settings, have the students check the highest and lowest brightness pixel. They will **always** be the same, because image processing does **not** change the count values, just how they are displayed.

Wrap-up discussion: How does adding color help us see brightness (flux) differences better? Give an example.

**Teacher tips/tricks:**

- Timing: This can take as little as 30 minutes.
- Having multiple instructors show small groups how to use the tools is most effective, including giving them the "processing challenges" to reproduce.
- To save time, we also tried showing two groups at once how to do a step, then let students try it out themselves, while instructors went around helping anyone who was really stuck.

**Assessment ideas:**

- Have students explicitly write out their response to the above wrap-up question.
- Students should predict what tools were used to make changes between two example displays of the same image. (See example images)