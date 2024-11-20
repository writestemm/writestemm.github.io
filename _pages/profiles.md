---
layout: profiles
permalink: /people/
title: People
description: Members of the Organizing Committee
tabs: true
nav: true
nav_order: 7

{% tabs people %}

{% tab participants %}

Regular text

{% endtab %}

{% tab Advisors %}

> A quote

{% endtab %}

{% tab Organizing Committee %}

profiles:
  # if you want to include more than one profile, just replicate the following block
  # and create one content file for each profile inside _pages/
  - align: right
    image: NM.png
    content: about_neha.md
    image_circular: false # crops the image to make it circular

  - align: left
    image: SD1.png
    content: about_sayantan.md
    image_circular: false # crops the image to make it circular
    
    
  - align: right
    image: VT.png
    content: about_vivek.md
    image_circular: false # crops the image to make it circular

{% endtab %}

{% endtabs %}

---
