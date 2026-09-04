---
permalink: /contact/
title: "Contact"
#excerpt: "Contact details and online profiles."
header:
  overlay_image: header/header5.jpg
  overlay_filter: 0.2 # same as adding an opacity of 0.2 to a black background
  caption: "Photo: A. Künstle"
author_profile: true
redirect_from: 
  - 
---

{% include base_path %}

### Office
<i class="fas fa-fw fa-building" aria-hidden="true"></i>&nbsp;&nbsp;Telegrafenberg A62, Room S10, 14473 Potsdam<br />

<i class="far fa-fw fa-envelope" aria-hidden="true"></i>&nbsp;&nbsp;<a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a><br />
<i class="fas fa-fw fa-desktop" aria-hidden="true"></i>&nbsp;&nbsp;<a href="{{ site.author.uri }}">{{ site.author.uri | remove: "https://" }}</a><br />
<i class="fas fa-fw fa-phone" aria-hidden="true"></i>&nbsp;&nbsp;<a href="tel:{{ site.author.phone }}">{{ site.author.phone }}</a><br />

### Mailing Address
<address>
Potsdam Institute for Climate Impact Research<br />
P.O. Box 60 12 03<br />
14412 Potsdam<br />
Germany
</address><br />

<iframe src="/contact/contact-map.html" width="80%" height="400px" style="border: none;"></iframe> <!-- width="100%" height="520px" -->

### Scientific Profiles
<div class="social-icons">
  <i class="ai fa-fw ai-orcid" aria-hidden="true"></i>&nbsp;&nbsp;<a href="https://orcid.org/{{ site.author.orcid }}">ORCID</a><br />
  <i class="fas fa-fw fa-graduation-cap" aria-hidden="true"></i>&nbsp;&nbsp;<a href="https://scholar.google.com/citations?user={{ site.author.googlescholar }}">Google Scholar</a><br />
  <i class="ai fa-fw ai-researchgate-square" aria-hidden="true"></i>&nbsp;&nbsp;<a href="https://www.researchgate.net/profile/{{ site.author.researchgate }}">ResearchGate</a><br />
  <i class="ai fa-fw ai-clarivate" aria-hidden="true"></i>&nbsp;&nbsp;<a href="{{ site.author.webofscience.url }}">Web of Science</a><br />
  <i class="ai fa-fw ai-scopus" aria-hidden="true"></i>&nbsp;&nbsp;<a href="https://www.scopus.com/authid/detail.uri?authorId={{ site.author.scopus }}">Scopus</a><br />
  <i class="fab fa-fw fa-github" aria-hidden="true"></i>&nbsp;&nbsp;<a href="https://github.com/{{ site.author.github }}">Github</a><br />
</div>


### Social Media Profiles
<div class="social-icons">
  <i class="fab fa-fw fa-bluesky" aria-hidden="true"></i>&nbsp;&nbsp;<a href="https://bsky.app/profile/{{ site.author.bluesky }}">Bluesky</a><br />
  <i class="fab fa-fw fa-mastodon" aria-hidden="true"></i>&nbsp;&nbsp;<a href="{{ site.author.mastodon.url }}">Mastodon</a><br />
  <i class="fab fa-fw fa-x-twitter" aria-hidden="true"></i>&nbsp;&nbsp;<a href="https://x.com/{{ site.author.x }}">X</a><br />
  <i class="fab fa-fw fa-linkedin" aria-hidden="true"></i>&nbsp;&nbsp;<a href="https://www.linkedin.com/in/{{ site.author.linkedin }}">LinkedIn</a><br />
</div>