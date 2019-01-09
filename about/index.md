---
layout: page
title: About
tags: [about, Jekyll, theme, moon]
date: 2016-03-21
comments: false
---

<img src="{{ site.url }}/{{ site.logo }}" alt="{{ site.title }} photo" class="author-photo">

Hi there! I'm Alyssa. I recently graduated from California State University, Los Angeles with a Bachelor's Degree in Computer Science and am currently seeking a job or internship related to Web Development.

Languages that I am familiar with are Java, JavaScript, SQL, HTML, CSS, and a little bit of C++.

If you would like to contact me, feel free to send me an email through clicking the link below.

{% if site.email %}
    <li>
        <a href="mailto:{{ site.email }}" target="_blank" rel="noopener noreferrer"><i class="fa fa-fw fa-envelope-square"></i> Email</a>
    </li>
{% endif %}
