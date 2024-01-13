---
name: Sherlock Gnomes
tools: [Film]
image: https://upload.wikimedia.org/wikipedia/en/2/25/Sherlock_Gnomes.png
description: Eminent detective Sherlock Gnomes and his assistant investigate the sudden disappearance of other gnomes after Gnomeo and Juliet hire him.
year: 2018
company: Mikros Animation
role: Technical Animator
tasks: ["Assisting and supporting the animation team", "Maintaining and developing animation tools"]
---

# Sherlock Gnomes
{% include elements/tags.html tags=page.tools year=page.year%}

{% include elements/video.html link="https://www.youtube.com/embed/gwcdJXhngBw?si=pzDBLH812F7O1BLv" %}

<div class="row justify-content-left align-items-left">
    <div class="col-md-6">
        {% include projects/project_company_card.html company=page.company role=page.role %}
        {% include projects/project_tasks.html tasks=page.tasks %}
    </div>
    <div class="col-md-6">
        {% include elements/text_card.html text=page.description %}
    </div>
</div>
