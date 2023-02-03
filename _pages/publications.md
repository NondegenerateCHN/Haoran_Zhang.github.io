---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Journal Paper

[1] H. Zhang and A. Shamim, “Wideband and Wide Beam-Scanning Dual-Polarized Phased Array Antenna-inPackage Design for 5G Applications,” IEEE Transactions on Antennas and Propagation. (Submitted, under review process)

## Conference Paper

[1] H. Zhang and A. Shamim, "Figure of Merit for Objective Assessment of mmWave 5G Phased Arrays," 2022 IEEE International Symposium on Antennas and Propagation and USNC-URSI Radio Science Meeting, Denver, USA, 2022

## Book Chapter

[1] A. Shamim and H. Zhang. Chapter 6: On Chip Antenna: Challenges and Design Considerations. In IET Book: Antennas and Propagation for 5G and Beyond. (Published 2021)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
