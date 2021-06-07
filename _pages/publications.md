---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Hi, I am Peixia, a DPhil (PhD) student of [SigmaLab](https://sigmalab-usyd.github.io/), the University of Sydney, supervised by [Prof.Wanli Ouyang](https://wlouyang.github.io/) and [Prof.Luping Zhou](https://www.sydney.edu.au/engineering/about/our-people/academic-staff/luping-zhou.html). I received my B.Eng. degree and M.Phil. degree from the faculty of Electronic Information and Electical Engineering, [Dalian University of Technology](https://www.dlut.edu.cn/). I was supervised by [Prof.Huchuan Lu](http://ice.dlut.edu.cn/lu/) during my Master process.
My research focus on developing fundamental algorithms for computer vision and deep learning, specifically on visual object tracking, object detection and neural architecture search. 
