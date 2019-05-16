---
title: "The SAMPL challenges"
layout: archive
permalink: /roadmap/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/hosts.jpg
excerpt: "The long-term roadmap"
---

<table style="width:100%;">
<colgroup>
<col style="width: 5%" />
<col style="width: 18%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th></th>
<th><span class="blue">SAMPL7</span></th>
<th><span class="green">SAMPL8</span></th>
<th><span class="yellow">SAMPL9</span></th>
<th><span class="orange">SAMPL10</span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td></td>
<td>Present-August 2019</td>
<td>September 2019-August 2020</td>
<td>September 2020-August 2021</td>
<td>September 2021-August 2022</td>
</tr>
<tr class="even">
<td>LogP</td>
<td>Challenge</td>
<td></td>
<td></td>
<td>Challenge</td>
</tr>
<tr class="odd">
<td>LogD</td>
<td></td>
<td>Challenge</td>
<td>Challenge</td>
<td>Challenge</td>
</tr>
<tr class="even">
<td>pKa</td>
<td></td>
<td></td>
<td>Challenge</td>
<td></td>
</tr>
</tbody>
</table>

**Roadmap**: Details to be filled in here

**Data donation**: In general we seek assistance in obtaining high quality data along the lines described in the roadmap above. Some of the measurements will be conducted in our own laboratories, but for others, we rely on donations of data, internships with industry partners, etc., and we are delighted to have help in this regard. Please contact [David L. Mobley](https://mobleylab.org/people/david-mobley/) at dmobley (you know what symbol) mobleylab.org if you have ideas or can help. Properties of particular interest include log P and log D values (between water and alternate solvents, or between diverse solvents), pKa, solubility, binding to well-understood or simple model systems, and selected protein-ligand binding data. 


{% for collection in site.collections %}
  {% if collection.label == "roadmap" %}
    {% for post in collection.docs %}
	  {% if post.layout != "archive" %}
        {% include archive-single.html %}
	  {% endif %}
    {% endfor %}
  {% endif %}
{% endfor %}
