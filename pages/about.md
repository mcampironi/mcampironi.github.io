---
layout: page
title: About
permalink: /about/
weight: 2
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
a 25 year old Data Scientist with an interest for <i>Computer Vision</i> and <i>Deep Learning</i> in general. Here you can learn more about my skills and my education.

<div class="row">
<div class="col-md-6">
<div class="col-lg p-4 border  rounded-lg">
  <h3 class="mb-4"><b>Programming Languages</b></h3>
  <p style="font-size: 1em">
  • Python
  <br>
  • R
  <br>
  • Java (basic level)


  </p>
</div>

</div>
<div class="col-md-6">
<div class="col-lg p-4 border rounded-lg">
  <h3 class="mb-4"><b>Other Skills</b></h3>
  <p style="font-size: 1em">

        • Linux user
        <br>
        • LaTeX
        <br>
        • Adobe Photoshop

  </p>
</div>

</div>
<div class="w-100"></div>
<div class="col mt-4">
<div class="col-lg p-4 border rounded-lg">
  <h3 class="mb-4"><b>Frameworks, Libraries and Technologies</b></h3>
  <p style="font-size: 1em">

        Pandas, PyTorch, TensorFlow, Keras, OpenCV, Git, SQL, MongoDB

  </p>
</div>

</div>
</div>

<div class="row">
{% include about/timeline.html title="🛠️ Experiences" source=site.data.experience-timeline %}
</div>

<div class="row">
{% include about/timeline.html title="🏫 Education" source=site.data.education-timeline %}
</div>
