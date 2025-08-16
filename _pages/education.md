---
layout: archive
title: "Education"
permalink: /education/
author_profile: true
redirect_from:
  - /education
---

{% include base_path %}

<h2>Education</h2>

<h3>University of California, Riverside</h3>
<p>Doctor of Philosophy (Ph.D.)<br>
Computer Science and Engineering<br>
Duration: 2024 - ongoing<br>
Supervisor: Dr. Yue Dong</p>

<h3>Ahsanullah University of Science and Technology</h3>
<p>Bachelor of Science (B.Sc.)<br>
Computer Science and Engineering [Certificate]<br>
Duration: 2014 - 2018<br>
CGPA: 3.973/4.00 scale (Ranked 1st) [Transcript]</p>

<h3>Dhaka College</h3>
<p>Higher Secondary Certificate (HSC) [Certificate]<br>
Duration: 2011 - 2013<br>
GPA: 5.00/5.00 scale</p>

<h3>Ideal School and College</h3>
<p>Secondary School Certificate (SSC) [Certificate]<br>
Duration: 2009 - 2011<br>
GPA: 5.00/5.00 scale</p>

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
