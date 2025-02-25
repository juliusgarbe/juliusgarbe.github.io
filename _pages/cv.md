---
permalink: /cv/
title: "Curriculum Vitae"
#excerpt: "Education, scientific background, research interests & skills, and more."
header:
  overlay_image: header/header2.jpg
  overlay_filter: 0.2 # same as adding an opacity of 0.2 to a black background
  caption: "Photo: J. Garbe"
author_profile: true
redirect_from:
  - 
---

{% include base_path %}

<!-- Click [here](/cv-print/) for a printable version or [download a PDF](/files/cv-print.pdf).<br /><br /><br /> -->

<h2 align="center">{{ site.author.name }}</h2>
<h3 align="center" style="margin: 0px auto 20px;">M.Sc. Climate Sciences</h3>
<p align="center" style="margin: auto; width: 80%">{{ site.author.bio }}</p>

<p align="center"><i class="far fa-envelope" aria-hidden="true"></i>&nbsp;<a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a> &#124; <i class="fas fa-desktop" aria-hidden="true"></i>&nbsp;<a href="{{ site.author.uri }}">{{ site.author.uri | remove: "https://" }}</a> &#124; <i class="fab fa-bluesky" aria-hidden="true"></i>&nbsp;<a href="https://bsky.app/profile/{{ site.author.bluesky }}">@{{ site.author.bluesky }}</a></p>

## Education
- **Ph.D. in Climate Physics**, 2017-present<br>
**[Earth Resilience Science Unit, Potsdam Institute for Climate Impact Research](https://www.pik-potsdam.de/ "https://www.pik-potsdam.de/") / [Institute of Physics and Astronomy, University of Potsdam](http://www.physik.uni-potsdam.de/ "http://www.physik.uni-potsdam.de/")**
  - *Thesis:* The Antarctic Ice Sheet as a tipping element in the Earth system
  - *Supervisors:* Prof. Ricarda Winkelmann & Dr. Jonathan F. Donges

- **M.Sc. in Integrated Climate System Sciences**, 2014-2017<br>
**[School of Integrated Climate System Sciences, University of Hamburg](https://www.sicss.uni-hamburg.de "https://www.sicss.uni-hamburg.de")**
  - *Thesis:* [Long-term evolution and critical thresholds of the Antarctic Ice Sheet](/publications/theses/garbe-2017 "/publications/theses/garbe-2017")
  - *Supervisors:* Dr. habil. Georg Feulner, Prof. Ricarda Winkelmann, & Prof. Lars Kaleschke

- **B.Sc. in Physics (major) and Mathematics (minor)**, 2009-2013<br>
**[Department of Physics, Humboldt University of Berlin](https://www.physik.hu-berlin.de/ "https://www.physik.hu-berlin.de/")**
  - *Thesis:* [An overview of explanations for the problem of weak temperature gradients in warm climates in Earth history](/publications/theses/garbe-2013 "/publications/theses/garbe-2013")
  - *Supervisors:* Prof. Jürgen Kurths & Dr. habil. Georg Feulner

## Relevant Academic Positions
- **Guest researcher**, Potsdam Institute for Climate Impact Research, 2024-present
  - *Working group:* [Ice Dynamics](https://www.pik-potsdam.de/en/institute/departments/earth-system-analysis/research/ice-dynamics/ "https://www.pik-potsdam.de/en/institute/departments/earth-system-analysis/research/ice-dynamics/")
  - *Department:* [Earth Resilience Science Unit](https://www.pik-potsdam.de/en/institute/futurelabs-science-units/ersu "https://www.pik-potsdam.de/en/institute/futurelabs-science-units/ersu")
- **Research assistant**, Potsdam Institute for Climate Impact Research, 2017-2023
  - *Working group:* [Ice Dynamics](https://www.pik-potsdam.de/en/institute/departments/earth-system-analysis/research/ice-dynamics/ "https://www.pik-potsdam.de/en/institute/departments/earth-system-analysis/research/ice-dynamics/")
- **Graduate research assistant**, Potsdam Institute for Climate Impact Research, 2016-2017
  - *Working group:* [Earth System Modes of Operation](https://www.pik-potsdam.de/en/institute/departments/earth-system-analysis/research/earth-system-modes-of-operation "https://www.pik-potsdam.de/en/institute/departments/earth-system-analysis/research/earth-system-modes-of-operation")
  - *Associated working group:* [Ice Dynamics](https://www.pik-potsdam.de/en/institute/departments/earth-system-analysis/research/ice-dynamics/ "https://www.pik-potsdam.de/en/institute/departments/earth-system-analysis/research/ice-dynamics/")
- **Undergraduate research assistant**, Potsdam Institute for Climate Impact Research, 2012-2013
  - *Working group:* [Earth System Modes of Operation](https://www.pik-potsdam.de/en/institute/departments/earth-system-analysis/research/earth-system-modes-of-operation "https://www.pik-potsdam.de/en/institute/departments/earth-system-analysis/research/earth-system-modes-of-operation")

## Peer-Reviewed Publications
<ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
{% endfor %}</ul>

## Submitted Articles & Preprints
<ul>{% for post in site.publications_preprints reversed %}
    {% include archive-single-cv.html %}
{% endfor %}</ul>

## Academic Theses
<ul>{% for post in site.publications_theses reversed %}
    {% include archive-single-cv.html %}
{% endfor %}</ul>

## Data & Code
<ul>{% for post in site.publications_data reversed %}
    {% include archive-single-cv.html %}
{% endfor %}</ul>

## Conference Contributions & Talks
<ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
{% endfor %}</ul>
  
## Teaching
<ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
{% endfor %}</ul>
