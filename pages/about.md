---
layout: page
title: About
permalink: /about/
weight: 3
---

## **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
Fresh graduate that passionate about data management and policy research, equipped with 
strong analytical thinking and writing skills. I have gained practical experience in regulatory 
compliance, fintech operations, and strategic documentation through my role at PT Adhyoka Berkah 
Maju. I have demonstrated the ability to coordinate effectively with financial institutions and contribute 
to the development of high-quality regulatory and business planning documents. I am a resilient and 
adaptable team player with a proven track record of problem-solving in dynamic environments, and I 
am a continuous learner committed to personal and professional growth. I also took a brief academic 
leave due to financial and health reasons, yet remained committed and completed my degree on time in 
8 semesters, demonstrating responsibility and perseverance. 

## **Skills**
<div class="row">
{% include about/skills.html title="Data Analysis & Programming" source=site.data.data-analysis-skills %}
{% include about/skills.html title="Office & Productivity Tools" source=site.data.productivity-skills %}
</div>

## **Education**
<div class="row mt-4">
  <div class="col">
    <div class="timeline-body bg-themed">
      {% for item in site.data.education %}
        <div class="timeline-item">
          <div class="content">
            <h4>{{ item.title }}</h4>
            <h6 class="date">{{ item.from }} — {{ item.to }}</h6>
            <p>{{ item.description }}</p>
          </div>
        </div>
      {% endfor %}
    </div>
  </div>
</div>

## <strong>Experience</strong>
<div class="row mt-4">
{% include about/timeline.html %}
</div>