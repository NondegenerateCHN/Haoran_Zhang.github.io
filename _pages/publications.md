---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Journal Paper

[1] **H. Zhang** and A. Shamim, “Wideband and Wide Beam-Scanning Dual-Polarized Phased Array Antenna-inPackage Design for 5G Applications,” IEEE Transactions on Antennas and Propagation. (Submitted, under review process)

[2] **H. Zhang** and A. Shamim, “Figure of Merit for the Objective Assessment of mmWave 5G Phased Arrays,” IEEE Antennas and Propagation Magazine. (Submitted, under review process)

[3] **H. Zhang**, Y. Yang, J. Zhou, and A. Shamim, "[Wearable Radar System Design on Semi-Flexible PCB for Visually Impaired People](https://www.frontiersin.org/articles/10.3389/frcmn.2021.768794/full), " in Frontiers in Communications and Networks, Dec 2021.”

[4] W. Li, **H. Zhang**, S. Kagita, and A. Shamim, "All Screen-Printed, Polymer-Nanowire based Foldable Electronics for mm-Wave Applications," in Advanced Materials Technologies, July 2021. (**Cover Article**)

[5] **H. Zhang** and A. Shamim, "Gain Enhancement of Millimeter-Wave on-Chip Antenna through an Additively Manufactured Functional Package," in IEEE Transactions on Antennas and Propagation, Feb 2020

## Conference Paper

[1] **H. Zhang** and A. Shamim, "Figure of Merit for Objective Assessment of mmWave 5G Phased Arrays," 2022 IEEE International Symposium on Antennas and Propagation and USNC-URSI Radio Science Meeting, Denver, USA, 2022

[2] **H. Zhang**, Y. Yang and A. Shamim, "Wearable Radar Antenna Array Design on Flexible PCB for Visually Impaired People," 2021 International Applied Computational Electromagnetics Society Symposium, 2021

[3] **H. Zhang** and A. Shamim, "An Electrically Small Antenna in Package Design with Embedded Electronics for RPW Detection," 2020 IEEE APS & USNC/URSI Conference, Online 2020

[4] **H. Zhang** and A. Shamim, "Tackling the Issues of Millimeter-wave On-chip Antenna Measurements," 2019 13th EuCAP, Krakow, Poland, 2019

[5] A. Shamim and **H. Zhang**, "Gain Enhancement Techniques for mm-Wave On-Chip Antennas on Lossy CMOS Platforms," 2018 18th ANTEM International Symposium, Waterloo, Canada, 2018

[6] **H. Zhang** and A. Shamim, "Gain and Efficiency Enhancement of a 77 GHz On-Chip Antenna through AMC and Superstrate Package," 2018 IEEE APS & USNC/URSI Conference, Boston, USA, 2018

## Book Chapter

[1] A. Shamim and **H. Zhang**. Chapter 6: On Chip Antenna: Challenges and Design Considerations. In IET Book: Antennas and Propagation for 5G and Beyond. (Published 2021)

[2] A. Shamim and **H. Zhang**. Chapter 6: Antenna‐in‐package Designs in Multilayered Low‐temperature Co‐fired Ceramic Platforms. In Wiley Book: Antenna-in-Package Technology and Applications. (Published 2020)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
