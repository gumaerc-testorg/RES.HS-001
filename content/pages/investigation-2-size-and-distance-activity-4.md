---
content_type: page
description: Students learn that filters allow only certain colors/energies of light
  through, and that our experience of colors comes from combining three fundamental
  colors (RGB) in either our eyes or through three separate filtered images.
draft: false
title: 'Investigation 2: Light and Color - Activity 4'
uid: 7b8b6ef7-48c3-4512-824a-79084e0691f7
---
## **Measuring Color**

**Overview:** Students learn that filters allow only certain colors/energies of light through, and that our experience of colors comes from combining three fundamental colors (RGB) in either our eyes or through three separate filtered images.

**Physical resources:** colored construction paper, exit sign, diffraction grating, overhead projector, colored pencils/crayons.

**Electronic resources:** Observation/prediction blank tables ({{% resource_link "53b42a99-10e5-497c-8ad1-526747a5d14b" "three color observations table" %}}, {{% resource_link "77ddcac1-40ec-400f-8e56-9b82b5e46c81" "three color predictions table" %}}), sunflower filtered images ({{% resource_link "5c401d0a-c778-46eb-9a52-c551c8ffb549" "Flower1.fits" %}}, {{% resource_link "77cbcc73-12a3-4ca4-8d1f-73126dec8001" "Flower2.fits" %}}, {{% resource_link "d94319c5-eeee-41c8-999e-f6627cd4408b" "Flower3.fits" %}} ), Orion filtered images from MicroObservatory ({{% resource_link "a083da38-046c-4647-97c5-4435b21d9497" "MO\_orion\_red.fits" %}} , {{% resource_link "5eb97655-0f75-4d18-af60-f1c662c09f9f" "MO\_orion\_green.fits" %}}, {{% resource_link "ec8e1bc7-9068-4272-93bc-e4c1b61ec3b1" "MO\_orion\_blue.fits" %}}), Orion filtered images from Hubble Space Telescope ({{% resource_link "18c34da4-45ae-411f-8931-72d9f72b52e6" "m42r.fits" %}}, {{% resource_link "2f520b26-d562-4df5-a7d3-2240be2548fa" "m42g.fits" %}}, {{% resource_link "51873030-9fd7-4a56-93fc-3f40b6134d20" "m42b.fits" %}}), open cluster NGC 7789 filtered images from MicroObservatory ({{% resource_link "038c9329-cce0-4e40-862d-ee123bd27def" "NGC7789\_redshifted.fits" %}}, {{% resource_link "7a90804d-0005-45d6-862d-e0c9c2e79900" "NGC7789\_greenshifted.fits" %}}, {{% resource_link "8c6a0065-98b6-42e5-960e-fa79c824384a" "NGC7789\_blueshifted.fits" %}}). Flexible Image Transport System (FITS) is a digital file format used to store, transmit, and manipulate scientific and other images. FITS is the most commonly used digital file format in astronomy. {{% resource_link "f717f1df-1a61-4c5d-9628-4dbf553ed68d" "DS9" %}} is an application that supports these files and is {{% resource_link "f717f1df-1a61-4c5d-9628-4dbf553ed68d" "available for free" %}}.

**Developing model of color and filters:**

- Filters: Students record observations of a red illuminated exit sign and different colored pieces of construction paper through red, green and blue filters. They describe results using "high flux" and "low flux." Could organize according to a chart: filters down the side, and objects across the top, filling in rows with "low flux" or "high flux." Empty example chart: ({{% resource_link "44fa238e-0483-4209-b1b0-61bbd2ef224d" "filter observation table" %}})
- Instructor introduces an addition to the particle model of light to explain these observations: Each photon can be a different amount of energy. Humans experience photons with different energies as different colors.
- Instructor builds a model of how filters work, using the particle model of light, and based on the observations of students. Notes: ({{% resource_link "16fb0c81-9646-4050-84dc-70c10093d967" "how filters work" %}}) Color is our experience of the energy of the different photons. They only allow through a range of energies (colors).

**Applying model of color and filters:**

- Instructor introduces diffraction grating, put over an overhead projector, with slit on overhead. Example setup: ({{% resource_link "21817ece-efeb-452a-9945-549c68e6b528" "overhead diffraction" %}}) Observe how it splits light into a spectrum.
- Prediction 1: Ask students to predict (by drawing with colored pencils) what the spectrum will look like if a red filter covers the diffraction grating.
- Test prediction 1: When done with predictions, observe what happens when you test this, have them draw this observation (results of the testing experiment), and then write about what was the same and different between their predictions and the results of the experiment. Discuss with their small group.
- Prediction 2: Show full color image of sunflower. If the sunflower was photographed with a filter in front of the detector, make a chart of predictions of what objects you'd expect to show up with high flux or low flux in an image taken behind each color filter. Instructor can show examples by filling in chart for first filtered image. Empty example chart: ({{% resource_link "77ddcac1-40ec-400f-8e56-9b82b5e46c81" "three color predictions table" %}})
    - Sunflower filtered images and combined true color image: {{% resource_link "5c401d0a-c778-46eb-9a52-c551c8ffb549" "Flower1.fits" %}}, {{% resource_link "77cbcc73-12a3-4ca4-8d1f-73126dec8001" "Flower2.fits" %}}, {{% resource_link "d94319c5-eeee-41c8-999e-f6627cd4408b" "Flower3.fits" %}}
- Test prediction 2: Instructor presents students with unlabeled images, and students use predictions to match which image was taken behind which filter.

{{< resource uuid="12f63dc8-df64-4ca5-abb2-add82fc47e49" >}}

**Creating and interpreting true color images of sunflower and Orion nebula:**

- Instructor (or multiple instructors in small groups) show students how to combine the filtered images of sunflower (red-filtered: {{% resource_link "77cbcc73-12a3-4ca4-8d1f-73126dec8001" "Flower2.fits" %}}, green-filtered: {{% resource_link "d94319c5-eeee-41c8-999e-f6627cd4408b" "Flower3.fits" %}}, blue-filtered: {{% resource_link "5c401d0a-c778-46eb-9a52-c551c8ffb549" "Flower1.fits" %}}) to create a true color image **(Process: creating a true color image by opening RGB frame.)**
- Students select 2–3 regions of true color sunflower image, each with a distinctive color (i.e. mostly red or blue), and use these regions to examine the individual filtered images and create a chart of observations of the number of counts in that region for each filtered image. Empty example chart: ({{% resource_link "53b42a99-10e5-497c-8ad1-526747a5d14b" "three color observations table" %}})
- Instructor wraps up discussion of color, using these observations (which show, for example, a blue region has higher flux in the blue filtered image than in any other image) and color combination demonstration (shining colored lights of different intensity on the same screen) to explain that we experience different colors because of a combination of these three.
- Students create a true color image of the Orion nebula, with red-, green- and blue-filtered images taken by the Hubble Space telescope
    - Orion filtered images from Hubble Space Telescope: red-filtered: {{% resource_link "18c34da4-45ae-411f-8931-72d9f72b52e6" "m42r.fits" %}}, green-filtered: {{% resource_link "2f520b26-d562-4df5-a7d3-2240be2548fa" "m42g.fits" %}}, blue-filtered: {{% resource_link "51873030-9fd7-4a56-93fc-3f40b6134d20" "m42b.fits" %}}
    - Students create a similar chart to the one for the sunflower above, choosing 2–3 regions with different color in the true color image, and recording the number of counts in those regions from each of the filtered images. Again, they should notice that a region with a pronounced color shows more counts (or photons collected) in the filtered image where only that color light is allowed to pass (i.e. in a green region, the highest number of counts are in the green-filtered image.)
    - Alternative target: Open cluster NGC 7789 filtered images from MicroObservatory {{% resource_link "038c9329-cce0-4e40-862d-ee123bd27def" "NGC7789\_redshifted.fits" %}}, {{% resource_link "7a90804d-0005-45d6-862d-e0c9c2e79900" "NGC7789\_greenshifted.fits" %}}, {{% resource_link "8c6a0065-98b6-42e5-960e-fa79c824384a" "NGC7789\_blueshifted.fits" %}}. Stars in this cluster can easily show different colors, especially if the blue image contrast is boosted

{{< resource uuid="96de36e2-bd54-456c-bd31-ade9bf61e279" >}}

**Teacher tips/tricks:**

- Timing: About 2 hours, but time can be cut by only working with prediction 2 (which is more relevant to true color images which students will use heavily later on.)
- ({{% resource_link "221b4c99-62a8-42a4-a115-1d8e3b9e7dd6" "filter reflections" %}}): Example of student-generated list of things they felt they learned from observations of color and filters, as put up at end of day for a review.
- ({{% resource_link "221b4c99-62a8-42a4-a115-1d8e3b9e7dd6" "true color reflections" %}}): Example of student-generated list of things they felt they learned about making true color images, as put up at end of day for a review.
- Working with small groups, as opposed to one large group, works best to show students the processing steps involved in making a true color image.
- If more emphasis on representing observations in a variety of ways is desired, student spokespeople could present the observations of the sunflower and/or Orion regions as a plot (counts vs. color in a bar chart), chart, image and written paragraph, and then use all those representations to present their results.
- Difficulties with "true color" images:
    - Although a true color image can represent what we'd see with our eyes, astronomers can still change the bias and contrast of the image, to emphasize different features of the image, just as with the images made in activity 2.
    - When making true color images, students should start by locking the colorbars together on the RGB dialog box. This means the bias and contrast of each color changes together, when one is adjusted. However, the colorbars are "stretched" over different ranges of counts in each image, so there is no "correct setting" for a "true color" image. Indeed, students can see this if they compare their Orion images to each other.
    - The important distinction to be made (in activity 6) is the difference between what color represents in true color (energy) vs. false color (intensity) images, so for now, let students experiment with making their "true color" images look different.

**Assessment ideas:**

- Pete is a CAI participant. When asked "What does a filter do?" here's what Pete said: "When you look through a red filter at things around a room (people, lights, or whatever), everything is colored shades of red. That means the filter must make any light that is coming through it turn red." Would you agree or disagree with Pete's statement? Use observations you have made to give an explanation for your answer.
- Predict what the spectrum projected through the diffraction grating would look like if it was covered by a blue filter. Draw with colored pencils.