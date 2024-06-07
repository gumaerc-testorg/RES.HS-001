---
content_type: page
description: Students explore several images to motivate the ideas that several effects
  contribute to how much light is collected when making an image. Students then use
  CCD images and their understanding of exposure time and flux/luminosity to measure
  the luminosity of the Sun.
draft: false
title: 'Investigation 2: Light and Color - Activity 3'
uid: e3104162-f200-4b58-8321-c931c651eeb1
---
## **Developing and Using Flux/Luminosity Relationship**

**Overview:** Students explore several images to motivate the ideas that several effects contribute to how much light is collected when making an image. These factors must be included when translating between an image and a measurement of luminosity for an object. Students then use CCD images and their understanding of exposure time and flux/luminosity to measure the luminosity of the Sun.

**Electronic resources:** lightbulb comparison image ({{% resource_link "cc016c99-d094-4e22-a4b2-c666cf7cb7a4" "lightbulb\_brightness5.fits" %}}), Orion nebula 30-second exposure ({{% resource_link "05d8ea0c-527e-454f-b3f7-a449395298e3" "Orion\_30s.fits" %}}), Orion nebula 45-second exposure ({{% resource_link "507594c5-e8a6-434d-b107-661cb2e4f91f" "Orion45shifted.fits" %}})

Flexible Image Transport System (FITS) is a digital file format used to store, transmit, and manipulate scientific and other images. FITS is the most commonly used digital file format in astronomy. [DS9](http://hea-www.harvard.edu/RD/ds9/) is an application that supports these files and is [available for free](http://hea-www.harvard.edu/RD/ds9/).

**Instructor presents the goal:** We want to turn a measurement of an image into a measurement of the total amount of light emitted by a source. What has an effect on the number of counts we collect from an object? Notes: {{% resource_link "eb124e45-5255-4023-9bfe-a37d26bae5a4" "luminosity intro" %}}

**Observations about what affects number of counts obtained in an image of a certain source:**

- Actual light energy output: Students observe the difference between two bulbs in the same image, using the "counts in regions" Chandra Ed tool, using a circular region around each bulb. We collect more photons from the brighter bulb. Image showing two bulbs of different luminosity: {{% resource_link "cc016c99-d094-4e22-a4b2-c666cf7cb7a4" "lightbulb\_brightness5.fits" %}}
    - Teacher note: this "effect" is included in the luminosity term of the mathematical relation below.
- {{% resource_link "08df3061-3ece-4ac2-883a-45359515fff1" "Exposure time" %}}: Students observe the difference in counts between the same regions of two images of the same object (Orion nebula), taken with different exposure time. The longer exposure time image has higher counts in the same region.
    - Images of Orion nebula with different exposure times: Orion nebula 30-second exposure ({{% resource_link "05d8ea0c-527e-454f-b3f7-a449395298e3" "Orion\_30s.fits" %}}), Orion nebula 45-second exposure ({{% resource_link "507594c5-e8a6-434d-b107-661cb2e4f91f" "Orion45shifted.fits" %}}). 

Teacher note: This effect is included in the flux measurement.

- Area of the collector: Recall the classroom kinesthetic model: a larger collector will collect more of the light emitted.
    - Teacher note: This effect is included in the flux measurement.
- Distance from object to collector: Recall the classroom kinesthetic model: the further away the collector is, the less photons/light/energy it collects. (The graph paper collectors were illuminated less as we looked at them from behind.)
    - Teacher note: This effect is included in the distance term of the mathematical relation below.
- Collector efficiency: Recall that photons are measured when the detector turns them into electrons which are then counted, giving us our measurement of "counts." In this way, a certain amount of energy from a photon is turned into a certain number of counts.
    - Teacher note: This effect is included in the flux measurement.

**Develop a mathematical relationship describing how flux and luminosity are related:**

- Recall the relationship from classroom kinesthetic model, and derive the relationship between flux and luminosity: Notes: {{% resource_link "57501b06-e214-4979-a00a-a9ea29d183a5" "flux luminosity" %}}
    - Amount of light collected = fraction of light collected \* total amount of light emitted
    - Amount of light collected = (area of collector / area of sphere needed to collect **all** light) \* total amount of light emitted
    - Add in all the effects examined above to get more information about the "amount of light collected" term on the left. All this depends on what specific telescope/detector combination you are using:
        - Change from counts to energy for a particular telescope/detector combination using the collector efficiency (for light bulb image taken with MicroObservatory telescope, 1 count = 10<sup>\-8</sup> Joules)
        - Divide by exposure time (10 seconds in light bulb image taken with MicroObservatory telescope)
        - Divide by the collecting area of finder telescope on MicroObservatory (circular collecting area with 1.5-inch diameter) = 1.1 x 10<sup>\-3</sup> m<sup>2</sup>
- We obtain: Notes: {{% resource_link "ddcd8a61-d226-4003-91db-3f17c62c3c99" "flux luminosity math" %}}
    - Energy collected per second = (area of collector / area of sphere) \* energy emitted per second
    - In order to gather all the information that only comes from the telescope/detector on the left side of the equation, we rearrange to get energy collected per second / area of collector = energy emitted per second / area of sphere
    - These terms are defined as:
        - Flux = energy collected per second/ area of collector
        - Luminosity = energy emitted per second by the source
        - Area of sphere = 4 \* pi \* (distance from source to detector)<sup>2</sup>
    - Leaving us with the relationship:
        - Flux = luminosity / (4 \* pi \* (distance from source to detector)<sup>2</sup>)

{{< resource uuid="c2b35a9c-b949-4eec-a838-84738b60b244" >}}

## **Apply the mathematical relationship**

- Students predict the luminosity of a light bulb, using the flux obtained from an image of a 200-watt light bulb taken by MicroObservatory from an 11-meter distance. (Prediction should be about 20 watts, given about a 10% efficiency for light bulbs—other energy emitted as infrared light.)
    - Example calculation of lightbulb luminosity prediction, and regions used for background subtraction: {{% resource_link "437630dd-27dc-4cd2-aa29-f0f789d1a6b2" "lightbulb flux" %}}
- Students predict the luminosity of the Sun, using the flux obtained from an image of the sun taken by MicroObservatory. (Prediction from the image should be about 1.3 x 10<sup>25</sup> watts, with actual about 4 x 10<sup>26</sup> watts.)
    - Example calculation of sun luminosity prediction, and regions used for background subtraction: {{% resource_link "17536145-6ac6-40b5-b7d6-740967f35477" "sun flux" %}}, {{% resource_link "41e20948-f4b1-44bc-ad7b-f15adffd6faa" "sun luminosity" %}}, {{% resource_link "d4665de0-493b-4782-ac70-5b1e91f1109f" "sun luminosity2" %}}
- Wrap up challenge: Set up a hypothetical situation of two stars, asking students to predict from which star we'd receive a larger flux:
    - Notes: {{% resource_link "05bbff6f-6459-488e-ab83-57ba0adfa7e3" "flux comparisons" %}}
    - Star 1: Distance = D, Luminosity = 10 \* L<sub>sun</sub>, Star 2: Distance = D, Luminosity = 5 \* L<sub>sun</sub> (We collect more flux from star 1.)
    - Star 1: Distance = D, Luminosity = 10 \* L<sub>sun</sub>, Star 2: Distance = 2D, Luminosity = 10 \* L<sub>sun</sub> (We collect more flux from star 1.)
    - Star 1: Distance = D, Luminosity = 5 \* L<sub>sun</sub>, Star 2: Distance = 2D, Luminosity = 10 \* L<sub>sun</sub> (We **still** collect more flux from star 1, because distance has a larger effect. Easy to show if you take the ratio of the two fluxes, in terms of the luminosity and distance.
    - Example calculation of ratios of luminosity of these three stars: {{% resource_link "d7fa5190-eaf9-4f4b-923b-a2e11ef3c160" "comparing star flux1" %}}, {{% resource_link "e739880d-f514-41ce-a4cf-e42b58241c09" "comparing star flux2" %}}

**Teacher tips/tricks:**

- Timing: In 2008, this took about 4 hours, but was done in a much more time-consuming way of talking about each effect, and then explicitly calculating the different values for a particular image of a lightbulb taken with MicroObservatory.
- If desired, students can be **given** flux measured from the lightbulb and sun images and use the flux/luminosity relationship directly, or they can use the Chandra Ed "counts in regions" tool with a background to then make their own measurement. See example calculation.
- It may be easier to do the wrap-up challenge before the actual calculations, especially if students are still conceptually unclear about flux and luminosity.

**Assessment:**

- How is the way a detector works different from how our eyes work? What happens if we "expose" our eyes for a longer time? (Our eyes "read out the detector" about every 1/30 of a second, so we continually "take images.")
- Define and or diagram flux and luminosity in terms of the particle model of light (i.e. use the words photon, straight lines, and collector).
- What are the units of each quantity? Flux, luminosity and distance.
- Which of the following are associated with flux, and which with luminosity?
    - Units: joules/sec/m<sup>2</sup>, joules/sec
    - Energy collected, energy emitted
    - observation, prediction
    - Would be a different number if we lived on Mars. Would not be a different number if we lived on Mars.
- In our efforts today, what were the observations (distance and flux, as determined from the image) and what were predictions (luminosity of the bulb and Sun) and what were the models (the mathematical relation itself)?
- How is the mathematical model (equation) we developed here similar to and different from the model of colored shapes we built in investigation 1?
- Some students have said that flux is like an "angular luminosity". How is the relationship between flux and luminosity similar to the relationship between angular width and linear width?

{{< resource uuid="892befbb-472d-4a76-814b-9555f6388de6" >}}