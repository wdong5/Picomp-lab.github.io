---
layout: page
permalink: /People/
title: People
nav: true
---

<style>
.profile-img {
    width: 200px;
    height: 200px;
    object-fit: cover;
    object-position: top;
}
</style>

**PRINCIPLE INVESTIGATOR**
<br>

<div class="row justify-content-md-center">
    <div class="col-sm-3">
        <img class="img-fluid rounded z-depth-1 profile-img" src="{{ '/assets/img/Wenqian_Dong.jpg' | relative_url }}" alt="" title="Wenqian Dong"/>
    </div>
    <div class="col-sm-4">
        <b>Wenqian Dong</b> <br>
        Ph.D. <br><br>
        Email: wenqian.dong <at> oregonstate.edu <br>
        <a href="https://scholar.google.com/citations?user=6qIVck4AAAAJ&hl=en">Google scholar</a>
    </div>
    <div class="col-sm-5">
       Wenqian Dong is an assistant professor in the School of EECS at <a href="https://engineering.oregonstate.edu/EECS" style="color:#538480;"> Oregon State University </a>. She studied her Ph.D. in Computer Science and Engineering at the University of California, Merced. Her research interests include high-performance computing (HPC), scientific machine learning, automatic performance tuning, and system-level optimization for large-scale ML models. Her work has been published in multiple top-tier conferences, including SC, HPDC, ASPLOS, ICS, EuroSys, VLDB, etc. Also, she is the recipient of the IEEE Computer Society TCHPC Early Career Researchers Award for Excellence in High-Performance Computing (2023). She worked in the High-Performance Computing Group at Pacific Northwest National Laboratory (PNNL) from 2019 and 2020, and AI Labs at Hewlett Packard Enterprise (HPE) in 2021. Her work at PNNL was highlighted at <a href="https://www.newswise.com/doescience/pnnl-researchers-speed-power-grid-simulations-using-ai/?article_id=741430"> DOE News wise</a> and <a href="https://www.pnnl.gov/news-media/pnnl-researchers-speed-power-grid-simulations-using-ai#:~:text=Share%3A,the%20blink%20of%20an%20eye">PNNL website </a>.
    </div>  
</div>  
<br>

---

**Ph.D. Students**
<br>

<div class="row justify-content-md-center">
    <div class="col-sm-3">
        <img class="img-fluid rounded z-depth-1 profile-img" src="{{ '/assets/img/Shouwei_gao_cunzhao.jpg' | relative_url }}" alt="" title="Shouwei Gao"/>
    </div>
    <div class="col-sm-4">
        <b>Shouwei Gao</b> <br>
        Ph.D. student (2023 Fall --) <br>
        Email: gaosho@oregonstate.edu <br>
    </div>
    <div class="col-sm-5">
        Shouwei Gao joined PiComp lab in fall 2023. His research interests include AI for science; Large-scale ML/AI models; Explainable AI.
    </div>  
</div>  
<br>

<div class="row justify-content-md-center">
    <div class="col-sm-3">
        <img class="img-fluid rounded z-depth-1 profile-img" src="{{ '/assets/img/haoyu.png' | relative_url }}" alt="" title="Haoyu Zheng"/>
    </div>
    <div class="col-sm-4">
        <b>Haoyu Zheng</b> <br>
        Ph.D. student (2023 Fall --) <br>
        Email: zhenghaoy@oregonstate.edu <br>
    </div>
    <div class="col-sm-5">
        His research interests include Disaggregated memory system; System optimization; MPI communication optimization.
    </div>  
</div>  
<br>
<br clear="left"/>

---

**Research Intern**

- Shanlin Liu
- Caichen Deng

---

**Alumni**

- Meiyan Gao First employment: Neocis Inc.

<div class="people">

{% for y in page.roles %}

  <h2 class="roles">{{role}}</h2>
  {% bibliography -f papers -q @*[roles={{y}}]* %}
{% endfor %}

</div>
