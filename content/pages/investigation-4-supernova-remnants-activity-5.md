---
content_type: page
description: 'Students investigate supernova remnants to compare their properties. '
draft: false
title: 'Investigation 4: Supernova Remnants - Activity 5'
uid: 44bffa8a-b6c1-4a13-86c1-453a5e09728a
---
## **Investigate 3 Supernova Remnants to Compare Their Properties**

Note: This activity was dropped in Summer 2008, as the previous activity ran long.

**Physical resources:** None

**Electronic resources:** X-ray images of the supernovae listed below

Groups repeat an investigation similar to their Cas A analysis above, for three additional remnants. (1–2 groups per remnant, so they are able to cross-check results during the mini poster session wrap up in activity 6 below…)

- Core collapse in galaxy: G11.2 (obsid 780): compact central object, pulsar wind nebula, synchrotron emission.
- Core collapse out of galaxy: N132d (obsid 5532) Massive star collapse, but no central object, **but** really far away.
- Type Ia in galaxy: Kepler (obsid 116): very different spectrum, no central object, center emission is thermal, but not a blackbody…

Notes on each SNR, from CAI mentor Dr. Tracey Delaney:

## **Cas A**

Pick several regions of each color to improve signal-to-noise. This suggestion goes for all of the SNR analyses. In general, use finer binning for global spectra and use coarser for spectra of smaller regions.

The central object and the blue regions do not have any intrinsic line emission, but the spectra show line emission because of the background. So perhaps you'll have to be concerned about background. One thing to do if you don't want to actually subtract a background through DS9, is to grab a big region (or regions) of diffuse emission inside of Cas A and look at its spectrum. There should be low-level line emission. If the line emission in any of your selected regions is about the same as in the background, then you can consider it background.

The largest peak in the red spectrum is Fe. I've changed the linelist to say it is Fe if 6.7 keV Fe is in the spectrum and Ne if there is no 6.7 keV Fe in the spectrum.

## **G11.2**

The pulsar wind nebula has background line emission. Use a bigger binning for the spectrum, this should help improve signal-to-noise in the 4–6 keV range for comparison to the other spectra.

Good energy ranges for true color image:

High energy: 4–10 keV - this is not an Fe-rich SNR, you could use the full 4–10 keV range without contamination, or just stick with 4–6 keV for consistency with the other remnants.

Low energy: 0.3–1.6 keV—the same as Cas A, again, no Fe contamination (better than Cas A) and lots of O and Ne which are from the same layer of the star. If the sky background is too high, then maybe use 0.8–1.6 instead of Medium energy: 1.6–4 keV—also the same as Cas A, this grabs Si, S, Ar, and Ca which are all from the same layer of the star.

Rather than trying for finer binning, it might be better to use the native block 8 binning for signal-to-noise reasons.

## **Kepler**

I would say that background subtraction is almost critical here to see the juicy differences that are hidden in the spectra.

You'll notice the strong 6.7 keV Fe emission meaning that the low energy emission is dominated by Fe as well. This spectral shape is different from Cas A's global spectrum, but does look like the Fe regions in Cas A.

## **N132D**

N132D does not have much forward shock emission like Cas A and Kepler, I think the blue spectra are just noise/background. The forward shock might be just too weak to pick up 50 kpc away. But perhaps it is useful to include the 4–6 keV anyway to illustrate how it is different from the other remnants. The final RGB is really nice.

This remnant is O-bright and Fe-poor and Si-weak in comparison to the other SNRs. Binning the spectrum a little more would be good.