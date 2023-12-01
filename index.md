---
layout: page
title: 
---

This site complements the paper **Self-Contained and Automatic Calibration of a Multi-Fingered Hand Using Only Pairwise Contact Measurements** by
[Johannes Tenhumberg\*](https://scholar.google.com/citations?user=2RZuYZMAAAAJ), [Leon Sievers\*](https://scholar.google.com/citations?user=y-MzVoUAAAA) and [Berthold Bäuml](https://scholar.google.com/citations?user=fjvpDsEAAAAJ) presented at the _2023 IEEE-RAS International Conference on Humanoid Robots_.
<p align="center">
<iframe src="https://www.youtube.com/embed/dkG9xz1fhOU?si=EfWu8aHsvoZlIpHt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

# Abstract
---
A self-contained calibration procedure that can be performed automatically without additional external sensors or tools is a significant advantage, especially for complex robotic systems. Here, we show that the kinematics of a multi-fingered robotic hand can be precisely calibrated only by moving the tips of the fingers pairwise into contact. The only prerequisite for this is sensitive contact detection, e.g., by torque-sensing in the joints (as in our DLR-Hand II) or tactile skin. The measurement function for a given joint configuration is the distance between the modeled fingertip geometries, but the actual measurement is always zero. In an in-depth analysis, we prove that this contact-based calibration determines all quantities needed for manipulating objects with the hand, i.e., the difference vectors of the fingertips, and that it is as sensitive as a calibration using an external visual tracking system and markers. We describe the complete calibration scheme, including the selection of optimal sample joint configurations and search motions for the contacts despite the initial kinematic uncertainties. In a real-world calibration experiment for the torque-controlled four-fingered DLR-Hand II, the maximal error of 17.7mm can be reduced to only 3.7mm.
