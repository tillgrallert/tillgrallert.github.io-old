---
layout: page
title: "DH"
author: Till Grallert
date: 2016-05-20 23:42:57 +0300
categories:
- project_dh
---

Since at least 2011 I find myself increasingly engaged in what is increasingly labelled digital humanities or *dh*. This is not the place to engage in the long discussions on what does or does not constitute *dh*, whether one has to build tools for computational analysis informed by the humanisties' research questions or whether one has to theorise the shift towards a new *digital* paradigm and episteme, whether we should all be sitting in a big tent or not, whether the increasing institutionalisation of *DH* (this time with capital letters) is responsible for or just a part of the "neoliberal" threat to the humanities or whether *dh* can indeed contribute to critical humanities.

Instead this page will simply link to current and past research projects that I would broadly label as *dh*. The most important of them which is currently occupying quite a bit of my time is the [GitHub-hosted digital edition of Muḥammad Kurd ʿAlī's monthly periodical *al-Muqtabas* (The Digest)](https://www.github.com/tillgrallert/digital-muqtabas), published between 1906 and 1918/19 in Cairo and Damascus. As the project has beget the [sister edition of *al-Haqāʾiq*](https://www.github.com/tillgrallert/digital-haqaiq), also published in Damascus between 1910 and 1912, this might evolve into a larger project of "Digital Editions of Early Arabic Periodicals". For the time being, however, the Digital Muqtabas project has it's own [project blog](https://tillgrallert.github.io/digital-muqtabas).

## News 

<ul class="post-list">
{% for post in site.categories['project_dh'] %}
  {% include post-list-item.html %}
{% endfor %}
</ul>