---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## Mars Rover
#### Fall 2022 



<div markdown="0" align="center">
    <a href="../files/" class="btn btn--info">??</a>
    <a href="../files/" class="btn btn--info">??</a>
    <a href="../files/" class="btn btn--info">??</a>
    <a href="../files/" class="btn btn--info">??</a>
</div>

## RADical Robotics
#### Fall 2022 and Winter 2023

Radiation detection robots could play a crucial role in identifying radiation hotspots in nuclear power plants during routine leakage detection and emergency responses, as well as in various defense applications, such as border control and or potential nuclear fallout. By introducing radiation detection robots, our project team aimed to reduce health risks for human operators, lessen their physical demands, and enhance efficiency in surveying challenging and high-risk areas. RADical Robotics developed a radiation detection robot utilizing a Rosbot Robot Car, a high-resolution H3D M400 CZT gamma-ray spectrometer, and the Robot Operating System (ROS).

As one aspect of characterizing the localized source or sources, my personal desgin goal was to determine the isotopes present based off of gamma energy spectra. I created a Python processing script that input a data file from the detector containing counts per energy channel information, and output a plot of the energy spectrum with identified peaks and the identified isotope(s). I also was involved with integrating the robot and detector and creating Light Detection and Ranging (LiDAR) maps.

I used a data file from the detector containing counts per energy channel information as an input to the Python processing script. After performing some data processing, I optimized the use of the peak finding algorithm from the SciPy package to identify peaks as to maximize detection probability and minimize false alarm probability. Furthermore, I developed a isotope database with 72 isotopes and an algorithm to compare the found peaks with the data in the isotope database, to lead to a final identified isotope(s). This included tricky cases such as isotopes with x-ray peaks (e.g. spectra with <sup>131</sup>I and <sup>239</sup>Pu) and a mixture of isotopes with possibly overlapping peaks (e.g. spectra with <sup>67</sup>Ga, <sup>235</sup>U, <sup>238</sup>U).

My algorithm 100% correcly identified only the isotopes present for 160 spectra including 10 spectra for 16 isotope combinations: <sup>241</sup>Am, <sup>133</sup>Ba, <sup>60</sup>Co, <sup>137</sup>Cs, <sup>67</sup>Ga, <sup>226</sup>Ra, <sup>99m</sup>Tc, <sup>201</sup>Tl, <sup>131</sup>I, <sup>232</sup>Th, Depleted uranium (DU), Highly enriched uranium (HEU), Weapons grade plutonium (WGPU), <sup>67</sup>Ga + HEU, <sup>131</sup>I + WGPU, <sup>137</sup>Cs + DU.

Using the bootstrapping method, I had a background dataset including 3002 spectra with no isotopes present, where 99.6% of the spectra were label with no isotope identified. This met the IAEA National Standard Identification Criteria (N42.34) background false alarm rate requirements.


<div markdown="0" align="center">
    <a href="../files/Radical_Robotics_Final_Report.pdf" class="btn btn--info">Paper</a>
    <a href="../files/RadicalRobotics_FinalOralPresentation_Submission.pdf" class="btn btn--info">Presentation</a>
    <a href="https://github.com/EmRobotics/RadRobo" class="btn btn--info">Github</a>
</div>

## Space design
#### December 2022

I played a crucial role in our team project focused on designing a nuclear-powered spaceship for a one-way journey to Saturn’s moon Titan, aimed at establishing an outer-heliosphere science and refuel hub for deep space mission, with a mission duration of under 20 years and a minimum three-person crew. Within this ambitious endeavor, my responsibilities revolved around the critical aspect of designing a life support system. Leveraging research and knowledge of current life support technologies, I contributed by proposing a comprehensive life support system that incorporated bioregenerative life support principles derived from exploring past algae experiments. I proposed algae growing chambers and gravity designs to meet mission requirements. This important facet of our mission was aimed at ensuring the well-being and survival of the crew throughout the extended journey to aim for mission success!

<div markdown="0" align="center">
    <a href="../files/KOIOS Final Report.pdf" class="btn btn--info">Paper</a>
    <a href="../files/FINAL KOIOS Presentation.pdf" class="btn btn--info">Presentation</a>
</div>

## Environmental Service Project
#### Winter 2020

In collaboration with two team members, I conducted hands-on fieldwork, collecting samples from local beaches and meticulously characterizing microplastics using optical microscopy. Furthermore, I transformed my research findings into a compelling environmental awareness film, which not only demonstrated my dedication to scientific outreach but also earned me the 1st place award in the 9th-12th grade State of Michigan Earth Day Environmental Service Award competition. This experience underscores my passion for making a positive impact on our planet.

<div markdown="0" align="center">
    <a href="https://youtu.be/5LB4wFwrM1M" class="btn btn--info">Video Link</a>
</div>