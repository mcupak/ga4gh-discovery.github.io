---
title: "Marc Fiume"
layout: default
date: 2018-12-15
excerpt_separator: <!--more-->
image_file: mfiume.jpg
category:
  - contact
  - people
tags:
  - contacts
  - leads
  - contributors
  - Discovery
  - Beacon
  - .featured
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; width: 80px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

Co-chair GA4GH Discovery    
Assistant Professor, OICR  
CEO, DNAstack  

<!--more-->

email [Marc@dnastack.com](mailto:Marc@dnastack.com)

web [DNAstack](http://dnastack.com)  
web [OICR](https://oicr.on.ca/investigators/marc-fiume/)  

