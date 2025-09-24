---
layout: page
title: About
permalink: /about/
weight: 3
id: about-page
---

## **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
a fresh graduate passionate about data management and policy research, equipped with strong analytical and writing skills. My professional experience at PT Adhyoka Berkah Maju provided hands-on experience in regulatory compliance and business operations within the fintech sector. Academically, I strengthened my research capabilities as a Research Assistant by managing large-scale datasets and contributing to publications, while my role as a Teaching Assistant at the University of Indonesia refined my organizational and communication skills. I am a resilient and adaptable team player, having demonstrated perseverance by overcoming personal challenges to complete my degree on schedule within 8 semesters.
 

## **Skills**
<div class="row">
{% include about/skills.html title="Data Analysis & Programming" source=site.data.data-analysis-skills %}
{% include about/skills.html title="Office & Productivity Tools" source=site.data.productivity-skills %}
</div>

## **Certificate**
{% include about/certifications.html %}

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

## **Working Experiences**
<div class="row mt-4">
{% include about/timeline.html %}
</div>

## **Organizational/Volunteer Activities**
<div class="row mt-4">
  <div class="col">
    <div class="timeline-body bg-themed">
      {% for item in site.data.organizational %}
        <div class="timeline-item">
          <div class="content">
            <h4>{{ item.title }}</h4>
            <h6 class="date">{{ item.from }} — {{ item.to }}</h6>
            <div>{{ item.description | markdownify }}</div>
          </div>
        </div>
      {% endfor %}
    </div>
  </div>
</div>