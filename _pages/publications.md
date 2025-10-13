---
permalink: /publications/
title: "Publications"
#excerpt: "List of academic publications."
header:
  overlay_image: header/header3.jpg
  overlay_filter: 0.2 # same as adding an opacity of 0.2 to a black background
  caption: "Photo: J. Garbe"
author_profile: true
redirect_from: 
  - /publications/articles/
  - /publications/preprints/
  - /publications/theses/
  - /publications/data/
---

{% include base_path %}

{% include toc title="Jump to" icon="fas fa-file-alt" %}

<div class="notice--info social-icons">
  <h4 class="no_toc" style="padding-bottom: 6px;">You can also find my articles on:</h4>
  {% if site.author.googlescholar %}<a href="https://scholar.google.com/citations?user={{ site.author.googlescholar }}" class="btn btn--inverse"><i class="fas fa-graduation-cap"></i> Google Scholar</a>{% endif %}
  {% if site.author.researchgate %}<a href="https://www.researchgate.net/profile/{{ site.author.researchgate }}" class="btn btn--inverse"><i class="ai ai-researchgate-square" aria-hidden="true"></i> ResearchGate</a> {% endif %}
  {% if site.author.orcid %}<a href="https://orcid.org/{{ site.author.orcid }}" class="btn btn--inverse"><i class="ai ai-orcid"></i> ORCID</a> {% endif %}
  {% if site.author.scopus %}<a href="https://www.scopus.com/authid/detail.uri?authorId={{ site.author.scopus }}" class="btn btn--inverse"><i class="ai ai-scopus"></i> Scopus</a> {% endif %}
  {% if site.author.webofscience %}<a href="{{ site.author.webofscience.url }}" class="btn btn--inverse"><i class="ai ai-clarivate"></i> Web of Science</a> {% endif %}
</div>

## Submitted Articles & Preprints
{% for post in site.publications_preprints reversed %}
  {% include archive-single.html %}
{% endfor %}

## Peer-Reviewed Publications
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Policy Reports
<div class="list__item">
<h2 class="archive__item-title" itemprop="headline"><a href="https://global-tipping-points.org" title="https://global-tipping-points.org" target="_blank">The Global Tipping Points Report 2025</a></h2>
<p class="page__meta"><i class="fa fa-book-open" aria-hidden="true"></i> University of Exeter | 2025</p>
Lenton, T. M., Milkoreit, M., Willcock, S., Abrams, J. F., Armstrong McKay, D. I., Buxton, J. E., Donges, J. F., Loriani, S., Wunderling, N., Alkemade, F., Barrett, M., Constantino, S., Powell, T., Smith, S. R., Boulton, C. A., Pinho, P., Dijkstra, H. A. Pearce-Kelly, P., Roman-Cuesta, R.M., Dennis, D. (eds): <i>The Global Tipping Points Report 2025</i>, University of Exeter, UK, <a href="https://global-tipping-points.org" title="https://global-tipping-points.org" target="_blank">global-tipping-points.org</a>, 2025.
</div>

<div class="list__item">
<h2 class="archive__item-title" itemprop="headline"><a href="https://report-2023.global-tipping-points.org" title="https://report-2023.global-tipping-points.org" target="_blank">The Global Tipping Points Report 2023</a></h2>
<p class="page__meta"><i class="fa fa-book-open" aria-hidden="true"></i> University of Exeter | 2023</p>
Lenton, T. M., Armstrong McKay, D. I., Loriani, S., Abrams, J. F., Lade, S. J., Donges, J. F., Milkoreit, M., Powell, T., Smith, S. R., Zimm, C., Bailey, E., Buxton, J. E., Dyke, J. G., Ghadiali, A., Laybourn, L. (eds): <i>The Global Tipping Points Report 2023</i>, University of Exeter, UK, <a href="https://report-2023.global-tipping-points.org" title="https://report-2023.global-tipping-points.org" target="_blank">report-2023.global-tipping-points.org</a>, 2023.
</div>

## Other Writing
<div class="list__item">
<h2 class="archive__item-title" itemprop="headline"><a href="https://blogs.egu.eu/divisions/cr/2020/12/04/hysteresis-for-dummies-why-history-matters/" title="https://blogs.egu.eu/divisions/cr/2020/12/04/hysteresis-for-dummies-why-history-matters/" target="_blank">Hysteresis For Dummies – Why history matters</a></h2>
<p class="page__meta"><i class="fa fa-book-open" aria-hidden="true"></i> EGU Blogs | 2020</p>
<b>Garbe, J.</b>: <i>Hysteresis For Dummies – Why history matters</i>, EGU Blogs, <a href="https://blogs.egu.eu/divisions/cr/2020/12/04/hysteresis-for-dummies-why-history-matters/" title="https://blogs.egu.eu/divisions/cr/2020/12/04/hysteresis-for-dummies-why-history-matters/" target="_blank">blogs.egu.eu/divisions/cr/2020/12/04/hysteresis-for-dummies-why-history-matters/</a>, 2020.
</div>

## Academic Theses
{% for post in site.publications_theses reversed %}
  {% include archive-single.html %}
{% endfor %}

## Open-Access Data & Code
{% for post in site.publications_data reversed %}
  {% include archive-single.html %}
{% endfor %}