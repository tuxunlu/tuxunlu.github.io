---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome! I am a Ph.D. student in Computer Science at the University of Maryland, College Park, working with the [Perception and Robotics Group](https://prg.cs.umd.edu/) under the guidance of Dr. Cornelia Fermuller and Prof. Yiannis Aloimonos. My research focuses on developing robust and efficient deep learning systems for computer vision applications, with particular emphasis on event-based vision, neuromorphic computing, and medical image analysis.

## Research Interests

My research spans several interconnected areas:

- **Event-Based Vision & Neuromorphic Computing**: Leveraging Dynamic Vision Sensors (DVS) and spiking neural networks for low-latency, energy-efficient visual processing. I work on processing spatio-temporal data from event cameras using State Space Models (SSMs) and Transformers for applications like gesture recognition and adverse weather de-raining.

- **Medical Image Analysis**: Developing automated 3D segmentation pipelines for high-resolution medical imaging, including 7T MRI and multi-view mammography, to assist in disease diagnosis and risk prediction.

## News & Updates

- **Jul 2024**: Our paper on SegSTRONG-C accepted at MICCAI 2024!
- **Nov 2023**: Presented our work on decision support tools for small farmers at AAAI Workshop on AI2ASE.

## Recent Publications

{% include base_path %}
{% for post in site.publications reversed limit:3 %}
- **[{{ post.title }}]({{ base_path }}{{ post.url }})**  
  {{ post.venue }}, {{ post.date | date: "%Y" }}  
  {% if post.paperurl %}[PDF]({{ post.paperurl }}){% endif %}
{% endfor %}

[View all publications →]({{ base_path }}/publications/)



## Professional Service

- **Journal Reviewer**: [IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=34)



## Education

**University of Maryland, College Park**  
*Doctor of Philosophy (PhD) in Computer Science*  
Aug 2024 - Present

**The Johns Hopkins University**  
*Bachelor of Science in Computer Science*  
Sep 2020 - May 2024

---

*Last updated: February 2025*

