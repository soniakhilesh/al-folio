---
layout: about
title: Home
permalink: /
subtitle: akhileshsoni95 [at] gmail [dot] com <br><a href='assets/pdf/Akhilesh_Soni_resume.pdf'> Download my resume</a>.
profile:
  align: right
  image: profile.jpg
  image_cicular: false # crops the image to make it circular
  address: <p>Bellevue, WA, USA</p>
news: false  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
nav_order: 1
---
Akhilesh is currently an Applied Scientist at Amazon, where he works on large scale vehicle routing problems. He holds an MS and PhD in Operations Research (Industrial Engineering), and an MS in Computer Science from the University of Wisconsin-Madison. During his PhD, Akhilesh worked with <a href='https://jlinderoth.github.io/'> Prof. Jeff Linderoth </a> and <a href='https://jrluedtke.github.io/'> Prof. Jim Luedtke </a> at the <br><a href='https://engineering.wisc.edu/departments/industrial-systems-engineering/'> Department of Industrial & Systems Engineering</a>, and at  <br><a href='https://wid.wisc.edu/'> Wisconsin Institue of Discovery</a>. Priro to this, Akhilesh earned his Bachelor’s in Mechanical Engineering from IIT (ISM) Dhanbad.

Akhilesh is passionate about developing advanced algorithms and optimization frameworks for complex decision-making problems with real-life applications. His research interests include developing methods for solving large-scale optimization problems in supply chain, vehicle routing, scheduling, and machine learning applications.

## Education

{% for entry in site.data.education %}
   {% include cv/time_table.html %}
{% endfor %}

<div class="publications">
<h2>Publications</h2>
{% bibliography -f papers -q @*[selected=true]* %}
</div>

## Academic Achievements
- Spotlight presentation, Optimization and Machine Learning workshop, NeurIPS, 2021
- Travel grant for Mixed Integer Programming workshop, 2021
- Recipient of Vinod K \& J. Gail Sahney Scholarship at UW-Madison, 2020
- Recipient of Mitacs Fellowship to intern at University of Windsor, Canada, 2016

## Coursework
- **Industrial and Systems Engineering**
  - Introduction to Optimization Modeling, Linear Optimization, Integer Optimization, Nonlinear Programming, Engineering models for supply chain, Health systmes engineering, Stochastic modeling, Machine learning in action, Simulation modeling
- **Computer Science/ Maths**
  - Intro to algorithms, Dynamic Programming, Matrix methods in machine learning, Stochastic Programming, Real analysis, Introduction to Combinatorial Optimization, Mathematical foundations of machine learning
  
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
