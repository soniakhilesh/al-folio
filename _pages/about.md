---
layout: about
title: Home
permalink: /
subtitle: soni6 [at] wisc [dot] edu. <br><a href='assets/pdf/Akhilesh_CV_PhD.pdf'> Download my resume</a>.
profile:
  align: right
  image: profile.jpg
  image_cicular: true # crops the image to make it circular
  address: 
news: false  # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
nav_order: 1
---

Akhilesh is a Ph.D student at University of Wisconsin Madison in the department of Industrial and Systems Engineering.
His reserach interests include developing methods to solve large-scale optimization problem arising in supply chain, scheduling, and machine learning applications.

## Education

{% for entry in site.data.education %}
   {% include cv/time_table.html %}
{% endfor %}



<!--- This is an HTML comment in Markdown
* Ph.D. in Industrial and Systems Engineering, UW-Madison, 2023 (Expected)
  - Advisors: [Prof. Jeff Linderoth](https://jlinderoth.github.io/), [Prof. Jim Luedtke](https://jrluedtke.github.io/)
* MS in Computer Science, UW-Madison, 2022
* MS in Industrial and Systems Engineering, UW-Madison, 2020
* BTech in Mechanical Engineering, IIT-ISM Dhanbad, 2017

Write your biography here. Tell the world about yourself. Link to your favorite [subreddit](http://reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also disable any these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](http://fortawesome.github.io/Font-Awesome/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them.
Previous subtitle
<a href='soni6@wisc.edu'>soni6 [at] wisc [dot] edu</a>. 
-->
