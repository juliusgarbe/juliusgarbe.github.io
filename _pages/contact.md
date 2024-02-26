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
<i class="fas fa-building" aria-hidden="true"></i>&nbsp;&nbsp;Telegrafenberg A62, Room S10, 14473 Potsdam<br />

<i class="fas fa-envelope" aria-hidden="true"></i>&nbsp;&nbsp;<a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a><br />
<i class="fas fa-desktop" aria-hidden="true"></i>&nbsp;&nbsp;<a href="{{ site.author.uri }}">{{ site.author.uri | remove: "https://" }}</a><br />
<i class="fas fa-phone" aria-hidden="true"></i>&nbsp;&nbsp;<a href="tel:{{ site.author.phone }}">{{ site.author.phone }}</a><br />

### Mailing Address
<address>
Potsdam Institute for Climate Impact Research<br />
P.O. Box 60 12 03<br />
14412 Potsdam<br />
Germany
</address><br />

<iframe src="/contact/contact-map.html" width="80%" height="400px" style="border: none;"></iframe> <!-- width="100%" height="520px" -->

### Scientific Profiles
<i class="ai ai-orcid" aria-hidden="true"></i>&nbsp;&nbsp;<a href="https://orcid.org/{{ site.author.orcid }}">ORCID</a><br />
<i class="ai ai-researcherid-square" aria-hidden="true"></i>&nbsp;&nbsp;<a href="{{ site.author.researcherid.url }}">WoS ResearcherID</a><br />
<i class="ai ai-scopus" aria-hidden="true"></i>&nbsp;&nbsp;<a href="https://www.scopus.com/authid/detail.uri?authorId={{ site.author.scopus }}">Scopus Author ID</a><br />
<i class="ai ai-researchgate-square" aria-hidden="true"></i>&nbsp;&nbsp;<a href="https://www.researchgate.net/profile/{{ site.author.researchgate }}">ResearchGate</a><br />
<i class="fas fa-graduation-cap" aria-hidden="true"></i>&nbsp;&nbsp;<a href="https://scholar.google.com/citations?user={{ site.author.googlescholar }}">Google Scholar</a><br />
<i class="fab fa-github" aria-hidden="true"></i>&nbsp;&nbsp;<a href="https://github.com/{{ site.author.github }}">Github</a><br />


### Social Media Profiles
<i class="fab fa-mastodon" aria-hidden="true"></i>&nbsp;&nbsp;<a href="{{ site.author.mastodon.url }}">Mastodon</a><br />
<i class="fab fa-x-twitter" aria-hidden="true"></i>&nbsp;&nbsp;<a href="https://twitter.com/{{ site.author.twitter }}">Twitter</a><br />
<!-- FIXME: replace Bluesky logo with FA icon -->
<span><svg viewBox="-50 -50 430 390" class="icon" aria-hidden="true"><path d="M180 141.964C163.699 110.262 119.308 51.1817 78.0347 22.044C38.4971 -5.86834 23.414 -1.03207 13.526 3.43594C2.08093 8.60755 0 26.1785 0 36.5164C0 46.8542 5.66748 121.272 9.36416 133.694C21.5786 174.738 65.0603 188.607 105.104 184.156C107.151 183.852 109.227 183.572 111.329 183.312C109.267 183.642 107.19 183.924 105.104 184.156C46.4204 192.847 -5.69621 214.233 62.6582 290.33C137.848 368.18 165.705 273.637 180 225.702C194.295 273.637 210.76 364.771 295.995 290.33C360 225.702 313.58 192.85 254.896 184.158C252.81 183.926 250.733 183.645 248.671 183.315C250.773 183.574 252.849 183.855 254.896 184.158C294.94 188.61 338.421 174.74 350.636 133.697C354.333 121.275 360 46.8568 360 36.519C360 26.1811 357.919 8.61012 346.474 3.43851C336.586 -1.02949 321.503 -5.86576 281.965 22.0466C240.692 51.1843 196.301 110.262 180 141.964Z"></path></svg>&nbsp;&nbsp;<a href="https://bsky.app/profile/{{ site.author.bluesky }}">Bluesky</a></span><br />
<i class="fab fa-linkedin" aria-hidden="true"></i>&nbsp;&nbsp;<a href="https://www.linkedin.com/in/{{ site.author.linkedin }}">LinkedIn</a><br />